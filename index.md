---
layout: home
title: CS6501, Fall 2025
nav_exclude: true
type: Course
name: CS6501--Serverless AI
---

# {{ site.title }}: {{ site.tagline }}
{: .mb-2 }
{: .fs-6 .fw-300 }

{% if site.announcements %}
{{ site.announcements.last }}
 [Announcements]({{ site.baseurl }}{% link announcements.md %}){: .btn .btn-outline .fs-3 }
{% endif %}


## Overview

> **Note for undergrad students interested in taking this course:**
Please send your latest CV to the instructor if you are interested in
taking this course. 

**Serverless computing** has emerged as a transformative paradigm in
cloud computing, offering elastic pay-per-use compute abstractions
that free developers from managing infrastructure. At the same time,
the rapid advancement of **artificial intelligence (AI)**,
particularly **large language model (LLM)** serving and inference,
has introduced new challenges in cloud computing and systems, ranging
from resource efficiency to scalability and performance. The
confluence of these two critical domains is giving rise to
**Serverless + AI**: a new design space where serverless platforms are
reimagined to support modern AI workloads.


This course is a graduate-level seminar-based course, exploring both
foundational and cutting-edge research in serverless computing and
its intersection with AI systems. 

The course consists of three components. The first two focus on paper
reading & in-class presentations and discussions, while the third
centers on building a demonstrable MVP that addresses a practical
problem in serverless AI.

1. **Serverless computing and Function-as-a-Service**: In this part, we
will study the design and implementation of serverless architectures
and a series of well-known problems of modern FaaS platforms
(including cold starts, virtualization, state management, fault
tolerance, and applications, etc.)
2. **Serverless systems for AI applications**: In this part, we will
explore how serverless computing is being reimagined / extended to
support emerging AI applications, such as serverless LLM inference,
serverless fine-tuning, and on-demand GPU allocation, etc.
3. **Project**: The most exciting part of this course is a term-long
(research) project where you will design and build a serverless AI
system that tackles a real-world pain point. *Why this is fun:* you
will work side-by-side with a **state-of-the-art AI coding
agent**---to bring your MVP to life. The instructor will supply you
with a list of interesting project ideas---some with a baseline
codebase he built for fun (and maybe a bit for profit :-)
  - We will provide necessary resources, including **{coding agent CLI
 and cloud infrastructure}**. More details will be
shared soon... 


## Lecture Info

* Instructor: [Yue Cheng](https://tddg.github.io)
* Meeting time: MW 11am - 12:15pm
* Location: Rice Hall 340


## Topic List

Serverless computing and FaaS:

* Introduction
* Function-as-a-Service platforms & workloads
* Cold starts
* Stateful serverless computing
* Serverless parallel computing & programming
* Serverless applications
* Serverless storage


LLMs and serverless AI:

* LLM serving
  * Key-value cache management
  * Prefill vs. decode
  * Parallelism
  * Cloud LLM serving
  
* Serverless AI
  * Serverless LLM in the wild
  * Serverless AI services
  * Serverless AI infrastructure


## Prerequisite

* CS 4414 (Operating Systems), CS 4740 / CS 6111 (Cloud Computing), or other related systems courses. 
  * **Hands-on system programming skills** are strongly recommended.

