# Calculate the digits of π

Hello! I wanted to share another one of my favorite math problems.

I'm actually listening to Tessa while I write this, a song by Steve Jablonsky: [https://www.youtube.com/watch?v=_tuLd3h19Fw](https://www.youtube.com/watch?v=_tuLd3h19Fw).

Okay, the problem is this. Find an algorithm for calculating the digits of π. The algorithm should allow you to calculate an arbitrary number of digits of π. It should also allow you to prove that the first three digits of π are 3.14.

I like to say that some things are implied. It's computationally difficult to calculate 1,000,000 digits of $\pi$. You can do it with a supercomputer, but it's very difficult to calculate 1,000,000 digits of $\pi$ with a MacBook.

So if we are calculating $n$ digits of $\pi$, for some positive integer $n$, it's implied that $n$ is reasonably sized. We can set $n$ equal to 5, or 10, or even 15, but setting $n$ equal to 1,000 or 1,000,000 is a bit too ambitious.

You can see, however, that if you had a supercomputer, your algorithm would enable you to calculate one million digits of $\pi$.

Now, you might ask, what's an algorithm?

That's a really good question.

In my opinion, an algorithm is a list of instructions.

If we revisit our cryptography tutorial, then we can show how the algorithms we use can be written down as a list of instructions.

Let's consider the encryption algorithm that we use in our cryptography tutorial.

The algorithm can be written down in this way:

Encrypt algorithm:
1. Let message be the message we want to encrypt
2. Let key be the numeric key
3. Let ciphertext be a variable containing a string
4. Let max_unicode be the maximum Unicode code point
5. Let ord be a function that returns a Unicode code point for a Unicode character
6. Let chr be a function that returns a Unicode character for a Unicode code point
7. Let b64encode be a function that encodes a string in base64
8. For each character in our message
8a. Let codepoint = ord(character)
8b. If codepoint + key > max_unicode, then raise an error
8c. Let target = codepoint + key
8d. Let ciphertext = ciphertext + chr(target)
9. Let encoded_ciphertext = b64encode(ciphertext)
10. Return encoded_ciphertext

You can see how we wrote down the encryption algorithm as a list of instructions.

I think it's very helpful to think of an algorithm as a list of instructions.

In fact, it should be the first lesson in any algorithms class.

After you learn what an algorithm is, you can go on to learn some useful algorithms, like sorting a list (e.g. Quicksort), searching a sorted or unsorted list, binary search tree algorithms, red-black tree algorithms (red-black trees are self-balancing binary trees), B-tree algorithms (B-trees are the underlying data structure in relational databases like MySQL, Postgresql, or Oracle), graph algorithms, encryption algorithms, hash algorithms, et cetera.

I wanted to take some time to talk about algorithms, because we use the word "algorithm" in the problem description.

But now let's return to the problem.

The problem is this: Find an algorithm that lets you calculate an arbitrary number of digits of $\pi$. (Of course, it's too much to ask anyone to calculate 1,000,000 digits of $\pi$, because you probably need a supercomputer for that. But the algorithm should let you calculate 5 digits of $\pi$ or even 10 digits of $\pi$, using a program written in Python, Java, or some other language.)

If you want, you can try proving that the first three digits of $\pi$ are 3.14, by hand, using pen and notebook, and then you can use a program written in Python or Java to calculate the first 5 or first 10 digits of $\pi$.

I have spent a lot of time on this problem.

You could even say, I have spent years on this problem :)

Because I didn't stop at finding one algorithm to calculate the digits of $\pi$.

I actually found three algorithms for calculating the digits of $\pi$.

So after you have discovered one algorithm for calculating the digits of $\pi$, you could try to discover more.

I know of three algorithms for calculating the digits of $\pi$, and each algorithm reveals a subject in mathematics that I did not know about previously. In other words, all three algorithms are very instructive.

I should mention that... two of the algorithms I had to look up. It's really hard to discover an algorithm for calculating the digits of $\pi$, so two of them I had to look up. But after looking them up and memorizing them, it taught me a lot about mathematics.

I like to strike a balance between sounding confident and humble.

There are some really sophisticated algorithms for calculating the digits of $\pi$, and I had to look them up.

In the last problem, find the sum of the first $n$ squares, I was unable to solve it myself, so I looked the solution up.

Everyone has different circumstances. Some people are millionaires; some people are not millionaires.

Some people get private math lessons from a young age. Some people have to learn math on their own.

So I feel comfortable looking up the solution to a problem when I am unable to solve it myself.

It doesn't matter what score you get on an exam.

It doesn't matter if you can solve a problem on your own or you have to look up the solution.

What matters is your enjoyment of a subject like mathematics.

It's not my test scores that make me happy. It's not my college degree that makes me happy. It's not my chess rating that makes me happy. It's actually my passions that make me happy. I like to say that my passions make me happy :)

I wanted to talk about this at length, because some of the problems that I post on my blog are really difficult, and it's a good habit to look up the solution to a problem when you can't solve it yourself, because it helps you learn.

Calculating the digits of $\pi$ is one of my favorite problems. There's actually a trick for showing that the first three digits of $\pi$ are 3.14. I like to say that some problems have a key or a trick. I often remember a solution by remembering the key or the trick.

I can think of three ways to calculate the digits of $\pi$. I can think of three algorithms for calculating the digits of $\pi$. The algorithms are quite different, and everyone would agree that the algorithms are distinct.

I don't want to write too little; I don't want to write too much.

But I will say this: the properties of $\pi$ are at the very heart of geometry.

How do we know that the ratio of the circumference of a circle and the diameter of a circle is a constant?

(I'm still learning how to prove this.)

How do we know that the first three digits of $\pi$ are 3.14?

How do we know that $\pi$ is an irrational number?

How do we calculate $n$ digits of $\pi$ for some positive integer $n$?

I like to ask myself these questions, and explore them, and try to figure out the answer.

Before I end this post, I'd like to point out one more thing.

The number $\pi$ doesn't just teach us about the ratio between the circumference and diameter of a circle.

It also teaches us an important lesson about real numbers.

It's impossible to represent $\pi$ as an integer, or as a finite number of integers.

We need an infinite number of integers to represent $\pi$.

We need an infinite sequence or an infinite series to properly define $\pi$.

This is why a real number is a sequence.

We can think of real numbers as infinite sequences or infinite series.

It's actually impossible to define real numbers without the concept of infinity.

What is a real number?

I like to say that a real number is a Cauchy sequence.

A real number is a sequence of rational numbers that has a special property called the Cauchy property.

The sequence doesn't have to converge to a rational number (the Cauchy sequences for $\pi$ do not converge to a rational number, for example) but the tail values of the sequence are so close to each other that it seems to converge to something.

Every Cauchy sequence converges to a real number.

But prior to defining real numbers, we cannot say that a rational sequence converges to a real number, so we call it a Cauchy sequence.

The number $\pi$ is a real number, and it can be defined by a Cauchy sequence.

In fact, some of the algorithms for calculating the digits of $\pi$ allow you to construct a Cauchy sequence that represents $\pi$.

I think this is a good stopping point.

Sometimes, I'm afraid that I have written too much.

But I wanted to point out that, in order to define real numbers, we need the concept of infinity.

We can think of an irrational number like $\pi$ as an infinite sequence or an infinite series.

We can think of every real number as a sequence or a series.

One of my favorite ways to define real numbers is this:

Informally, a real number is a point on the number line. 

Formally, a real number is a Cauchy sequence, or the equivalence class of a Cauchy sequence.

Now, before I end, I'll restate the problem once again.

Problem: Find one or more algorithms for calculating an arbitrary number of digits of $\pi$.

I spent years working on this problem, and I had to look up a lot of things on the internet.

But it's one of my favorite problems, and it taught me a lot about mathematics.
