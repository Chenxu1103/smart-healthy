# smart-healthy
智能医护助手-康护宝
# 康护宝 - 智能医疗小程序

康护宝是一款基于微信小程序平台开发的智能医疗健康管理应用，致力于为用户提供便捷的健康报告管理、用药提醒和智能问诊服务。

## 主要功能

### 1. 健康报告管理
- 支持拍照和相册上传检查报告
- 智能解析报告内容
- 历史报告记录查询
- 报告分享功能

### 2. 用药提醒
- 个性化用药计划设置
- 多时段提醒支持
- 用药执行情况追踪
- 详细用药记录管理

### 3. 智能问诊
- 智能症状分析
- 快速症状选择
- 对话式问诊
- 专业医疗建议

### 4. 个人中心
- 微信授权登录
- 个人健康数据存储
- 健康指标追踪
- 隐私数据保护

## 技术架构

### 前端技术
- 微信小程序框架
- TDesign 组件库
- 自定义组件
- SVG 图标系统

### 后端技术
- 微信云开发
- 云函数
- 云数据库
- 云存储

## 项目结构

```
miniprogram/
├── components/          # 自定义组件
│   ├── login-modal/    # 登录弹窗组件
│   └── tdesign/        # TDesign UI组件
├── images/             # 图片资源
│   ├── icons/          # SVG和PNG图标
│   └── tabbar/         # 底部导航栏图标
├── pages/              # 页面文件
│   ├── index/         # 首页
│   ├── report/        # 报告管理
│   ├── medicine/      # 用药提醒
│   ├── consult/       # 智能问诊
│   └── profile/       # 个人中心
└── utils/             # 工具函数

cloudfunctions/
└── login/             # 用户认证云函数
```

## 开发环境搭建

### 环境要求
- [微信开发者工具](https://developers.weixin.qq.com/miniprogram/dev/devtools/download.html)
- Node.js (v12 或以上)
- npm 或 yarn

### 安装步骤

1. 克隆项目
```bash
git clone [仓库地址]
cd [项目目录]
```

2. 安装依赖
```bash
npm install
# 或
yarn install
```

3. 生成图标（可选）
```bash
npm run create-icons
```

### 配置说明

1. 在微信开发者工具中打开项目
2. 在 `project.config.json` 中配置小程序 AppID
3. 初始化云开发环境
4. 更新相关文件中的云环境ID

### 开发流程

1. 使用微信开发者工具打开项目
2. 开启调试模式
3. 使用内置模拟器
4. 实时预览修改

## 部署说明

1. 部署云函数
```bash
# 在微信开发者工具中
右键点击 cloudfunctions/login
选择 "上传并部署：云端安装依赖"
```

2. 部署小程序
- 通过微信开发者工具上传
- 提交审核
- 等待微信平台审核通过

## 参与贡献

1. Fork 本仓库
2. 创建新的功能分支
3. 提交代码变更
4. 推送到远程分支
5. 创建 Pull Request

## 开源协议

本项目采用 MIT 协议开源 - 查看 LICENSE 文件了解更多详情

## 致谢

- [TDesign 小程序组件库](https://tdesign.tencent.com/miniprogram/overview) - UI组件支持
- 微信云开发平台
- 所有贡献者

## 联系方式：626291605@qq.com

如有问题或建议，请在仓库中创建 Issue。 
