---
layout: home  # minima 的首页布局（自动渲染最新文章）
sitemap: false  # 避免某些 SEO 插件重复抓取
---

{:.intro}
这里记录我对技术、设计和开源的一切思考 →

---

### ✨ 文章列表

<div class="project-grid">
  {% for project in site.data.projects %}
  <div class="project-card">
    <h3><a href="{{ project.url }}">{{ project.title }}</a></h3>
    <p>{{ project.description }}</p>
  </div>
  {% endfor %}
</div>
