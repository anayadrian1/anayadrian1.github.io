## Introduction

I am a quick visual learner with critical thinking skills who works well with others and am currently going to attend the Deep Dive Coding Java + Android Bootcamp. My plans upon course completion is to hopefully get a job or internship to advance my skills in computer science and obtain a career in this field.

## Current projects

* [Hello World: Java console application](https://github.com/anayadrian1/deep-dive-hellow-world-aa)

* [Hello World: Android application](https://github.com/anayadrian1/hello-world)

## Recently updated repositories

{% assign public_repositories = site.github.public_repositories | where: 'fork', false | sort: 'updated_at' | reverse %}
{% for repo in public_repositories limit: 10 %}
* [{{ repo.name }}]({{ repo.html_url }})
{% endfor %}

## Links

* [LinkedIn](https://www.linkedin.com/in/adrian-anaya-434808127/ "Adrian Anaya")
