# Introduction

We will work on this repo according to the tasks inside the issues folder, I guess?

# Code

# Contributors
{% for student in site.stu %}
  <img src="stu.image">
  <h2>{{ stu.user }} - {{ stu.name }}</h2>
  <p>{{ stu.content | markdownify }}</p>
{% endfor %}
