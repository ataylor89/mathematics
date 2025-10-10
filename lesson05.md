# Lesson 5: Notation; the order of operations; PEMDAS

In the last lesson, we talked at length about long addition

We also briefly mentioned long subtraction, long multiplication, and long division

So far, we have really discovered arithmetic

We have also discovered number systems, like binary, decimal, hexadecimal, and tally

We can write a list of topics we have covered so far:

1. Number systems (decimal, hexadecimal, binary, tally)
2. Arithmetic operations (addition, subtraction, multiplication, division, powers, roots, modulo)
3. Long addition, long subtraction, long multiplication, long division

So far, we have only worked with simple arithmetic expressions, like 2+2 or 365+879

How do we evaluate a complex arithmetic expression, like 2+7*8?

Well, before we talk about this, let's talk about mathematical notation

Notation is just a word that means language

Chess notation is a language for recording chess games

There are many types of chess notation

Algebraic notation is the most commonly used form of chess notation

The opening moves of the Scotch gambit, in algebraic notation, are:

1. e4 e5
2. Nf3 Nc6
3. d4 exd4
4. Bc4

Descriptive notation is another form of chess notation

Bobby Fischer recorded a lot of his games in descriptive notation

I think that, if you open the book My 60 Memorable Games by Bobby Fischer, you will see that the games are recorded in descriptive notation

The opening moves of the Scotch gambit, in descriptive notation, are:

1. P-K4 P-K4
2. N-KB3 N-QB3
3. P-Q4 PxP
4. B-QB4

So... I actually just opened my copy of My 60 Memorable Games

The edition that I have actually uses algebraic notation

So it might depend on the edition of the book

I remember reading this book, as a child, and I remember it using descriptive notation

So, to summarize, a notation system is just a language

In other words, notation and language are synonyms

Synonyms are useful because they have many phonetic advantages

We could say that we are learning mathematical language, and we are

We can also say that we are learning mathematical notation

We could say that we are learning chess language, and we are

We can also say that we are learning chess notation

The word "notation" really fits in this phrase, for some reason -- either semantically or phonetically

Semantically they mean the same thing (in my opinion)

I think they have the same denotation

Do they have different connotations? I don't know

But the word "notation" really fits in some contexts, either because of its connotations, or because of the way it sounds

So... I wanted to give some examples of the word "notation"

In the game of chess, there are two forms of chess notation that are commonly used: algebraic notation and descriptive notation

In mathematics, there are many notation systems

Decimal notation is a system for writing numbers in base ten

Binary notation is a system for writing numbers in base two

Hexadecimal notation is a system for writing numbers in base sixteen

Tally notation is a system for writing numbers in tally (e.g. 6 = ||||| |)

So every numeral system is really a notation system

Mathematics has many notation systems

We are going to talk about arithmetic

There are many notation systems for writing arithmetic expressions

We can write two plus two using infix notation: 2 + 2

We can also write two plus two using prefix notation: + 2 2

We can also write two plus two using postfix notation: 2 2 +

Things get interesting when we introduce a complex expression like two plus six times ten

We can write two plus six times ten using infix notation: 2 + 6 * 10

We can also write it using prefix notation: + 2 * 6 10

We can also write it using postfix notation: 6 10 * 2 +

When we use prefix notation and postfix notation, we don't need to specify the order of operations

When we use infix notation, we actually have to specify the order of operations

When we write 2 + 6 * 10 (using infix notation) we have to specify which operation comes first, addition or multiplication

For this reason, we have a set of rules which define the order of operations when we evaluate an infix expression

(The subject "set of rules" is singular so perhaps the verb "define" should be "defines"... but the s's kind of clash with each other)

PEMDAS is a set of rules that defines the order of operations

PEMDAS is an acronym that means "Parentheses, Exponents, Multiplication, Division, Addition, Subtraction"

The idea is this: every operator has a rank, also called a precedence

Addition and subtraction have the lowest rank/precedence

We can say that addition and subtraction have a precedence of 0

We can also say that addition and subtraction have low precedence

We can say that multiplication and division have a precedence of 1

We can also say that multiplication and division have medium precedence

We can say that exponents have a precedence of 2

We can also say that exponents have high precedence

We can say that parentheses have a precedence of 3

We can also say that parentheses have highest precedence

Parentheses tell us to evaluate an expression first, that is, the expression enclosed by parentheses

Parentheses tell us to evaluate a subexpression first

So when we write 2 + 6 * 10, there are two operations, addition and multiplication

Multiplication has a higher rank than addition, so we evaluate 6 * 10 first, and then we add 2

2 + 6 * 10 = 2 + 60 = 62

What if we write (2 + 6) * 10?

Parentheses tell us to evaluate the expression 2 + 6 first

(2 + 6) * 10 = 8 * 10 = 80

So you see, when we evaluate an arithmetic expression written using infix notation, we have to know the order of operations

But when we evaluate an arithmetic expression written using prefix notation or postfix notation, the OOO are not needed

For example, we can write (2 + 6) * 10 in prefix as *10+26

The algorithm for evaluating prefix expressions does not require knowledge of the order of operations

The algorithm for evaluating prefix expressions does not require knowledge of operator precedence

In the prefix expression *10+26, the operator + has precedence just because it has two operands that follow it, whereas the * operator has an operand and an operator that follows it

The algorithm for evaluating prefix expressions is greedy, because it performs an operation wherever it can

We cannot perform the operation *10+, but we can perform the operation +26, so we perform the operation +26 first

After simplifying, we are able to perform the operation * 10 8

So you see, in order to evaluate an arithmetic expression written using infix notation, we need to know the order of operations

We have three notations for writing arithmetic expressions: prefix, postfix, and infix

Infix notation has many advantages

It is easier to read and understand infix notation

Furthermore, infix notation lends itself better to algebra

It is easier to write equations using infix notation, especially since the = relation is placed between two expressions

In infix notation, the operator is placed in between the operands

In prefix notation, the operator is placed before the operands

In postfix notation, the operator is placed after the operands

In algebraic equations, we are accustomed to placing the = sign between two expressions

The equals sign is a symbol (and also a relation) that asserts two expressions are equal

Equality is a relation that asserts two expressions are equal

The equals sign is a symbol that asserts two expressions are equal

We are accustomed to placing the = sign in between two algebraic expressions

For example, 2 + 6 * 10 = 2x

It is easy to write this equation using infix notation

What if we wrote this equation using prefix notation?

\+ 2 * 6 10 = * 2 x

Honestly, it's not clear where we should put the = sign

Maybe you can think of a better way of writing this equation using prefix notation...

I have thought about it for some time...

I cannot think of a good way to write equations using prefix notation

Equations are so important, in algebra and also in arithmetic, that it makes sense to use infix notation

So you see...

In the fields of algebra and arithmetic, infix notation is the preferred notation

If we use infix notation, then we have to know the order of operations

PEMDAS is a nice acronym that reminds us of the order of operations

PEMDAS is a mnemonic, a memory tool

We evaluate a subexpression enclosed by parentheses first

Exponents have a higher rank (precedence) than multiplication and division

Multiplication and division have a higher rank (precedence) than addition and subtraction

Addition and subtraction have the lowest rank (prededence)

So, to summarize...

Parentheses have the highest precedence

Exponents have high precedence

Multiplication and division have medium precedence

Addition and subtraction have low precedence

It's also important to know some important properties that involve parentheses

The distributive property of real numbers says that a * (b + c) = a * b + a * c for any real numbers a, b, and c

When we evaluate a * (b + c), we can evaluate b + c first, but we can also distribute a into the parentheses, and evaluate a * b + a * c

The associative property of real numbers says that a + (b + c) = (a + b) + c

We can evaluate (b + c) first, but we can also move the parentheses, and evaluate (a + b) first

So you see...

It's really useful to say "We evaluate an expression enclosed by parentheses first"

But there are some exceptions to this rule

We can distribute a factor into a parenthetical expression, e.g. a * (b + c) = a * b + a * c

We can also rewrite an expression using the associative property, e.g. a + (b + c) = (a + b) + c

So listen

The bottom line is this

When we evaluate an expression, we can locate the highest-ranking operator, and perform the associated operation

When we evaluate an expression, we can locate the highest-ranking operation, and perform the operation

But we can also use the substitution property to substitute expression X for expression Y if X = Y

For example, we can evaluate (1 + 5) + 5 by peforming the highest ranking operation, i.e. (1 + 5)

But we can also rewrite (1 + 5) + 5 as 1 + (5 + 5), and evaluate an equivalent expression

We can write (1 + 5) + 5 = 1 + (5 + 5) because of the associative property

Then we can write 1 + (5 + 5) = 1 + 10 = 11

First, we make a substitution by invoking the associative property

Then, we perform the highest-ranking operation, (5 + 5)

Then, we perform the one remaining operation, 1 + 10

Finally, we get an answer of 11

You can see that...

When we evaluate a complex expression like 1 + (5 + 5), we recursively simplify the expression

On each iteration, we perform the highest-ranking operation, or we make a substitution

Let's try evaluating 2 + 6 * 10 - 3

First, we locate the highest-ranking operation, 6 * 10

We perform the operation

2 + 6 * 10 - 3 = 2 + 60 - 3

Now we can see that the operations 2 + 60 and 60 - 3 have the same precedence

When two operators or operations have the same precedence, we can evaluate them left to right

2 + 60 - 3 = 62 - 3

You can see that we are recursively simplifying the original expression, and on each iteration, we perform the highest-ranking operation

62 - 3 = 59

Finally, we arrive at the answer 59

2 + 6 * 10 - 3 = 59

So... to make a long story short...

In this lesson we talked about how we evaluate a complex expression, like 2 + 6 * 10 - 3

In order to evaluate a complex expression, we need to know the order of operations

This is true when we use infix notation, which is the standard notation for arithmetic and algebra

When we use prefix notation or postfix notation, we actually don't need to know the order of operations

So, just to be clear...

In order to evaluate a complex expression written in infix notation, we need to know the order of operations

Infix notation is the preferred notation for arithmetic and algebra, because it's really suited for writing equations

In this document we talked about three kinds of arithmetic notation systems: infix, prefix, and postfix

In addition to that, we really defined the word "notation"

A notation is a language

Algebraic notation is the language we use for writing algebraic equations

Algebraic notation uses infix notation

We can write arithmetic expressions in infix notation, prefix notation, or postfix notation

But for writing algebraic equations, we really need to use infix notation

In order to solve algebraic equations, it helps to use infix notation

So algebraic notation uses infix expressions

It's really interesting... we are learning about mathematical notation

There are many types of mathematical notation

Infix notation is one subject in mathematical notation

Decimal notation is another subject

When we learn mathematical notation, we can learn to read mathematical sentences like...

2 + 6 * 10 - 3 = x + 5

We know how to solve this equation, because we know the rules of algebra, and because we know the order of operations

We know how to interpret the numbers, because we know decimal notation

We know how to interpret the variable x, because we know algebraic notation

We know how to evaluate each operation, because we know infix notation

So, our knowledge of mathematical notation really helps us understand mathematical documents

Mathematics is a language...

We can say that mathematical notation is really just a phrase that means "the language of mathematics"

It's either part of that language, or the language itself, depending on how you want to define the word "notation"

For example, the words "algebra" and "probability" are two terms taken from the language of mathematics

Are these words part of "mathematical notation"?

We can say yes, they are

Mathematical vocabulary is part of mathematical notation

I like to say, the words "notation" and "language" are really just synonyms

You can argue that the word "notation" has a more specific meaning, but I like to think of it as a synonym for language

In this document we learned about mathematical notation

We learned about infix notation, prefix notation, postfix notation

We learned about PEMDAS and the order of operations

We need to know the order of operations in order to evaluate infix expressions

In conclusion, I'd like to say...

PEMDAS is a set of rules that defines the order of operations

PEMDAS helps us evaluate infix expressions, like 2 + 6 * 10 - 3

We are really learning the rules of arithmetic

We are also learning the language of arithmetic

So far we have discovered arithmetic

We can talk about algebra later on

But... if we are going to track our progress...

We can say...

We have discovered number systems and arithmetic

We know how to evaluate simple expressions and complex expressions

We can use long addition, long subtraction, long multiplication, and long division, to make difficult calculations

So we can really say...

We have gotten far in the field of arithmetic

We have mastered many subjects in the field of arithmetic

What's next?

It might be that algebra is next
