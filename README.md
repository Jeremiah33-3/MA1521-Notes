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
- theorem 12 in Thomos Calculas: all limits laws in Theorem 1 are true when we replace lim(x->c) by lim(x->∞) or lim(x->-∞); That is, the variable x may approach a finite number c or +-∞
- Note: lim(x->+-∞)(Ax^c + .../Bx^d + ...) -> which are the leading terms,
  - 0 if c < d
  - A/B if c = d
  - +-∞ if c > d 
