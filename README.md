# Big-O-notation- https://www.quora.com/What-is-the-difference-between-big-oh-big-omega-and-big-theta-notations

Big O, Big Omega, and Big Theta are mathematical notations used to describe the asymptotic behavior of functions, particularly in computer science for analyzing algorithms. Here’s a breakdown of each:

# 1. Big O Notation (O)

Definition: Big O notation describes an upper bound on the time (or space) complexity of an algorithm. It provides a worst-case scenario for the growth rate of a function.
Mathematical Formulation: A function  
f(n) is in  O(g(n))
 if there exist positive constants  c  and  n0such that:f(n)≤c⋅g(n) for all n≥n0
 
Example: If  f(n)=3n^2+2n+1 , then  f(n) is in  O(n2) because there are constants  c and n0 that satisfy the definition.

# 2. Big Omega Notation (Ω)

Definition: Big Omega notation describes a lower bound on the time (or space) complexity of an algorithm. It provides a best-case scenario for the growth rate of a function.
Mathematical Formulation: A function  f(n) is in  Ω(g(n)) if there exist positive constants c and  n0 such that: f(n)≥c⋅g(n) for all n≥n0
 
Example: If  f(n)=3n^2+2n+1, then  f(n) is in  Ω(n^2) because it grows at least as fast as n^2 for large n.

# 3. Big Theta Notation (Θ)

Definition: Big Theta notation describes a tight bound on the time (or space) complexity of an algorithm. It indicates that a function grows at the same rate as another function for large inputs.
Mathematical Formulation: A function  f(n) is in Θ(g(n)) if there exist positive constants c1,c2, and  n0 such that: c1⋅g(n)≤f(n)≤c2⋅g(n) for all n≥n0
 
Example: If  f(n)=3n2+2n+1 , then  f(n) is in  Θ(n2) because it is both O(n2) and  Ω(n2).

# Summary

Big O (O): Upper bound (worst-case)
Big Omega (Ω): Lower bound (best-case)
Big Theta (Θ): Tight bound (average-case or exact growth)
These notations help in analyzing and comparing the efficiency of algorithms, especially in terms of their time and space complexity.

# Basic programing Example
