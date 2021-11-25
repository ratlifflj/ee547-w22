---
layout: home
title: EE547
nav_exclude: true
seo:
  type: Course
  name: EE/AA 547
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

{% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}

## EE/AA 547 Linear Systems Theory

**Reminder**: EE/AA 510 is a pre-requisite to this course. If you have not taken it, please email me.

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign instructors = site.staffers | where: 'role', 'Teaching Assistant' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

## Overview and outcomes
This focus of this course is the use of linearity in systems theory. It provides foundational tools for modeling and control and serves as a prerequisite for more advanced courses in control theory, robotics, and optimization. The class will be mathematically rigorous, and builds upon concepts familiar from linear algebra (510), ordinary differential equations, and feedback control. In addition to analytical results, we will see computational tools and illustrate abstract concepts whenever possible using numerical examples.

By the end of this course, you will be able to:
  - construct and simulate linear control system models for physical phenomena;
  - approximate nonlinear control system models using linear control systems;
  - assess stability, controllability, and observability of linear control systems;
  - design and implement a stabilizing controller + observer for linear systems.

This course website/syllabus is a living document.

## Textbook and References
There is no single text that provides adequate coverage of the systems theory concepts and the background material in sufficient detail and at a sufficiently advanced level to serve the needs of this course. There is no required textbook for the course. That being said, the two main textbooks we will follow are:

- Hespanha, [Linear Systems Theory](https://web.ece.ucsb.edu/~hespanha/linearsystems/)
- Callier and Desoer, [Linear Systems Theory](https://link.springer.com/book/10.1007/978-1-4612-0957-7)

#### Other references
- Math language and logic: [Real Mathematical Analysis](https://link.springer.com/book/10.1007%2F978-3-319-17771-7) by Pugh
- Linear algebra: [Vectors, Matrices, and Least Squares](http://www.seas.ucla.edu/~vandenbe/133A/133A-textbook.pdf)  by Boyd and Vandenberghe AND [Linear Algebra](http://joshua.smcvt.edu/linearalgebra/)  by Hefferon
- Dynamical systems theory: [Nonlinear dynamics and chaos](http://ebookcentral.proquest.com.offcampus.lib.washington.edu/lib/washington/detail.action?docID=1181622)  by Strogatz
- Linear control theory: [Linear System Theory and Design](https://app.knovel.com/web/toc.v/cid:kpLSTDE003/viewerType:toc/root_slug:linear-system-theory)  by Chen (You can get this book online through the UW Library; it is good for frequency domain analysis in linear systems theory)
- More Linear control theory: [Feedback Systems](http://www.cds.caltech.edu/~murray/amwiki/Main_Page)   by Astrom and Murray
- Scientific computing: [Dive into Python](http://www.diveintopython3.net/)

#### Additional Video References:

- [videos on basics of numerical integration, differentiation, optimization, numerical linear algebra, etc.](https://www.youtube.com/channel/UC_6KMU8k4R6q4Vk5IGTfJEQ/playlists) 
- [videos on Introduction to Dynamical Systems](https://www.youtube.com/view_play_list?p=06960BA52D0DB32B)


## Lectures
[Lectures](lecture.md){: .btn .btn-outline .fs-3 }

Lectures will be posted on the lecture link above. This includes all materials such
as latex'd notes, slides, problem worksheets, and videos. Course materials are
organized into modules.

## Homework Self-Grading Process
Homework will be graded via a two part process. We will randomly select one problem to grade from each homework. The remainder of the problems you will be required to self-assess through the process below.

Homeworks will be assigned on Monday and due the following Sunday, with extra credit if you turn it in on Friday. The self-assessment portion will be due the following  Friday after the homework is due.


There will be a written homework assignment due in electronic form as a .pdf on Canvas due. There will be roughly weekly homework assignments.  There will be approximately 6-8 homework assignments.

#### Self-assessment Process
 To provide training and feedback that helps cultivate self-reflection, you will grade your homework assignments and receive oversight and feedback from the instructional staff regarding the accuracy of your self-assessment.

**Rubric**: we will provide detailed solutions on the day of the homework submission deadline, and you will have until the following Friday to grade each of your homework problems on a 0,1,2 point scale:
0 points - no effort / not attempted
1 points - attempted, but incomplete or incorrect solution
2 points - complete and correct solution
For any problem that earns a 1, you have the opportunity to explain the error in your solution and how to correct it; if this explanation is correct, you earn the full 2 points on the problem. You do not give yourself the 2 points if you got an incorrect problem and corrected it. The TA and myself will assign you the extra point after going through your homework.  To specify grades and provide explanations of any errors, use the Comment feature in Canvas's Assignment page for the homework.

Notes and caveats intended to ensure the integrity of this process:
- if you did not attempt the problem initially, you will receive zero points;
- if you do not grade a problem, you will receive zero points;
- if you grade incorrectly (i.e. initial solution is incomplete or incorrect and your explanation is incomplete or incorrect), you will receive one or zero at the discretion of the instructional staff (this ensures you cannot simply assign all "2"s, nor can you receive full credit for incomplete or incorrect explanations).

#### Frequently Asked Questions (FAQ)
**Q**:  should I download my .pdf, add comments (e.g. via Adobe Acrobat), and re-upload the .pdf?

**A**: That's fine, but it's probably easier to use the in-browser "CrocoDoc" viewing and annotation pane provided in Canvas.

**Q**:  does my .pdf need to contain all of my homework writeup materials, or can some be in an .ipynb file?

**A**: Your writeup must be submitted as a single self-contained .pdf document.  You must also upload sourcecode for any computational tools used to complete the assignment, but these will not be graded (they are used only to protect against plagiarism of sourcecode).

Submission suggestions: You are welcome (and we encourage you) to typeset your homework assignments rather than write them by hand.


