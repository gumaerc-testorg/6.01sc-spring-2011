---
content_type: page
learning_resource_types: []
ocw_type: CourseSection
parent_title: Python Tutorial
parent_type: CourseSection
parent_uid: eb35763e-4457-1074-0617-fdcde7901af1
title: Association Lists
uid: e9eff05a-fba0-05d6-b94c-6396635771d3
---

« [Previous]({{< baseurl >}}/pages/python-tutorial/part-6) | [Next]({{< baseurl >}}/pages/unit-1-software-engineering) »

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
[Add an entry to an alist (PDF)]({{< baseurl >}}/resources/mit6_01scs11_py7_1_1)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
7.1.2
{{< tdclose >}}
{{< tdopen >}}
[Look up an entry in an alist (PDF)]({{< baseurl >}}/resources/mit6_01scs11_py7_1_2)
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

« [Previous]({{< baseurl >}}/pages/python-tutorial/part-6) | [Next]({{< baseurl >}}/pages/unit-1-software-engineering) »