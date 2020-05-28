---
layout: index
title: Home
---

# About Me

---

:wave: Hello, I am Emanuele Iannone, a **Computer Science** MSc student at [University of Salerno](https://www.unisa.it/) (Italy).
I was born in Salerno (Italy) on 1st September 1996.

:pencil: I am currently attending my last year, in which I'm going to present an extension of [Evosuite](https://github.com/EvoSuite/evosuite) for ***Automatic Exploit Generation*** of Java applications that rely on OSS libraries and frameworks affected by [known vulnerabilities](https://cve.mitre.org/).   This work is under the supervision of [Prof. F. Palomba](https://fpalomba.github.io/) and [Prof. A. De Lucia](https://docenti.unisa.it/003241/home)

:mortar_board: I received (110/110 magna cum laude) the BSc Degree in Computer Science at University of Salerno in 2018, defending a thesis on ***Automatic Refactoring of Android-specific Energy Smells*** in **Software Engineering**, advised by Prof. A. De Lucia.

My research interests are:

&nbsp;&nbsp;&nbsp;&nbsp;:bangbang: **Software Engineering**  
&nbsp;&nbsp;&nbsp;&nbsp;:bangbang: Software Testing  
&nbsp;&nbsp;&nbsp;&nbsp;:exclamation: Search-based Software Engineering  
&nbsp;&nbsp;&nbsp;&nbsp;:exclamation: Software Vulnerabilities  
&nbsp;&nbsp;&nbsp;&nbsp;:grey_exclamation: Software Quality  
&nbsp;&nbsp;&nbsp;&nbsp;:grey_exclamation: Software Maintenance and Evolution  

:nerd_face: I am fond of Anime and Videogames. I'm also getting into TV Series.

[//]: # (Source of CV is on my overleaf)
:scroll: You can download a more detailed résumé [here](./download/resume.pdf).

---

# :newspaper_roll: News

{% for post in site.posts %}
  <article>
    <h2>
      <a href="{{ post.url }}">
        :pushpin: {{ post.title }}
      </a>
    </h2>
    <time datetime="{{ post.date | date: "%Y-%m-%d" }}">{{ post.date | date_to_long_string }}</time>
    {{ post.excerpt }}
  </article>
  ---
{% endfor %}

# :information_source: General Info

| **Name** | Emanuele Iannone |
| **Birth Date**  | 01/09/1996 |
| **Birthplace** | Salerno (Italy) |
| **Nationality** | Italian |

# :telephone_receiver: Contacts

| **Email (University)** | e.iannone16@studenti.unisa.it |
| **Email (Personal)** | emaiannone@hotmail.it |
| **Skype** | emaiannone |
