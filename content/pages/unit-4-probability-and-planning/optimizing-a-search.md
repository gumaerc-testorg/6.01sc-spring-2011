---
content_type: page
description: This session contains readings, lecture and recitation video, and software
  and design labs.
learning_resource_types: []
ocw_type: CourseSection
parent_title: 'Unit 4: Probability and Planning'
parent_type: CourseSection
parent_uid: f216c72d-f519-1296-c531-19833fb7c73a
title: Optimizing a Search
uid: da41172c-d83b-2571-9eae-caa5c1bcde32
---

« {{% resource_link 497582d8-68ca-82e7-7ef7-6b997e187b13 "Previous" %}} | {{% resource_link f0df2cae-e4ea-c3e0-a431-246d722e93a5 "Next" %}} »

Session Overview
----------------

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}
{{< resource fda65a5c-1968-cceb-1619-8e8186c90464 >}}
{{< tdclose >}}
{{< tdopen >}}


In the last session, we introduced the concept of search. We looked at the 6.01 implementation of a general search algorithm, addressed issues of common sense and dynamic programming, and localized a robot.

In this session, we focus on improving search. We can systematically use information we have about the state space we're searching, in order to save us time and space.

The overview handout provides a more detailed introduction, including the big ideas of the session, key vocabulary, what you should understand (theory) and be able to do (practice) after completing this session, and additional resources.

*   {{% resource_link 4cccf934-9d3c-5417-be97-4dfd8bb9e5c3 "Session 13 Handout: Optimizing a Search (PDF)" %}}


{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Session Content
---------------

### Readings

Read sections 8.5-8.6 of the course notes.

*   {{% resource_link 840b87b4-1bfd-9c95-446e-de3604a9312b "Chapter 8: Long-Term Decision-Making and Search (PDF)" %}}

### Lecture Video

Watch the lecture video. The handout and slides present the same material, but the slides include answers to the in-class questions.

*   {{% resource_link 02bf2c9e-d49c-5023-6a5a-325538b053d2 "Lecture 13: Optimizing a Search" %}}

> ### About this Video
> 
> Uniform cost search takes into account the cost associated with an action, and can be implemented with a priority queue. Heuristics estimate the cost of the remaining path to the goal; the Manhattan distance is an example of an admissible heuristic.

*   {{% resource_link c4b5db63-ed78-92ed-a59a-7a047dc3806c "Lecture handout (PDF)" %}}
*   {{% resource_link ff5adf49-8ea3-88ad-7842-beaeaf990676 "Lecture slides (PDF)" %}}

### Recitation Video

These videos have been developed for OCW Scholar, and are designed to supplement the lecture videos.

*   {{% resource_link 069d127a-c9a8-a02d-405d-e0f68c518a84 "Recitation 16: Search: Dynamic Programming, Costs and Heuristics" %}}

Session Activities
------------------

The problems in the tables below are taken from the 6.01 Online Tutor, an interactive environment that is not available on OCW. Do not try to answer these questions in the PDF files; answers will not be checked, and cannot be submitted.

### Software Lab

*   {{% resource_link cae1b8b5-66e4-65b5-ab4a-613fe7065f8e "Software Lab 14: Plan from Outer Space (PDF)" %}}
*   {{% resource_link 01f0f94f-591f-7020-ef71-8a2dafbc2aaa "Code for Software Lab 14 (ZIP)" %}} (This ZIP file contains: 3 .py files.)

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
{{% resource_link 7c716782-3ea0-84c6-d1b0-e03b6edb1fd7 "Modeling the world (PDF)" %}}
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
14.1.2
{{< tdclose >}}
{{< tdopen >}}
{{% resource_link c7e38589-e9a0-1e99-af4f-3a376c509d49 "Robot on a grid map (PDF)" %}}
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

### Design Lab

*   {{% resource_link eac44100-b94f-c1b8-48b9-ea46cd0a9594 "Design Lab 14: I'm the Map! (PDF)" %}}
*   {{% resource_link ac67003a-96de-8ae4-4ba6-da23e5c9c665 "Code for Design Lab 14 (ZIP)" %}} (This ZIP file contains: 13 .py files.)

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
{{% resource_link 758e5d26-841b-0ef1-141a-c2722e4d9e73 "Aliasing instances (PDF)" %}}
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
14.2.6
{{< tdclose >}}
{{< tdopen >}}
{{% resource_link "ac14e7e8-9ae0-1b23-6621-416d237463a7" "Robot race results \[optional\] (PDF)" %}}
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

« {{% resource_link 497582d8-68ca-82e7-7ef7-6b997e187b13 "Previous" %}} | {{% resource_link f0df2cae-e4ea-c3e0-a431-246d722e93a5 "Next" %}} »