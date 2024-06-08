---
layout: page
title: Publications
permalink: /publications/
---
{::options auto_ids="false" /}

This page contains selected talks, papers, and other publications. 

[Google Scholar Profile](https://scholar.google.com/citations?user=sMjarhAAAAAJ&hl=en)

<a name="2022"></a>

## 2022

- <a name="BinaryPaper"></a>Payas Awadhutkar, Ahmed Tamrawi, RyanGoluch, Suresh Kothari. **Control Flow Equivalence Method for Establishing Sanctity of Compiling.** *[Computers & Security](https://www.sciencedirect.com/science/journal/01674048)*, January 2022.<br/>
**Paper:**&nbsp;[<a href="#" class="toggle-abstract">Abstract</a>]&nbsp;[[Paper](https://www.sciencedirect.com/science/article/pii/S0167404822000074)]
<div class="abstract"><p>Compiler trap doors constitute a longstanding security problem for which there is currently no  good solution. This paper presents a practical approach that shifts the focus from compiler  correctness  in its entirety to compiler  correctness for a particular software. The guarantee is that  the compiled binary's control flow is consistent with the source's control flow for a software of interest. We present an automated method to establish the equivalence by checking whether the source and the binary control flow graphs (CFGs) are isomorphic after semantics preserving graph transformations. The automated method produces evidence that can enable and simplify manual cross-checking as required to qualify an automated tool for safety-critical applications.  We believe the proposed control equivalence method and its automation would be equally useful in avionics, automotive, medical devices and other safety-critical software industries where establishing trust in the binary code is critically important.</p>
</div>

<a name="2020"></a>

## 2020

- <a name="PhD Thesis"></a>Payas Awadhutkar. **Human-centric verification for software safety and security** *[Iowa State University](https://www.iastate.edu)*, Ames, Iowa, May 2020.<br/>
**PhD Thesis:**&nbsp;[<a href="#" class="toggle-abstract">Abstract</a>][[Slides](/docs/thesis/final-defense.pdf)]&nbsp;[[Thesis](/docs/thesis/human-centric-verification.pdf)]&nbsp;[[Library](https://dr.lib.iastate.edu/handle/20.500.12876/32192)]
<div class="abstract"><p>Software forms a critical part of our lives today. Verifying software to avoid violations of safety
and security properties is a necessary task. It is also imperative to have an assurance that the
verification process was correct. We propose a human-centric approach to software verification. This
involves enabling human-machine collaboration to detect vulnerabilities and to prove the correctness
of the verification.
We discuss two classes of vulnerabilities. The first class is Algorithmic Complexity Vulnerabilities
(ACV). ACVs are a class of software security vulnerabilities that cause denial-of-service attacks. The
description of an ACV is not known a priori. The problem is equivalent to searching for a needle in
the haystack when we don’t know what the needle looks like. We present a novel approach to detect
ACVs in web applications. We present a case study audit from DARPA’s Space/Time Analysis for
Cybersecurity (STAC) program to illustrate our approach.
The second class of vulnerabilities is Memory Leaks. Although the description of the Memory
Leak (ML) problem is known, a proof of the correctness of the verification is needed to establish trust
in the results. We present an approach inspired by the works of Alan Perlis to compute evidence of
the verification which can be scrutinized by a human to prove the correctness of the verification. We
present a novel abstraction, the Evidence Graph, that succinctly captures the verification evidence
and show how to compute the evidence. We evaluate our approach against ML instances in the
Linux kernel and report improvement over the state-of-the-art results. We also present two case
studies to illustrate how the Evidence Graph can be used to prove the correctness of the verification.</p>
</div>

<a name="2019"></a>

## 2019

- <a name="ESEC-FSE2019"></a>Payas Awadhutkar, Ganesh Ram Santhanam, Benjamin Holland, Suresh Kothari. **DISCOVER: Detecting Algorithmic Complexity Vulnerabilities**, *[The 27th ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (ESEC/FSE 2019)](https://esec-fse19.ut.ee)*, Tallinn, Estonia, August 2019.<br/>
**Paper:**&nbsp;[<a href="#" class="toggle-abstract">Abstract</a>]&nbsp;[[PDF](https://dl.acm.org/doi/pdf/10.1145/3338906.3341177)]&nbsp;[<a href="https://youtu.be/LtaOYxo7AWI">Video</a>]
<div class="abstract"><p>Algorithmic Complexity Vulnerabilities (ACV) are a class of vulnerabilities that enable Denial of Service attacks. ACVs stem from asymmetric consumption of resources due to complex loop termination logic, recursion, and/or resource intensive library APIs. Completely automated detection of ACVs is intractable and it calls for tools that assist human analysts.</p><p>We present DISCOVER, a suite of tools that facilitates human-on- the-loop detection of ACVs. DISCOVER's workflow can be broken into three phases - (1) Automated characterization of loops, (2) Selection of suspicious loops, and (3) Interactive audit of selected loops. We demonstrate DISCOVER using a case study using a DARPA challenge app. DISCOVER supports analysis of Java source code and Java bytecode. We demonstrate it for Java bytecode.</p></div>

<a name="2018"></a>

## 2018

- <a name="DySDoc3"></a>Ahmed Tamrawi, Sharwan Ram, Payas Awadhutkar, Benjamin Holland, Ganesh Ram Santhanam, Suresh Kothari. **DynaDoc: Automated On-Demand Context-Specific Documentation.** *[Third International Workshop on Dynamic Software Documentation (DySDoc3)](https://dysdoc.github.io/dysdoc3)*, Madrid, Spain, September 2018.<br/>
<sup style="vertical-align: super; font-size: smaller;">&#10025;&nbsp;[Winner of the 2018 DOCGEN challenge comprehensiveness category!](https://dysdoc.github.io/dysdoc3/#section-program)</sup>
**Paper:**&nbsp;[<a href="#" class="toggle-abstract">Abstract</a>]&nbsp;[[Paper](/docs/publications/DynaDoc.pdf)]&nbsp;[[DynaDoc](https://github.com/EnSoftCorp/DynaDoc)]&nbsp;[[Sample Output](https://ensoftcorp.github.io/DynaDoc/)]
<div class="abstract"><p>This 2018 DOCGEN Challenge paper describes DynaDoc, an automated documentation system for on-demand context-specific documentation. A key novelty is the use of graph database technology with an eXtensible Common Software Graph Schema (XCSG). Using XCSG-based query language, DynaDoc can mine efficiently and accurately a variety of program artifacts and graph abstractions from millions of lines of code to provide semantically relevant and rich documentation. DynaDoc leverages the extensibility of XCSG to incorporate information about commits, issues, and other supplementary artifacts and links that information to program artifacts.</p>
</div>

- <a name="ICSE2018"></a>Benjamin Holland, Payas Awadhutkar, Suresh Kothari, Ahmed Tamrawi and Jon Mathews. **COMB: Computing Relevant Program Behaviors.** *The 40th International Conference on Software Engineering [(ICSE 2018)](https://www.icse2018.org/)*, Gothenburg, Sweden, May 2018.<br/>
**Paper:**&nbsp;[<a href="#" class="toggle-abstract">Abstract</a>]&nbsp;[[Toolbox](https://ensoftcorp.github.io/pcg-toolbox/)]&nbsp;[[Paper](https://dl.acm.org/doi/pdf/10.1145/3183440.3183476)]&nbsp;[<a href="https://youtu.be/YoOJ7avBIdk">Video</a>]
<div class="abstract"><p>The paper presents COMB, a tool to improve accuracy and efficiency of software engineering tasks that hinge on computing all relevant program behaviors.</p><p>Computing all behaviors and selecting the relevant ones is computationally intractable. COMB uses Projected Control Graph (PCG) abstraction to derive the relevant behaviors directly and efficiently. The PCG is important as the number of behaviors relevant to a task is often significantly smaller than the totality of behaviors.</p><p>COMB provides extensive capabilities for program comprehension, analysis, and verification. We present a basic case study and a Linux verification study to demonstrate various capabilities of COMB and the addressed challenges. COMB is designed to support multiple programming languages. We demonstrate it for C and Java.</p></div>

- <a name="Springer2018"></a>Suresh Kothari, Ganesh Santhanam, Benjamin Holland, Payas Awadhutkar, and Jon Mathews, Ahmed Tamrawi. **Catastrophic Cyber-Physical Malware.** *Springer Verlag Publishers*, April 2018.<br/>
**Book Chapter:**&nbsp;[<a href="#" class="toggle-abstract">Abstract</a>]&nbsp;[[Chapter](/docs/publications/cpm-malware.pdf)]
<div class="abstract"><p>With the advent of highly sophisticated cyber-physical malware (CPM) such as Industroyer, a cyberattack could be as destructive as the terrorist attack on 9/11, it would virtually paralyze the nation. We discuss as the major risks the vulnerability of: telecommunication infrastructure, industrial control systems (ICS), and mission-critical software.</p><p>In differentiating CPM from traditional malware, the difference really comes from the open-ended possibilities for malware triggers resulting from the wide spectrum of sensor inputs, and the almost limitless application-specific possibilities for designing malicious payloads.</p><p>Fundamentally, the challenges of detecting sophisticated CPM stem from the complexities inherent in the software at the heart of cyber-physical systems. We discuss three fundamental challenges: explosion of execution behaviors, computational intractability of checking feasible behaviors, and difficult-to-analyze programing constructs.</p><p>In detecting novel CPM, the tasks are: developing plausible hypotheses for malware trigger and mali- cious payload, analyzing software to gather evidence based on CPM hypotheses, and verifying software to prove or refute a hypothesis based on the gathered evidence. We discuss research directions for effective automation to support these tasks.</p></div>

<a name="2017"></a>

## 2017

- <a name="WSC2017"></a>Suresh Kothari, Payas Awadhutkar, Ahmed Tamrawi, Jon Mathews. **Modeling Lessons from Verifying Large Software Systems for Safety and Eecurity.** *[The 2017 Winter Simulation Conference (WSC 2017)](http://meetings2.informs.org/wordpress/wsc2017/)*, Las Vegas, Nevada, December, 2017.<br/>
**Paper:**&nbsp;[<a href="#" class="toggle-abstract">Abstract</a>]&nbsp;[[Paper](http://simulation.su/uploads/files/default/2017-kothari-awadhutkar-tamrawi-mathews.pdf)]
<div class="abstract"><p>Verifying software in mission-critical Cyber-Physical Systems (CPS) is an important but daunting task with challenges of accuracy and scalability. This paper discusses lessons learned from verifying properties of the Linux kernel. These lessons have raised questions about traditional verification approaches, and have led us to a model-based approach for software verification. These models are high-level models of the software, as opposed to the prevalent formal methods with low-level representations of software. We use models to gain insights into software verification challenges and use those insights to improve software verification. We demonstrate significant advantages of models with a Linux kernel study involving verification of 66,609 Lock instances. We use models to: (a) analyze and find flaws in verification results from LDV, a top-rated Linux verification tool, (b) show significant improvement over LDV by improving accuracy, speed, and by verifying 99.3% instances compared to 65.7% instances by LDV.</p></div>

- <a name="APSEC2017"></a>Payas Awadhutkar, Ganesh Ram Santhanam, Benjamin Holland, Suresh Kothari. **Intelligence Amplifying Loop Characterizations for Detecting Algorithmic Complexity Vulnerabilities.** *The 24th Asia-Pacific Software Engineering Conference [(APSEC 2017)](http://www.apsec2017.org/)*, Nanjing, China, December 2017.<br/>
**Paper:**&nbsp;[<a href="#" class="toggle-abstract">Abstract</a>]&nbsp;[[Paper](/docs/publications/loop-catalog.pdf)]
<div class="abstract"><p>Algorithmic complexity vulnerabilities (ACVs) can be exploited to cause denial-of-service. Detecting ACVs is hard because of the numerous kinds of loop complexities that cause ACVs. This renders automatic detection intractable for ACVs. State-of-the-art loop analyses aim to obtain precise loop iteration bounds automatically; they can do so for relatively simple loops. This research focuses on techniques to amplify intelligence so that the analyst can gain a deeper knowledge of complex loops that is necessary to discover ACVs. We describe: (a) loop abstractions and use them to define patterns and other characterizations of loop behaviors which in turn can be applied to create automated filters to isolate complex loops with high likelihood of ACVs, (b) innovative visual querying mechanisms for interactive loop analysis; they enable the analyst to hypothesize ACVs and gather the necessary evidence for targeted dynamic analysis for confirming ACVs. These capabilities are illustrated with an ACV detection case study. We present an empirical study using over 5000 loops from 4 open source libraries, and 18 DARPA challenge apps. The study evaluates the usefulness of the loop characterizations and patterns to enable the analyst to create effective filters to isolate complex loops.</p></div>

<a name="2016"></a>

## 2016

- <a name="ISSREW2016"></a>Suresh Kothari, Payas Awadhutkar, Ahmed Tamrawi. **Insights for Practicing Engineers from a Formal Verification Study of the Linux Kernel.** *The 2016 IEEE International Symposium on Software Reliability Engineering Workshops [ISSREW 2016](http://2016.issre.net/)*, Ottawa, Canada, October 2016.<br/>
**Paper:**&nbsp;[<a href="#" class="toggle-abstract">Abstract</a>]&nbsp;[[Paper](/docs/publications/fvpe.pdf)]
<div class="abstract"><p>Formal verification of large software has been an illusive target, riddled with the problem of scalability. Even if the obstacle of scale may be cleared, major challenges remain to adopt formal verification in practice. This paper presents an empirical study using a top-rated formal verification tool for Linux, and draws insights from the study to discuss the intrinsic challenges for adopting formal verification in practice. We discuss challenges that focus on practical needs: (a) facilitate crosschecking of verification results, (b) enable the use of formal verification for certification, and (c) integrate formal methods in a development environment. Leaning on visionary papers by Turing Award recipients, we present novel ideas for advancing formal verification in new directions that would help practicing engineers.</p>
</div>

- <a name="SCAM2016"></a>Benjamin Holland, Ganesh Ram Santhanam, Payas Awadhutkar, and Suresh Kothari. **Statically-informed Dynamic Analysis Tools to Detect Algorithmic Complexity Vulnerabilities.** *The 16th IEEE International Working Conference on Source Code Analysis and Manipulation ([SCAM 2016](http://www.ieee-scam.org/2016/))*, Raleigh, North Carolina, October 2016.<br/>
**Paper:**&nbsp;[<a href="#" class="toggle-abstract">Abstract</a>]&nbsp;[[Paper](/docs/publications/scam2016.pdf)]&nbsp;[[Video](https://www.youtube.com/watch?v=8dH7q9aPD44)]&nbsp;[[SID Tools](https://ensoftcorp.github.io/SID/)]
<div class="abstract"><p>Algorithmic Complexity (AC) vulnerabilities can be exploited to cause a denial of service attack. Specifically, an adversary can design an input to trigger excessive (space/time) resource consumption. It is not possible to build a fully automated tool to detect AC vulnerabilities. Since it is an open-ended problem, a human-in-loop exploration is required to find the program loops that could have AC vulnerabilities. Ascertaining whether an arbitrary loop has an AC vulnerability is itself difficult, which is equivalent to the halting problem.</p><p>This paper is about a pragmatic engineering approach to detect AC vulnerabilities. It presents a statically-informed dynamic (SID) analysis and two tools that provide critical capabilities for detecting AC vulnerabilities. The first is a static analysis tool for exploring the software to find loops as the potential candidates for AC vulnerabilities. The second is a dynamic analysis tool that can try many different inputs to evaluate the selected loops for excessive resource consumption. The two tools are built and integrated together using the interactive software analysis, transformation, and visualization capabilities provided by the Atlas platform.</p><p>The paper describes two use cases for the tools, one to detect AC vulnerabilities in a Java bytecode and another to use the tools in an undergraduate algorithm class for students to perform experiments to learn different aspects of algorithmic complexity.</p></div>