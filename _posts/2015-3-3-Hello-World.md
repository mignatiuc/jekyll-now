---
layout: default
title: Iteration 1
---

In the first iteration I have completed two [excercises](http://mignatiuc.github.io/Hello-World/)  in order to familiarize
with Ruby as well as compare it to Java/C#. The first problem was Prime Factorization, which was pretty easy to do both in Java and Ruby. I used straight-forward logic: divided the given number A by all possible factors B(starting at 2) and if A = 0 (MOD B) => I recorded B to the prime factor array and then assigned the value of (A mod B) to A.
The same logic was initially used in Ruby code. It took more time since I had to get familiarized with the use of operators/operands/ and function definition/call first. However, after browsing Ruby manuals I stumbled on Prime class which provided the possibility of using prime_division() method. This was my first pleasant surprise brought by Ruby: the whole "algorithm" ended up being just one row of code: 
Prime.prime_ division(n). flat_map { |a , b| [a]*b }

The second assignment was called Mars Rover Kata. It basically described the robot travelling on a sphere with grid coordinates.
Some coordinates, however, can be non-passable; we call them "obstacles". The rover cannot be located as the same coordinate with an obstacle, therefore their coordinates can never be the same + rover should display a warning message.
I uses OOP approach for this problem and created a class for describing a point, grid, rover movement, obstacle set-up and compass arrow. It was basically a meticulous setter/getter assignmnet with logic only applicable to compass arrow direction and "resetting" the coordinate in case its > MAX coordinte or < MIN coordinate.
As of Ruby, again, it was much easier and faster experience as in my program it excluded linked lists, multiple classes, datatype/function type explicit declaration. The only complications I met were, again, syntax difficulties due to lack of experience in Ruby(for example readInstructionStr.each_char do |instruct| didn't execute without || brackets around "instruct" )

Overall, it was a pleasant experience, that made me look at Ruby as at a tool that I can use ot get maximum efficiency in minimal time.


