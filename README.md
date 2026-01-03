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
- [<b>Lectures and Slides</b>](calendar.md)
- Ashwin's Office Hours: Fri 2:30pm-4:00pm (or by appointment) in [ICME Mezzanine level, Room M05](https://campus-map.stanford.edu/?id=04-080)
- Catherine's Office Hours: Tuesday & Thursday 4:30 - 5:30 PM in Huang Basement

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

# Coures Project
The problem we want to solve is to identify the optimal extractions from your IRA and your regular investment account so that we maximize your annual (after-tax) consumption. To keep things simple, we work with the constraint that the inflation-adjusted annual consumption is the same over all T years (note that this inflation-adjusted annual consumption is the quantity being maximized). [See details here](https://colab.research.google.com/drive/1AqTM-uhOOiodnvO9xgKFqrKc6G53C_SE#scrollTo=iSDGfha88iux).

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
*   [Python codebase Tikhon Jelvis and I have developed](https://github.com/TikhonJelvis/RL-book/tree/master/rl) to help you "learn through coding"
*   [Technical Documents/Lecture Slides/Assignments Catherine and I have prepared for this course](https://github.com/coverdrive/technical-documents/tree/master/finance/cme241)
*   [Ed Discussion](https://edstem.org/us/courses/70339) (Online discussion forum)

# Grading

*   45%: Assignments (15% per assignment, 3 total)
*   50%: Course Project
*   5%: Attendance (18/20 minimum lecture attendance)

# Access and Accommodations

Stanford is committed to providing equal educational opportunities for disabled students. Disabled students are a valued and essential part of the Stanford community. We welcome you to our class.

If you experience disability, please register with the Office of Accessible Education (OAE). Professional staff will evaluate your needs, support appropriate and reasonable accommodations, and prepare an Academic Accommodation Letter for faculty. To get started, or to re-initiate services, please visit [oae.stanford.edu](http://oae.stanford.edu)

If you already have an Academic Accommodation Letter, we invite you to share your letter with us. Academic Accommodation Letters should be shared at the earliest possible opportunity so we may partner with you and OAE to identify any barriers to access and inclusion that might be encountered in your experience of this course.



