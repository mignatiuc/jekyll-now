---
layout: Iteration 1
title: Iteration 1
---



In the first iteration I have completed two exercises in order to familiarize
with Ruby as well as compare it to Java/C#. The first problem was Prime Factorization, which was pretty easy to do both in Java and Ruby. I used straight-forward logic: divided the given number A by all possible factors B(starting at 2) and if A = 0 (MOD B) => I recorded B to the prime factor array and then assigned the value of (A mod B) to A.
The same logic was initially used in Ruby code. It took more time since I had to get familiarized with the use of operators/operands/ and function definition/call first. However, after browsing Ruby manuals I stumbled on Prime class which provided the possibility of using prime_division() method. This was my first pleasant surprise brought by Ruby: the whole "algorithm" ended up being just one row of code:
Prime.prime_division(n).flat_map { |a , b| [a]*b }
