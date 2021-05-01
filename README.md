# Introduction

We will work on this repo according to the tasks inside the issues folder, I guess?

# Code
```c
{% include_relative code.c %}
```
![example workflow](https://github.com/csci3251-2021/project-team-a/actions/workflows/main.yml/badge.svg)

# Contributors
{% for student in site.stu %}
  <img src="stu.image">
  <h2>{{ stu.user }} - {{ stu.name }}</h2>
  <p>{{ stu.content | markdownify }}</p>
{% endfor %}
