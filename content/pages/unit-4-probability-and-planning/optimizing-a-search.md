---
content_type: page
learning_resource_types: []
ocw_type: CourseSection
parent_title: 'Unit 4: Probability and Planning'
parent_type: CourseSection
parent_uid: f216c72d-f519-1296-c531-19833fb7c73a
title: Optimizing a Search
uid: da41172c-d83b-2571-9eae-caa5c1bcde32
---

« [Previous]({{< baseurl >}}/pages/unit-4-probability-and-planning/search-algorithms) | [Next]({{< baseurl >}}/pages/final-exam) »

Session Overview
----------------

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}
![Illustration of the Manhattan distance.]({{< resource_file fda65a5c-1968-cceb-1619-8e8186c90464 >}})
{{< tdclose >}}
{{< tdopen >}}


In the last session, we introduced the concept of search. We looked at the 6.01 implementation of a general search algorithm, addressed issues of common sense and dynamic programming, and localized a robot.

In this session, we focus on improving search. We can systematically use information we have about the state space we're searching, in order to save us time and space.

The overview handout provides a more detailed introduction, including the big ideas of the session, key vocabulary, what you should understand (theory) and be able to do (practice) after completing this session, and additional resources.

*   [Session 13 Handout: Optimizing a Search (PDF)]({{< baseurl >}}/resources/mit6_01scs11_ses13)


{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Session Content
---------------

### Readings

Read sections 8.5-8.6 of the course notes.

*   [Chapter 8: Long-Term Decision-Making and Search (PDF)]({{< baseurl >}}/resources/mit6_01scs11_chap08-1)

### Lecture Video

Watch the lecture video. The handout and slides present the same material, but the slides include answers to the in-class questions.

*   [Lecture 13: Optimizing a Search]({{< baseurl >}}/resources/lecture-1-object-oriented-programming-10)

> ### About this Video
> 
> Uniform cost search takes into account the cost associated with an action, and can be implemented with a priority queue. Heuristics estimate the cost of the remaining path to the goal; the Manhattan distance is an example of an admissible heuristic.

*   [Lecture handout (PDF)]({{< baseurl >}}/resources/mit6_01scs11_lec13_handout)
*   [Lecture slides (PDF)]({{< baseurl >}}/resources/mit6_01scs11_lec13)

### Recitation Video

These videos have been developed for OCW Scholar, and are designed to supplement the lecture videos.

*   [Recitation 16: Search: Dynamic Programming, Costs and Heuristics]({{< baseurl >}}/resources/recitation-1-object-oriented-programming-9)

Session Activities
------------------

The problems in the tables below are taken from the 6.01 Online Tutor, an interactive environment that is not available on OCW. Do not try to answer these questions in the PDF files; answers will not be checked, and cannot be submitted.

### Software Lab

*   [Software Lab 14: Plan from Outer Space (PDF)]({{< baseurl >}}/resources/mit6_01scs11_swlab14)
*   [Code for Software Lab 14 (ZIP)]({{< baseurl >}}/resources/swlab14) (This ZIP file contains: 3 .py files.)

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
14.1.1
{{< tdclose >}}
{{< tdopen >}}
[Modeling the world (PDF)]({{< baseurl >}}/resources/mit6_01scs11_14_1_1)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
14.1.2
{{< tdclose >}}
{{< tdopen >}}
[Robot on a grid map (PDF)]({{< baseurl >}}/resources/mit6_01scs11_14_1_2)
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

### Design Lab

*   [Design Lab 14: I'm the Map! (PDF)]({{< baseurl >}}/resources/mit6_01scs11_designlab14)
*   [Code for Design Lab 14 (ZIP)]({{< baseurl >}}/resources/designlab14) (This ZIP file contains: 13 .py files.)

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
14.2.3
{{< tdclose >}}
{{< tdopen >}}
[Aliasing instances (PDF)]({{< baseurl >}}/resources/mit6_01scs11_14_2_3)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
14.2.6
{{< tdclose >}}
{{< tdopen >}}
[Robot race results \[optional\] (PDF)]({{< baseurl >}}/resources/mit6_01scs11_14_2_6)
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

« [Previous]({{< baseurl >}}/pages/unit-4-probability-and-planning/search-algorithms) | [Next]({{< baseurl >}}/pages/final-exam) »