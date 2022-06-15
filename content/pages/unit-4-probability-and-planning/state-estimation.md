---
content_type: page
description: This session contains readings, recitation video, software and design
  labs, a nano-quiz, and homework.
learning_resource_types: []
ocw_type: CourseSection
parent_title: 'Unit 4: Probability and Planning'
parent_type: CourseSection
parent_uid: f216c72d-f519-1296-c531-19833fb7c73a
title: State Estimation
uid: 78921a7e-c8e9-b114-852d-caa46d83fd04
---

« {{% resource_link e97072ec-1818-d115-7deb-3b29326fe85e "Previous" %}} | {{% resource_link 497582d8-68ca-82e7-7ef7-6b997e187b13 "Next" %}} »

Session Overview
----------------

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}
{{< resource 8e7d761e-1fa5-1646-ffba-6ac411acfbde >}}
{{< tdclose >}}
{{< tdopen >}}


In the last session, we introduced probability and the basic tools to interact with probability distributions. We use probability to model degrees of belief, so that we can build systems that are robust in the face of uncertainty.

In this session, we focus on state estimation. We'll use state estimation to estimate the location of a robot in a hallway, and use it to localize a robot. Later we'll be able to localize and map at the same time.

The overview handout provides a more detailed introduction, including the big ideas of the session, key vocabulary, what you should understand (theory) and be able to do (practice) after completing this session, and additional resources.

*   {{% resource_link d58f73bb-5360-ce67-fc4c-c2d61ad4b8e4 "Session 11 Handout: State Estimation (PDF)" %}}


{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Session Content
---------------

### Readings

Read sections 7.5-7.8 of the course notes.

*   {{% resource_link e6a5d216-b5a9-d26d-cf3a-12222ec33d86 "Chapter 7: Probabilistic State Estimation (PDF)" %}}

### Recitation Video

These videos have been developed for OCW Scholar, and are designed to supplement the lecture videos.

*   {{% resource_link 578ce089-c0b6-d62f-83ab-7731da5d0322 "Recitation 14: Probability: State Estimation" %}}

Session Activities
------------------

The problems in the tables below are taken from the 6.01 Online Tutor, an interactive environment that is not available on OCW. Do not try to answer these questions in the PDF files; answers will not be checked, and cannot be submitted.

This session contains a design lab from week 11 of the MIT course, and a software lab from week 12.

### Design Lab

*   {{% resource_link d48ae9c9-0b69-0c2d-2e23-b7a6c02d4c8c "Design Lab 11: Robots in Hallways (PDF)" %}}
*   {{% resource_link ec06e4de-d396-a5bf-2b6a-cb495ce96e2f "Code for Design Lab 11 (ZIP)" %}} (This ZIP file contains: 1 .py file.)

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
{{% resource_link 98fa1aad-8da6-b135-0b72-3e9d1f3c2951 "Observation models (PDF)" %}}
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
11.1.2
{{< tdclose >}}
{{< tdopen >}}
{{% resource_link afdeaab7-4a08-23b2-19cc-319d434deb54 "Transition models (PDF)" %}}
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
11.1.4
{{< tdclose >}}
{{< tdopen >}}
{{% resource_link 97d6e9ae-5682-1475-c9d1-1063ba9cecbe "Simulating hallways (PDF)" %}}
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
11.1.5
{{< tdclose >}}
{{< tdopen >}}
{{% resource_link 670de0f9-8d44-6244-d6a1-dd5ff4446284 "Simulating hallways: the noisy-noisy case (PDF)" %}}
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
11.1.6
{{< tdclose >}}
{{< tdopen >}}
{{% resource_link 5302ca81-e449-3ea7-c19a-e4df196f5c0a "Sonar hit (PDF)" %}}
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
11.1.7
{{< tdclose >}}
{{< tdopen >}}
{{% resource_link 98463b30-c7f6-163e-4737-2c251a876dba "Ideal sonar readings (PDF)" %}}
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

### Software Lab

*   {{% resource_link b8b8b4c7-24ea-7023-a1a4-1f54f9d79392 "Software Lab 12: I think therefore where am I (PDF)" %}}
*   {{% resource_link 5e590783-1ddf-22f0-2f65-b682cc9ce418 "Code for Software Lab 12 (ZIP)" %}} (This ZIP file contains: 1 .py file.)

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
{{% resource_link aa8ec892-942f-279d-dd3b-9e1afa773de2 "Stochastic state machines (PDF)" %}}
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
12.2.2
{{< tdclose >}}
{{< tdopen >}}
{{% resource_link d97fc6ef-e6db-c82e-7122-cae74e27e3ef "Faster state estimation (PDF)" %}}
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
12.2.3
{{< tdclose >}}
{{< tdopen >}}
{{% resource_link 74bc53c8-6bb7-a14b-fb22-9a8485e2d76b "Localization (PDF)" %}}
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Check Yourself
--------------

### Nano-Quiz

Nano-quiz problems and solutions are taken from a previous version of the 6.01 Online Tutor. Do not try to answer these questions in the PDF files; answers will not be checked, and cannot be submitted.

*   {{% resource_link 350ea6e0-d9f2-4923-891e-d1edbdb7e8d5 "Quiz Problem (PDF)" %}}
*   {{% resource_link 4bf983b7-2d7b-6336-675b-b33e14a7fc06 "Quiz Solution (PDF)" %}}

### Homework

*   {{% resource_link 484a79a4-5eb9-f7ee-ad30-52e87a495c17 "Homework 4: Distributions (PDF)" %}}
*   {{% resource_link 2af533f1-6111-3a31-8664-c482841194be "Code for Homework 4 (ZIP)" %}} (This ZIP file contains: 1 .py file.)

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
{{% resource_link 9cc9bc91-8da4-8c68-40d0-c3a21e357e39 "Basic distributions: square (PDF)" %}}
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
11.2.2
{{< tdclose >}}
{{< tdopen >}}
{{% resource_link 5db7a3d0-03f6-1278-b655-7776531e7ae2 "Basic distributions: triangle (PDF)" %}}
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
11.2.3
{{< tdclose >}}
{{< tdopen >}}
{{% resource_link 490cc826-baef-d627-3afa-6114f709ec68 "Mixture distribution (PDF)" %}}
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

« {{% resource_link e97072ec-1818-d115-7deb-3b29326fe85e "Previous" %}} | {{% resource_link 497582d8-68ca-82e7-7ef7-6b997e187b13 "Next" %}} »