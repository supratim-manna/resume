---
#
# By default, content added below the "---" mark will appear in the home page
# between the top bar and the list of recent posts.
# To change the home page layout, edit the _layouts/home.html file.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: default
---
---
layout: default
title: "Supratim Manna - Portfolio"
---

# Welcome to My Portfolio 🚀

I am **Supratim Manna**, a Data Science student at **DIAT-DRDO**, passionate about **AI/ML, Generative Models, and Deep Learning**. My work includes **Network Intrusion Detection, Exoplanet Discovery, and Diffusion Models**.

## 🔥 Featured Projects
{% for project in site.data.projects %}
- **[{{ project.title }}]({{ project.link }})**: {{ project.quote }}
{% endfor %}

---

## 📫 Contact Me
- 📧 Email: [supratimmannas7@gmail.com](mailto:supratimmannas7@gmail.com)
- 🏢 GitHub: [Supratimmannas7](https://github.com/Supratimmannas7)
- 🔗 LinkedIn: [supratim-manna-728315293](https://www.linkedin.com/in/supratim-manna-728315293/)
