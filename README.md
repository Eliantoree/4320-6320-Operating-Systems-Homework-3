# 4320-6320-Operating-Systems-Homework-3
4320/6320 Operating Systems Homework 3


**Download Link:https://programming.engineering/product/4320-6320-operating-systems-homework-3/**

Description
5/5 – (1 vote)
Your programs – if requested – must compile with gcc and execute on snowball.cs.gsu.edu!

Please see https://cscit.cs.gsu.edu/sp/guide/snowball for more details. You may use whatever

IDEs / text editors you like, but you must submit your responses on iCollege.

Consider a system of 9 processes, P = {p1, …, p9}.

Associated with the system are 6 memory cells, M = {M1, …, M6}.

The domain and range for each process is given in the following table:

Process pi

Domain D(pi)

Range R(pi)

p1

M1, M2

M3

p2

M1

M5

p3

M3, M4

M1

p4

M3, M4

M5

p5

M3

M4

p6

M4

M4

p7

M5

M5

p8

M3, M4

M2

p9

M5, M6

M6

In addition, you are given the following precedence relation:

= {(P1,P2), (P1,P6), (P2,P3), (P2,P4), (P2,P5),(P3,P6),(P3,P8),(P4,P6), (P4,P7), (P5,P7), (P5,P8), (P6,P8), (P6,P9), (P7,P9), (P8,P9)}

Construct the Precedence Graph (not containing any redundant edges; also modify è accordingly). Use PowerPoint, diagrams.net, or any other app to draw the graph. (15 points)

Is the system above determinate for all interpretations of its processes? If it is not, add to è necessary elements to make it determinate (no graph drawing needed). Explain your reasoning. (20 points)

In the first problem, there were 9 processes, many of which were listed as pairs under the precedence relation. Suppose we are now dealing with a system of only 5 processes named P1 through P5. You

are given a set of constraints that are expressed by the following precedence relation:

= {(P1,P3), (P1, P5), (P2,P4), (P3, P4), (P4, P5)}

Fall 2022 – 4320/6320 Operating Systems

Provide pseudocode for each of those 5 processes to show how semaphores can be used to enforce these constraints (i.e., the precedence relation è). Also, you must initialize these semaphores correctly (15 points).

