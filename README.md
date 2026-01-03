---
layout: home
title: Home
nav_exclude: false
permalink: /:path/
seo:
  type: Course
  name: CME 241
---

Welcome to the Winter 2026 edition of CME 241: Foundations of Reinforcement Learning with Applications in Finance.

- Instructor: [Ashwin Rao](http://stanford.edu/~ashlearn)
- Course Assistant (CA): [Catherine Chen](https://icme.stanford.edu/people/catherine-chen)
- Lectures: Wed & Fri 4:30pm-5:50pm in [Gates B12](https://campus-map.stanford.edu/?srch=Gates+B12)
- [<b>Lecture Topics Schedule</b>](calendar.md)
- Ashwin's Office Hours: Fri 2:30pm-4:00pm (or by appointment) in [ICME Mezzanine level, Room M05](https://campus-map.stanford.edu/?id=04-080)
- Catherine's Office Hours: Tuesday & Thursday 4:30 - 5:30 PM in Huang Basement

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}


# Overview of the Course

- Theory of Markov Decision Processes (MDPs)
- Dynamic Programming (DP) Algorithms
- Backward Induction (BI) and Approximate DP (ADP) Algorithms
- Reinforcement Learning (RL) Algorithms
- Plenty of Python implementations of models and algorithms
- We apply these algorithms to 5 Financial/Trading problems:
  - (Dynamic) Asset-Allocation to maximize Utility of Consumption
  - Pricing and Hedging of Derivatives in an Incomplete Market
  - Optimal Exercise/Stopping of Path-dependent American Options
  - Optimal Trade Order Execution (managing Price Impact)
  - Optimal Market-Making (Bid/Ask managing Inventory Risk)
- By treating each of the problems as MDPs (i.e., Stochastic Control)
- We will go over classical/analytical solutions to these problems
- Then we will introduce real-world considerations, and tackle with RL (or DP)
- The course blends Theory/Mathematics, Programming/Algorithms and Real-World Financial Nuances

# Learning Material

*   [Course Textbook](https://www.amazon.com/Foundations-Reinforcement-Learning-Applications-Finance/dp/1032124121) (henceforth known as "RLForFinanceBook"). PDF version available as [free download](https://stanford.edu/~ashlearn/RLForFinanceBook/book.pdf)
*   [Accompanying Python codebase (git repo)](https://github.com/TikhonJelvis/RL-book/tree/master/rl) to help you "learn through coding"
*   [<b>Lecture Slides</b>](calendar.md)
*   [Ed Discussion](https://edstem.org/us/courses/90295/discussion) (Online discussion forum)
*   Python Coding Background
    * [Chapter 2 Colab](https://colab.research.google.com/drive/1OOz8vKQRyJeindRwp0cKC9rCENitx1vQ) (overview of the Python pre-reqs)
    * Python workshop - [Part1](https://colab.research.google.com/drive/1kN6RX031p4ExcKPkaBxgk7qx30Ds_U50?usp=sharing) and [Part2](https://colab.research.google.com/drive/1safN7aN8d3hvS9KJMdXTGv_aXhl9utkl) (dig deeper into the pre-reqs with these tutorials)
 
# Course Project
The course project is meant to be configured within the realm of a broad topic that is of high practical
relevance, has traditionally been challenging to solve, and is well suited for appropriate formulation
and solution using the mathematical and computational techniques taught in this course. Each
project group can specialize the project scope within this broad topic.

The broad topic is <b>Personal Finance Optimization</b>. At various stages of our lives, we are
trying to grow our wealth while simultaneously making payments on our obligations and tactically
paying for optional/selective products and services that give us specific forms of satisfaction or
enjoyment. We typically grow our wealth by receiving salary, bonuses and equity while doing jobs
and by making appropriate choices on investments made with our savings (eg: stocks, real-estate,
gold etc.) Our payments obligations are typically our rent or mortgage, vehicle payments, utility bills
etc. Our tactical payments for optional/selective products/services giving us satisfaction/enjoyment
can be wide-ranging - a vacation, a luxury car, a birthday celebration, a gift for a loved one etc.
The objective is to maximize the aggregated <i>Utility of Consumption</i> (something that you will learn
about during the course). The problem is to make a sequence of optimal decisions on the optional/selective products/services,
amidst significant uncertainty around how our lives will transpire. [See details here](https://github.com/coverdrive/technical-documents/blob/master/finance/cme241/Project-Winter2026.pdf).

# Grading

*   45%: Assignments (15% per assignment, 3 total)
*   50%: Course Project
*   5%: Attendance (18/20 minimum lecture attendance)

# Access and Accommodations

Stanford is committed to providing equal educational opportunities for disabled students. Disabled students are a valued and essential part of the Stanford community. We welcome you to our class.

If you experience disability, please register with the Office of Accessible Education (OAE). Professional staff will evaluate your needs, support appropriate and reasonable accommodations, and prepare an Academic Accommodation Letter for faculty. To get started, or to re-initiate services, please visit [oae.stanford.edu](http://oae.stanford.edu)

If you already have an Academic Accommodation Letter, we invite you to share your letter with us. Academic Accommodation Letters should be shared at the earliest possible opportunity so we may partner with you and OAE to identify any barriers to access and inclusion that might be encountered in your experience of this course.



