Download Link: https://assignmentchef.com/product/solved-cse-396-assignment-2
<br>






We have formalized the DFA model and have continued to build upon our discussion of what it means to solve a problem using one of these algorithms. From there, we have introduced regular expressions as a means to provide a concise pattern with an equivalent expressive power to the class of problems that can be solved using a DFA. This has led us to two results: every regular language can be represented by a regex and the incomplete theorem that we began on Thursday which states that every regex can be solved using a DFA.

Regarding homework submissions and late work: In general, late work will be assessed a 50%-point penalty for one day late and will not be accepted after one day late. Please take note of the due date of assignments as Thursdays *before* lecture. This is to avoid missing class time to complete work. Please also take note that TopHat problems will not be accepted late, so be sure to complete them prior to the deadline. Also, ensure that your submission displays properly and that it is of a reasonable resolution (your view should not be limited to the top-right corner of your pdf when viewed).

Problem 1. ( Complete the TopHat worksheet )

Problem 2. Prove that the regular expression <em>r </em>= (0∪1)<sup>∗ </sup>is not equivalent to PARITY.

Problem 3. For this problem, let Σ = {a<em>,</em>b}. Consider the problem of determining if a string has an odd length and does not end with bb.

3(a) State the problem as a decision problem.

3(b) Write the decision problem as a language.

3(c) Provide a regular expression that represents the language. Provide a brief justification as to why (i.e., what were your thoughts to construct it).

3(d) Build a DFA to recognize this language. Provide comments explaining how your process is working.

Hint: this language has the form of <em>A</em>∩<em>B </em>where <em>A </em>contains the odd length strings and <em>B </em>contains the strings ending with bb. You may want to consider using a modified version of the Cartesian product construction to recognize the union of two regular languages (see Theorem 1.25 and selected solutions for problem 1.4 for more insights, as well as our coverage in lecture).

Problem 4.  Following the process of converting a DFA to a regular expression from lecture, convert the following DFA to an equivalent regular expression. Be sure to show all steps or you will receive no credit.


