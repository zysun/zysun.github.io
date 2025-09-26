# 个人博客项目

这是一个基于 Hexo 的个人博客项目，使用 Fluid 主题，部署在 GitHub Pages 上。

## 快速开始

### 环境要求
- Node.js
- npm/yarn/pnpm

### 安装依赖
```bash
npm install
```

### 开发模式
启动本地服务器进行预览和开发：
```bash
npm run server
```
访问 `http://localhost:4000` 查看效果。

### 构建项目
生成静态文件：
```bash
npm run build
```
生成的文件会在 `public` 目录中。

### 清理缓存
清理生成的文件和缓存：
```bash
npm run clean
```

### 部署博客
部署到配置的平台（GitHub Pages）：
```bash
npm run deploy
```

## 项目结构
- **scaffolds/**: 模板文件目录
- **source/**: 源码目录，存放文章和页面
- **themes/**: 主题目录
- **_config.yml**: Hexo 主配置文件
- **_config.fluid.yml**: Fluid 主题配置文件

## 配置说明
### 网站信息
在 `_config.yml` 中可以修改网站标题、作者、描述等基本信息。

### 主题设置
- 默认使用 Fluid 主题
- 可以在 `_config.fluid.yml` 中自定义主题外观和功能

## 写作指南
### 创建新文章
```bash
hexo new "文章标题"
```
新文章会生成在 `source/_posts/` 目录下。

### 文章格式
文章使用 Markdown 格式编写，支持 front-matter 配置。

## 更多信息
- [Hexo 文档](https://hexo.io/docs/)
- [Fluid 主题文档](https://hexo.fluid-dev.com/docs/guide/)