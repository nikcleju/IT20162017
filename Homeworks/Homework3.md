---
title: "Information Theory - Homework 3"
geometry: margin=2.5cm
---

1. Consider a systematic code with codeword length $n=8$ and information word length $k=4$.
The $4$ control bits $c_0, c_1, c_2, c_3$ are defined by the following equations
(the information bits are $i_0, i_1, i_2, i_3$):
$$
\begin{cases}
    c_0 =& i_1 + i_2 + i_3 \\
    c_1 =& i_0 + i_1 + i_2 \\
    c_2 =& i_0 + i_1 + i_3 \\
    c_3 =& i_0 + i_2 + i_3
\end{cases}
$$
    a. Find the generator matrix [G] and the parity-check matrix [H] for this code
    b. Find how many errors this code can detect and how many it can correct 
(based on the columns of [H])
	c. From the result b), deduce the minimum Hamming distance of the code

2. Consider the following source code:
 
 A   C   D   E   G   I   N   O
--- --- --- --- --- --- --- ---
000 100 010 001 110 101 011 111

The letters are encoded with an error correcting code with the following
generator matrix:

$$[G]=
\begin{pmatrix}
1 & 0 & 1 & 0 & 1 \\
0 & 1 & 0 & 1 & 0 \\
0 & 0 & 0 & 1 & 1
\end{pmatrix}$$

Use [G] to encode the word "ENCODING" (letter by letter).

3. Some data is transmitted over a Binary Symmetric Channel with 
probability of error $p = 10^{-6}$. The data is encoded with
the Hamming(7,4) code used for correction.

    a. How many errors can this code correct?
    b. What is the probability that the correction fails? 
    (i.e. a codeword has errors that go undetected or are wrongly corrected).
	*Hint*: Find the smallest number of errors the code can *not* correct, 
	and compute the probability to have this many errors in a codeword (we neglect
	the probability of having more errors than that). You
	might need the value $C(7,2)=21$ (combinations of 7 taken by 2).
