---
layout: index
title: Home
---

# About Me

:wave: Hello, I'm Emanuele Iannone, a **Computer Science** Ph.D. student at [University of Salerno](https://www.unisa.it/) (Italy), and I'm part of the extraordinary family of [SeSa Lab](https://sesalabunisa.github.io/).
I was born in Salerno, Italy, on 1st September 1996.

:pencil: I'm currently at the second year of my Ph.D. program. My research resolves around the analysis of **Software Vulnerabilities** in the field of **Software Maintenance and Evolution**, advised by [Prof. Fabio Palomba](https://fpalomba.github.io/) and [Prof. Andrea De Lucia](https://docenti.unisa.it/003241/home).
I'm currently investigating the life-cycle of known software vulnerabilities in open-source system and finding efficient ways to detect, mitigate and assess their risk. In this respect, I'm also working on envising automated exploit generation and security testing techniques to improve the dependability of software systems.

:mortar_board: I received (110/110 cum laude) the M.Sc. Degree in Computer Science at
University of Salerno in September 2020, defending a thesis on ***Automatic Exploit Generation of Known Java API vulnerabilities*** advised by Prof. F. Palomba and Prof. A. De Lucia.  
:mortar_board: In July 2018, I received (110/110 magna cum laude) the B.Sc. Degree in Computer Science at University of Salerno, defending a thesis on ***Automatic Refactoring of Android-specific Energy Smells*** advised by Prof. A. De Lucia.

My main research interests are:

&nbsp;&nbsp;&nbsp;&nbsp;:bangbang: **Software Vulnerability Analysis**  
&nbsp;&nbsp;&nbsp;&nbsp;:bangbang: **Software Security Testing**  
&nbsp;&nbsp;&nbsp;&nbsp;:exclamation: Mining Software Repositories  
&nbsp;&nbsp;&nbsp;&nbsp;:exclamation: Search-based Software Engineering  

All my research activities are in the context of:

&nbsp;&nbsp;&nbsp;&nbsp;:grey_exclamation: Empirical Software Engineering  
&nbsp;&nbsp;&nbsp;&nbsp;:grey_exclamation: Software Maintenance and Evolution  

[//]: # (The sources of CV is on my overleaf)
:scroll: You can download a more detailed résumé [here](./download/resume.pdf) (last version 17th November 2020... I'll update it soon!).

:nerd_face: I have always been fond of video gamers, especially role-playing games (RPG), but since my professional life got new perspectives, I (sadly) had to change my habits, so I got into anime and TV series.  
My favourite video game series are *Final Fantasy* and *Pokémon*, while I'm a great fan on *Attack on Titan* TV show.

<hr>

# :newspaper_roll: News

{% for post in site.posts limit:3 %}
  <article>
    <h2>
      <a href="{{ post.url }}">
        :pushpin: {{ post.title }}
      </a>
    </h2>
    <i><time datetime="{{ post.date | date: "%Y-%m-%d" }}">{{ post.date | date_to_long_string }}</time></i>
    {{ post.excerpt }}
  </article>
{% endfor %}

# :information_source: General Info

| **First Name** | Emanuele |
| **Last Name** | Iannone |
| **Birth Date**  | 01/09/1996 |
| **Birthplace** | Salerno, Italy |
| **Nationality** | Italian |

# :telephone_receiver: Contacts

| **Email (University)** | eiannone *at* unisa *dot* it |
| **Email (Personal)** | emaiannone *at* hotmail *dot* it |
