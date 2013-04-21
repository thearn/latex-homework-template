LaTeX homework template
=======================

A LaTeX template that I used during graduate school for my homework assignments.
Lays the problems out in a double-column landscape style.

Usage:
-------
- homework.tex is the main template file. At the beginning you will find many fields that should be personalized, such as:
	1. Name
	2. Class name
	3. Date
	4. etc..
- The main template file imports the actual markup for the problems from `problems.tex`. This is where each problem should be typed out.
- The syntax for laying out each problem using this template is:

```latex
\begin{homeworkProblem}
	% Homework code
	% Goes
	% Here
\end{homeworkProblem}
``` 

- [Example 1](example_1.md) and [Example 2](example_2.md) show examples of the template used on two complete homework sets, including the use of figures.
