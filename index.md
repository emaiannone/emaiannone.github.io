---
layout: index
title: Home
---

# About Me

---

:wave: Hello, I am Emanuele Iannone, a **Computer Science** Ph.D. student at
[University of Salerno](https://www.unisa.it/) (Italy). I was born in Salerno (Italy) on 1st September 1996.

:pencil: I am currently attending my first (out three) year, in which I'm working on **Software Vulnerabilities**
and their impact on the *Internet of Things* (e.g., Cyberphysical Systems), under the supervision of
[Prof. F. Palomba](https://fpalomba.github.io/).
Along this topic, I'm focusing on Automatic Exploit Generation, Automatic Test Case Generation and API usages.

:mortar_board: I received (110/110 cum laude) the M.Sc. Degree in Computer Science at
University of Salerno in September 2020, defending a thesis on
***Automatic Exploit Generation of known Java API vulnerabilities*** in **Software Engineering**,
advised by Prof. F. Palomba and [Prof. A. De Lucia](https://docenti.unisa.it/003241/home).  
In July 2018, I received (110/110 magna cum laude) the B.Sc. Degree in Computer Science at
University of Salerno, defending a thesis on
***Automatic Refactoring of Android-specific Energy Smells*** in **Software Engineering**,
advised by Prof. A. De Lucia.

My main research fields are:

&nbsp;&nbsp;&nbsp;&nbsp;:bangbang: **Software Security Engineering**  
&nbsp;&nbsp;&nbsp;&nbsp;:bangbang: Vulnerability Management  
&nbsp;&nbsp;&nbsp;&nbsp;:exclamation: Software Testing and Debugging  
&nbsp;&nbsp;&nbsp;&nbsp;:grey_exclamation: Software Libraries and Repositories  
&nbsp;&nbsp;&nbsp;&nbsp;:grey_exclamation: Search-based Software Engineering  

:nerd_face: I have always been a passionate video gamers, but since my
professional life got new perspectives, I changed my habits and got into
anime and Tv series.
My favourite video game series are *Final Fantasy* and *Pokémon*, while I am a great fan
on *Attack on Titan* Tv show.

[//]: # (The sources of CV is on my overleaf)
:scroll: You can download a more detailed résumé [here](./download/resume.pdf).

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

| **Email (University)** | eiannone@sunisa.it |
| **Email (Personal)** | emaiannone@hotmail.it |
| **Skype** | emaiannone |
| **Discord** | emaiannone |