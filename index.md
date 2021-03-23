---
layout: index
title: Home
---

# About Me

---

:wave: Hello, I am Emanuele Iannone, a **Computer Science** Ph. D. student at [University of Salerno <i class="fa fa-external-link" style="font-size:16px"></i>](https://www.unisa.it/) (Italy). I was born in Salerno (Italy) on 1st September 1996.

:pencil: I am currently attending the first out of three years of Ph. D. in which I'm working on **Software Vulnerabilities** under the supervision of [Prof. F. Palomba <i class="fa fa-external-link" style="font-size:16px"></i>](https://fpalomba.github.io/) and [Prof. A. De Lucia <i class="fa fa-external-link" style="font-size:16px"></i>](https://docenti.unisa.it/003241/home).
Currently, I'm investigating the lifecycle of known software vulnerabilities in open-source system and finding efficient ways to detect, mitigate and assess their risk. In this regard, I'm working on envising automatic exploit generation and security testing techniques to improve the dependability of software system.

:mortar_board: I received (110/110 cum laude) the M. Sc. Degree in Computer Science at
University of Salerno in September 2020, defending a thesis on
***Automatic Exploit Generation of known Java API vulnerabilities*** in **Software Dependability**,
advised by Prof. F. Palomba and Prof. A. De Lucia.  
In July 2018, I received (110/110 magna cum laude) the B. Sc. Degree in Computer Science at
University of Salerno, defending a thesis on
***Automatic Refactoring of Android-specific Energy Smells*** in **Software Engineering**,
advised by Prof. A. De Lucia.

My main research fields are:

&nbsp;&nbsp;&nbsp;&nbsp;:bangbang: **Software Vulnerabilities**  
&nbsp;&nbsp;&nbsp;&nbsp;:bangbang: **Software Maintenance and Evolution**  
&nbsp;&nbsp;&nbsp;&nbsp;:exclamation: Mining Software Repositories  
&nbsp;&nbsp;&nbsp;&nbsp;:grey_exclamation: Search-based Software Engineering  
&nbsp;&nbsp;&nbsp;&nbsp;:grey_exclamation: Software Testing  

[//]: # (The sources of CV is on my overleaf)
:scroll: You can download a more detailed résumé [here](./download/resume.pdf).

:nerd_face: I have always been fond of video gamers, especially role-playing games (RPG), but since my
professional life got new perspectives, I (sadly) had to change my habits, so I got into anime and TV series.  
My favourite video game series are *Final Fantasy* and *Pokémon*, while I am a great fan
on *Attack on Titan* TV show.

<br>

# :newspaper_roll: News

---

{% for post in site.posts %}
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
| **Birth Date**  | 01 September 1996 |
| **Birthplace** | Salerno (Italy) |
| **Nationality** | Italian |

# :telephone_receiver: Contacts

| **Email (University)** | eiannone@unisa.it |
| **Email (Personal)** | emaiannone@hotmail.it |
| **Skype** | emaiannone |
| **Discord** | emaiannone |
