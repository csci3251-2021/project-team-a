# Introduction

We will work on this repo according to the tasks inside the issues folder, I guess?

# Code
```c
{% include_relative code.c %}
```
![example workflow](https://github.com/csci3251-2021/project-team-a/actions/workflows/<I dont know workflow name because no workflow file.>/badge.svg)

# Contributors
{% for stu in site.stu %}
  <img src="stu.image">
  <h2>
    <a href="{{ stu.url }}">
      {{ stu.user }} - {{ stu.name }}
    </a>
  </h2>
  <p>{{ stu.content | markdownify }}</p>
{% endfor %}
