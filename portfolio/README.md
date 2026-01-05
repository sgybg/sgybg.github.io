# 个人网站模板 | Personal Portfolio Template

一个现代化、响应式的个人网站模板，采用暗色霓虹科技风格设计。

## 📁 文件结构

```
portfolio/
├── index.html              # 首页
├── css/
│   ├── style.css          # 主样式文件（全局样式、变量、组件）
│   ├── animations.css     # 动画效果
│   └── pages.css          # 内页专属样式
├── js/
│   └── main.js            # JavaScript 功能
├── pages/
│   ├── about.html         # 关于我页面
│   ├── projects.html      # 项目展示页面
│   └── contact.html       # 联系页面
├── images/                 # 图片文件夹（放置你的图片）
│   ├── avatar.jpg         # 头像
│   ├── project1.jpg       # 项目截图
│   └── ...
└── README.md              # 说明文档
```

## 🚀 快速开始

### 1. 下载文件
将所有文件下载到本地，保持文件结构不变。

### 2. 个性化修改

#### 基本信息修改
打开每个 HTML 文件，搜索并替换以下内容：

| 查找 | 替换为 |
|-----|-------|
| `你的名字` | 你的真实姓名 |
| `YourName` | 你的英文名/昵称 |
| `your-email@example.com` | 你的邮箱 |
| `yourusername` | 你的 GitHub/社交媒体用户名 |

#### 修改头像
1. 将你的头像图片放入 `images/` 文件夹
2. 在 HTML 文件中找到头像区域，取消注释并修改路径：
```html
<!-- 替换为你的头像 -->
<img src="images/avatar.jpg" alt="头像">
```

#### 修改主题颜色
打开 `css/style.css`，在顶部的 CSS 变量区域修改颜色：
```css
:root {
    --accent-cyan: #00d4ff;      /* 主色调 */
    --accent-magenta: #ff00aa;   /* 辅助色 */
    --accent-purple: #8b5cf6;    /* 强调色 */
}
```

### 3. 部署到 GitHub Pages

1. 创建一个新的 GitHub 仓库，名称为 `你的用户名.github.io`
2. 将所有文件上传到仓库
3. 在仓库设置中启用 GitHub Pages
4. 访问 `https://你的用户名.github.io` 查看网站

## 📝 内容修改指南

### 修改项目信息
在 `pages/projects.html` 中找到项目卡片，修改以下内容：
- 项目标题和描述
- 技术栈标签
- 项目链接
- 项目图片（放入 images 文件夹）

### 修改技能
在 `pages/about.html` 中找到技能卡片，修改：
- 技能名称和描述
- 技能标签

### 修改经历
在 `pages/about.html` 中找到时间线区域，修改：
- 时间范围
- 职位名称
- 公司名称
- 工作描述

### 设置联系表单
联系表单默认使用 [Formspree](https://formspree.io/)：
1. 注册 Formspree 账号
2. 创建新表单，获取表单 ID
3. 在 `pages/contact.html` 中替换表单 action：
```html
<form action="https://formspree.io/f/你的表单ID" method="POST">
```

其他表单服务选项：
- [Netlify Forms](https://docs.netlify.com/forms/setup/)
- [EmailJS](https://www.emailjs.com/)
- 自建后端 API

## 🎨 自定义建议

### 添加更多页面
1. 复制现有页面作为模板
2. 修改导航链接
3. 更新内容

### 添加博客功能
推荐使用：
- [Jekyll](https://jekyllrb.com/) (GitHub Pages 原生支持)
- [Hugo](https://gohugo.io/)
- [Hexo](https://hexo.io/)

### 添加网站统计
推荐服务：
- [Google Analytics](https://analytics.google.com/)
- [百度统计](https://tongji.baidu.com/)
- [Umami](https://umami.is/) (开源自托管)

## 📱 浏览器兼容性

- Chrome (推荐)
- Firefox
- Safari
- Edge
- 移动端浏览器

## 📄 许可证

本模板免费使用，可自由修改和分发。

---

**祝你的个人网站大获成功！** 🎉

如有问题，欢迎联系模板作者或提交 Issue。
