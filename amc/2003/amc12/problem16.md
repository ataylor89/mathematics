# AMC12 2003 Problem 16

Problem: A point P is chosen at random in the interior of equilateral triangle ABC. What is the probability that ABP has a greater area than each of ACP and BCP?

(A) 1/6 (B) 1/4 (C) 1/3 (D) 1/2 (E) 2/3

Solution:

I think that this problem would be clearer if we specified that P is not the incenter of ABC

(The incenter of ABC is the point Q that divides ABC into three congruent triangles -- ABQ, ACQ, and BCQ)

Let P be a point chosen at random in the interior of ABC, such that P is not the incenter of ABC

P divides ABC into three triangles, ABP, ACP, and BCP

We know that the areas of these three triangles sum up to the area of ABC

    Area(ABP) + Area(ACP) + Area(BCP) = Area(ABC)

Let h1, h2, h3 be the altitudes of ABP, ACP, and BCP respectively

Let s be the side length of the equilateral triangle ABC

    Area(ABP) + Area(ACP) + Area(BCP) = Area(ABC)
    (1/2)(s)(h1) + (1/2)(s)(h2) + (1/2)(s)(h3) = (1/2)(s)(s*sqrt(3)/2)
    (1/2)(s)(h1 + h2 + h3) = (1/2)(s)(s*sqrt(3)/2)
    h1 + h2 + h3 = s * sqrt(3)/2

We see that the altitudes of the three triangles (ABP, ACP, BCP) sum up to the altitude of ABC, since s*sqrt(3)/2 is the altitude of ABC

If we assume that P is not the incenter of ABC, then it's impossible for all three altitudes to be equal

(The altitudes h1, h2, and h3 are only equal when P is the incenter of ABC)

By symmetry we can say that each altitude has an equal chance of being the largest altitude

Thus, each altitude has a 1/3 chance of being the largest altitude

The largest triangle (among ABP, ACP, BCP) is the triangle with the largest altitude, since all three triangles have the same base length

ABP has a 1/3 chance of having the largest altitude, thus it has a 1/3 chance of being the largest triangle

The answer is (C) 1/3

Afterword:

If we allow P to be any point in the interior, including the incenter, I think that the probability is still the same... it's just hard to explain how the probability does not change

Perhaps the answer is 1/3

Perhaps the answer is 1/3 minus an infinitesimal
