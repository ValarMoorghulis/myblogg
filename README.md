# 🌐 周周周的技术笔记 (Valar Morghulis)

这是我的个人博客仓库，基于 **Beautiful Jekyll** 主题构建，完全托管在 GitHub Pages 上。

## 🚀 快速访问
- **博客主页**: [https://ValarMoorghulis.github.io](https://github.io)
- **仓库地址**: [ValarMoorghulis/valarmoorghulis.github.io](https://github.com)

---

## 🛠️ 管理指南 (给自己的备忘录)

### 1. 发布新文章
所有的博文都存放在 `_posts/` 文件夹中。
- **文件名格式**: `YYYY-MM-DD-title.md` (例如: `2023-10-27-first-post.md`)
- **文章必备头信息 (Front Matter)**:
  ```yaml
  ---
  layout: post
  title: "文章标题"
  subtitle: "副标题(选填)"
  date: 2023-10-27
  author: "周周周"
  tags: [技术, 笔记]
  ---
  ```

### 2. 修改全局设置
如果你想修改博客名字、头像、大标题文字或社交链接，请编辑：
- 📂 `_config.yml`

### 3. 修改导航栏
如果你想增加或减少页面链接，请编辑：
- 📂 `_data/navigation.yml`

### 4. 存放图片
- 建议将图片统一存放在 `assets/img/` 目录下。

---

## 📁 目录结构说明
* `_posts/` - 存放所有的 Markdown 博文。
* `_data/` - 存放导航栏设置（navigation.yml）。
* `_layouts/` - 页面模板（由主题提供，一般无需修改）。
* `index.html` - 博客首页的配置。

---

## 📅 待办事项 (TODO)
- [x] 搭建博客基础框架
- [x] 配置自定义域名/主站域名
- [ ] 修改首页大背景图
- [ ] 撰写第一篇正式技术文章
- [ ] 集成评论系统 (Giscus/Disqus)

---

## 📜 许可
本项目采用 [MIT](LICENSE) 协议。内容创作遵循 [CC BY-NC-SA 4.0](https://creativecommons.org)。

---
*Powered by [Beautiful Jekyll](https://beautifuljekyll.com)*
