---
content_type: page
learning_resource_types: []
ocw_type: CourseSection
parent_title: 'Unit 2: Signals and Systems'
parent_type: CourseSection
parent_uid: 523e1f18-8f85-4804-7030-f2ec4580e9b6
title: Linear Time-Invariant Signals and Systems
uid: 09ae0a4b-00ca-3719-2b3f-fe9f36ca05cd
---

« [Previous]({{< baseurl >}}/pages/unit-2-signals-and-systems/signals-and-systems) | [Next]({{< baseurl >}}/pages/unit-2-signals-and-systems/characterizing-system-performance) »

Session Overview
----------------

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}
 ![Diagram of feedback addition composition.]({{< resource_file cd231b17-a8b2-ca23-1b9d-7577e61b44e7 >}})
{{< tdclose >}}
{{< tdopen >}}


In the last session, we demonstrated the versatility of state machines and introduced signals and systems. In this session, we will focus on linear time-invariant (LTI) systems. We'll be able to represent LTI systems using state machines, and introduce other ways to represent LTI systems. Once we know that a system is LTI, we can use what we know about linear time-invariance to analyze and predict the behavior of the system.

The overview handout provides a more detailed introduction, including the big ideas of the session, key vocabulary, what you should understand (theory) and be able to do (practice) after completing this session, and additional resources.

*   [Session 4 Handout: Linear Time-Invariant Signals and Systems (PDF)]({{< baseurl >}}/resources/mit6_01scs11_ses04)


{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Session Content
---------------

### Readings

Read sections 5.1-5.4 of the course notes.

*   [Chapter 5: Signals and Systems (PDF - 1.7MB)]({{< baseurl >}}/resources/mit6_01scs11_chap05)

### Recitation Video

These videos have been developed for OCW Scholar, and are designed to supplement the lecture videos.

*   [Recitation 5: LTI Motivations and Representations]({{< baseurl >}}/resources/recitation-1-object-oriented-programming-2)
*   [Recitation 6: System Equivalences]({{< baseurl >}}/resources/recitation-2-inheritance-2)

Session Activities
------------------

The problems in the tables below are taken from the 6.01 Online Tutor, an interactive environment that is not available on OCW. Do not try to answer these questions in the PDF files; answers will not be checked, and cannot be submitted.

### Software Lab

*   [Software Lab 4: Signal Class (PDF)]({{< baseurl >}}/resources/mit6_01scs11_swlab04)
*   [Code for Software Lab 4 (ZIP)]({{< baseurl >}}/resources/swlab04) (This ZIP file contains: 5 .py files.)

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
4.1.1
{{< tdclose >}}
{{< tdopen >}}
[Constructing signals (PDF)]({{< baseurl >}}/resources/mit6_01scs11_4_1_1)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
4.1.2
{{< tdclose >}}
{{< tdopen >}}
[Step signal (PDF)]({{< baseurl >}}/resources/mit6_01scs11_4_1_2)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
4.1.3
{{< tdclose >}}
{{< tdopen >}}
[Subclasses of signals (PDF)]({{< baseurl >}}/resources/mit6_01scs11_4_1_3)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
4.1.4
{{< tdclose >}}
{{< tdopen >}}
[Additional subclasses (PDF)]({{< baseurl >}}/resources/mit6_01scs11_4_1_4)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
4.1.5
{{< tdclose >}}
{{< tdopen >}}
[PolyR on signals (PDF)]({{< baseurl >}}/resources/mit6_01scs11_4_1_5)
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

### Design Lab

*   [Design Lab 4: Hitting the Wall (PDF)]({{< baseurl >}}/resources/mit6_01scs11_designlab04)
*   [Code for Design Lab 4 (ZIP)]({{< baseurl >}}/resources/designlab04) (This ZIP file contains: 2 .py files.)

Do problem 4.2.1 before the design lab.

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
4.2.1
{{< tdclose >}}
{{< tdopen >}}
[Difference equations (PDF)]({{< baseurl >}}/resources/mit6_01scs11_4_2_1)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
4.3.1
{{< tdclose >}}
{{< tdopen >}}
[Wall finder (PDF)]({{< baseurl >}}/resources/mit6_01scs11_4_3_1)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
4.3.3
{{< tdclose >}}
{{< tdopen >}}
[State machine composition (PDF)]({{< baseurl >}}/resources/mit6_01scs11_4_3_3)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
4.3.5
{{< tdclose >}}
{{< tdopen >}}
[Wall finder state machine (PDF)]({{< baseurl >}}/resources/mit6_01scs11_4_3_5)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
4.3.6
{{< tdclose >}}
{{< tdopen >}}
[Wall finder gains (PDF)]({{< baseurl >}}/resources/mit6_01scs11_4_3_6)
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

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
4.4.1
{{< tdclose >}}
{{< tdopen >}}
[LTISM (PDF)]({{< baseurl >}}/resources/mit6_01scs11_4_4_1)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
4.4.2
{{< tdclose >}}
{{< tdopen >}}
[Implement LTISM (PDF)]({{< baseurl >}}/resources/mit6_01scs11_4_4_2)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
4.4.3
{{< tdclose >}}
{{< tdopen >}}
[TransducedSignal (PDF)]({{< baseurl >}}/resources/mit6_01scs11_4_4_3)
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Check Yourself
--------------

### Nano-Quiz

Nano-quiz problems and solutions are taken from a previous version of the 6.01 Online Tutor. Do not try to answer these questions in the PDF files; answers will not be checked, and cannot be submitted.

*   [Quiz Problem (PDF)]({{< baseurl >}}/resources/mit6_01scs11_quiz04)
*   [Quiz Solution (PDF)]({{< baseurl >}}/resources/mit6_01scs11_quiz04_sol)

« [Previous]({{< baseurl >}}/pages/unit-2-signals-and-systems/signals-and-systems) | [Next]({{< baseurl >}}/pages/unit-2-signals-and-systems/characterizing-system-performance) »