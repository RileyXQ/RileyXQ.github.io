---
layout: default
title: Welcome to My Blog
---

# Welcome to My Blog

Hi, I'm **Riley X. Quinn**, and this is a collection of my blog posts. You can browse through my articles below, where I dive deep into topics related to **Java development** and more. 🎉

---

## 📚 Blog Posts

Here are my latest posts:

<ul>
  {% for post in site.pages %}
    {% if post.path contains "blogs" %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

---

## 🌟 About Me

I'm a passionate **freelance Java developer** with a love for sharing knowledge. I regularly post tutorials and articles to help developers of all levels grow and succeed in their coding journey. Follow me on [Medium](https://medium.com/@yourusername) for more content!

---

## 📬 Contact Me

Feel free to reach out:

- [LinkedIn](https://www.linkedin.com/in/greg-shenefelt)
- [Email Me](mailto:rileyxq@rxquinn.net)

---

Thank you for visiting, and happy coding! 💻
