---
content_type: page
parent_title: 'Unit 4: Probability and Planning'
parent_uid: f216c72d-f519-1296-c531-19833fb7c73a
title: State Estimation
uid: 78921a7e-c8e9-b114-852d-caa46d83fd04
---

« [Previous]({{< baseurl >}}/pages/unit-4-probability-and-planning/discrete-probability) | [Next]({{< baseurl >}}/pages/unit-4-probability-and-planning/search-algorithms) »

Session Overview
----------------

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}
![Diagram of robot estimating its distance from the wall.]({{< resource_file 8e7d761e-1fa5-1646-ffba-6ac411acfbde >}})
{{< tdclose >}}
{{< tdopen >}}


In the last session, we introduced probability and the basic tools to interact with probability distributions. We use probability to model degrees of belief, so that we can build systems that are robust in the face of uncertainty.

In this session, we focus on state estimation. We'll use state estimation to estimate the location of a robot in a hallway, and use it to localize a robot. Later we'll be able to localize and map at the same time.

The overview handout provides a more detailed introduction, including the big ideas of the session, key vocabulary, what you should understand (theory) and be able to do (practice) after completing this session, and additional resources.

*   [Session 11 Handout: State Estimation (PDF)]({{< baseurl >}}/resources/mit6_01scs11_ses11)


{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Session Content
---------------

### Readings

Read sections 7.5-7.8 of the course notes.

*   [Chapter 7: Probabilistic State Estimation (PDF)]({{< baseurl >}}/resources/mit6_01scs11_chap07-1)

### Recitation Video

These videos have been developed for OCW Scholar, and are designed to supplement the lecture videos.

*   [Recitation 14: Probability: State Estimation]({{< baseurl >}}/resources/recitation-1-object-oriented-programming-8)

Session Activities
------------------

The problems in the tables below are taken from the 6.01 Online Tutor, an interactive environment that is not available on OCW. Do not try to answer these questions in the PDF files; answers will not be checked, and cannot be submitted.

This session contains a design lab from week 11 of the MIT course, and a software lab from week 12.

### Design Lab

*   [Design Lab 11: Robots in Hallways (PDF)]({{< baseurl >}}/resources/mit6_01scs11_designlab11)
*   [Code for Design Lab 11 (ZIP)]({{< baseurl >}}/resources/designlab11) (This ZIP file contains: 1 .py file.)

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
11.1.1
{{< tdclose >}}
{{< tdopen >}}
[Observation models (PDF)]({{< baseurl >}}/resources/mit6_01scs11_11_1_1)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
11.1.2
{{< tdclose >}}
{{< tdopen >}}
[Transition models (PDF)]({{< baseurl >}}/resources/mit6_01scs11_11_1_2)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
11.1.4
{{< tdclose >}}
{{< tdopen >}}
[Simulating hallways (PDF)]({{< baseurl >}}/resources/mit6_01scs11_11_1_4)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
11.1.5
{{< tdclose >}}
{{< tdopen >}}
[Simulating hallways: the noisy-noisy case (PDF)]({{< baseurl >}}/resources/mit6_01scs11_11_1_5)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
11.1.6
{{< tdclose >}}
{{< tdopen >}}
[Sonar hit (PDF)]({{< baseurl >}}/resources/mit6_01scs11_11_1_6)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
11.1.7
{{< tdclose >}}
{{< tdopen >}}
[Ideal sonar readings (PDF)]({{< baseurl >}}/resources/mit6_01scs11_11_1_7)
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

### Software Lab

*   [Software Lab 12: I think therefore where am I (PDF)]({{< baseurl >}}/resources/mit6_01scs11_swlab12)
*   [Code for Software Lab 12 (ZIP)]({{< baseurl >}}/resources/swlab12) (This ZIP file contains: 1 .py file.)

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
12.2.1
{{< tdclose >}}
{{< tdopen >}}
[Stochastic state machines (PDF)]({{< baseurl >}}/resources/mit6_01scs11_12_2_1)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
12.2.2
{{< tdclose >}}
{{< tdopen >}}
[Faster state estimation (PDF)]({{< baseurl >}}/resources/mit6_01scs11_12_2_2)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
12.2.3
{{< tdclose >}}
{{< tdopen >}}
[Localization (PDF)]({{< baseurl >}}/resources/mit6_01scs11_12_2_3)
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Check Yourself
--------------

### Nano-Quiz

Nano-quiz problems and solutions are taken from a previous version of the 6.01 Online Tutor. Do not try to answer these questions in the PDF files; answers will not be checked, and cannot be submitted.

*   [Quiz Problem (PDF)]({{< baseurl >}}/resources/mit6_01scs11_quiz11)
*   [Quiz Solution (PDF)]({{< baseurl >}}/resources/mit6_01scs11_quiz11_sol)

### Homework

*   [Homework 4: Distributions (PDF)]({{< baseurl >}}/resources/mit6_01scs11_hw4)
*   [Code for Homework 4 (ZIP)]({{< baseurl >}}/resources/hw4) (This ZIP file contains: 1 .py file.)

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
11.2.1
{{< tdclose >}}
{{< tdopen >}}
[Basic distributions: square (PDF)]({{< baseurl >}}/resources/mit6_01scs11_11_2_1)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
11.2.2
{{< tdclose >}}
{{< tdopen >}}
[Basic distributions: triangle (PDF)]({{< baseurl >}}/resources/mit6_01scs11_11_2_2)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
11.2.3
{{< tdclose >}}
{{< tdopen >}}
[Mixture distribution (PDF)]({{< baseurl >}}/resources/mit6_01scs11_11_2_3)
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

« [Previous]({{< baseurl >}}/pages/unit-4-probability-and-planning/discrete-probability) | [Next]({{< baseurl >}}/pages/unit-4-probability-and-planning/search-algorithms) »