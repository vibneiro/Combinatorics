Combinatorics
=============
Author: Ivan Voroshilin

Groovy utility classes based on lazy Iterators for combinatorics such as C(n,k), P(n,k).
At your will, it's easy to turn this code into pure java.

Description:
=============
When working with large arrays of elements, sometimes there is a need to iterate combinatorial sets without preliminary calculations by saving memory. E.g. C(n, k) = C(1000,5) results into 82,50,291,250,200 elements.

I wrote this library with the goal to calculate the next k elements on the fly. The only array under the iterator is "indices" of length k which is negligible.
