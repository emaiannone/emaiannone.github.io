---
layout: category
title: Publications
permalink: publications
sidebar_sort_order: 1
---

<a name="j1"></a>

#### :page_with_curl: [J1] The Secret Life of Software Vulnerabilities: A Large-Scale Empirical Study
**E. Iannone**, R. Guadagni, F. Ferrucci, A. De Lucia, F. Palomba.  
***To appear** IEEE Transactions on Software Engineering (TSE)*
[[preprint]](download/papers/j1.pdf) [[cite]](download/cites/j1.bib)

>**Abstract:**
>Software vulnerabilities are weaknesses in source code that can be potentially exploited to cause loss or harm.
>While researchers have been devising a number of methods to deal with vulnerabilities, there is still a noticeable lack of knowledge on their
software engineering life cycle, for example how vulnerabilities are introduced and removed by developers. [...]
>We consider 3,663 vulnerabilities with public patches from the National Vulnerability Database [...] and define an eight-step process involving both automated parts and manual analyses.
>The investigated vulnerabilities can be classified in 144 categories, take on average at least 4 contributing commits before being
introduced, and half of them remain unfixed for at least more than one year. Most of the contributions are done by developers with high
workload, often when doing maintenance activities, and removed mostly with the addition of new source code aiming at implementing
further checks on inputs. [...]

<a name="c3"></a>

#### :page_with_curl: [C3] Toward Understanding the Impact of Refactoring on Program Comprehension
G. Sellitto, **E. Iannone**, Z. Codabux, V. Lenarduzzi, A. De Lucia, F. Palomba, F. Ferrucci.  
***To appear** In Proceedings of the 29th IEEE/ACM International Conference on Software Analysis, Evolution and Reengineering (SANER 2022),
Honolulu, Hawaii, US, 2022*
[[preprint]](download/papers/c3.pdf)

>**Abstract:**
>Software refactoring is the activity associated with
developers changing the internal structure of source code without modifying its external behavior. The literature argues that refactoring might have beneficial and harmful implications [...]. This paper continues the narrative on the effects of refactoring by exploring the dimension of program comprehension, namely the property that describes how easy it is for developers to understand source code. [...]
>First, we mine refactoring data and, for each commit involving a refactoring, we compute (i) the amount and type(s) of refactoring actions performed and (ii) eight state-of-the-art program comprehension metrics. Afterwards, we build statistical models relating the various refactoring operations to each of the readability metrics [...]. The key results are that refactoring has a notable impact on most of the readability metrics considered.

<a name="c2"></a>

#### :page_with_curl: [C2] Toward Automated Exploit Generation for Known Vulnerabilities in Open-Source Libraries
**E. Iannone**, D. Di Nucci, A. Sabetta, A. De Lucia.  
*In Proceedings of the 29th IEEE/ACM International Conference on Program Comprehension (ICPC 2021),
Madrid, Spain, 2021 (virtual)*
[[preprint]](download/papers/c2.pdf) [[slides]](download/slides/c2-slides.pdf) [[cite]](download/cites/c2.bib)

>**Abstract:**
>Modern software applications, including commercial ones, extensively use Open-Source Software (OSS) components, accounting for 90% of software products on the market. This has serious security implications, mainly because developers rely on non-updated versions of libraries affected by software vulnerabilities. 
>[...] In this work, we propose SIEGE, a novel automatic exploit generation approach based on genetic algorithms, which generates test cases that execute the methods in a library known to contain a vulnerability. These test cases [...] are also useful for security researchers to better understand how the vulnerability could be exploited in practice.

<a name="c1"></a>

#### :page_with_curl: [C1] Refactoring Android-specific Energy Smells: A Plugin for Android Studio
**E. Iannone**, F. Pecorelli, D. Di Nucci, F. Palomba, A. De Lucia.  
*In Proceedings of the 28th IEEE/ACM International Conference on Program Comprehension (ICPC 2020),
Seoul, South Korea, 2020 (virtual)*
[[preprint]](download/papers/c1.pdf)
[[video]](https://www.youtube.com/watch?v=iXFXpD5FqWA&t=141s)
[[cite]](download/cites/c1.bib)

>**Abstract:**
>Mobile applications are major means to perform daily actions, including social and emergency
>connectivity. However, their usability is threatened by energy consumption that may be impacted
>by code smells. [...] In this paper, we extend and revise aDoctor,
>a tool that we previously implemented to identify energy-related smells.