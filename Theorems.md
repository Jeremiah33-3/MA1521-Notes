# Most theorems in Thomas Calculus textbook

## Chapter 2: Limits 
1. Theorem 1: Limit Laws
   - sum, difference, product, division, constant mulitple, power, root rules
2. Theorem 2: Limits on polynomial
   - If P(x) = anxn + an-1xn-1 + g + a0, then lim(x->c)P(x) = P(c) = anx^c +... + a^0
   - polynomial is continuous
3. Theorem 3: Limits on rational funcitons
   - If P(x) and Q(x) are polynomials and Q(c) ≠ 0, then lim(x->c)(P(x)/Q(x)) = P(c)/Q(c)
4. Theorem 4: The Sandiwch Theorem
   - Suppose that g(x) <= ƒ(x) <= h(x) for all x in some open interval containing c, except possibly at x = c itself. Suppose also that lim(x->c)g(x) = lim(x->c)h(x) = L. Then lim(x->c)f(x) = L
6. Theorem 6:
   - Suppose that a function f is defined on an open interval containing c, except perhaps at c itself. Then ƒ(x) has a limit as x approaches c if and only if it has left-hand and right-hand limits there and these one-sided limits are equal: lim(x->c)f(x) = L <=> left side and right side equal (lim...)
7. Theorem 7: Limit of the Ratio (sin x)/x as x -> 0 = 1 (x in radians)
8. Theorem 8: Properties of Continuous Functions
   - If the functions ƒ and g are continuous at x = c, then the following algebraic combinations are continuous at x = c:
     a. sums
     b. difference
     c. constant multiples
     d. product
     e. quotient 
     f. powers
     g. roots
9. Compositions of Continuous Functions
    - If ƒ is continuous at c and g is continuous at ƒ(c), then the composition g ∘ ƒ is continuous at c.
10. Limits of Continuous Functions
    - If lim(x->c)ƒ(x) = b and g is continuous at the point b, then lim(x->c)g(f(x)) = g(b)
11. The Intermediate Value Theorem for Continuous Functions
    - If ƒ is a continuous function on a closed interval [a, b], and if y0 is any value between ƒ(a) and ƒ(b), then y0 = ƒ(c) for some c in [a, b].
12. Theorem 12:
    - All the Limit Laws in Theorem 1 are true when we replace lim(x->c) by lim(x->∞) or lim(x->-∞).
    - That is, the variable x may approach a finite number c or +-∞.

## Vectors and geometry space (chap 12)

1. T7.1: (distance formula) The distance |P1P2| between points P1(x1, y1, z1) and P2(x2,y2,z2) is |P1P2| = sqrt( (x2 - x1)^2 + (y2 - y1)^2 + (z2- z1)^2 )
2. T7.2: (consquently from 7.1; equation of sphere) An equation of a sphere with center C(h,k,l) and radius r is (x − h)^2 + (y − k)^2 + (z − l)^2 = r^2
3. D7.1: (Adding Vectors - the triangle law) Let u and v be two vectors. Then their sum u+v is the vector from the initial point of u to the terminal point of v when we position the vectors so that the initial point of v coincide with the terminal point of u
4. D7.2 (Scalar multiplication) Let c ∈ R and u be a vector. The scalar multiple cu is the vector whose length is |c| times the length of u and whose direction is the same as u if c > 0 and is opposite to u if c < 0. If c = 0 or u = 0, then cu = 0.
5. T7.3: Given the points A(x1,y1, z1) and B(x2,y2, z2), the vector **a** representing ->AB is a = <x2 − x1,y2 − y1, z2 − z1>
6. T7.4: (Properties of Vectors) Suppose a, b and c are vectors, and c, d ∈ R are scalars. Then
   - (1) a + b = b + a
   - (2) a + (b + c) = (a + b) + c
   - (3) a + 0 = a
   - (4) a + (-a) = 0
   - (5) c(a + b) = ca + cb
   - (6) (c + d)a = ca + da
   - (7) (cd)a = c(da)
   - (8) 1a = a
7. T7.5: If **a** != 0,  then a unit vector in the same direction as **a** is given by **u** = **a**/||**a**||
8. T7.6: (Properties of dot product) For vectors **a**, **b** and **c** and any scalar d,
   - (i) a · b = b · a (commutativity)
   - (ii) a · (b + c) = a · b + a · c (distributive law)
   - (iii) (da) · b = d(a · b) = a · (db)
   - (iv) 0 · a = 0 (length)
   - (v) a · a = ||a||^2
9. T7.7: Let θ be the angle between nonzero vectors a and b. Then a · b = ||a|| ||b||cosθ --> derived from law of cosine
10. T7.8: Two vectors a and b are orthogonal if and only if a · b = 0
11. (Distance from a point to a plane) The (shortest) distance from a point P (x0,y0, z0) to the plane ax + by + cz = d is given by |ax0 + by0 + cz0 − d| / √a^2 + b^2 + c^2
12. T7.10: The  vector a × b is orthogonal to both a and b.
13. T7.11: If θ is the angle between a and b, then ||a × b|| = ||a|| ||b|| sinθ
   - cross product can be used to (1) calculate area of parallelogram (2) find the distance from a point to a line in R3
   - a × b != b × a
14. T7.12: If a, b and c are vectors and d is a scalar, then
   - a × b = −b × a
   - (da) × b = d(a × b) = a × (db)
   - a × (b + c) = a × b + a × c
   - (a + b) × c = a × c + b × c
15. T7.13: (Parametric Equation of Line) vector format； r = r0 + tv; <x,y, z> = <x0,y0, z0> + t<a,b, c> --> x = x0 + at, y = y0 + bt, z = z0 + ct.
16. T7.14: (Vector equation of plane) n ·(r − r0) = 0 or n · r = n · r0
17. T7.14 (Linear equation of plane) ax + by + cz + d = 0, where d = −(ax0 + by0 + cz0).

## Vector functions of several variables 

> A vector-valued function r(t) is a mapping from its domain D ⊆ R to its range R ⊆ V3, so that for each t ∈ D, r(t) = v for exactly one vector v ∈ V3.
> r(t) = f (t)i + g(t)j + h(t)k
> or r(t) = <f (t),g(t), h(t)>

1. Definition 8.1. The derivative r'(t) of the vector-valued function r(t) is defined by r'(t) = lim ( 🔺t→0) ( (r(t +🔺t) − r(t)) / 🔺t) for any values of t for which the limit exists.
2. Theorem 8.1 (Derivative of Vector-valued Function) Let r(t) = <f (t),g(t), h(t)> and suppose that the components f , g and h are all differentiable at
t = a. Then r is differentiable at t = a and its derivative is given by r'(a) = <f'(a),g'(a), h'(a)>.
3. Theorem 8.2 (Derivative Rules). pg 154
4. Theorem 8.3 (Arc Length Formula) Let C be the curve given by r(t) = <f (t),g(t), h(t)>, a ≤ t ≤ b where f', g' and h' are continuous. If C is traversed exactly once as t increases from a to b, then its length is s = int b a ( sqrt(f'(t)^2 + g'(t)^2 + h'(t)^2) dt ) = int b a( ||r'(t)|| dt)
5. Definition 8.2. A function f of two variables is a rule that assigns to each ordered pair of real numbers (x,y) in a set D ⊆ R2 = R × R a unique real number denoted by f (x,y).
6. Definition 8.3 (Level Curve). A level curve of f (x,y) is the two-dimensional graph of the equation f (x,y) = k for some constant k.
7. Definition 8.4 (Contour Plot). A contour plot of f (x,y) is a graph of numerous level curves f (x,y) = k, for representative values of k.
8. Definition 8.5. A surface is a cylinder if there is a plane P such that all the planes parallel to P intersect the surface in the same curve (when viewed in 2-dimension).


## Others helpful theorems and formulas 

1. Trigonometric identities

![trigo](https://www.onlinemathlearning.com/image-files/trigonometric-identities.png)

2. Sine rule

info: https://www.mathsisfun.com/algebra/trig-sine-law.html

3. Cosine rule

info: https://www.youtube.com/watch?v=9CGY0s-uCUE&pp=ygULY29zaW5lIHJ1bGU%3D

4. sum of angles properties

![sin (a+b) all these](https://i.pinimg.com/originals/0f/0b/52/0f0b52735d040a376085b1cf361dd166.jpg)
