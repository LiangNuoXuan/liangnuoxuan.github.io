# 诺愃 · NuoXuan

一个基于 Docsify 构建的个人文档站点。

## 项目简介

本项目是一个静态文档网站，收集整理了 Android Root 相关的方案、模块和工具，所有链接均为官方源，旨在为用户提供便捷的资源导航。

## 文件结构

```
GR/
├── index.html          # 网站入口文件
├── home.md             # 主页内容（Root 方案和模块推荐）
├── 404.html            # 404 错误页面
├── ftpico.jpg          # 网站图标
├── .nojekyll           # GitHub Pages 配置文件
├── LICENSE.txt         # Apache 2.0 许可证
├── docsify/            # Docsify 库文件
│   ├── docsify@4.js   # Docsify 核心脚本
│   └── vue.css        # Docsify Vue 主题样式
└── alist/              # AList 相关资源
    ├── sty.css        # 自定义样式（毛玻璃效果）
    └── MoonStarsKai-Regular.ttf  # 自定义字体
```

## 技术栈

- **Docsify** - 文档网站生成器（v4）
- **Vue.css** - Docsify Vue 主题
- **alist自定义字体** - MoonStarsKai（星月楷）
- **alist自定义样式** - 毛玻璃效果、明暗主题适配 

## 本地运行

1. 克隆仓库到本地

2. 使用任意 HTTP 服务器运行，例如：
   
   ```bash
   # 使用 Python
   python -m http.server 8080
   
   # 或使用 Node.js 的 http-server
   npx http-server -p 8080
   ```

3. 浏览器访问 `http://localhost:8080`

## 部署

本项目可直接部署到 GitHub Pages、Vercel、Netlify 等静态托管平台。

### GitHub Pages 部署

1. 将项目推送到 GitHub 仓库
2. 在仓库设置中启用 GitHub Pages
3. 选择分支和根目录即可

## 许可证

本项目采用 Apache License 2.0 许可证，详见 [LICENSE.txt](LICENSE.txt)。