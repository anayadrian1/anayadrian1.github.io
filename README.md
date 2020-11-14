## Introduction

Hello! My name is Adrian Anaya. I am a 23 year old student in the CNM Ingenuity Deep Dive Java + Android Bootcamp at Central New Mexico Community College. I am studying to become a junior software developer to advance my skills in the industry and further my education within the field. I am advancing my skills in Java, SQL, Android architecture, databasing with Room and JPA/Hiberante, and touching on other languages as necessary like Ruby, and am excited and open to learning more about computer science and the many languages, skills, and challenged that come with it.

## Current projects

* [Sno: Productivity Android Application](https://github.com/anayadrian1/sno)

* [Powdr: A Social Ski App for Android](https://github.com/powdr-ddc/powdr-ddc.github.io)

## Recently updated repositories

{% assign public_repositories = site.github.public_repositories | where: 'fork', false | sort: 'updated_at' | reverse %}
{% for repo in public_repositories limit: 10 %}
* [{{ repo.name }}]({{ repo.html_url }})
{% endfor %}

## Links

* [LinkedIn](https://www.linkedin.com/in/adrian-anaya-434808127/ "Adrian Anaya")
