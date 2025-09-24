# AMC12 2003 Problem 6

Problem: Define x ♡ y to be |x-y| for all real numbers x and y. Which of the following statements is not true?

    (A) x ♡ y = y ♡ x for all x and y
    (B) 2(x ♡ y) = (2x) ♡ (2y) for all x and y
    (C) x ♡ 0 = x for all x
    (D) x ♡ x = 0 for all x
    (E) x ♡ y > 0 if x != y

Solution:

I'm using MacOS Sequoia on an Apple M1 chip

I can click on the Apple icon at the top left of my screen, open the System Settings dialog, and then open the Keyboard menu (you might have to scroll down to find the Keyboard menu on the left)

In the Keyboard settings, there is a label that says "Text Input", and underneath it, to the right, there is an option to edit the input sources

I have Unicode Hex Input as one of my input sources (I probably added it a long time ago because it helps me insert Unicode characters that aren't represented on the keyboard)

If you click the "edit" button next to Input Sources, you'll see that there's an option to show the Input menu in the menu bar

I have this option enabled -- the keyboard/input source shows in my menu bar

So, while typing this document, I navigated my cursor to the top-right menu bar, and clicked on the icon that says A | U.S.

Then I select "Unicode Hex Input"

After selecting "Unicode Hex Input", I can hold down the option key, and type "2661" (without the quotes) to create a heart

♡

If I switch my keyboard source to the U.S. keyboard, it doesn't work

I need to be using the Unicode Hex Input keyboard for it to work

♡

So I just type option+2661 to create that heart

What about Pi?

I can type the Greek letter Pi by typing option+03c0

π

So we learned about ♡ (option+2661) and π (option+03c0)

Now, let's get back to the problem

I wanted to give that Unicode lesson so we can write ♡ on a MacBook using the vi text editor

Returning the problem... let's evaluate statements A through E

Statement A is true because |x - y| = |y - x| for all real numbers x and y

Statement B is true for the following reason:

    (2x) ♡ (2y) = |(2x) - (2y)|
                = |2(x - y)|
                = 2|x - y|
                = 2(x ♡ y)

Statement C is false for the following reason:

    x ♡ 0 = |x - 0|
          = |x|

We can see that x ♡ 0 != x when x is negative

For example, -1 ♡ 0 = |-1 - 0| = |-1| = 1 and 1 != -1

So the answer is C

We can quickly check statements D and E to strengthen our confidence in the answer we gave

Statement D is true because x ♡ x = |x - x| = |0| = 0 for all real numbers x

Statement E is true because x ♡ y = |x - y| > 0 for all real numbers x and y provided x != y

We have shown that statements A, B, D, and E are true

We have shown that statement C is false

So the answer is C

I know that I kind of went on a digression, at the beginning, to talk about the Unicode Hex Input keyboard

It's really useful, so I thought I would spend some time talking about it
