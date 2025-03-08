---
layout: home  # minima 的首页布局（自动渲染最新文章）
sitemap: false  # 避免某些 SEO 插件重复抓取
---

# 👋 欢迎来到我的数字花园

{:.intro}
这里记录我对技术、设计和开源的一切思考 → [[订阅博客]](/feed.xml)  

🔍 **近期聚焦**:  
- **Rust 嵌入式开发** | [项目仓库](https://github.com/your/repo)
- **分布式系统设计模式** | [系列文章](/tags/distributed/)

---

## ✨ 精选项目

<div class="project-grid">
  {% for project in site.data.projects %}
  <div class="project-card">
    <h3><a href="{{ project.url }}">{{ project.title }}</a></h3>
    <p>{{ project.description }}</p>
  </div>
  {% endfor %}
</div>
