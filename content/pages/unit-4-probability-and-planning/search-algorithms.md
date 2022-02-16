---
content_type: page
learning_resource_types: []
ocw_type: CourseSection
parent_title: 'Unit 4: Probability and Planning'
parent_type: CourseSection
parent_uid: f216c72d-f519-1296-c531-19833fb7c73a
title: Search Algorithms
uid: 497582d8-68ca-82e7-7ef7-6b997e187b13
---

« [Previous]({{< baseurl >}}/pages/unit-4-probability-and-planning/state-estimation) | [Next]({{< baseurl >}}/pages/unit-4-probability-and-planning/optimizing-a-search) »

Session Overview
----------------

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}
![The eight puzzle in its goal state.]({{< resource_file 746bcd6f-2b77-7e86-0f5f-e4d244b1c9eb >}})
{{< tdclose >}}
{{< tdopen >}}


In this session, we introduce the idea of search. We've designed systems to tackle static problems and modeled the idea of uncertainty, but we still haven't developed a way to approach that uncertainty and engage in decision-making that we can codify into our systems.

We can tackle uncertainty through search; if we know the domain of possible solutions to a problem, and know the steps to get from one part of the domain to the other, then we can search the domain until we reach the solution.

The overview handout provides a more detailed introduction, including the big ideas of the session, key vocabulary, what you should understand (theory) and be able to do (practice) after completing this session, and additional resources.

*   [Session 12 Handout: Search Algorithms (PDF)]({{< baseurl >}}/resources/mit6_01scs11_ses12)


{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Session Content
---------------

### Readings

Read sections 8.1-8.4 of the course notes.

*   [Chapter 8: Long-Term Decision-Making and Search (PDF)]({{< baseurl >}}/resources/mit6_01scs11_chap08)

### Lecture Video

Watch the lecture video. The handout and slides present the same material, but the slides include answers to the in-class questions.

*   [Lecture 12: Search Algorithms]({{< baseurl >}}/resources/lecture-1-object-oriented-programming-9)

> ### About this Video
> 
> Two search algorithms are introduced, depth-first search and breadth-first search. Pruning rules (including dynamic programming) are also considered, so that the same state is not visited repeatedly.

*   [Lecture handout (PDF)]({{< baseurl >}}/resources/mit6_01scs11_lec12_handout)
*   [Lecture slides (PDF)]({{< baseurl >}}/resources/mit6_01scs11_lec12)

### Recitation Video

These videos have been developed for OCW Scholar, and are designed to supplement the lecture videos.

*   [Recitation 15: Search: Basics]({{< baseurl >}}/resources/recitation-2-inheritance-5)

Session Activities
------------------

The problems in the tables below are taken from the 6.01 Online Tutor, an interactive environment that is not available on OCW. Do not try to answer these questions in the PDF files; answers will not be checked, and cannot be submitted.

### Software Lab

*   [Software Lab 13: Farmer Goat Wolf Cabbage (PDF)]({{< baseurl >}}/resources/mit6_01scs11_swlab13)
*   [Code for Software Lab 13 (ZIP)]({{< baseurl >}}/resources/swlab13) (This ZIP file contains: 2 .py files.)

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
PROBLEM #
{{< thclose >}}
{{< thopen >}}
QUESTIONS
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}
13.1.1
{{< tdclose >}}
{{< tdopen >}}
[Farmer et al.: Machine (PDF)]({{< baseurl >}}/resources/mit6_01scs11_13_1_1)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
13.1.2
{{< tdclose >}}
{{< tdopen >}}
[Farmer et al.: Search (PDF)]({{< baseurl >}}/resources/mit6_01scs11_13_1_2)
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

### Design Lab

*   [Design Lab 13: I Walk the Line (PDF)]({{< baseurl >}}/resources/mit6_01scs11_designlab13)
*   [Code for Design Lab 13 (ZIP)]({{< baseurl >}}/resources/designlab13) (This ZIP file contains: 5 .py files.)

### Additional Exercises

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
PROBLEM #
{{< thclose >}}
{{< thopen >}}
QUESTIONS
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}
13.3.1
{{< tdclose >}}
{{< tdopen >}}
[Compare searches (PDF)]({{< baseurl >}}/resources/mit6_01scs11_13_3_1)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
13.3.2
{{< tdclose >}}
{{< tdopen >}}
[Compare searches (PDF)]({{< baseurl >}}/resources/mit6_01scs11_13_3_2)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
13.3.3
{{< tdclose >}}
{{< tdopen >}}
[Paths in the map (PDF)]({{< baseurl >}}/resources/mit6_01scs11_13_3_3)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
13.3.4
{{< tdclose >}}
{{< tdopen >}}
[Robot on a grid (PDF)]({{< baseurl >}}/resources/mit6_01scs11_13_3_4)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
13.3.5
{{< tdclose >}}
{{< tdopen >}}
[Obstacles \[optional\] (PDF)]({{< baseurl >}}/resources/mit6_01scs11_13_3_5)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
13.3.6
{{< tdclose >}}
{{< tdopen >}}
[Knight paths on a chessboard \[optional\] (PDF)]({{< baseurl >}}/resources/mit6_01scs11_13_3_6)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
13.3.7
{{< tdclose >}}
{{< tdopen >}}
[Two robots on a grid \[optional\] (PDF)]({{< baseurl >}}/resources/mit6_01scs11_13_3_7)
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Check Yourself
--------------

### Nano-Quiz

Nano-quiz problems and solutions are taken from a previous version of the 6.01 Online Tutor. Do not try to answer these questions in the PDF files; answers will not be checked, and cannot be submitted.

*   [Quiz Problem (PDF)]({{< baseurl >}}/resources/mit6_01scs11_quiz12)
*   [Quiz Solution (PDF)]({{< baseurl >}}/resources/mit6_01scs11_quiz12_sol)

« [Previous]({{< baseurl >}}/pages/unit-4-probability-and-planning/state-estimation) | [Next]({{< baseurl >}}/pages/unit-4-probability-and-planning/optimizing-a-search) »