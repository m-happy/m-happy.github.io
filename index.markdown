---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
Hello, How are you?
Hello! I'm a CSE Graduate of IIT Hyderabad, class of 2021. Currently working as compiler engineer.I'll write about things I find interesting or whatever I learnt and would like everyone to know my perspective on the same topic. Thanks for visiting. 