---
content_type: page
description: ''
draft: false
layout: instructor_insights
learning_resource_types: []
ocw_type: CourseSection
parent_title: Instructor Insights
parent_type: ThisCourseAtMITSection
parent_uid: 2aef49a5-63b7-0f93-319d-156d62607fed
title: Using an Online Tutoring Environment to Promote Student Self-Assessment
uid: 7443b17e-ca68-13d3-084e-83a7f25a4319
---
_In this section Dennis Freeman describes the online tutoring environment in_ 6.01 Introduction to Electrical Engineering and Computer Science I.

## Using Test Cases to Help Novices Self-Assess

We use programming throughout _6.01 Introduction to Electrical Engineering and Computer Science I_. We believe that programming is an essential tool for engineers and scientists. However, programming can be difficult, especially for beginners. While expert programmers are able to assess their own work to determine whether or not their code is functioning, this is a much more difficult task for novices. Although the staff was eager to help students, we realized from the outset that one-on-one help with debugging does not scale well. With more than 650 students per year, we just didn't have the resources to help students find the dozens of bugs that can plague even modest programming assignments. Instead, we wanted to develop a way for students to self-assess whenever and wherever they were coding so that they could keep going and continue working.

An online tutoring environment was our solution. Building on his previous work in _6.001 Structure and Interpretation of Computer Programs_, Professor Tomás Lozano-Peréz developed an online tutor that could automatically check code. The idea is to run the student's code on test cases for which the answers are known. This idea is extraordinarily clever and amazingly powerful!

At the time, online technologies generally allowed for multiple choice and true/false-type questions. Checking test cases offers much richer feedback. "Your code passes tests 1, 2, 4, and 5 but fails test 3." This message contains a wealth of information about not only the problem at hand but also about how to construct effective test cases, which is essential to becoming an expert programmer.

## From Checking Programs to Checking Equations: Generalizing the Online Tutoring Structure

{{< quote "[W]e wanted to develop a way for students to self-assess whenever and wherever they were coding so that they could keep going and continue working." "—Dennis Freeman" >}}

One of the most powerful aspects of our online tutoring environment is that it can be generalized and used in other subjects. For example, I have used the same structure when teaching _6.003 Signals and Systems_. In that class, students often derive equations. Let’s say a student says the answer is T sine of T divided by cosine of T. How do we know whether his or her expression is right? This problem is complicated because there can be numerous ways to represent the same mathematical relation. T times the sine of T divided by the cosine of T could equivalently be expressed as T times the tangent of T. Or it might be the square root of T times the sine of T times the square root of T divided by the cosine of T.

Initially, we tried to use symbolic algebra to reduce the equations, but that was very difficult. What turned out to be really easy was comparing answers for test cases, i.e., for T=1, T=2, T=10, and T=1,000. The same strategy that had worked for checking programs also worked for checking equations. Students were delighted to get feedback that not only contributed to their grade but also contributed to their understanding. 

The online tutoring environment was invented for checking programs—now we're checking equations. Both applications flip the meaning of feedback. It's not about assessing the student's performance. It's about helping students to understand the technical material.