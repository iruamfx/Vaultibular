# What is it?
A polynomial is an algebraic expression formed by numbers (coefficients) and letters (literals). It's name (monomial, binomial, trinomial, etc..) is given based on the number of monomials present in the expression. Monomials follow the form: $$ R \cdot x \cdot x_2 \cdot x_n \cdot y_n$$
Where $R$ is a real number, acting as the coefficient of the monomial, and $x_n$ acts as the literal part.

# Terms of a polynomial
The polynomial's representing expression is composed of terms, which are joined, **exclusively**, by the operations of sum and subtraction. Observe the examples: 
###### Monomial: $$2xyz$$
###### Binomial: $$4x^2z + 5cx$$
###### Trinomial: $$cy + xy - cd$$
##### Zero/Null Polynomial:
The zero, or null, polynomial, has all of it's coefficients be zero, thus, it also equals zero. It can appears in questions such as: *Find the values of $a, b, c$ and $d$ so that $(a – b – c + d)x³ + (2b – c)x² + (c – d)x + 4d – 8 ≡ 0$;* for which we can create the following system of equations:
$a-b-c+d = 0$
$2b-c = 0$
$c-d = 0$
$4d-8 = 0$ 

# Operations with polynomials
#### Sum: 
The sum of polynomials is realized by summing the coefficients of similar terms (same literal part):

$(- 7x3 + 5 x2y - xy + 4y) + (- 2x2y + 8xy - 7y) \Rightarrow$
$- 7x3 + 5x2y - 2x2y - xy + 8xy + 4y - 7y \Rightarrow$
$- 7x3 + 3x2y + 7xy - 3y$
#### Subtraction:
The minus sign in front of a polynomial inverts the signal of all the terms in the polynomial, which can then be, as previously explained, summed up.

$(4x2 - 5xk + 6k) - (3xk - 8k) \Rightarrow$
$4x2 - 5xk + 6k - 3xk + 8k \Rightarrow$
$4x2 - 8xk + 14k$
#### Multiplication:
Whilst multiplying polynomials, we must multiplicate each term in the first polynomial by all of the terms in the second one. *P.s: exponents are repeated and summed*

$(3x2 - 5x + 8) . (-2x + 1) \Rightarrow$
$-6x3 + 3x2 + 10x2 - 5x - 16x + 8 \Rightarrow$
$-6x3 + 13x2 - 21x +8$
#### Division:
W.I.P https://www.mathsisfun.com/algebra/polynomials-division-long.html

# Factoring
The factoring of a polynomial consists in representing an expression composed by $n$ terms (monomials) as the product of a multiplication of factors *- commonly, polynomials -*, therefore, simplifying it. 
This process can be done in a multitude of ways, depending on the expression in question. Some of the methods that can be utilized include:

## Completing the square:
Completing the square is a technique utilized to transform any polynomial in a [[#Factoring of a Perfect Square Trinomial|PST]] of the form $$(ax+b)^2$$
which expands to $$ax^2+2axb+b^2$$
It is done by dividing the coefficient of $x$, or generally the middle-term, by $2$ and obtaining it's square, then summing and subtracting it in the expression, which results in a PST that can be contracted in the form first shown. 

#### Examples:
##### 1. *Complete the square of $x^2+14x$:*
###### Step 1: Obtain the square of the quotient of $\frac{C_x}{2}$:
$(\frac{14}{2})^2 = 7^2 = 49$
###### Step 2: Sum and subtract the result in the expression, obtaining a trinomial:
$(x^2 + 14x + 49) - 49$
###### Step 3: [[#Factoring of a Perfect Square Trinomial|Factor the PST]]:
$(x+7)^2 - 49$

##### 2. *Obtain the canonical form of $x^2 +4x + 3$:

###### Step 1: Obtain the square of the quotient of $\frac{C_x}{2}$:
$(\frac{4}{2})^2$ = 4
###### Step 2: Sum and subtract the result of the operation:
$(x^2+4x+4)-4+3$
###### Step 3: [[#Factoring of a Perfect Square Trinomial|Factor the obtained PST]]:
$(x+2)^2-1$

## Factoring of a Perfect Square Trinomial:
*Sources: https://www.purplemath.com/modules/specfact3.html //*
Perfect square trinomials are quadratics which are the results of a squared binomial. *(Remember that "trinomial" means "three-term polynomial")*
These trinomials will always come in the form:
$$(ax+b)^2 = ax^2+2axb+b^2$$$$(ax-b)^2 = ax^2 - 2axb +b^2$$
#### It is important to note that not every quadratic is a **perfect square** trinomial. 
The process for factoring these cases will be addressed further down. For now, it is possible to know that a trinomial is indeed a perfect square by following the steps below:
* If the first and third terms are squares, find what they are squares of
* Multiply the obtained roots
* Multiply the product by 2
* If this product, ignoring the sign, equals the second term of the trinomial, it is a **perfect square trinomial**
#### Example: 
##### *Is the trinomial $16x^2 -48x + 36$ a perfect square trinomial? If yes, factor it:*
###### Verify if the trinomial is a PST:
###### Step 1: Find the roots of $ax$ and $c$
	$16x^2 \Rightarrow \sqrt{16x^2} \Rightarrow 4x$
	$36 \Rightarrow \sqrt{36} \Rightarrow 6$
###### Step 2: Multiply the obtained roots
	$4x \cdot 6 = 24x$
###### Step 3: Multiply the product by 2
	$24x \cdot 2 = 48x$
###### Step 4: If this product, ignoring the sign, equals the second term, it is a PST
	$|48x| = |-48x|$
###### Factor the trinomial:
###### Step 0 (opt): Define the canonical form of a perfect square trinomial:
	$(ax\pm b)^2 = (ax)^2 \pm 2axb + b^2 = 16x^2 -48x + 36$
###### Step 1: Find $b$:
	$b = \sqrt{b^2} = \sqrt{36} = 6$
###### Step 2: Find $ax$:
	$ax = \sqrt{(ax)^2} = \sqrt{16x^2} = 4x$
###### Step 2.5 (opt): Verify if $-2axb = -48x$:
	$-2 \cdot 4x \cdot 6 \Rightarrow -8x \cdot 6 \Rightarrow -48x$
###### Step 3: Write the PST in the canonical form:
	$(ax-b)^2 = (4x - 6)^2 ⟺ 16x^2 -48x + 36$

## Factoring of a Quadratic Trinomial
A quadratic trinomial, equation, or simply quadratic, is an equation that follows the form:$$ax^2 \pm bx \pm c$$
The processes for factoring a quadratic can vary depending on desired final form and leading coefficient. These include:

### Factored Form: Factorization by the roots
It is possible to write a quadratic in what is known as it's **factored** form. There are two ways to represent the expanded quadratic equation whilst in a contraction based on it's roots. They can be written as:
###### 1. Simple Factoring: $$ax^2 \pm bx \pm c ⟺ a(x-x_1)(x-x_2)$$
This form can be used when the leading coefficient $a$ can be easily factorized by putting it in evidence, and describes the expanded equation by its unaltered roots, obtained using the [[Classical Sum and Product]] method.

This form can be obtained by putting $a$ in evidence and factoring the obtained simplified quadratic:$$ax^2 \pm bx \pm c \Rightarrow a(\frac{ax^2 \pm bx \pm c}{a}) \Rightarrow a(x-x_1)(x-x_2)$$
Watch as it is realized in a practical example [[#1. Simple Factoring *Factor $x 2 + 7x + 6$*|here]]
###### 2. Hard/Adjusted Factoring
$$ax^2 \pm bx \pm c ⟺ (ax-p)(x-q)$$
This form can be used when the leading coefficient $a$ shows itself as too complicated to be factorized using, for example, GCF as in the [[#1. Simple Factoring $$ax 2 pm bx pm c ⟺ a(x-x_1)(x-x_2)$$ |Simple Factoring]] method. 

Therefore, we can instead calculate the **adjusted roots** $p$ and $q$, which represent the roots $x_1$ and $x_2$ whilst constrained by $a$, using the Hard or [[#2. Hard Factoring Factor $2x 2 + x - 6$* |Hard Factoring]] method.
#### **OR...**

Much more advisable it is to use the [[#3. Box method *Factor $4x 2 -19x + 12$|Box]] method, which, like the [[#2. Hard Factoring Factor $2x 2 + x - 6$* |Hard Factoring]] method, also involves in finding **adjusted roots** $p$ and $q$, whoever, diverts from it in the factoring step, since instead of linearly replacing terms we find $2$ sets of $2$ common factors that when multiplied have the product be the expanded quadratic. Watch as it is realized in a practical example [[#|here]]
P.s: The only cases the box method does not work, mean the polynomial is a prime, indivisible, polynomial

#### Examples:
#### 1. Simple Factoring | *Factor $x^2 + 7x + 6$*
###### Step 1: Find the roots:
$x_1 + x_2 = \frac{-b}{a} = -7$
$x_1 \cdot x_2 = \frac{c}{a} = 6$
$Solution$: $\{x_1 = -6;x_2=-1\}$ 
###### Step 2: Substitute for $a$, $x_1$ and $x_2$ in the factored form:
$a(x-x_1)(x-x_2) \Rightarrow 1(x-(-6))(x-(-1)) \Rightarrow (x+6)(x+1)$
$(x+6)(x+1) ⟺ x^2 + 7x + 6$
#### 2. Hard Factoring | Factor $2x^2 + x - 6$*
###### Step 0 (opt): Define the form of a adjusted factored quadratic:
$(ax-p)(x-q) \Rightarrow ax^2 + bx + c \Rightarrow 2x^2 + 1x -6$
Where:
$b = (p-aq) \Rightarrow 1 = (p - 1 \cdot c)$
$c = pq \Rightarrow -6 = pq$
###### Step 1: Find the factors $p$ and $q$ of $a \cdot c$ that add up to $b$:
$a \cdot c = 2 \cdot -6 = -12$
$b = 1$
$p \cdot q = -12$
$p + q = 1$
$\{p = 4; q = -3\}$
--------------------
###### Step 2: Replace the middle term for $\pm px \pm qx$:
$2x^2 + 1x -6 \Rightarrow 2x^2 +4x -3x -6$
###### Step 3: Factor the resulting polynomial in pairs:
$2x^2 + 4x = 2x(x+2)$
$-3x-6 = -3(x+2)$
###### Step 4: Put the common factor polynomial in evidence:
$(x+2)(2x-3)$

#### 3. Box method | *Factor $4x^2 -19x + 12$:

###### Step 1: Find the factors $p$ and $q$ of $a \cdot c$ that add up to $b$:
$a \cdot c = 4 \cdot 12 = 48$
$b = -19$
$p \cdot q = 48$
$p + q = -19$
$\{p = -16; q=-3\}$
###### Step 2: Draw a box and fill it with the following values:

| 1st Term | $qx$         | $\Rightarrow$ | $+4x^2$ | $-3x$ |
| -------- | ------------ | ------------- | ------- | ----- |
| $px$     | **3rd Term** | $\Rightarrow$ | $-16x$  | $+12$ |
###### Step 3: Factor every row and column, one by one, and write the factor by the side:

Top row:

| N/A |         |       |
| --- | ------- | ----- |
| x   | $+4x^2$ | $-3x$ |
|     | $-16x$  | $+12$ |

Bottom row:

| N/A |         |       |
| --- | ------- | ----- |
| x   | $+4x^2$ | $-3x$ |
| -4  | $-16x$  | $+12$ |
Left column:

| N/A | -4x     |       |
| --- | ------- | ----- |
| x   | $+4x^2$ | $-3x$ |
| -4  | $-16x$  | $+12$ |
Right column:

| N/A | 4x      | -3    |
| --- | ------- | ----- |
| x   | $+4x^2$ | $-3x$ |
| -4  | $-16x$  | $+12$ |
###### Step 4: Multiply the pair of row and column factors, respectively.
$(4x-3)\cdot(x-4)$
### Canonical form: Factorization by the vertex
The canonical form of an equation, like the factored form, refers to a simplified form of a quadratic, whoever, unlike it, it's focus is on obtaining the equivalent perfect square of an equation is primarily used to describe the graph of the expression since it is built around the vertices of the quadratic. It follows the form: $$ax2+bx+c ⟺ a(x+h)^2 + k$$
Where $\{h, k\}$ is the vertex of the equation; the form can be obtained by [[completing the square]] of the equation. 
#### Example:
##### *Obtain the canonical form of $x^2 +4x + 3$:

###### Step 1: We will [[#|complete the square]] of this equation. For this, obtain the square of the quotient of $\frac{C_x}{2}$:
$(\frac{4}{2})^2$ = 4
###### Step 2: Sum and subtract the result of the operation:
$(x^2+4x+4)-4+3$
###### Step 3: [[#Factoring of a Perfect Square Trinomial|Factor the obtained PST]]:
$(x+2)^2-1$


