# Precalculus 12 Cheat Sheet

## Functions Basics

### Function Notation
- f(x) = output when input is x
- Domain: All possible x values
- Range: All possible y values
- Vertical line test: If line crosses graph more than once, NOT a function

### Transformations
**Parent function: f(x)**
- f(x) + k: Shift UP k units
- f(x) - k: Shift DOWN k units
- f(x + h): Shift LEFT h units
- f(x - h): Shift RIGHT h units
- -f(x): Reflect over x-axis
- f(-x): Reflect over y-axis
- a·f(x): Vertical stretch (a > 1) or compress (0 < a < 1)
- f(bx): Horizontal compress (b > 1) or stretch (0 < b < 1)

## Polynomial Functions

### Degree and Behavior
- Degree n = highest power
- Degree 0: Constant (y = 5)
- Degree 1: Linear (y = 2x + 3)
- Degree 2: Quadratic (y = x²)
- Degree 3: Cubic (y = x³)

### End Behavior
- Even degree, positive leading coefficient: Both ends up
- Even degree, negative leading coefficient: Both ends down
- Odd degree, positive leading coefficient: Left down, right up
- Odd degree, negative leading coefficient: Left up, right down

### Quadratic Functions
**Standard form:** ax² + bx + c
**Vertex form:** a(x - h)² + k (vertex at (h, k))
**Factored form:** a(x - r₁)(x - r₂) (roots at r₁, r₂)

**Vertex:** x = -b/(2a), then find y
**Axis of symmetry:** x = -b/(2a)
**Quadratic formula:** x = [-b ± √(b² - 4ac)] / (2a)
**Discriminant:** b² - 4ac
  - Positive: 2 real roots
  - Zero: 1 real root
  - Negative: No real roots (2 complex)

### Factoring
- GCF: Factor out common terms
- Difference of squares: a² - b² = (a + b)(a - b)
- Trinomial: x² + bx + c = (x + m)(x + n) where m·n = c, m + n = b
- Grouping: For 4 terms

## Rational Functions

### Form: f(x) = P(x)/Q(x)
**Vertical asymptote:** Set Q(x) = 0
**Horizontal asymptote:**
- Degree P < Degree Q: y = 0
- Degree P = Degree Q: y = (leading coefficient P)/(leading coefficient Q)
- Degree P > Degree Q: No horizontal asymptote (oblique instead)

**Holes:** Factor both P and Q, common factors create holes
**Domain:** All real numbers except where Q(x) = 0

## Exponential Functions

### Form: f(x) = a·bˣ
- b > 1: Growth
- 0 < b < 1: Decay
- Horizontal asymptote: y = 0 (usually)

### Exponential Growth/Decay
**Growth:** A = A₀(1 + r)ᵗ
**Decay:** A = A₀(1 - r)ᵗ
**Continuous:** A = A₀eᵏᵗ

### Properties of Exponents
- xᵃ · xᵇ = xᵃ⁺ᵇ
- xᵃ / xᵇ = xᵃ⁻ᵇ
- (xᵃ)ᵇ = xᵃᵇ
- (xy)ᵃ = xᵃyᵃ
- x⁰ = 1
- x⁻ᵃ = 1/xᵃ

## Logarithmic Functions

### Definition: logₐ(x) = y means aʸ = x
**Common log:** log(x) = log₁₀(x)
**Natural log:** ln(x) = logₑ(x), where e ≈ 2.718

### Log Properties
- log(xy) = log(x) + log(y)
- log(x/y) = log(x) - log(y)
- log(xⁿ) = n·log(x)
- logₐ(a) = 1
- logₐ(1) = 0
- logₐ(aˣ) = x
- a^(logₐ(x)) = x

### Change of Base Formula
logₐ(x) = log(x)/log(a) = ln(x)/ln(a)

## Trigonometry

### Unit Circle
**Angles:** 0°, 30°, 45°, 60°, 90°, 180°, 270°, 360°
**Radians:** 0, π/6, π/4, π/3, π/2, π, 3π/2, 2π

### Key Values (memorize!)
| Angle | sin | cos | tan |
|-------|-----|-----|-----|
| 0° | 0 | 1 | 0 |
| 30° | 1/2 | √3/2 | √3/3 |
| 45° | √2/2 | √2/2 | 1 |
| 60° | √3/2 | 1/2 | √3 |
| 90° | 1 | 0 | undefined |

### Trig Functions
- sin(θ) = opposite/hypotenuse = y/r
- cos(θ) = adjacent/hypotenuse = x/r
- tan(θ) = opposite/adjacent = y/x = sin/cos
- csc(θ) = 1/sin(θ)
- sec(θ) = 1/cos(θ)
- cot(θ) = 1/tan(θ)

### Trig Identities
**Pythagorean:**
- sin²(θ) + cos²(θ) = 1
- tan²(θ) + 1 = sec²(θ)
- 1 + cot²(θ) = csc²(θ)

**Double angle:**
- sin(2θ) = 2sin(θ)cos(θ)
- cos(2θ) = cos²(θ) - sin²(θ)

**Sum/Difference:**
- sin(A ± B) = sin(A)cos(B) ± cos(A)sin(B)
- cos(A ± B) = cos(A)cos(B) ∓ sin(A)sin(B)

### Graphs
- sin(x): Period 2π, amplitude 1, starts at 0
- cos(x): Period 2π, amplitude 1, starts at 1
- tan(x): Period π, vertical asymptotes at π/2 + nπ

**Transformations:** y = a·sin(b(x - c)) + d
- a = amplitude
- b affects period: Period = 2π/b
- c = horizontal shift (phase shift)
- d = vertical shift

## Sequences and Series

### Arithmetic Sequence
- Form: a, a+d, a+2d, a+3d, ...
- nth term: aₙ = a₁ + (n-1)d
- Sum of n terms: Sₙ = n/2(a₁ + aₙ) or Sₙ = n/2(2a₁ + (n-1)d)

### Geometric Sequence
- Form: a, ar, ar², ar³, ...
- nth term: aₙ = a₁·rⁿ⁻¹
- Sum of n terms: Sₙ = a₁(1 - rⁿ)/(1 - r), r ≠ 1
- Infinite sum (|r| < 1): S = a₁/(1 - r)

## Combinatorics

### Factorial: n! = n·(n-1)·(n-2)·...·2·1
- 0! = 1
- 5! = 5·4·3·2·1 = 120

### Permutations (order matters)
- ₙPᵣ = n!/(n-r)!
- Example: 5P3 = 5!/(5-3)! = 5!/2! = 60

### Combinations (order doesn't matter)
- ₙCᵣ = n!/[r!(n-r)!]
- Example: 5C3 = 5!/(3!2!) = 10

## Study Tips
- Practice transformations with graphing
- Memorize unit circle values
- Do lots of word problems for exponential/log
- Factor everything you can
- Check domain restrictions (especially division by zero, square roots of negatives)
- Use graphing calculator to check work
- Trig: Draw the triangle or unit circle every time
