# MA1521-Notes
My take on MA1521 (AY23/24 Sem 1)

## Definitions and concepts

1. Numbers
- Collection of real numbers R
- integers, rational no, irrational no. (not square root of negative no)
- closed interval [a,b] | open interval (a, b) | half-open intervals (a, b] or [a, b)

2. Absolute
- defined as a piecewise function |a| = { a, if a>=0 or -a, if a <0
- properties of |x|:
  - | − x| = |x|, for all x ∈ R.
  - |xy| = |x||y|, for all x,y ∈ R.
  - −|x| ≤ x ≤ |x|, for all x ∈ R.
  - For a fixed r > 0, |x| < r if and only if x ∈ (−r, r).
  - √x^2 = |x|, x ∈ R.
  - **(Triangle Inequality) |x + y| ≤ |x| + |y| for all x,y ∈ R.**
 
3. Functions
- f : A −→ B or a |→ f (a): a rule that assigns to each a ∈ A one specific member f (a) of B
- specify function -> gives rule f(x) = ....
- jargons
  - codomain: set B, the set of output the function is constrained to give 
  - domain: set A, the set of values funciton f is being applied to 
  - range: the subset of set B/codomain containing all the values of f -> range of f = {f (x) ∈ B | x ∈ A}
  - real-valued function (functions mapping to real numbers)
  - composite function: applying two functions to a value in succession, provided the first function's codomain matches the second function's domain:
g ◦f : A → C given by g ◦ f (x) = g(f (x)).
  - inverse function f^-1: applying the two functions to a value x in succession in either order gives back value x
    - graph of inverse functions -> symmetric about y = x line 
  - injective function: each x in the domain gives a unique output in the codomain after applying the function
  - surjective function: no z in B (codomain) is left alone -> every z in B has a corresponding x in A s.t. f(x) = z
  - bijective: injective and surjective

[relations between domain, codomain, range.](https://en.wikipedia.org/wiki/Codomain#/media/File:Codomain2.SVG)

4. Polynomials
- polynomial in degree n: a function in the form p(x) = anx^n + an-1x^n-1 + ... + a1x + a0, where an... are constants
- can be factored in as a product of linear and quadratic factors
- polynomial in degree n has at most n roots

5. Rational function
- function in the form of p(x)/q(x), where they are polynomials
- domain of it consists of all real numbers except the roots of q(x) -> division by zero error

6. Trigometric function
- sinx,cosx,tanx,cscx, secx,cotx
- periodic functions of period 2pi

7. Exponential and Logarithmic function
- f (x) = a^x, where a > 0
- logarithmic is **inverse function** of exponential: logax (to base a)
- e is Euler number, inverse of exponential function e^x is the natural logarithm lnx
- **e^lnx = x for x > 0 and lne ^ x = x for all x**
- domain of e^x is R and the range is the set R+ of all positive real numbers.

8. Domain and range in depth
- maximal domain: domain not specified -> take domain to be as large as possible (e.g. R \ {1})
- for some cases -> basic algebra can find the range of the function (let y = f(x) -> y = _expr_)

9. Limits
- let f be a real-valued function (R) defined on some interval I and c is a point in I
  - left limit: lim (x -> c-) f(x) is the value that f(x) approaches when x approaches c from the left.
  - right limit: lim(x -> c+) f(x) is the value that f(x) approached c from the right
  - let c be the interior point in I, if left limit = right limit = L (and L in R), lim(x -> c) f(x) exists and has value L
  - [find limit from graph](https://www.youtube.com/watch?v=7Q2HwTHcxA0)

10. Continuity and discontinuity
- discontinuity: hole, jump, infinite ~
- let f be a real-valued function (R) defined on some interval I and c is a point in I
  - if c is an interior point in I
  - f is continuous at c if (i) lim (x->c) f(x) exists and (ii) lim (x -> c)f(x) = f(c)
- c is the left end-point
  - f is continuous at x = c if (i) lim(x-> c+) f(x) exits and (ii) lim(x->c+) f(x) = f(c)
- c is the right end-point
  - f is continuous at x = c if (i) lim(x -> c-) f(x) exists and (ii) lim(x-> c-) f(x) = f(c)
- continuity on an interval: f is continuous on an interval if f is continuous at x = c for all points c in I.
- no sudden jump if continuous
- [con and discon](https://www.youtube.com/watch?v=joewRl1CTL8)
- [3 steps con test](https://www.youtube.com/watch?v=WT7oxiiFYt8)

11. Evaluation of limits 
- Laws of limits: (let L, M, c, and k be real numbers and lim(x->c)f(x) = L lim(x->c)g(x)=M
  1. Sum rule: + becomes L + M 
  2. Difference rule: - becomes L - M 
  3. Constant multiple rule: lim (x->c)(k*f(x)) = k*L
  4. Product rule: * becomes L * M 
  5. Quotient rule: divide becomes L/M, M not equal 0 
  6. Power rule: f(x) raised to the power of n becomes L^n, n is positive integer 
  7. Root rule: f(x) root by n, becomes L root by n, n is a positive integer (or L^1/n)
- composite function limit: If g is continuous at the point b and lim(x→c)f (x) = b, then lim(x→c)g(f (x)) = g(b) = g(lim(x→c)f (x))).
- all these can be two-sided or one-sided limit, and the limit should exist
- Continuity of function implied by laws of limits:
  - If f and g are continuous at x = c, then for any constant k and any positive constant n, each of the following functions is continuous at x = c.
    - (i) f ± g, (ii) f^n, (iii) k* f , (iv) f g, (v) f /g provided g(c) not 0
  - If g is continuous at x = c and f is continuous at x = g(c), then the composite function f ◦ g is continuous at x = c.
- these functions are continuous on any interval contained on their maximal domain (PELT) :
  1. Polynomials
  2. Exponential functions
  3. Logarithmic functions
  4. Trigonometric functions
  5. Combination of any of the above on the domain it is defined
- Note: Since lim(x→c)f (x) = f (c) when f is continuous at x = c, finding the limit at x = c of any of the above functions is a matter of evaluating f at x = c.

12. Limits at infinity
- let f be dfined on R
   - lim(x-> ∞)f(x) is the value f(x) as x approaches positive infinity .
   - lim(x-> -∞)f(x) is the value f(x) as x tends to negative infinity.
- graphical representations if there is finite limit as x appraoches infinity -> asymptotes (horizontal, oblique...)
- asymptotes
  - A line y = b is a horizontal asymptote of the graph of a function y = ƒ(x) if either lim(x->∞)f(x) = b or lim(x->-∞)f(x) = b
  - A line x = a is a vertical asymptote of the graph of a function y = ƒ(x) if either lim(x->a+)f(x) = +-∞ or lim(x->a-)f(x) = +-∞
  - If the degree of the numerator of a rational function is 1 greater than the degree of the denominator, the graph has an oblique or slant line asymptote.
- dominant terms: a term in the expr dominates when x approaches const c/+∞/-∞ when it is large 

13. Infinite limits, replacement rule
- indeterminate forms:
  - a limit of the form lim(x->c)(f(x)/g(x)) where f(x) -> 0 and g(x) -> 0 as x -> c is called an indeterminate form of the type 0/0
  - a limit of the form lim(x->c)(f(x)/g(x)) where f(x) -> ∞ and g(x) -> ∞ as x -> c is called an indeterminate form of the type ∞/∞
- replacement rule
  - Let I be an open interval containing the point x = c.Suppose f (x) = g(x) for all x ∈ I,except possibly at x = c, then lim(x->c)f(x) = lim(x->c)g(x)
  - this is useful when you encounter indeterminate forms and there exists a function g(x) to f(x) that are identical except at x =c, where f(x) is not defined but g(x) is well defined -> use the limit of g(x) at point c to find lim(x->c)f(x)
- theorem 12 in Thomos Calculas: all limits laws in Theorem 1 are true when we replace lim(x->c) by lim(x->∞) or lim(x->-∞); That is, the variable x may approach a finite number c or +-∞
- Note: lim(x->+-∞)(Ax^c + .../Bx^d + ...) -> which are the leading terms,
  - 0 if c < d
  - A/B if c = d
  - +-∞ if c > d
- useful results of tanx and sinx and tan(g(x)) and sin(g(x))

14. Squeeze (Sandwich) Theorem
> Suppose g(x) ≤ f (x) ≤ h(x) for all x in some open interval containing a point c, except possibly at x = c. If lim(x->c)g(x) = lim(x->c)h(x) = L, then lim(x->c)f(x) = L

15. Intermediate Value Theorem (IVT)
> If a real-valued function f is continuous on [a,b] and k is a number between f (a) and f (b),then f (c) = k for some c ∈ [a,b].

## Deriavatives

1. slope of a curve  y = ƒ(x) at the point P(x0, ƒ(x0)) AND deriavative of a function f at point x0
- is the number lim(h->0)( (f(x0 + h) - f(x0)) / h)
- provided the limit exists
- the tangent line to the curve at P is the line through P with this slope.

2. Deriavative of a function at point x
> The derivative of the function ƒ(x) with respect to the variable x is the function ƒ′ whose value at x is lim(h->0)( (f(x + h) - f(x)) / h) provided the limit exists
- If ƒ′ exists at a particular x, we say that ƒ is differentiable (has a derivative) at x. If ƒ′ exists at every point in the domain of ƒ, we call ƒ differentiable
- alternative definition of derivative with z->x (let z = x + h)
- The process of calculating a derivative is called differentiation
- dy/dx means the deriative of y w.r.t. to x, not a ratio 

3. Differentiable on an Interval; One-Sided Derivatives
> A function y = ƒ(x) is differentiable on an open interval (finite or infinite) if it has a derivative at each point of the interval.  It is differentiable on a closed interval [a, b4] if it is differentiable on the interior (a, b) and if the limits right-hand derivative at a and left-hand derivative at a

4. Differentiability Implies Continuity
> If ƒ has a derivative at x = c, then ƒ is continuous at x = c.

5. Rules of differentiation
- Derivative of a Power: If n is a positive integer, then d/dx(x^n) = nx^(n-1 for all x where the powers xn and xn-1 are defined
- constant multiples: If u is a differentiable function of x, and c is a constant, then d/dx(cu) = c(du/dx) 
- sum/difference rule: If u and y are differentiable functions of x, then their sum/difference u + y/ u - y is differentiable at every point where u and y are both differentiable. At such points, d/dx(u +- v) = du/dx +- dv/dx
- constant function: if f(x) has constant value ƒ(x) = c, then df/dx = d/dx(c) = 0
- product rule: If u and v are differentiable at x, then so is their product uv, and d/dx(uv) = v*du/dx + u*dv/dx
- quotient rule: If u and v are differentiable at x and if v(x) ≠ 0, then the quotient u/v is differentiable at x, and d/dx(u/v) = ( v*du/dx - u*dv/dx )/v^2

6. Second deriavative or higher order deriavative
- deriavatives of deriavatives 

7. Deriavative as a rate of change
- The instantaneous rate of change of ƒ with respect to x at x0 is the derivative ƒ′(x0) = lim(h->0) (f(x0+h) - f(x0))/h

8. Velocity
> Velocity (instantaneous velocity) is the derivative of position with respect to time. If a body’s position at time t is s = ƒ(t), then the body’s velocity at time t is v(t) = ds/dt = lim(change in t -> 0) (f(t+ change in t) - f(t)) / change in t

9. Speed
- speed measure the rate of progress rather than direction
> Speed is the absolute value of velocity. Speed = |v(t)| = |ds/dt|

10. Acceleration
> Acceleration is the derivative of velocity with respect to time. If a body’s position at time t is s = ƒ(t), then the body’s acceleration at time t is
> a(t) = dv/dt = d^2s/dt^2
- Jerk is the derivative of acceleration with respect to time: j(t) = da/dt = d^3s/dt^3

11. Deriavative of trigometric functions
![Trigo identities](https://www.onlinemathlearning.com/image-files/trigonometric-identities.png)
- [angle sum formula](https://mathworld.wolfram.com/TrigonometricAdditionFormulas.html)
- d/dx(sin x) = cos x
- d/dx(cos x) = -sin x
- d/dx(tan x) = sec^2x
- d/dx(cot x) = -cosec^2 x
- d/dx(sec x) = sec x tan x
- d/dx(cosec x) = -cosec x cot x

12. The chain rule
- Thoerem 2
> If ƒ(u) is differentiable at the point u = g(x) and g(x) is differentiable at x, then the composite function (ƒ ∘ g)(x) = ƒ(g(x)) is differentiable at x, and (ƒ ∘ g)′(x) = ƒ′(g(x)) * g′(x).
- In Leibniz’s notation, if y = ƒ(u) and u = g(x), then dy/dx = dy/du*du/dx  (where dy/du is evaluated at u = g(x) )
- Inside-Outside rule
  - e.g. f(x) = sin(x^2 + x); f'(x) = cos (x^2 + x) * (2x + 1)
- chain rule with powers of a function
  - d/dx (u^n) = nu^(n-1) * du/dx

13. Implicit differentiation
> y^n cases
- How:
  1. Differentiate both sides of the equation with respect to x, treating y as a differentiable function of x
  2. Collect the terms with dy>dx on one side of the equation and solve for dy>dx.
- differentiating deriavative of higher orders can think of substituting the result of dy/dx to the equation to make the **final result** consists of x and y only
- tangent (deriavative), normal (perpendicular, orthogonal)

14. Deriatives of Inverse Functions
- Bijectiveness
  -  a bijective function (or one-one function) f has an inverse f−1 defined on the range of f
  -   increasing or decreasing functions are bijective. (monotone functions) -> conclusive of injectivity
  -   subjectivity is guranteed by the restriction of range (cover all y in the codomain) 
  -   f is increasing on I if x2 > x1 => f(x2) > f(x1) for all x1, x2 in I
  -   f is decreasing on I if x2 > x1 => f(x2) < f(x1) for all x1, x2 in I
  -   examples
    - e^x is increaseing on R (real numbers)
    - in x is increasing on R+ (or for x > 0)
    - if f and g are increasing on I then f+ g is increasing on I
    - if f is increasing or decreasing ten f has an inverse function f^-1
- Theorem 2.2
  - Let f be bijective and differentiable on an open interval I. Then (f^-1)'(a) = 1/(f'(f^-1(a)))
  - or = 1/f'(b)
  - or dx/dy = 1/(dy/dx) ->  let y = y(x) be a function, suppose y has an inverse function x = x(y) then..
 
15. Higher order deriavative
- second deriavative of f, f'' or f^(2) superscript; provided that f' is differentiable: f''(x) = d/dx(('(x))
- In general, we can define the nth order derivative of f for any positive integer n provided the derivative exists.
- aka y'', D^2f(x)

16. Parametric equation
- a curve is defined by the parametric equation: x = f (t) and y = g(t), (t is the parameter)
- differentiable at a point where t = t0 if both f and g are differentiable at t = t0
- f'(t0) and g'(t0) not 0
- dy/dt = dy/dx * dx/dt => dy/dx = dy/dt / dx/dt = g'(t) / f'(t)  **(by chain rule)**
- second deriavative -> replace y with dy/dx => d2y/dx2 = d/dt(dy/dx) / dx/dt    =   d/dt(g'(t)/f'(t)) / f'(t)    =   (g''(t)f'(t) - g'(t)f''(t)) / f'(t)^3
- examples of parametric curves
  - ellipses: (x - x0)^2/a^2 + (y - y0)^2/b^2 = 1 
    - x = acost + x0; y = bsint + y0
  - hyperbolas: (difference: x less y)
    - x = asect + x0; y = btant + y0 OR x = atant + x0; y = bsect + y0
  - circles: (x-x0)^2 + (y - y0)^2 = r^2 (cartesian equation)
    - x = rcost + x0 and y = rsint + y0 (parametric equation) => search "How to convert from cartesian equation to parametric equation"
    - where r > 0, x0 and y0 are fixed constants and 0 <= t <= 2PI

17. Special forms
- deriavative of y = f(x)^g(x)
  - can be found by first finding the deriavative of ln y and then solving for dy/dx
- change of base formula
  - loga x = lnx/lna, a > 0 and a != 1
 
## Application of deriavatives
> solve optimisation problem easier 

1. tangents and normal
- The tangent at the point (x0, f (x0)) on the graph of a differentiable function f has equation: y − f (x0) = m(x − x0)
- to check if parallel to axes
  - x axes: let dy/dx be 0
  - y axes: look at the deriavative of the normal (since normal is orthogonal to the tangent) (minus reciprocal of tangent) 
- normal: gradient is m = f'(x0) (minus of the reciprocal)
- parametric equations: x = x(t) and y = y(t)
  - the equation of the tangent at the point where t = t0 is: y − y(t0) = m(x − x(t0))
  - the equation of the normal at the point where t = t0 is: y − y(t0) = −1/m(x − x(t0))
  - where m = dy/dx  = dy/dt / dx/dt at t = t0 

2. Absoulte maximum and min/ extremes/ global maxima or minima 
> Let ƒ be a function with domain D. Then ƒ has an absolute maximum value on D at a point c if f(x) <= f(c) for all x in D. and an absolute minimum value on D at c if f(x) >= f(c) for all x in D

3. Extreme value theorem (Theorem 3.4)
- If ƒ is continuous on a closed interval [a, b] , then ƒ attains both an absolute maximum value M and an absolute minimum value m in [a, b] . That is, there are numbers x1 and x2 in [a, b] with ƒ(x1) = m, ƒ(x2) = M, and m <= f(x) <= M for every other x in [a, b]
- only conclude existence but do not help us find the extreme value 

4. Local maximum and minimum (Definition 3.5) 
> A function ƒ has a local maximum value at a point c within its domain D if ƒ(x) <= ƒ(c) for all x∊D lying in some open interval containing c.
> A function ƒ has a local minimum value at a point c within its domain D if f(x) >= f(c) for all x∊D lying in some open interval containing c.

5. Absolute extrema/global extrema (Definition 3.4)
> A function f has an
> - absolute maximum at x = c if f(x) <= f(c) for all x in the **domain** of f
> - absolute minimum at x = c if f(x) >= f(c) for all x in the **domain** of f 

7. The First Derivative Theorem for Local Extreme Values (THEOREM 2)
- If ƒ has a local maximum or minimum value at an interior point c of its domain, and if ƒ′ is defined at c, then ƒ′(c) = 0.
- Theorem 3.5. If f is differentiable on an open interval containing x = c and f has a local extremum at x = c, then f;(c) = 0.

7. interior point
> An interior point of the domain of a function ƒ where ƒ′ is zero or undefined is a critical point of ƒ.
- to find absolute extrema of a continuous func f on a closed interval I
  - Find all critical points of ƒ on the interval.
  - Evaluate ƒ at all critical points and endpoints.
  - Take the largest and smallest of these values.
- **(Critical Point Formal definition in LN)** A number c in the domain of a function f is a critical point of f if the following 2 conditions hold
  1. it is not an end-point
  2. either f'(c) = 0 or f'(c) does not exist.
- Theorem 3.6. If f has a local minimum/maximum at x = c, then c is a critical point of f. (converse may not be true)

8. Rolle's Theorem (Theorem 3)
> Suppose that y = ƒ(x) is continuous over the closed interval [a, b] and differentiable at every point of its interior (a, b). If ƒ(a) = ƒ(b), then there is at least one number c in (a, b) at which ƒ′(c) = 0.
- The hypotheses of Theorem 3 are essential. If they fail at even one point, the graph may not have a horizontal tangent.
- may be combined with the Intermediate Value Theorem to show when there is only one real solution of an equation ƒ(x) = 0

9. Mean Value Theorem (Theorem 4)
> Suppose y = ƒ(x) is continuous over a closed interval [a, b] and differentiable on the interval’s interior (a, b). Then there is at least one point c in (a, b) at which (ƒ(b) - ƒ(a)) / (b - a) = ƒ′(c)
- physical interpretation: Mean Value Theorem says that the instantaneous change at some interior point is equal to the average change over the entire interval.
- colloary (mathematical consequences)
  - corollary 1: If ƒ′(x) = 0 at each point x of an open interval (a, b), then ƒ(x) = C for all x∊(a, b), where C is a constant.
  - corollary 2: If ƒ′(x) = g′(x) at each point x in an open interval (a, b), then there exists a constant C such that ƒ(x) = g(x) + C for all x∊(a, b). That is, ƒ - g is a constant function on (a, b).

10. Monotonic functions and first deriavative test 
- to show that functions with postive deriavative is increasing function and that with negative deriavative is decreasing function: a function that is increasing or decreasing on an interval is said to be monotomic on an interval
- increasing and dereasing functions (definition in lecture notes) 
  - collolary 3 (Theorem 3.1): Suppose that ƒ is continuous on [a, b] and differentiable on (a, b)
    - If ƒ′(x) > 0 at each point x∊(a, b), then ƒ is increasing on [a, b] (an interval I) 
    - If ƒ′(x) < 0 at each point x∊(a, b), then ƒ is decreasing on [a, b]
  - first deriavative test for local extrema (218)
  - second deriavative test for local extrema (225) 
 
11. Concavity
> a graph of a differentiable function y = ƒ(x) is
> - concave up  on an open interval I if ƒ′ is increasing on I; (convex) 
> - concave down on an open interval I if ƒ′ is decreasing on I.
> - The graph of f is concave upward (downward) on (a,b) if it is concave upward (downward) at every point in (a,b).
- second deriavative test for concavity
  - Let y = ƒ(x) be twice-differentiable on an interval I. (Theorem 3.2) 
    - If ƒ″ > 0 on I, the graph of ƒ over I is concave up
    - If ƒ″ < 0 on I, the graph of ƒ over I is concave down

12. Points of inflection (Definition 3.3)
- A point (c, ƒ(c)) where the graph of a function has a tangent line and where the concavity changes is a point of inflection
  - At a point of inflection (c, ƒ(c)), either ƒ″(c) = 0 or ƒ″(c) fails to exist.
  - ^ (Theorem 3.3) . Let f be differentiable on (a,b). Let c ∈ (a,b). If (c, f (c)) is a point of inflection of the graph of f and f''(c) exists, then f''(c) = 0

13. Related rates
- let y = f(x) and let x and y be functions of a third var t that represents, e.g, time. By the chain rule, dy/dt = dy/dx*dx/dt
