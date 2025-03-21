# 个人主页项目

这是一个使用现代网页技术构建的响应式个人主页项目。

## 项目概述

本项目是一个展示个人信息、作品集和联系方式的单页面应用。采用简约现代的设计风格，突出展示专业背景和项目经验。

### 主要功能

- 响应式设计，完美适配移动端和桌面端
- 作品集展示，包含项目链接和简介
- 个人技能和经验介绍
- 社交媒体和联系方式整合
- 现代化的UI动效

## 技术栈

- HTML5
- Tailwind CSS v3.0+
- Font Awesome 图标库
- 原生JavaScript

## 项目结构

```
PersonalHomepage/
│
├── index.html          # 主页面
└── README.md          # 项目说明文档
```

## 快速开始

1. 克隆项目到本地：
```bash
git clone [repository-url]
```

2. 直接在浏览器中打开 `index.html` 文件即可查看效果

## 自定义修改

### 修改个人信息

编辑 `index.html` 文件中的相关部分：

- 个人简介：修改 Hero Section 中的内容
- 作品展示：更新 Works Section 中的项目信息
- 联系方式：更新 Contact Section 中的联系信息

### 修改样式

项目使用 Tailwind CSS 进行样式管理，主要的自定义配置在 `index.html` 的 `<head>` 部分：

```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                primary: '#f5f5f5',
                secondary: '#1a1a1a',
            },
            fontFamily: {
                sans: ['Inter', 'system-ui', 'sans-serif'],
            },
        }
    }
}
```

## 部署说明

本项目是纯静态网页，可以部署在任何支持静态网站托管的平台：

1. GitHub Pages
2. Netlify
3. Vercel
4. 个人服务器

### GitHub Pages 部署步骤

1. 创建一个名为 `username.github.io` 的仓库
2. 将项目文件推送到该仓库
3. 在仓库设置中启用 GitHub Pages
4. 访问 `https://username.github.io` 查看效果

## 注意事项

- 图片资源使用了 [Picsum Photos](https://picsum.photos/) 服务，建议在正式使用时替换为自己的图片
- 确保所有链接都指向正确的地址
- 定期更新依赖的 CDN 资源版本

## 维护者

- 李南 (Nave)
- 联系方式：[nan315774101@qq.com](mailto:nan315774101@qq.com)

## 许可证

MIT License 