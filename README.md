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
  - injective function: each x in the domain gives a unique output in the codomain after applying the function
  - surjective function: no z in B (codomain) is left alone -> every z in B has a corresponding x in A s.t. f(x) = z
  - bijective: injective and surjective

![relationship between domain, codomain, range.](https://en.wikipedia.org/wiki/Codomain#/media/File:Codomain2.SVG)

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
