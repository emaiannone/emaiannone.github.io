---
layout: category
title: Publications
permalink: publications
sidebar_sort_order: 1
---

<a name="c4"></a>

#### :page_with_curl: [C4] Predicting The Energy Consumption Level of Java Classes in Android Apps: An Exploratory Analysis
**E. Iannone**, M. De Stefano, F. Pecorelli, A. De Lucia  
*In Proceedings of the 9th IEEE/ACM International Conference on Mobile Software Engineering and Systems 2022 (MobileSoft 2022), Pittsburgh, PA, US, 2022*.  
<button type="button" onclick="location.href='download/papers/c4.pdf'">Preprint</button> <button type="button" onclick="location.href='download/cites/c4.bib'">Cite</button> <button type="button" onclick="location.href='https://www.youtube.com/watch?v=DIv471PKrTQ'">Video</button>

<details open>
  <summary><b>Summary</b></summary>
  <hr>
  <p align="justify">Mobile applications usage has considerably increased since the last decade. One of the most influencing factors for user experience is battery consumption, which should have the minimum possible impact on the battery.</p>
  <p align="justify">The current body of knowledge on energy consumption measurement only reports approaches relying on complex instrumentation or stressing the application with many test scenarios, thus making it hard to measure energy consumption.</p>
  <p align="justify">In this work, we explore the performance of machine learning to predict the energy consumption level of Java classes in Android apps, leveraging only on a set of structural properties extracted via source code analysis.
  The preliminary results show poor performance likely caused by (1) an insufficient amount of training data, (2) a limited feature set, and (3) an inappropriate way to label the dependent variable. The paper concludes by presenting the limitations of the experimented models and the possible strategies to address them.</p>
</details>

<hr>

<a name="j3"></a>

#### :page_with_curl: [J3] Just-in-Time Software Vulnerability Detection: Are We There Yet?
F. Lomio, **E. Iannone**, A. De Lucia, F. Palomba, V. Lenarduzzi  
*Journal of Systems and Software (JSS)*.  
<button type="button" onclick="location.href='download/papers/j3.pdf'">Preprint</button> <button type="button" onclick="location.href='download/cites/j3.bib'">Cite</button>
<details>
  <summary><b>Summary</b></summary>
  <hr>
  <p align="justify">Software vulnerabilities are weaknesses in source code that might be exploited to cause harm or loss. Previous work has proposed several machine learning approaches to detect them.
  While most of these techniques work at release-level, researchers have shown that a commit-level identification of source code issues might better fit the developer’s needs.</p>
  <p align="justify">We perform an empirical study where we consider nine projects accounting for 8,991 commits and experiment with eight machine learners using process, product, and textual metrics.</p>
  <p align="justify">We point out three main findings: (1) basic machine learners rarely perform well; (2) ensemble learning algorithms based on boosting can substantially improve the performance; and (3) the combination of more metrics does not necessarily improve the performance.
  Further research should focus on the introduction of smart approaches for feature selection and training strategies.</p>
</details>

<hr>

<a name="j2"></a>

#### :page_with_curl: [J2] The Secret Life of Software Vulnerabilities: A Large-Scale Empirical Study
**E. Iannone**, R. Guadagni, F. Ferrucci, A. De Lucia, F. Palomba  
*IEEE Transactions on Software Engineering (TSE)*.  
<button type="button" onclick="location.href='download/papers/j2.pdf'">Preprint</button> <button type="button" onclick="location.href='download/cites/j2.bib'">Cite</button>

<details>
  <summary><b>Summary</b></summary>
  <hr>
  <p align="justify">Software vulnerabilities are weaknesses in source code that can be potentially exploited to cause loss or harm. While researchers have been devising a number of methods to deal with vulnerabilities, there is still a noticeable lack of knowledge on their software engineering life cycle, for example how vulnerabilities are introduced and removed by developers.</p>
  <p align="justify">In this paper we consider 3,663 vulnerabilities with public patches from the National Vulnerability Database and define an eight-step process involving both automated parts and manual analyses.</p>
  <p align="justify">The investigated vulnerabilities can be classified in 144 categories, take on average at least 4 contributing commits before being introduced, and half of them remain unfixed for at least more than one year.
  Most of the contributions are done by developers with high workload, often when doing maintenance activities, and removed mostly with the addition of new source code aiming at implementing further checks on inputs.</p>
</details>

<hr>

<a name="c3"></a>

#### :page_with_curl: [C3] Toward Understanding the Impact of Refactoring on Program Comprehension
G. Sellitto, **E. Iannone**, Z. Codabux, V. Lenarduzzi, A. De Lucia, F. Palomba, F. Ferrucci  
***To appear** In Proceedings of the 29th IEEE/ACM International Conference on Software Analysis, Evolution and Reengineering (SANER 2022), Honolulu, Hawaii, US, 2022*.  
<button type="button" onclick="location.href='download/papers/c3.pdf'">Preprint</button> 

<details>
  <summary><b>Summary</b></summary>
  <hr>
  <p align="justify">Software refactoring is the activity associated with developers changing the internal structure of source code without modifying its external behavior. The literature argues that refactoring might have beneficial and harmful implications.</p>
  <p align="justify">This paper continues the narrative on the effects of refactoring by exploring the dimension of program comprehension, namely the property that describes how easy it is for developers to understand source code.</p>
  <p align="justify">First, we mine refactoring data and, for each commit involving a refactoring, we compute (i) the amount and type(s) of refactoring actions performed and (ii) eight state-of-the-art program comprehension metrics. Afterwards, we build statistical models relating the various refactoring operations to readability metrics.
  The key results are that refactoring has a notable impact on most of the readability metrics considered.</p>
</details>

<hr>

<a name="j1"></a>

#### :page_with_curl: [J1] Impacts of Software Community Patterns on Process and Product: An Empirical Study
M. De Stefano, **E. Iannone**, F. Pecorelli, D.A. Tamburri  
*Science of Computer Programming (SCICO)*.  
<button type="button" onclick="location.href='download/papers/j1.pdf'">Preprint</button> <button type="button" onclick="location.href='download/cites/j1.bib'">Cite</button>

<details>
  <summary><b>Summary</b></summary>
  <hr>
  <p align="justify">Software engineering projects are now more than ever a community effort. Researchers have shown that their success not only depends on source code quality, but also on other aspects like the balance of power distance, culture, and global engineering practices, and more.</p>
  <p align="justify">In this paper, we propose an exploratory study on the relation between community patterns and aspects related to the quality of software products and processes by mining open-source software repositories.</p>
  <p align="justify">Our findings show that different organizational patterns are connected to different forms of socio-technical problems; further on, they support two possible conclusions: (1) practitioners should put in place specific preventive actions aimed at avoiding the emergence of community smells and (2) such actions should be drawn according to the contextual conditions of the organization and the project.</p>
</details>

<hr>

<a name="c2"></a>

#### :page_with_curl: [C2] Toward Automated Exploit Generation for Known Vulnerabilities in Open-Source Libraries
**E. Iannone**, D. Di Nucci, A. Sabetta, A. De Lucia  
*In Proceedings of the 29th IEEE/ACM International Conference on Program Comprehension (ICPC 2021), Madrid, Spain, 2021 (virtual)*.  
<button type="button" onclick="location.href='download/papers/c2.pdf'">Preprint</button> <button type="button" onclick="location.href='download/slides/c2-slides.pdf'">Slides</button> <button type="button" onclick="location.href='download/cites/c2.bib'">Cite</button>

<details>
  <summary><b>Summary</b></summary>
  <hr>
  <p align="justify">Modern software applications, including commercial ones, extensively use Open-Source Software (OSS) components, accounting for 90% of software products on the market. This has serious security implications, mainly because developers rely on non-updated versions of libraries affected by software vulnerabilities. </p>
  <p align="justify">In this work, we propose SIEGE, a novel automatic exploit generation approach based on genetic algorithms, which generates test cases that execute the methods in a library known to contain a vulnerability. These test cases are also useful for security researchers to better understand how the vulnerability could be exploited in practice.</p>
</details>

<hr>

<a name="c1"></a>

#### :page_with_curl: [C1] Refactoring Android-specific Energy Smells: A Plugin for Android Studio
**E. Iannone**, F. Pecorelli, D. Di Nucci, F. Palomba, A. De Lucia  
*In Proceedings of the 28th IEEE/ACM International Conference on Program Comprehension (ICPC 2020), Seoul, South Korea, 2020 (virtual)*.  
<button type="button" onclick="location.href='download/papers/c1.pdf'">Preprint</button> <button type="button" onclick="location.href='download/cites/c1.bib'">Cite</button> <button type="button" onclick="location.href='https://www.youtube.com/watch?v=iXFXpD5FqWA&t=141s'">Video</button>

<details>
  <summary><b>Summary</b></summary>
  <hr>
  <p align="justify">Mobile applications are major means to perform daily actions, including social and emergency connectivity.</p>
  <p align="justify">However, their usability is threatened by energy consumption that may be impacted by code smells.</p>
  <p align="justify">In this paper, we extend and revise aDoctor, a tool that we previously implemented to identify energy-related smells.</p>
</details>
