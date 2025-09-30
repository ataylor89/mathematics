# AMC12 2003 Problem 12

Problem: Sally has ﬁve red cards numbered 1 through 5 and four blue cards numbered 3 through 6. She stacks the cards so that the colors alternate and so that the number on each red card divides evenly into the number on each neighboring blue card. What is the sum of the numbers on the middle three cards?

Solution:

Sally has a stack of nine cards

We know that Sally's stack satisfies the following two conditions:

1. The colors alternate
2. The number on each red card evenly divides the number on each neighboring blue card

We can represent Sally's stack as a list of nine cards

The first card in the list is the bottom card (at the bottom of the stack), and the last card is the top card (at the top of the stack)

The first and last card (i.e. the bottom and top cards) have to be red

We know that 2R has to be neighbored by 4B and 6B

I think that 4R has to be on the end... because it can only be neighbored by 4B

So we already know that 4R is at the bottom or the top of the stack

Let's try putting 4R at the bottom of the stack

4B comes next

So our first two cards are 4R, 4B

Then 2R has to come next, and 6B comes after 2R

4R, 4B, 2R, 6B

3R has to follow 6B, and 3B has to follow 3R

4R, 4B, 2R, 6B, 3R, 3B

1R has to come next, since 1 is the only remaining number that evenly divides 3

4R, 4B, 2R, 6B, 3R, 3B, 1R

The only remaining blue card is 5B, so that comes next

4R, 4B, 2R, 6B, 3R, 3B, 1R, 5B

The only remaining red card is 5R, so that comes last

4R, 4B, 2R, 6B, 3R, 3B, 1R, 5B, 5R

Let's write these as a vertical list

1. Red 4
2. Blue 4
3. Red 2
4. Blue 6
5. Red 3
6. Blue 3
7. Red 1
8. Blue 5
9. Red 5

We can quickly confirm that the colors alternate

Also, the number on each red card evenly divides the number on its neighboring blue cards

Our stack meets the two requirements defined by the problem statement

The sum of the numbers on the middle three cards is 6 + 3 + 3 = 12

So the answer is 12
