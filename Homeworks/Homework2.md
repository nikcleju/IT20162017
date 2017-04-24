---
title: "Information Theory - Homework 2"
geometry: margin=2.5cm
---

1. Consider two communication channels, Channel 1 and Channel 2, which **never** deliver the actual input.
    - Channel 1 works in the following way: one flips a coin and sends the result on a channel, but the channel always changes
the result (in case of *head* it always outputs *tails*, and vice-versa).
    - Channel 2 works in the following way: one throws a dice and sends the result on a channel, but the channel never
delivers the actual input value, but chooses at random one of the other five values for the output.

For each of these channels:

   a. Draw the graph of the channel.
   b. What is the input entropy H(X)?
   c. What is the average information transmitted on the channel?
   d. Argue how useful do you think each channel is for communication.

\ 

2. Consider the following information source:
$$S:
\begin{pmatrix}
s_1 & s_2 & s_3 & s_4 & s_5 & s_6\\
0.2 & 0.01 & 0.02 & 0.6 & 0.1 & 0.07
\end{pmatrix}$$

   a. Encode this source using Shannon, Shannon-Fano and Huffman coding
   b. Compute the average codeword length $\overline{l}$ for each of the codes. Which code is best and why?
   c. Encode the following sequence with the Huffman code found above:
$$s_2 s_2 s_3 s_1 s_6 s_2$$
   d. The encoded sequence at c). is quite long. What do you think is wrong with it?

\ 

3. Find a distribution $S: (s_1, s_2, s_3, s_4, s_5)$ for which the Huffman code might be the following code:

Message     Codeword
---------   ---------
$s_1$         100
$s_2$         0
$s_3$         1010
$s_4$         11
$s_5$         1011


