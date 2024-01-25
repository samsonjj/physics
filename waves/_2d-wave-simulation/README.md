Lesson from https://beltoforion.de/en/recreational_mathematics/2d-wave-equation.php
Copied from https://github.com/beltoforion/recreational_mathematics_with_python/blob/master/waves_2d_improved.py

# Learnings

## Hyperbolic PDE
Hyperbolic partial differential equations are a subset of second-order PDEs (the others are elliptic and parabolic). They have the specific property that localized disturbances to the initial conditions are not felt across the space instantly, instead they propogate over time. Very wave-like if you ask me :)

## Subscript Notation
Subscripts can be used to shorten partial derivative terms: u<sub>xy</sub> would be the second partial derivative of u with respect to dudy.

## Laplace Operator
∆u (Laplace Operator is the ∆ symbol) means the sum of second partial derivitives in the cartesian coordinates of a field quantity. i.e. u<sub>xx</sub> + u<sub>yy</sub>

## Difference Quotient
We are familiar with the equation

$$ f(x+h) - f(x) \over h $$

This is the different quotient. Turns out there are [higher order difference quotients](https://en.wikipedia.org/wiki/Difference_quotient#Second_order) for solving second derivatives, etc. Second order is

$$ F(P_2) - 2F(P_1) + F(P_0) \over dP^2 $$

or something like that.

------
When $a \ne 0$, there are two solutions to $(ax^2 + bx + c = 0)$ and they are 
$$ x = {-b \pm \sqrt{b^2-4ac} \over 2a} $$