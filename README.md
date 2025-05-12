# 个人多功能管理系统

基于Jekyll的个人网站系统,集成AI技术文档、项目管理和个人财务管理功能。

## 项目结构

```
.
├── _posts/          # AI技术文档文章
├── _projects/       # 项目管理文档
├── _finance/        # 财务管理数据
├── _tabs/          # 导航页面
├── _layouts/       # 页面布局模板
├── _includes/      # 可重用组件
├── assets/         # 静态资源
│   ├── css/       # 样式文件
│   ├── js/        # JavaScript文件
│   └── img/       # 图片资源
├── admin/          # 后台管理界面
└── server/         # 后端服务
    ├── api/       # API接口
    ├── models/    # 数据模型
    └── config/    # 配置文件
```

## 主要功能

1. AI技术文档
- Markdown文档管理
- 分类和标签系统
- 全文搜索

2. 项目管理
- 项目状态跟踪
- 文件管理
- 进度展示

3. 个人财务
- 存钱目标追踪
- 收支记录
- 数据可视化

## 开发环境

1. 前端开发
```bash
bundle install    # 安装Jekyll依赖
jekyll serve      # 启动开发服务器
```

2. 后端开发
```bash
cd server
npm install      # 安装依赖
npm run dev      # 启动开发服务器
```

## 部署说明

1. 文档站点
- 使用GitHub Pages自动部署

2. 后端服务
- 使用Docker部署
- 需要配置MongoDB
- 需要设置环境变量

## 技术栈

- 前端: Jekyll + Vue.js
- 后端: Node.js + Express
- 数据库: MongoDB
- 部署: GitHub Pages + Docker 