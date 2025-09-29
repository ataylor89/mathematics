# AMC12 2003 Problem 11

Problem: A square and an equilateral triangle have the same perimeter. Let A be the area of the circle circumscribed about the square and B be the area of the circle circumscribed about the triangle. Find A/B.

Solution:

Let P be the perimeter of the square and the equilateral triangle

The square has a side length of P/4 and the triangle has a side length of P/3

We can draw a line segment from the top-left corner of the square to the center of the square

We can also draw a line segment from the midpoint of the top side to the center of the square

This creates a right triangle with side lengths P/8, P/8, and sqrt(2)*P/8

The hypotenuse of the right triangle is the radius of the circle that circumscribes the square

The area of the circle, A, is equal to (Pi)(r^2) = (Pi)(sqrt(2)*P/8)^2

    A = (Pi)(r^2)
      = (Pi)(sqrt(2)*P/8)^2
      = (Pi)(2*P^2 / 64)
      = (Pi)(P^2)/32

Now, let's figure out the area of the circle that circumscribes the equilateral triangle

We can draw a point at the center of the equilateral triangle

We can draw three perpendiculars from this point to the sides of the equilateral triangle

This creates six 30-60-90 right triangles

Each 30-60-90 right triangle has a side length of P/6 opposite the 60 degree angle

The hypotenuse is the radius of the circle that circumscribes the equilateral triangle

Thus we have

    sin(60) = P/6 / hypotenuse
    sqrt(3)/2 = P/6 / hypotenuse
    hypotenuse * sqrt(3)/2 = P/6
    hypotenuse * sqrt(3) = P/3
    hypotenuse * 3 = P * sqrt(3) / 3
    hypotenuse = P*sqrt(3)/9

The radius of the circle is P*sqrt(3)/9

The area of the circle, B, is equal to (Pi)(r^2)

    B = (Pi)(r^2)
      = (Pi)(P*sqrt(3)/9)^2
      = (Pi)(P^2*3/81)
      = (Pi)(P^2)/27

Now we can calculate the ratio A/B

    A/B = (Pi) (P^2) * 1/32 / (Pi)(P^2) * 1/27
        = 1/32 / 1/27
        = 1/32 * 27
        = 27/32

Thus A/B = 27/32
