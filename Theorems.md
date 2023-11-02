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
9. Definition 8.6 (Quadric surface) A quadric surface is the graph of a second-degree equation in three variables x, y and z: Ax2 + By2 +Cz2 + Dxy + Eyz + Fxz + Gx + Hy + Iz + J = 0; where A, B, ..., J are constants.
10. Definition 8.7 (Elliptic paraboloid – symmetric about the z-axis). x^2/a^2 + y^2/b^2= z/c (vertex of the parabola is when the three variables are 0)
11. Definition 8.8 (Ellipsoid) If a = b = c, then the ellipsoid is a sphere:  x^2/a^2 + y^2/b^2 + z^2/c^2 = 1
12. Definition 8.9. (function of three var) is is a rule that assigns to each ordered triple of real numbers (x,y, z) in a set D ⊆ R3 = R × R × R a unique real number denoted by f (x,y, z).
13. Definition 8.10 (Level Surface). A level surface of f (x,y, z) is the three-dimensional graph of the equation f (x,y, z) = k for some constant k.
14. Definition 8.11 (Partial Deriavative) If f is a function of two variables, its partial derivatives are the functions fx and fy defined by: fx(x,y) = lim(h→0)f (x + h,y) − f (x,y) / h, and fy(x,y) = lim(h→0)f (x,y + h) − f (x,y) / h.
   - the partial derivatives fx(a,b) and fy(a,b) can be interpreted geometrically as: The slopes of the tangent lines at P (a,b,c) to the traces C1 and C2 of S in the planes y = band x = a.
   - for three var, pariative deriative, treat two of the three var as constants
   - can use implicit differentiation for implicitly defined functions (e.g. x^3 + y^3 + z^3 + 6xyz = 1)
15. higher order partial deriavative > fxx, fxy, fyx, fyy
16. Theorem 8.4 (Clairaut’s Theorem). Suppose f is defined on a disk D that contains (a,b). If the functions fxy and fyx are both continuous on D, then fxy(a,b) = fyx(a,b).
   - partial deriavatives of order 3 and higher can also be defined, fxyy = (fxy)y
   - using Clairaut's theorem, fxyy = fyxy = fyyx if these functions are continuous
17. Theorem 8.5 (Equation of Tangent Plane).Suppose f (x,y) has continuous first partial derivatives at (a,b). A normal vector to the tangent plane at (a,b, f (a,b)) to the surface z = f (x,y) is <fx(a,b), fy(a,b),−1>.
   - Further, an equation of the tangent plane is given by fx(a,b)(x − a) + fy(a,b)(y − b) − (z − f (a,b)) = 0
   - or z = f (a,b) + fx(a,b)(x − a) + fy(a,b)(y − b)
18. Definition 8.12. Informally, we say that f is differentiable at (a,b) if the tangent plane at (a,b) is a good approximation to f at points close to (a,b).
19. Theorem 8.6 (The Chain Rule - Case 1). dz/dt = ∂f/∂x · dx/dt + ∂f/∂y · dy/dt .
20. Theorem 8.7 (The Chain Rule - Case 2) Suppose that z = f (x,y) is a differentiable function of x and y, where x = g(s, t) and y = h(s, t) are both differentiable functions of s and t. Then
   - ∂z/∂s = ∂f/∂x · ∂x/∂s + ∂f/∂y · ∂y/∂s,
   - ∂z/∂t = ∂f/∂x · ∂x/∂t + ∂f/∂y · ∂y/∂t
21. Theorem 8.8 (The Chain Rule - General Version). Suppose that u is a differentiable function of n variables x1,..., xn, and each xj is a differentiable function of m variables t1,..., tm. Then u is a function of t1,..., tm and
   - ∂u/∂ti = ∂u/∂x1 · ∂x1/∂ti + ∂u/∂x2 · ∂x2/∂ti + ··· + ∂u/∂xn · ∂xn/∂t
   - for each i = 1,...,m.
22. Theorem 8.9 (Implicit Differentiation: Two Independent Variables). Suppose the equation F(x,y, z) = 0, where F is differentiable, defines z implicitly as a differentiable function of x and y. Then,
   - ∂z/∂x = −Fx(x,y, z)/ Fz(x,y, z),
   - ∂z/∂y = −Fy(x,y, z) / Fz(x,y, z)
   - provided Fz(x,y, z) , 0
23. Definition 8.13. Let z = f (x,y). Suppose 🔺x and 🔺y are increments in the independent variable x and y respectively. Then the increment in z is defined by 🔺z = f(x + 🔺x, y + 🔺y) - f(x,y)
24. Definition 8.14.
Let z = f (x,y). Suppose 🔺x and 🔺y are increments in the independent variable x and y
respectively. Then the differentials of the independent variables x and y are dx = 🔺x, dy = 🔺y. The differential (or total differential) of the dependent variable z is dz = fx(x,y)dx + fy(x,y)dy.
25. Theorem 8.10. Suppose f is differentiable at (a,b). Let 4x and 4y be small increments in x and y respectively from (a,b). Then 🔺z ≈ dz = fx(a,b)dx + fy(a,b)dy = fx(a,b)🔺x + fy(a,b)🔺y.
26. Definition 8.15 (Directional Derivative). The directional derivative of f (x,y) at (x0,y0) in the direction of unit vector u = <a,b> is Duf(x0,y0) = lim(h→0) (f (x0 + ha,y0 + hb) − f (x0,y0) ) / h _provided this limit exists_.
26. Theorem 8.11 (Computing Directional Derivative).
If f (x,y) is a differentiable function, then f has a directional derivative in the direction of any unit vector u = <a,b> and Duf (x,y) = fx(x,y)a + fy(x,y)b.
   - We can rewrite it in terms of vectors: Duf (x,y) = <fx, fy> · ha,bi = <fx, fy> · u
27. Definition 8.16 (Gradient). The gradient of f (x,y) is the vector-valued function ∇f (x,y) = <fx, fy> = fxi + fyj = ∂f/∂x · i + ∂f/∂y · j provided both partial derivatives exist
   - 'del f'
28. Definition 8.17 (3-D Directional Derivative). The directional derivative of f (x,y, z) at (x0,y0, z0) in the direction of unit vector u = <a,b,c> is Duf (x0,y0, z0) = lim(h→0)f (x0 + ha,y0 + hb, z0 + hc) − f (x0,y0, z0)  / h _provided this limit exists_.
29. Theorem 8.12 (Computing 3-D Directional Derivative). Duf (x0,y0, z0) = ∇f (x0,y0, z0) · u where ∇f = <fx, fy, fz> = ∂f/∂x · i + ∂f/∂y · j + ∂f/∂z · k is the gradient vector.
30. Theorem 8.13 (Level Curve vs ∇f; geometric significance or intepretation). Suppose f (x,y) is differentiable function of x and y at (x0,y0). Suppose ∇f (x0,y0) != 0. Then ∇f (x0,y0) is perpendicular/normal to the level curve f (x,y) = k at the point (x0,y0) where f (x0,y0) = k.
31. Theorem 8.14 (Level Surface vs ∇f ). Suppose F(x,y, z) is differentiable function of x, y and z at (x0,y0, z0). Suppose S is the level surface F(x,y, z) = k containing (x0,y0, z0). Let C be any curve that lies on S and passes through (x0,y0, z0). Let r(t) be a parametric equation of C such that r(t0) = <x0,y0, z0>. Suppose ∇F(x0,y0, z0) , 0. Then ∇F(x0,y0, z0) · r'(t0) = 0, That is, the ∇F(x0,y0, z0) is perpendicular/normal to tangent vector r'(t0) to any curve C on the surface S that passes through (x0,y0, z0).
32. Theorem 8.15 (Tangent Plane to Level Surface equation). ∇F(x0,y0, z0) · <x − x0,y − y0, z − z0> = 0 or equivalently, Fx(x0,y0, z0)(x − x0) + Fy(x0,y0, z0)(y − y0) + Fz(x0,y0, z0)(z − z0) = 0.
33. Theorem 8.16 (Maximizing Rate of Increase/Decrease of f ). Suppose f is a differentiable function of two or three variables. Let P denote a given point. Assume ∇f (P ) , 0. Let u be a unit vector making an angle θ with ∇f . Then Duf (P ) = ||∇f (P )||cosθ. Moreover,
   - • ∇f (P ) points in the direction of maximum rate of increase of f at P (maximum value of Duf (P ) is ||∇f (P )||)
   - • −∇f (P ) points in the direction of maximum rate of decrease of f at P (minimum value of Duf (P ) is −||∇f (P )||)
34. Definition 8.18 (Local and Absolute Maximum). Let f (x,y) : D → R. Then
   - • f has a local maximum at (a,b) if f (x,y) ≤ f (a,b) for all points in some disk with center (a,b). The number f (a,b) is called a local maximum value.
   - • f has an absolute maximum at (a,b) if f (x,y) ≤ f (a,b) for all points in the domain D. The number f (a,b) is called a absolute maximum value.
35. Definition 8.19 (Local and Absolute Minimum). Let f (x,y) : D → R. Then
   -• f has a local minimum at (a,b) if f (x,y) ≥ f (a,b) for all points in some disk with center (a,b). The number f (a,b) is called a local minimum value.
   - • f has an absolute minimum at (a,b) if f (x,y) ≥ f (a,b) for all points in the domain D. The number f (a,b) is called a absolute minimum value.
36. Theorem 8.17. (Finding local extrema) If f has a local maximum or minimum at (a,b) and the first-order derivatives of f exist there, then fx(a,b) = fy(a,b) = 0.
37. Definition 8.20 (Critical or Stationary Point). Let f (x,y) : D → R. Then a point (a,b) is called a critical point of f if
   - • fx(a,b) = 0 and fy(a,b) = 0, OR
   - • one of the partial derivatives does not exist.
38. Definition 8.21 (Saddle Point). Let f (x,y) : D → R. Then A point (a,b) is called a saddle point of f if
   - • it is a critical point of f , AND
   - • every open disk centered at (a,b) contains points (x,y) ∈ D for which f (x,y) < f (a,b) and points (x,y) ∈ D for which f (x,y) > f (a,b).
39. Theorem 8.18 (Second Derivative Test). Suppose f (x,y) has continuous second-order partial derivatives on some open disk centered at (a,b). Suppose fx(a,b) = fy(a,b) = 0 (that is (a,b) is a critical point). Define the discriminant D for the point (a,b) by D = D(a,b) = fxx(a,b)fyy(a,b) − \[fxy(a,b)]^2
   - (a) If D > 0 and fxx(a,b) > 0, then f (a,b) is a local minimum.
   - (b) If D > 0 and fxx(a,b) < 0, then f (a,b) is a local maximum.
   - (c) If D < 0, then (a,b) is a saddle point of f .
   - (d) If D = 0, then no conclusion can be drawn.

## Double Integrals

1. Definition 9.1 (Double Integral). The double integral of f over the rectangle R is int( int(Rf(x,y)dA)) = lim(m,n→∞) sum(m i=1 sum(nj=1 f (x∗ij,y∗ij)🔺A ))provided the limit exists and is the same for any choice of the sample points (x∗ij,y∗ij) in Rij, for 1 ≤ i ≤ m, 1 ≤ j ≤ n. When this happens, we say that f is integrable over R
2. Theorem 9.1 (Volume as a Double Integral). If f (x,y) ≥ 0, the volume V of the solid that lies above the rectangle R and below the surface z = f (x,y) is V = int (int (R f (x,y)dA))
3. properties of the doble integral -- pg 198 ➡️ sum, constant multiplication, greater/equal to
4. Definition 9.2 (Iterated Integral).
   - int( b a int( d c f (x,y)dy ) dx) means we first integrate with respect to y from c to d (keeping x fixed) and then with respect to x from a to b.
   - int( d c int( b a f (x,y)dx ) dy) means we first integrate with respect to x from a to b (keeping y fixed) and then with respect to y from c to d.
5. Theorem 9.2 (Fubini's Theorem): If f is continuous on the rectangle R = [a,b] × [c,d], then int( int( R f (x,y)dA)) =  int( b a int( d c f (x,y)dy )dx) = int( d c int( b a f (x,y)dx) dy). More generally, this is true if we assume that f is bounded on R, f is discontinuous only on a finite number of smooth curves, and the iterated integrals exist.
6. Theorem 9.3 (A Special Case). int( int( R g(x)h(y)dA )) = int( b a g(x)dx) int( d c h(y)dy) where R = [a,b] × [c, d].
7. Definition 9.3. Type I Region -- A plane region D is said to be of Type I if it lies between the graphs of two continuous functions of x, that is, D = {(x,y) : a ≤ x ≤ b, g1(x) ≤ y ≤ g2(x)} _where g1(x) and g2(x) are continuous on [a,b]._
8. Definition 9.4. Type II Region -- A plane region D is said to be of Type II if it lies between the graphs of two continuous functions of y, that is, D = {(x,y) : c ≤ y ≤ d, h1(y) ≤ x ≤ h2(y)} where h1(y) and h2(y) are continuous on [c, d].
9. Theorem 9.4. Double Integral over Type I Domain -- If f is continuous on a Type I domain D such that D = {(x,y) : a ≤ x ≤ b, g1(x) ≤ y ≤ g2(x)} then int( int( D f (x,y)dA)) = int( b a int( g2(x) g1(x) f (x,y)dy )dx).
10. Theorem 9.5. Double Integral over Type II Domain -- If f is continuous on a Type II domain D such that D = {(x,y) : c ≤ y ≤ d, h1(y) ≤ x ≤ h2(y)} then int( int (D f (x,y)dA)) = int( d c int( h2(y) h1(y) f (x,y)dx )dy).
11. Theorem 9.6. Additivity With Respect to Domain int( int( Df (x,y)dA)) = int( int(D1f (x,y)dA)) + ··· + int( int (Dnf (x,y)dA)).
12. Theorem 9.7: int( int( D \[f (x,y) + g(x,y)] dA)) = int ( int(D f (x,y)dA)) + int( int (D g(x,y)dA))
13. Theorem 9.8: int(int(D cf (x,y)dA)) = c int( int( Df (x,y)dA))
14. Theorem 9.9: If f (x,y) ≥ g(x,y) for all (x,y) ∈ D then int ( int( D f (x,y)dA )) ≥ int ( int (D g(x,y)dA))
15. Theorem 9.10. Area of plane region Let f (x,y) = 1 over a given region D. Then the area of D is A(D) = int( int (D 1dA))
16. Theorem 9.11. Polar Coordinates Versus Rectangle Coordinates: r^2 = x^2 + y^2, x = r cosθ, y = r sinθ.
17. Definition 9.5 (Polar Rectangle). A polar rectangle is a region R = {(r,θ) : a ≤ r ≤ b, α ≤ θ ≤ β}.
18. Theorem 9.12. Change to Polar Coordinates in Double Integral: If f is continuous on a polar rectangle R given by R = {(r,θ) : 0 ≤ a ≤ r ≤ b,α ≤ θ ≤ β} where 0 ≤ β − α ≤ 2π, then int int (R f (x,y)dA ) = int( β α int( b a f (r cosθ, r sinθ)r dr) dθ).
19. Surface area of a plane = int ( int D( dS)) = int ( int D ( sqrt(fx^2 + fy^y+ 1) dA))

## Ordinary Differential Equations
1. Definition: An equation involving x,y and at least one derivative of y (can be separable, separable ODE)
2. Reduction to Separable Form: This holds for equations of the form y' = g(y / x),
   - where g is any function of y / x
   - let v = y / x, --> y = vx, y' = v + xv'
   - then the equation y' = g(y/x) can be written as v + xv' = g(v) <-> v' = ( g(v) - v) / x, which is separable
   - can solve for v, then solve for y
   - note v is also a function of x, independent var here is always x

## Others helpful theorems and formulas 

1. Trigonometric identities

![trigo](https://www.onlinemathlearning.com/image-files/trigonometric-identities.png)

2. Sine rule

info: https://www.mathsisfun.com/algebra/trig-sine-law.html

3. Cosine rule

info: https://www.youtube.com/watch?v=9CGY0s-uCUE&pp=ygULY29zaW5lIHJ1bGU%3D

4. sum of angles properties

![sin (a+b) all these](https://i.pinimg.com/originals/0f/0b/52/0f0b52735d040a376085b1cf361dd166.jpg)
