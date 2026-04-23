---
layout: minimal
title: CS4720 Research in Program Analysis
nav_exclude: true
seo:
  type: Course
  name: CS4720 Research in Program Analysis
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

### [Burcu Kulahcioglu Ozkan](https://burcuku.github.io/home/), &nbsp; [Arie van Deursen](https://avandeursen.com/about/)

### TU Delft, Spring 2026/Q4 



## Course description:

This course provides a comprehensive introduction to the field of software analysis, a critical aspect of software development and maintenance. We will delve into both theoretical foundations and practical applications, learning how to analyze, understand, and improve software systems. This course explores a comprehensive set of techniques for software analysis, including practical formal methods, model checking, static and dynamic analysis, and other key approaches to evaluating and improving software systems. Through hands-on project, you will gain experience understanding and applying these techniques and presenting them using a scientific valid methodology.

## Study goals:

At the end of this course, you will be able to:  
1. Explain different software analysis approaches, such as model checking, static, and dynamic analyses.  
2. Apply the software analysis techniques to sample programs.  
3. Analyze the results of software analysis techniques in terms of their precision and computational performance.  
4. Evaluate the performance of different software analysis techniques and compare their pros and cons. 


## Course organization

* **5 ECTS:** You need to devote at least 140 hours of study for this course.  
* **In-class meetings:** The course consists of 8 2-hour meetings. 
* **Assessment:** Group Report (weighting 80%), Group Presentation and Participation (weighting 20%)
* **Teams:** The students are responsible to form teams and communicate them to the course TAs.


## Teaching assistants

* [Ege Berkay Gulcan](https://eldarfin.github.io/)
* [Luan Li](https://github.com/lililuanluan)
* [Zahra Seyedghorban](https://github.com/vagabondboffinn)


## Course schedule:


{% assign currentschedule = site.modules | where: 'year', '2026' %}
{% for module in currentschedule %}
{{ module }}
{% endfor %}


The schedule of the presentations will be announced in the first week of lectures.
The list of papers and the schedule is subject to small changes during the term.



## Paper presentations:

Each presentation will consist of a presentation followed by a Q&A session. 

Each paper will be presented by a team of 2-3 students, where all students are expected to participate in the presentation and the Q/A. The presentations will be graded individually, based on *individual performance*.

You are expected to **read all the presented papers**, give **peer-feedback to assigned presentations**, and  **actively participate in the Q&A discussions**.

 
<!--  
Tentative list of the papers to be presented and discussed:
: - ["Can LLMs transform natural language intent into formal method postconditions"](https://dl.acm.org/doi/10.1145/3660791), FSE'24  
: - ["OSVBENCH: Benchmarking LLMs on specification generation tasks for operating system verification"](https://arxiv.org/pdf/2504.20964v2), AAAI'26   
: - ["SysMoBench: Evaluating AI on formally modeling complex real-world systems"](https://arxiv.org/abs/2509.23130), Arxiv'26     
: - ["MutDafny: A mutation-based approach to assess Dafny specifications"](https://arxiv.org/abs/2511.15403), ICSE'26  

: - ["Model checking distributed protocols in Must](https://dl.acm.org/doi/10.1145/3689778), OOPSLA'24
: - ["Model checking guided testing for distributed systems"](https://dl.acm.org/doi/10.1145/3552326.3587442), EuroSys'23   
: - ["Greybox fuzzing of distributed systems"](https://dl.acm.org/doi/10.1145/3576915.3623097), CCS'23
: - ["Model-guided fuzzing of distributed systems"](https://dl.acm.org/doi/10.1145/3763060), OOPSLA'25
: - ["Formal model guided conformance testing for blockchains"](https://arxiv.org/pdf/2501.08550), Arxiv'25  
: - ["Smart casual verification of the confidential consortium framework"](https://www.usenix.org/conference/nsdi25/presentation/howard), NSDI'25
: - ["Validating traces of distributed programs against TLA+ specifications](https://inria.hal.science/hal-04813639v1/file/2404.16075v2.pdf), SEFM'24  
: - ["Trace validation of unmodified concurrent systems with OmniLink"](https://arxiv.org/abs/2601.11836), Arxiv'26
: - ["VeriPlan: Integrating formal verification and LLMs into end-user planning"](https://dl.acm.org/doi/10.1145/3706598.3714113), CHI'05  
: - ["Runtime protocol refinement checking for distributed protocol implementations"](https://www.usenix.org/conference/nsdi25/presentation/ding), NSDI'25
: - ["AgentSpec: Customizable runtime enforcement for safe and reliable LLM agents"](https://arxiv.org/abs/2503.18666), ICSE'26     
: - ["VeriGrey: Greybox Agent Validation"](https://arxiv.org/abs/2603.17639), ArXiv'26
-->

<!-- Generating and assessing formal specifications:-->
<!--Model checking, automated testing, runtime verification, trace validation: -->    


## Course projects:
 
 
Project assignments are announced and submitted at [BrightSpace](https://brightspace.tudelft.nl/d2l/home/774599).

<!-- Please find the information about the course projects on the [BrightSpace](https://brightspace.tudelft.nl/d2l/home/680678). -->


## Contact and communication:

Announcements will be made through [BrightSpace](https://brightspace.tudelft.nl/d2l/home/774599).

<!-- You can also enroll in [the course Mattermost channel](https://mattermost.tudelft.nl/signup_user_complete/?id=bq4nuq8hctra7ci7n7smr3145r&md=link&sbr=su) to connect to your peers and faster discussion. -->
