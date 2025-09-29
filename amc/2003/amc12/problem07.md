# AMC12 2003 Problem 7

Problem: How many non-congruent triangles with perimeter 7 have integer side lengths?

Solution:

We can write out every integer triple that adds up to seven... (each integer has to be a positive integer)

1. 1,1,5
2. 1,2,4
3. 1,3,3
4. 1,4,2
5. 1,5,1
6. 2,1,4
7. 2,2,3
8. 2,3,2
9. 2,4,1
10. 3,1,3
11. 3,2,2
12. 3,3,1
13. 4,1,2
14. 4,2,1
15. 5,1,1

Now we can remove the duplicates...

1. 1,1,5
2. 1,2,4
3. 1,3,3
4. 2,2,3

Some of these integer triples cannot be triangles, because the longest leg of a triangle has to be less than the sum of the other two legs

(This is owing to the triangle inequality, which states that AC < AB + BC for all triangles ABC)

Only options (3) and (4) can be triangles, so the answer is two

There are two non-congruent triangles with perimeter 7 that have integer side lengths
