# Prime Factorizer

The `index.html` file contains a simple HTML form that can factor integers into prime numbers.

It is [provable](https://en.wikipedia.org/wiki/Fundamental_theorem_of_arithmetic#Proof) that all integers greater than 1 (no matter how large) have a unique Prime Factorization.  For an example using a small number, the prime factorization of `24` is given by <code>24 = 2<sup>3</sup>&middot;3</code>. 

This JavaScript routine in `prime-factorizer.js` implements one possible algorithm for finding the prime factorization of an integer.

It is [well known](https://en.wikipedia.org/wiki/Integer_factorization) that despite the _existence_ of a solution in all cases, factoring integers into primes is not always _temporally_ possible (even for computers) if we are given a large enough integer to factor.  The set of integers is limitless, and so it follows that limitless too is the amount of time it can conceivably take for any process to find the prime factors of a sufficiently large integer.

This JavaScript example illustrates the above paragraph in a "fun" way, by making your browser crash if you enter a number that is too large for our JS algorithm to handle.