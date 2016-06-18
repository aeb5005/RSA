## RSA (Rivest-Shamir-Adleman) encryption algorithm

# RSA simple explanation

A.	One Way:
These functions are easy to compute in one direction, but essentially impossible in the other direction.
f(x) = y  Easy to compute
f-1(y) = x  NP hard
B.	Trap Door:
Identify applicable sponsor/s here. If no sponsors, delete this text box (sponsors).
If a crucial piece of information is known, it is easy to calculate the inverse:
f-1(y) = x, given trap door information  Easy

An easy to understand example:
It is easy to mix different types of rice together.
f(white rice + brown rice) = mixture  Easy
It is difficult to separate
f-1(mixture) = white rice + brown rice
If we had the “trap-door” piece of information, f-1() would become an easy operation.

# Safety

The “trap door one way” function, for sufficiently large numbers, are considered secure. The security of the RSA cryptosystem is based on the intractability of the integer factorization problem. Additionally, imagine if someone wanted to decrypt the plaintext message m and had the public information (n, e). There is no efficient algorithm for this problem, and it is known as the RSA problem. When generating RSA keys, it is imperative that the primes p and q are selected such that n = pq is computationally infeasible. e is also recommended to be small to improve the efficiency of the algorithm. 
