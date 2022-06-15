---
content_type: page
description: This section contains Python exercises.
learning_resource_types: []
ocw_type: CourseSection
parent_title: Python Tutorial
parent_type: CourseSection
parent_uid: eb35763e-4457-1074-0617-fdcde7901af1
title: Association Lists
uid: e9eff05a-fba0-05d6-b94c-6396635771d3
---

« {{% resource_link 2bb3ee0d-342c-8763-0f58-9691f27ba007 "Previous" %}} | {{% resource_link 0c533b50-ae1f-2ed5-2d4e-2e0343b23b5b "Next" %}} »

The idea of a dictionary is very important and useful in programming. A dictionary allows you to associate _values_ with _keys_. In an actual English dictionary, the words are the keys and the definitions are the values. So, given a key, you can look up the value. In a phone book, names are the keys and phone numbers are the values.

Python has a built-in dictionary data structure, which you have read about already. We can make our own, simpler and less efficient data structure as a list of lists. It operates like this:

d = emptyAlist()  
\>>> addEntry(d, 4, 5)  
\>>> addEntry(d, 5, None)  
\>>> addEntry(d, 'ben', 'boa')  
\>>> addEntry(d, 'kim', 'krait')  
\>>> d  
\[\[4, 5\], \[5, None\], \['ben', 'boa'\], \['kim', 'krait'\]\]  
\>>> addEntry(d, 'bella', 'bi-colored-python-rock-snake')  
\>>> d  
\[\[4, 5\], \[5, None\], \['ben', 'boa'\], \['kim', 'krait'\], \['bella', 'bi-colored-python-rock-snake'\]\]  
\>>> lookup(d, 'ben')  
\['ben', 'boa'\]  
\>>> lookup(d, 'biz')

The problems in the table below are taken from the 6.01 Python Tutor, an interactive environment that is not available on OCW. Do not try to answer these questions in the PDF files; answers will not be checked, and cannot be submitted.

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
7.1.1
{{< tdclose >}}
{{< tdopen >}}
{{% resource_link b137abbe-5dd3-bdce-7734-b81c9f98d8ca "Add an entry to an alist (PDF)" %}}
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
7.1.2
{{< tdclose >}}
{{< tdopen >}}
{{% resource_link b874c99a-ea29-a928-a62d-3cd159fae56f "Look up an entry in an alist (PDF)" %}}
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

« {{% resource_link 2bb3ee0d-342c-8763-0f58-9691f27ba007 "Previous" %}} | {{% resource_link 0c533b50-ae1f-2ed5-2d4e-2e0343b23b5b "Next" %}} »