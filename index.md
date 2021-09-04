---
title: Home Page
sidebar: toc
---

<h2>{{ site.data.samplelist.docs_list_title }}</h2>
<ul>
   {% for item in site.data.samplelist.toc %}
      <li><a href="{{ item.url }}">{{ item.title }}</a></li>
   {% endfor %}
</ul>

- [Welcome Message](./welcome.html)
- [Next Steps](./steps.html)
- What to Expect
- Responsibilities and Obligations
- Lab Rules
- General Advices
- [Useful Resources](./resources.html)

[About this page](./README.html)
