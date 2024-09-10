java c
CS 3800
Homework 3
Spring 2024
1. [6 Points] In the shortlex numbering of strings over the alphabet {0, 1, 2, 3} what number corre-sponds to string 0 0 2 1 3 0 2 ?
2. [10 Points] In the shortlex numbering of strings over the alphabet {a, b, c}, what string has number 28599 ?
3. [8 Points] Suppose that S0, S1, S2, . . . is a sequence of subsets of N. Which one of the following sets is guaranteed to be different from all sets in the sequence?
(a) S = {n | n ̸∈ Sn2 }
(b) S = {n | n2 ̸∈ Sn2 }
(c) S = {n2| n ̸∈ Sn2 }
(d) S = {n2| n2 ̸∈ Sn}
(e) S = {n2| n ̸∈ Sn}
Explain why your chosen set is guaranteed not to be in the sequence S0, S1, S2, . . .
4. [9 Points] Use (a modified) diagonalization to show that for each sequence S0, S1, S2, . . . of subsets of N, there is a set S ⊆ N consisting only of even numbers such that
S ≠ S0, S1, S2, . . .
Give a formula for your set S, similar to those suggested in Problem 3.
5. [4 Points] Alice and Bob. Alice found a proof that no numbering of finite subsets of N is possible, that includes every finite subset of N; that is, for each sequence S0, S1, S2, . . . of finite subsets of N, there is some finite subset S ⊆ N that isn’t in the sequence. Here is her argument:
Consider any sequence S0, S1, S2, . . . of finite subsets of N.
1. Claim: some finite subset of N is not in the sequence.
2. Proof of the claim:
3. Define a new subset S ⊆ N by:
S = {n ∈ N | n ̸∈ Sn}
4. Thus for each n ∈ N, number n guarantees that S ≠ Sn
5. Therefore S is not a set of the sequence. □
Bob claims that there is an error in Alice’s argument. Is he right? If yes, what is the flaw? If no,代 写CS 3800 Homework 3 Spring 2024R
代做程序编程语言 does Alice’s result contradict our results in lecture?
6. [5 Points] Cantor’s Theorem states that for every function f : X → P(X) from a set X to its power set, there exists a set S ⊆ X such that S ≠ f(x) for all x ∈ X. This set S is constructed using Cantor’s diagonalization method.
Suppose that X = {a, b, c, d, e} and that f is given by
f(a) = {a, c, d, e}
f(b) = {a, d, e}
f(c) = ∅
f(d) = {a, c, d}
f(e) = {a, b, d}
What is the set S constructed by Cantor’s diagonalization method?
7. [9 Points] Consider the finite automaton whose diagram is depicted below.

(a) Describe the language recognized by this automaton.
(b) Write down this automaton’s formal (5-tuple) description. (Specify each of the 5 compo-nents.)
8. [5 Points] Draw the state transition diagram for the DFA whose formal description is
({q1, q2, q3}, {a, b}, δ, q1, {q1, q2})
where δ is the function given in the following table:

9. [6 Points]. Tint. Submission is separate from the other problems. Instructions will be posted on Piazza. Let language L consist of all binary strings in which any two successive zeros are separated by an even number of ones. For example, ε ∈ L and 101101 ∈ L and 101100111101 ∈ L but 010 ̸∈ L and 1011011101 ̸∈ L. Write a tint program for a DFA over the alphabet {0, 1} such that L is the language accepted by your DFA.
10. [0 Point] Do not submit. Exercise 1.1 page 83. The solution is in the book page 94, this is for practice only.
11. [0 Point] Do not submit. Exercise 1.2 page 83. The solution is in the book page 94, this is for practice only.









         
加QQ：99515681  WX：codinghelp
