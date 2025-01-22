---
layout: default
title: Home
permalink: /
---

# Welcome to My Site!

This is where I dump what's on my mind. I'm a CS PhD student, working on AI/ML, specifically Computer Vision. I like to do deep dives into things I'm interested about, and then writing down what I learned from them.

## My Projects
Here are the latest things I've got going on:

<ul>
  {% for post in site.categories.projects limit:5 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %-d, %Y" }}
    </li>
  {% endfor %}
</ul>
[View all projects](/projects/)

## Book Reviews
Here are my latest book reviews:
<ul>
  {% for post in site.categories.book-reviews limit:5 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %-d, %Y" }}
    </li>
  {% endfor %}
</ul>
[View all book reviews](/book-reviews/)

## Thoughts
Here are my latest thoughts:
<ul>
  {% for post in site.categories.thoughts limit:5 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %-d, %Y" }}
    </li>
  {% endfor %}
</ul>
[View all thoughts](/thoughts/)

## Lists
Here are my latest lists:
<ul>
  {% for post in site.categories.lists limit:5 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %-d, %Y" }}
    </li>
  {% endfor %}
</ul>
[View all lists](/lists/)