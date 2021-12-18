---
layout: post
title:  "First Invited Talk"
permalink: first_talk
comments: false
---

Today at **[SAP](www.sap.com)** I'll give my very first invited talk on **"Automated Test Case Generation: Toward Its Application in Exploit Generation for Known API Vulnerabilities"**.

I want to sincerely thank [Antonino Sabetta](https://sabetta.com/), member of the Security Research team working on Software Security, for inviting me to talk with a wide audience of security enthusiasts!
I really hope this will be a chance to start new collaborations in the near future.

***Talk Abstract**: Software testing is an expensive activity, taking over 30% of the total project effort. Most testing strategies involve the use of systematic techniques, such as coverage testing. These, however, are quite difficult to apply manually, making it necessary to use automatic solutions. Most of these rely on evolutionary strategies, such as Genetic Algorithms (GAs), to generate a near-optimal test suite with respect to a specific set of coverage criteria.
Differently, in the context of security testing the main approaches aim to discover vulnerabilities in the source code, without considering any risk assessment. The tool Eclipse Steady partially fills this gap with an in-depth reachability analysis of OSS vulnerabilities, also providing a set of metrics related to the effort of a library update. Unfortunately, in order to achieve adequate reachability, the tool requires a large test suite from which the executions are started, which could be difficult to prepare in a short time. Any test case that can reach an OSS vulnerability could be considered as a "template" of an exploit.
In this talk, I will show (1) the core concepts behind Automatic Test Case Generation (ATCG), (2) the implementation of ATCG with GAs, and (3) present the first step toward an Automatic Exploit Generation technique, called SIEGE, whose goal is to generate exploit templates for specific known OSS vulnerabilities. The talk is concluded by presenting the future agenda, concerning the provision of a novel risk assessment technique for measuring the actual exploitability of OSS vulnerabilities.*

Check out the slides [here](./download/talks/t1.pdf).
