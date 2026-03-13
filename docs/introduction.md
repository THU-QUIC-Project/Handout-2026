---
icon: lucide/graduation-cap
---

# The THQUIC Project (2026 Spring)

## Overview
In this project, you will implement the QUIC transport protocol almost from scratch. This project
will be done in teams of **at most three** students. 
All teams are required to implement certain ”base” features and several ”advanced” features selected from a given list. 
You need to implement all ”base” features to get **60** points and implement enough ”advanced” features, to obtain the remaining **40** points. Each ”advanced” feature is assigned a score according to its difficulty.

You need to complete several labs (3 + X, depending on your choices of features) to finish this
project. In each lab, you implement a piece of QUIC (e.g., reliable transmission, flow control) and
finally get a rather complicated transmission protocol. We prepare 3 labs (lab I-1 to lab I-3) for all ”base” features and one lab (lab II-x) for each ”advanced” feature. You can read the handout of each lab to learn more details, including its background, target, and requirement. We also give some
suggestions in handouts.

You have to read RFCs – the standard of the Internet – to understand QUIC before implementing
it. RFC is long and, honestly, verbose, especially for beginners. We prepare some mini RFC, a
simplified and re-organized version of the original RFCs, to help you understand QUIC more easily.
We prepare one mini RFC for each lab. You could skim the mini RFC before reading the handout
but you will refer to mini RFCs frequently during coding.


!!! note

    We provide the starter code in both `C++` and `Rust` languages this year. There is no promise that they are synchronized. Feel free to use either language, or any other language you prefer that can be compiled into an executable.

## Important Dates

- Thu, May 14th, 2026:  Meeting with TA with 10% bonus
- Thu, May 21st, 2026:  Meeting with TA 
- Thu, May 28th, 2026:  Meeting with TA 
- Thu, June 4th, 2026:  Meeting with TA with -20% penalty
- Thu, June 11th, 2026:  Meeting with TA with -40% penalty 
- Sun, June 14th, 2026:  Deadline for Reports

## Grading
This lab is worth 90% of your course grade. The grade of this project is given according to both the
correctness of your implementations, a one-to-one meeting with TA, and a final report. 
The correctness weighs 75% while the meeting and the report weigh 25% in sum. 
Note that the correctness of some features, such as the congestion control, is defined by the *delivery performance* of your implementation. Every team should attend a one-to-one meeting with TA. All members should
attend this meeting and answer TA’s questions about your design choices and implementation
details. Each team also needs to submit a short report to briefly describe its design and respond
to all questions not answered in the meeting. Again, both the meeting and the report are required
for you to pass the course.

## How to Start

1. Find other students to organize your team if you wish.

2. Submit the homework in Web Learning with your name, GitHub account, and the names of your
team members (Everyone in the team should submit it).

3. You will be invited into a GitHub organization called [THU-QUIC-Project](https://github.com/THU-QUIC-Project). We host all materials:
handouts (the source code for this website), mini RFCs, and starter code in repositories of the organization because they are updated frequently. You could ask questions, submit bug reports, and start discussions by opening issues on certain repositories.
