# AMC12 2003 Problem 5

Problem: The sum of the two 5-digit numbers AMC10 and AMC12 is 123422. What is A+M+C?

Solution:

I like this problem

It shows that we can use variables in creative ways (e.g. a variable can stand for a digit in a number)

So we know that AMC10 + AMC12 = 123422

The variables A, M, and C are digits, and each digit has a weight, according to its position in the decimal number

We can write the following equation:

    A*10^4 + M*10^3 + C*10^2 + 10 + A*10^4 + M*10^3 + C*10^2 + 12 = 123422

Now we can simplify

    A*10^4 + M*10^3 + C*10^2 + 10 + A*10^4 + M*10^3 + C*10^2 + 12 = 123422  (step 1)
    A*10^4 + M*10^3 + C*10^2 + A*10^4 + M*10^3 + C*10^2 = 123400            (step 2)
    A*10^2 + M*10 + C + A*10^2 + M*10 + C = 1234                            (step 3)
    100A + 10M + C + 100A + 10M + C = 1234                                  (step 4)
    200A + 20M + 2C = 1234                                                  (step 5)
    100A + 10M + C = 617                                                    (step 6)

C has to be 7  
M has to be 1  
A has to be 6

Therefore, A + M + C = 14
