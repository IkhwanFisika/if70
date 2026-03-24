# PM3 Further Integration

## Summary of Further Integration
Here is a summary of the important concepts and integral properties from the two provided files (Hodder PM3 Integral 1.pdf and Hodder PM3 Integral 2.pdf), organized by topic.
### 1. Integrals Involving Exponential Functions
**Standard Result**:
$$
\int e^{ax+b} \, dx = \frac{1}{a} e^{ax+b} + C, \quad a \neq 0
$$
**Derivation**: Reverse of differentiation: $\frac{d}{dx}(e^{ax+b}) = a e^{ax+b}$.
### 2. Integrals Involving the Natural Logarithm
**Standard Result**:
$$
\int \frac{1}{x} \, dx = \ln|x| + C, \quad x \neq 0
$$
**Linear Composite**:
$$
\int \frac{1}{ax+b} \, dx = \frac{1}{a} \ln|ax+b| + C, \quad a \neq 0
$$
**General Form**:
$$
\int \frac{f'(x)}{f(x)} \, dx = \ln|f(x)| + C
$$
**Domain Consideration**: The integral $\int \frac{1}{x} dx$ is valid only when the limits of integration have the same sign (both positive or both negative), because the function is undefined at $x=0$.
### 3. Integrals Involving Trigonometric Functions
**Standard Results**:
$$
\int \cos(ax+b) \, dx = \frac{1}{a} \sin(ax+b) + C
$$
$$
\int \sin(ax+b) \, dx = -\frac{1}{a} \cos(ax+b) + C
$$
$$
\int \sec^2(ax+b) \, dx = \frac{1}{a} \tan(ax+b) + C
$$
**Using Trigonometric Identities**:
- $\sin^2 x = \frac{1}{2}(1 - \cos 2x)$
- $\cos^2 x = \frac{1}{2}(1 + \cos 2x)$
- $\cos^3 x = \cos x - \cos x \sin^2 x$ (useful with substitution $u = \sin x$)
- Even powers of sine or cosine are reduced using double-angle formulas.
**Integrals of $\tan x$ and $\cot x$**:
$$
\int \tan x \, dx = \int \frac{\sin x}{\cos x} \, dx = -\ln|\cos x| + C
$$
$$
\int \cot x \, dx = \int \frac{\cos x}{\sin x} \, dx = \ln|\sin x| + C
$$
### 4. Integration by Substitution
**Principle**: If $u = g(x)$ and $du = g'(x) dx$, then:
$$
\int f(g(x)) \, g'(x) \, dx = \int f(u) \, du
$$
For definite integrals, change the limits:
$$
\int_{x=a}^{b} f(g(x)) \, g'(x) \, dx = \int_{u=g(a)}^{g(b)} f(u) \, du
$$
**Common Substitutions**:
- $u =$ expression inside a bracket or under a root
- $u =$ denominator when numerator is its derivative
- For $\sqrt{x}$, try $u = \sqrt{x}$ or $x = u^2$
### 5. Integration by Parts
**Formula**:
$$
\int u \frac{dv}{dx} \, dx = uv - \int v \frac{du}{dx} \, dx
$$
For definite integrals:
$$
\int_a^b u \frac{dv}{dx} \, dx = \left[ uv \right]_a^b - \int_a^b v \frac{du}{dx} \, dx
$$
**Choice of $u$**: Typically choose $u$ as the function that simplifies when differentiated (e.g., polynomial, $\ln x$, inverse trig).
**Applications**:
- $\int x^n e^{ax} \, dx$
- $\int x^n \sin(ax) \, dx$
- $\int x^n \cos(ax) \, dx$
- $\int \ln x \, dx = x \ln x - x + C$
- $\int x^n \ln x \, dx$
### 6. Integration Using Partial Fractions
**When to use**: When integrating rational functions where the denominator factorizes.
**Technique**: Decompose the fraction into simpler fractions, then integrate term by term.
**Types**:
- Distinct linear factors: $\frac{A}{ax+b} + \frac{B}{cx+d}$
- Repeated linear factors: $\frac{A}{ax+b} + \frac{B}{(ax+b)^2} + \cdots$
- Quadratic factors (irreducible): $\frac{Ax+B}{x^2+k^2}$ leads to $\frac{1}{k}\tan^{-1}\left(\frac{x}{k}\right)$ after integration
**Standard Result for Quadratic Denominator**:
$$
\int \frac{1}{x^2 + k^2} \, dx = \frac{1}{k} \tan^{-1}\left(\frac{x}{k}\right) + C
$$
### 7. Integrals Involving Inverse Trigonometric Functions
**Differentiation Results** (used to derive integrals):
$$
\frac{d}{dx} \left( \tan^{-1} x \right) = \frac{1}{1+x^2}
$$
$$
\frac{d}{dx} \left( \sin^{-1} x \right) = \frac{1}{\sqrt{1-x^2}}, \quad |x|<1
$$
$$
\frac{d}{dx} \left( \cos^{-1} x \right) = -\frac{1}{\sqrt{1-x^2}}
$$
**Linear Composite**:
$$
\int \frac{1}{x^2 + k^2} \, dx = \frac{1}{k} \tan^{-1}\left( \frac{x}{k} \right) + C
$$
$$
\int \frac{k}{x^2 + k^2} \, dx = \tan^{-1}\left( \frac{x}{k} \right) + C
$$
### 8. Choosing an Integration Method
A structured approach:
| Type of Expression | Example | Method |
|---|---|---|
| Simple linear composite | $\cos(2x+1)$, $e^{3x}$ | Inspection or substitution |
| Product $f'(x) \cdot g(f(x))$ | $2x e^{x^2}$, $x^2(x^3+1)^6$ | Substitution $u = f(x)$ |
| Product (polynomial × exponential/trig) | $x e^x$, $x^2 \sin x$ | Integration by parts |
| Quotient $\frac{f'(x)}{f(x)}$ | $\frac{2x}{x^2+1}$, $\frac{\cos x}{\sin x}$ | Natural logarithm result |
| Rational function with factorizable denominator | $\frac{x+1}{x(x-1)}$ | Partial fractions |
| Odd power of $\sin x$ or $\cos x$ | $\cos^3 x$ | Use $\sin^2 x + \cos^2 x = 1$ |
| Even power of $\sin x$ or $\cos x$ | $\sin^2 x$, $\cos^4 x$ | Double-angle formulas |
| $\frac{1}{x^2 + k^2}$ | $\frac{1}{x^2+4}$, $\frac{1}{2x^2+3}$ | Inverse tangent formula |
### 9. Key Standard Integrals Summary
$$
\begin{aligned}
\int x^n \, dx &= \frac{x^{n+1}}{n+1} + C, \quad n \neq -1 \\
\int \frac{1}{x} \, dx &= \ln|x| + C \\
\int e^{ax+b} \, dx &= \frac{1}{a} e^{ax+b} + C \\
\int \cos(ax+b) \, dx &= \frac{1}{a} \sin(ax+b) + C \\
\int \sin(ax+b) \, dx &= -\frac{1}{a} \cos(ax+b) + C \\
\int \sec^2(ax+b) \, dx &= \frac{1}{a} \tan(ax+b) + C \\
\int \frac{1}{x^2 + k^2} \, dx &= \frac{1}{k} \tan^{-1}\left( \frac{x}{k} \right) + C
\end{aligned}
$$
This summary captures the core techniques and properties covered in the two files, providing a structured reference for integration methods up to the level of AS/A Level Mathematics (9709).


## Hodder PM3 Drill

**Example 5.1**  
Find the following integrals.  
(i) $\int \mathrm{e}^{2x - 3}\mathrm{d}x$  
(ii) $\int_{1}^{5}6\mathrm{e}^{3x}\mathrm{d}x$  
**Example 5.2**  
Find $\int_{2}^{5}\frac{1}{2x}\mathrm{d}x.$  
**Example 5.3**  
Find $\int_{0}^{2}\frac{1}{5x + 3}\mathrm{d}x$ .  
**Example 5.4**  
Find the value of $\int_{5}^{7}\frac{1}{4 - x}\mathrm{d}x$  
**Example 5.5**  
Find  
(i) $\int \sec^{2}x\mathrm{d}x$  
(ii) $\int \sin 2x\mathrm{d}x$  
(iii) $\int \cos (3x - \pi)\mathrm{d}x.$  
**Example 5.6**  
Find the exact value of $\int_{0}^{\frac{\pi}{3}}(\sin 2x - \cos 4x)\mathrm{d}x.$  
**Example 5.7**  
Find $\int \sin^2 x \mathrm{d}x$ .  
**Example 5.8**  
Find $\int \cos^4 x \mathrm{d}x$ .  

---
#### Hodder PM3 **Exercise 5A**  
1. Find the following indefinite integrals.  
(i) $\int_{x}^{3}\mathrm{d}x$  
(ii) $\int_{4x}^{1}\mathrm{d}x$  
(iii) $\int_{x - 5}^{1}\mathrm{d}x$  
(iv) $\int_{2x - 9}^{1}\mathrm{d}x$  
2. Find the following indefinite integrals.  
(i) $\int \mathrm{e}^{3x}\mathrm{d}x$  
(ii) $\int \mathrm{e}^{-4x}\mathrm{d}x$  
(iii) $\int \mathrm{e}^{-\frac{x}{3}}\mathrm{d}x$  
(iv) $\int \frac{10}{\mathrm{e}^{5x}}\mathrm{d}x$  
(v) $\int \frac{\mathrm{e}^{3x} + 4}{\mathrm{e}^{2x}}\mathrm{d}x$  
3. Find the following definite integrals. Where appropriate give your answers to 3 significant figures.  
(i) $\int_{0}^{4}\mathrm{e}^{2x}\mathrm{d}x$  
(ii) $\int_{1}^{3}\frac{4}{2x + 1}\mathrm{d}x$  
(iii) $\int_{-1}^{1}(\mathrm{e}^{x} + \mathrm{e}^{-x})\mathrm{d}x$  
(iv) $\int_{-2}^{1}\mathrm{e}^{3x - 2}\mathrm{d}x$  
4. The graph of $y = x + \frac{4}{x}$ is shown below. [image]  
(i) Find the coordinates of the minimum point, P, and the maximum point, Q.  
(ii) Find the area of each shaded region.  
5. The diagram illustrates the graph of $y = \mathrm{e}^{x}$ . The point A has coordinates $(\ln 5, 0)$ , B has coordinates $(\ln 5, 5)$ and C has coordinates $(0, 5)$ . [image]  
(i) Find the area of the region OABE enclosed by the curve $y = \mathrm{e}^{x}$ , the $x$ -axis, the $y$ -axis and the line AB. Hence find the area of the shaded region EBC.  
(ii) The graph of $y = \mathrm{e}^{x}$ is transformed into the graph of $y = \ln x$ . Describe this transformation geometrically.  
(iii) Using your answers to parts (i) and (ii), or otherwise, show that  $$\int_{1}^{5}\ln x\mathrm{d}x = 5\ln 5 - 4.$$  
(iv) Deduce the values of  
(a) $\int_{1}^{5}\ln (x^{3})\mathrm{d}x$  
(b) $\int_{1}^{5}\ln (3x)\mathrm{d}x.$  
6. (i) Differentiate $\ln (2x + 3)$.  
(ii) Hence, or otherwise, show that  $\int_{-1}^{3}\frac{1}{2x + 3}\mathrm{d}x = \ln 3.$  
(iii) Find the quotient and remainder when $4x^{2} + 8x$ is divided by $2x + 3$ .  
(iv) Hence show that
$$\int_{-1}^{3}\frac{4x^{2} + 8x}{2x + 3}\mathrm{d}x = 12 - 3\ln 3.$$  
Cambridge International AS & A Level Mathematics 9709 Paper 2 Q7 June 2006  
8. A curve is such that $\frac{\mathrm{d}y}{\mathrm{d}x} = \mathrm{e}^{2x} - 2\mathrm{e}^{- x}$ . The point $(0,1)$ lies on the curve.  
(i) Find the equation of the curve.  
(ii) The curve has one stationary point. Find the $x$ coordinate of this point and determine whether it is a maximum or a minimum point.  
Cambridge International AS & A Level Mathematics 9709 Paper 2 Q6 November 2005  
9. (i) Find the equation of the tangent to the curve $y = \ln (3x - 2)$ at the point where $x = 1$ .  
(ii) (a) Find the value of the constant $A$ such that  $$\frac{6x}{3x - 2}\equiv 2 + \frac{A}{3x - 2}.$$  
(b) Hence show that $$\int_{2}^{6}\frac{6x}{3x - 2}\mathrm{d}x = 8 + \frac{8}{3}\ln 2$$.  
Cambridge International AS & A Level Mathematics 9709 Paper 2 Q8 June 2009  
10. Find the exact value of the constant $k$ for which $\int_{1}^{k}\frac{1}{2x - 1}\mathrm{d}x = 1$.  
Cambridge International AS & A Level Mathematics 9709 Paper 3 Q1 November 2007

---
#### Hodder PM3 **Exercise 5B**  
1. Integrate the following with respect to $x$ .  
(i) $\sin x - 2\cos x$  
(ii) $3\cos x + 2\sin x$  
(iii) $5\sin x + 4\cos x$  
(iv) $4\sec^2 x$  
(v) $\sin (2x + 1)$  
(vi) $\cos (5x - \pi)$  
(vii) $6\sec^2 2x$  
(viii) $3\sec^2 3x - \sin 2x$  
(ix) $4\sec^2 x - \cos 2x$  
2. Find the exact value of the following.  
(i) $\int \frac{\pi}{3}\sin x\mathrm{d}x$  
(ii) $\int \frac{\pi}{4}\sec^2 x\mathrm{d}x$  
(iii) $\int \frac{\pi}{3}\cos x\mathrm{d}x$  
(iv) $\int \frac{2\pi}{3}\sin 2x\mathrm{d}x$  
(v) $\int \frac{5\pi}{6}\cos 3x\mathrm{d}x$  
(vi) $\int \frac{\pi}{8}\sec^2 2x\mathrm{d}x$  
(vii) $\int \frac{\pi}{6}\cos \left(2x + \frac{\pi}{2}\right)\mathrm{d}x$  
(viii) $\int \frac{\pi}{4}\left(\sec^2 x + \cos 4x\right)\mathrm{d}x$  
(ix) $\int \frac{\pi}{6}\left(\cos x + \sin 2x\right)\mathrm{d}x$  
3. (i) Show that sin x cos x = sin 2x.  
(ii) Hence find the exact value of $\int \frac{\pi}{3}\sin x\cos x\mathrm{d}x$  
4. Use a suitable trigonometrical identity to help you find these.  
(a) $\int \cos^2 x\mathrm{d}x$  
(b) $\int \frac{\pi}{2}\cos^2 x\mathrm{d}x$  
(i) (a) $\int \sin^2 x\mathrm{d}x$  
(b) $\int \frac{\pi}{3}\sin^2 x\mathrm{d}x$  
5. (i) Express $\left(\sqrt{3}\right)\cos x + \sin x$ in the form $R\cos (x - \alpha)$ , where $R > 0$ and $0< \alpha < \frac{1}{2}\pi$ giving the exact values of $R$ and $\alpha$  
(ii) Hence show that $\int \frac{\frac{1}{2}\pi}{\frac{1}{6}\pi}\frac{1}{\left(\left(\sqrt{3}\right)\cos x + \sin x\right)^{2}}\mathrm{d}x = \frac{1}{4}\sqrt{3}.$  
Cambridge International AS & A Level Mathematics 9709 Paper 33 Q4 June 2013  
6. (i) Prove that tan $\theta + \cot \theta \equiv \frac{2}{\sin 2\theta}$  
(ii) Hence  
(a) find the exact value of $\tan \frac{1}{8}\pi +\cot \frac{1}{8}\pi$  
(b) evaluate $\int_{0}^{\frac{1}{2}\pi}\frac{6}{\tan\theta + \cot\theta}\mathrm{d}\theta .$  
Cambridge International AS & A Level Mathematics 9709 Paper 21 Q5 June 2014  
7. (i) Express $\cos^2 x$ in terms of $\cos 2x$  
(ii) Hence show that $\int_{0}^{\frac{1}{3}\pi}\cos^2 x\mathrm{d}x = \frac{1}{6}\pi +\frac{1}{8}\sqrt{3}.$  
(iii) By using an appropriate trigonometrical identity, deduce the exact value of $\int_{0}^{\frac{1}{3}\pi}\sin^2 x\mathrm{d}x.$  
Cambridge International AS & A Level Mathematics 9709 Paper 2 Q6 June 2007  
8. (i) Prove the identity $(\cos x + 3\sin x)^2\equiv 5 - 4\cos 2x + 3\sin 2x.$  
(ii) Using the identity, or otherwise, find the exact value of $\int_{0}^{\frac{1}{4}\pi}(\cos x + 3\sin x)^2\mathrm{d}x.$  
Cambridge International AS & A Level Mathematics 9709 Paper 2 Q7 November 2007  
9. (i) Show that $\int_{0}^{\frac{1}{4}\pi}\cos 2x\mathrm{d}x = \frac{1}{2}.$  
(ii) By using an appropriate trigonometrical identity, find the exact value of $\int_{0}^{\frac{1}{3}\pi}3\tan^2 x\mathrm{d}x.$  
Cambridge International AS & A Level Mathematics 9709 Paper 22 Q4 June 2010  
10. (i) Find $\int 4\mathrm{e}^{x}(3 + \mathrm{e}^{2x})\mathrm{d}x.$  
(ii) Show that $\int_{- \frac{1}{4}\pi}^{\frac{1}{4}\pi}(3 + 2\tan^2 \theta)\mathrm{d}\theta = \frac{1}{2}(8 + \pi).$  
Cambridge International AS & A Level Mathematics 9709 Paper 21 Q6 June 2011  
11. (i) Prove the identity $\cos 4\theta +4\cos 2\theta \equiv 8\cos^4 \theta - 3.$  
(ii) Hence  
(a) solve the equation $\cos 4\theta +4\cos 2\theta = 1$ for $- \frac{1}{2}\pi \leq \theta \leq \frac{1}{2}\pi$  
(b) find the exact value of $\int_{0}^{\frac{1}{4}\pi}\cos^4 \theta \mathrm{d}\theta .$  
Cambridge International AS & A Level Mathematics 9709 Paper 31 Q9 June 2011  
12. (i) By first expanding $\cos (2x + x)$ , show that $\cos 3x \equiv 4\cos^3 x - 3\cos x.$  
(ii) Hence show that $\int_{0}^{\frac{1}{6}\pi}(2\cos^3 x - \cos x)\mathrm{d}x = \frac{5}{12}.$  
Cambridge International AS & A Level Mathematics 9709 Paper 21 Q8 November 2011  
13. (i) Find $\int 4\cos^2 (\frac{1}{2}\theta)\mathrm{d}\theta .$  
(ii) Find the exact value of $\int_{-1}^{6}\frac{1}{2x + 3}\mathrm{d}x.$  
Cambridge International AS & A Level Mathematics 9709 Paper 21 Q3 November 2014  

---

**Example 8.1**  
Find $\frac{\mathrm{d}y}{\mathrm{d}x}$ in terms of $x$ when $y = \tan^{- 1}x$  
**Example 8.2**  
Evaluate $\int_{1}^{3}(x + 1)^{3}\mathrm{d}x$ by making a suitable substitution.  
**Example 8.3**  
Evaluate $\int_{3}^{4}2x(x^{2} - 4)^{\frac{1}{2}}\mathrm{d}x$ by making a suitable substitution.  
**Example 8.4**  
Find $\int x(x^{2} + 2)^{3}\mathrm{d}x$ by making an appropriate substitution.  
**Example 8.5**  
By making a suitable substitution, find $\int x\sqrt{x - 2}\mathrm{d}x$ .  
**Example 8.6**  
By making a suitable substitution, find $\int_{0}^{4}2x\mathrm{e}^{x^2}\mathrm{d}x$ .  
**Example 8.7**  
Evaluate $\int_{1}^{5}\frac{2x}{x^2 + 3}\mathrm{d}x$ .  
**Example 8.8**  
Evaluate $\int_{1}^{2}\frac{5x^{4} + 2x}{x^{5} + x^{2} + 4}\mathrm{d}x.$  
**Example 8.9**  
Evaluate $\int_{0}^{1}\frac{x^{5}}{x^{6} + 7}\mathrm{d}x.$  
**Example 8.10**  
Find $\int 2x\cos (x^2 + 1)\mathrm{d}x$ .  
**Example 8.11**  
Find $\int_{0}^{\frac{\pi}{2}}\cos x\sin^{2}x\mathrm{d}x.$  
**Example 8.12**  
Find $\int \cos^{3}x\mathrm{d}x$ .  
**Example 8.13**  
Find  
(i) $\int \cot x \mathrm{d}x$  
(ii) $\int_{\frac{\pi}{6}}^{\frac{\pi}{3}} \tan x \mathrm{d}x$  
**Example 8.14**  
Find  
(i) $\int \frac{1}{x^{2} + 4}\mathrm{d}x$  
(ii) $\int \frac{1}{5x^{2} + 3}\mathrm{d}x.$  
**Example 8.15**  
Find $\int \frac{x + 4}{(2x - 1)(x + 1)^2}\mathrm{d}x.$  
**Example 8.16**  
Find $\int \frac{x - 2}{(x^2 + 2)(x + 1)}\mathrm{d}x.$  
**Example 8.17**  
Find $\int x\cos x\mathrm{d}x.$  
**Example 8.18**  
Find $\int 2x \mathrm{e}^{x} \mathrm{~d}x$ .  
**Example 8.19**  
Find $\int x \ln x \mathrm{~d} x$ .  
**Example 8.20**  
Find $\int \ln x \mathrm{~d} x$ .  
**Example 8.21**  
Find $\int x^{2}\sin x\mathrm{d}x$  
**Example 8.22**  
Evaluate $\int_{0}^{2}x\mathrm{e}^{x}\mathrm{d}x.$  
**Example 8.23**  
Find the area of the region between the curve $y = x$ cos $x$ and the $x$ - axis, between $x = 0$ and $x = \frac{\pi}{2}$ .  
[image]  

#### Hodder PM3 **Exercise 8A**  
1. Find $\frac{\mathrm{d}y}{\mathrm{d}x}$ in terms of $x$ for each of the following.  
$$y = \tan^{-1}2x$$  
$$y = \tan^{-1}\left(\frac{x}{2}\right)$$  
2. Given $f(x) = k\tan^{- 1}(kx)$ where $k$ is a constant, prove that $f^{\prime}(x) = \frac{k^{2}}{k^{2}x^{2} + 1}$  
3. Given $f(x) = \frac{1}{k}\tan^{- 1}\left(\frac{x}{k}\right)$ where $k$ is a constant, prove that $f^{\prime}(x) = \frac{1}{x^{2} + k^{2}}$  
4. Prove that the equation of the tangent to the curve $y = \tan^{- 1}\left(\frac{x}{\sqrt{3}}\right)$ at the point where $x = 3$ is $12y = \sqrt{3} x + 4\pi - 3\sqrt{3}$  
5. Prove that the equation of the normal to the curve $y = \tan^{- 1}(\sqrt{2} x)$ at the point where $x = \frac{\sqrt{2}}{2}$ is $y + \sqrt{2} x = \frac{4 + \pi}{4}$  
6. Find $\frac{\mathrm{d}y}{\mathrm{d}x}$ in terms of $x$ for each of the following.  
(i) $y = \cos^{- 1}x$  
(ii) $y = \sin^{- 1}x$  
7. Find the equations of the tangent and the normal to the curve $y = \cos^{- 1}2x$ at the point $\left(\frac{1}{4},\frac{\pi}{3}\right)$ .


#### Hodder PM3 **Exercise 8B**  
1. Find the following indefinite integrals by making the suggested substitution. Remember to give your final answer in terms of $x$ .  
(i) $\int 3x^{2}(x^{3} + 1)^{7}\mathrm{d}x, u = x^{3} + 1$  
(ii) $\int 2x(x^{2} + 1)^{5}\mathrm{d}x, u = x^{2} + 1$  
(iii) $\int 3x^{2}(x^{3} - 2)^{4}\mathrm{d}x, u = x^{3} - 2$  
(iv) $\int x\sqrt{2x^{2} - 5}\mathrm{d}x, u = 2x^{2} - 5$  
(v) $\int x\sqrt{2x + 1}\mathrm{d}x, u = 2x + 1$  
(vi) $\int \frac{x}{\sqrt{x + 9}}\mathrm{d}x, u = x + 9$  
2. Evaluate each of the following definite integrals by using a suitable substitution. Give your answer to 3 significant figures where appropriate.  
(i) $\int_{1}^{5}x^{2}(x^{3} + 1)^{2}\mathrm{d}x$  
(ii) $\int_{-1}^{2}2x(x - 3)^{5}\mathrm{d}x$  
(iii) $\int_{1}^{5}x\sqrt{x - 1}\mathrm{d}x$  
3. Find the area of the shaded region for each of the following graphs. [image]  
4. A curve has a gradient function $\frac{\mathrm{d}y}{\mathrm{d}x} = \frac{1}{\sqrt{2x + 3}}$ and passes through the point $(0, 2\sqrt{3})$ . Find the equation of the curve.  
5. The diagram shows the curve $y = \sqrt{x + 1}$ and the line $y = 2$ . Find the area of the shaded region. [image]  
6. Evaluate $\int_{1}^{2}x^{2}(x^{3} - 4)\mathrm{d}x$ using the substitution $u = x^{3} - 4$ .  
7. (i) Integrate with respect to $x$ .  
(a) $\frac{4}{\sqrt{x}} +\frac{3}{x^3}$  
(b) $6x(1 + x^2)^{\frac{1}{2}}$  
(ii) Show that the substitution $x = u^2$ transforms $\int_{1}^{4}\frac{(1 + \sqrt{x})^3}{\sqrt{x}}\mathrm{d}x$ into an integral of the form $\int_{a}^{b}k(1 + u)^3\mathrm{d}u$ . State the values of $k,a$ and $b$ . Evaluate this integral.  
8. Find the integral $\int \frac{\ln x}{x} (1 + \ln x)\mathrm{d}x$ using the substitution $u = 1 + \ln x$ .

#### Hodder PM3 **Exercise 8C**  
1. Find the following indefinite integrals.  
(i) $\int \frac{2x}{x^{2} + 1}\mathrm{d}x$  
(ii) $\int \frac{2x + 3}{3x^{2} + 9x - 1}\mathrm{d}x$  
(iii) $\int 12x^{2}\mathrm{e}^{x^{3}}\mathrm{d}x$  
2. Find the following definite integrals. Where appropriate give your answers to 3 significant figures.  
(i) $\int_{2}^{3}2x\mathrm{e}^{- x^{2}}\mathrm{d}x$  
(ii) $\int_{4}^{6}\frac{x - 3}{x^{2} - 6x + 9}\mathrm{d}x$  
3. The sketch shows the graph of $y = x\mathrm{e}^{x^{2}}$ [image]  
(i) Find the area of region $A$  
(ii) Find the area of region $B$  
(iii) Hence write down the total area of the shaded region.  
4. The graph of $y = \frac{x + 2}{x^{2} + 4x + 3}$ is shown below. [image] Find the area of each shaded region.  
5. A curve has the equation $y = (x + 3)\mathrm{e}^{- x}$  
(i) Find $\frac{\mathrm{d}y}{\mathrm{d}x}$  
(ii) Hence find $\int \frac{x + 2}{\mathrm{e}^{x}}\mathrm{d}x$  
(iii) Find the $x$ and $y$ coordinates of the stationary point S on the curve.  
(iv) Calculate $\frac{\mathrm{d}^{2}y}{\mathrm{d}x^{2}}$ at the point S. What does its value indicate about the stationary point?  
(v) Show that the substitution $u = \mathrm{e}^{x}$ converts $\int \frac{2 + \ln u}{u^{2}}\mathrm{d}u$ into $\int \frac{2 + x}{\mathrm{e}^{x}}\mathrm{d}x$  
(vi) Hence evaluate $\int_{1}^{\mathrm{e}}\frac{2 + \ln u}{u^{2}}\mathrm{d}u$  
6. (i) Sketch the curve with equation $y = \frac{\mathrm{e}^{x}}{\mathrm{e}^{x} + 1}$ for values of $x$ between 0 and 2.  
(ii) Find the area of the region enclosed by this curve, the axes and the line $x = 2$  
(iii) Find the value of $\int_{1}^{\mathrm{e}}\frac{2t}{t^{2} + 1}\mathrm{d}t$  
(iv) Compare your answers to parts (ii) and (iii). Explain this result.  
7. The diagram shows part of the curve $y = \frac{x}{x^2 + 1}$ and its maximum point M. The shaded region $R$ is bounded by the curve and by the lines $y = 0$ and $x = p$ . [image]  
(i) Calculate the $x$ coordinate of M.  
(ii) Find the area of $R$ in terms of $p$ .  
(iii) Hence calculate the value of $p$ for which the area of $R$ is 1, giving your answer correct to 3 significant figures.  
Cambridge International AS & A Level Mathematics 9709 Paper 3 Q9 June 2005  
8. Let $I = \int_{1}^{4}\frac{1}{x(4 - \sqrt{x})}\mathrm{d}x.$  
(i) Use the substitution $u = \sqrt{x}$ to show that $I = \int_{1}^{2}\frac{2}{u(4 - u)}\mathrm{d}u$ .  
(ii) Hence show that $I = \frac{1}{2}\ln 3$ .  
Cambridge International AS & A Level Mathematics 9709 Paper 3 Q7 June 2007

---  
#### Hodder PM3 **Exercise 8D**  
1. Integrate the following by using the substitution given, or otherwise.  
[image]  
2. Use a suitable substitution to integrate the following.  
[image]  
3. Evaluate the following definite integrals by using suitable substitutions.  
(i) $\int_{0}^{\frac{\pi}{2}}\cos \left(2x - \frac{\pi}{2}\right)\mathrm{d}x$  
(ii) $\int_{0}^{\frac{\pi}{2}}\cos x\sin^{3}x\mathrm{d}x$  
(iii) $\int_{0}^{\sqrt{\pi}}x\sin (x^{2})\mathrm{d}x$  
(iv) $\int_{0}^{\frac{\pi}{4}}\frac{\mathrm{e}^{\tan x}}{\cos^{2}x}\mathrm{d}x$  
(v) $\int_{0}^{\frac{\pi}{4}}\frac{1}{\cos^{2}x(1 + \tan x)}\mathrm{d}x$  
4. Find the following.  
(i) $\int\frac{1}{x^{2}+1}\mathrm{d}x$  
(ii) $\int\frac{1}{x^{2}+16}\mathrm{d}x$  
(iii) $\int\frac{2}{x^{2}+9}\mathrm{d}x$  
(iv) $\int\frac{1}{2x^{2}+5}\mathrm{d}x$  
(v) $\int\frac{1}{3x^{2}+4}\mathrm{d}x$  
(vi) $\int\frac{1}{2x^{2}+5}\mathrm{d}x$  
(vii) $\int\frac{1}{2x^{2}+5}\mathrm{d}x$  
5. Find $\int_{0}^{5\sqrt{3}}\frac{10}{x^{2} + 25}\mathrm{d}x$  
6. The diagram shows the curve $y = \sin^{2}2x\cos x$ for $0\leq x\leq \frac{1}{2}\pi$ and its maximum point M. [image]  
(i) Find the $x$ coordinate of M.  
(ii) Using the substitution $u = \sin x$ find by integration the area of the shaded region bounded by the curve and the $x$ - axis.  
Cambridge International AS & A Level Mathematics 9709 Paper 33 Q9 June 2013  
7. The diagram shows the curve $y = \mathrm{e}^{2\sin x}\cos x$ for $0\leq x\leq \frac{1}{2}\pi$ , and its maximum point M. [image]  
(i) Using the substitution $u = \sin x$ , find the exact value of the area of the shaded region bounded by the curve and the axes.  
(ii) Find the $x$ coordinate of M, giving your answer correct to 3 decimal places.  
Cambridge International AS & A Level Mathematics 9709 Paper 33 Q9 June 2014  
8. (i) Prove that cot $\theta +\tan \theta \equiv 2\cos \mathrm{c}2\theta$  
(ii) Hence show that $\int_{\frac{1}{6}\pi}^{\frac{1}{3}\pi}\mathrm{cosec}2\theta \mathrm{d}\theta = \frac{1}{2}\ln 3$  
Cambridge International AS & A Level Mathematics 9709 Paper 31 Q5 November 2013  
9. (i) Use the substitution $x = \sin^{2}\theta$ to show that  
$$\int \sqrt{\left(\frac{x}{1 - x}\right)}\mathrm{d}x = \int 2\sin^{2}\theta \mathrm{d}\theta$$  
(ii) Hence find the exact value of  
$$\int_{0}^{\frac{1}{4}}\sqrt{\left(\frac{x}{1 - x}\right)}\mathrm{d}x.$$  
Cambridge International AS & A Level Mathematics 9709 Paper 31 Q6 November 2005  
10. (a) Find $\int (4 + \tan^{2}2x)\mathrm{d}x$  
(b) Find the exact value of $\int_{\frac{1}{4}\pi}^{\frac{1}{2}\pi}\frac{\sin(x + \frac{1}{6}\pi)}{\sin x}\mathrm{d}x$  
Cambridge International AS & A Level Mathematics 9709 Paper 31 Q5 June 2015  
11. The diagram shows part of the curve $y = \sin^{3}2x\cos^{3}2x$ . The shaded region shown is bounded by the curve and the $x$ - axis and its exact area is denoted by $A$ . [image]  
(i) Use the substitution $u = \sin 2x$ in a suitable integral to find the value of $A$ .  
(ii) Given that $\int_{0}^{k\pi}\left|\sin^{3}2x\cos^{3}2x\right|\mathrm{d}x = 40A$ , find the value of the constant $k$ .  
Cambridge International AS & A Level Mathematics 9709 Paper 33 Q7 November 2012

---
#### Hodder PM3 **Exercise 8E**  
1. Express the fractions in each of the following integrals as partial fractions, and hence perform the integration.  
(i) $\int \frac{1}{(1 - x)(3x - 2)}\mathrm{d}x$  
(ii) $\int \frac{7x - 2}{(x - 1)^2(2x + 3)}\mathrm{d}x$  
(iii) $\int \frac{x + 1}{(x^2 + 1)(x - 1)}\mathrm{d}x$  
(iv) $\int \frac{3x + 3}{(x - 1)(2x + 1)}\mathrm{d}x$  
(v) $\int \frac{1}{x^2(1 - x)}\mathrm{d}x$  
(vi) $\int \frac{1}{(x + 1)(x + 3)}\mathrm{d}x$  
(vii) $\int \frac{2x - 4}{(x^2 + 4)(x + 2)}\mathrm{d}x$  
(viii) $\int \frac{5x + 1}{(x + 2)(2x + 1)^2}\mathrm{d}x$  
2. Express in partial fractions $\mathrm{f}(x) = \frac{3x + 4}{(x^2 + 4)(x - 3)}$ and hence find $\int_0^2\mathrm{f}(x)\mathrm{d}x$  
3. (i) (a) Express $\frac{3}{(1 + x)(1 - 2x)}$ in partial fractions.  
(b) Hence find $\int_0^{0.1}\frac{3}{(1 + x)(1 - 2x)}\mathrm{d}x$ giving your answer to 5 decimal places.  
(ii) (a) Find the first three terms in the binomial expansion of $3(1 + x)^{- 1}(1 - 2x)^{- 1}$  
(b) Use the first three terms of this expansion to find an approximation for $\int_0^{0.1}\frac{3}{(1 + x)(1 - 2x)}\mathrm{d}x$  
(c) What is the percentage error in your answer to part (b)?  
4. (i) Find the values of the constants $A,B,C$ and $D$ such that  
$\frac{2x^3 - 1}{x^2(2x - 1)}\equiv A + \frac{B}{x} +\frac{C}{x^2} +\frac{D}{2x - 1}$  
(ii) Hence show that $\int_1^2\frac{2x^3 - 1}{x^2(2x - 1)}\mathrm{d}x = \frac{3}{2} +\frac{1}{2}\ln \left(\frac{16}{27}\right)$  
Cambridge International AS & A Level Mathematics 9709 Paper 32 Q10 June 2010  
5. Let $\mathrm{f}(x)\equiv \frac{x^2 + 3x + 3}{(x + 1)(x + 3)}$  
(i) Express $\mathrm{f}(x)$ in partial fractions.  
(ii) Hence show that $\int_0^3\mathrm{f}(x)\mathrm{d}x = 3 - \frac{1}{2}\ln 2$  
Cambridge International AS & A Level Mathematics 9709 Paper 3 Q7 June 2008  
6. Let $\mathrm{f}(x) = \frac{12 + 8x - x^2}{(2 - x)(4 + x^2)}.$  
(i) Express $\mathrm{f}(x)$ in the form $\frac{A}{2 - x} +\frac{Bx + C}{4 + x^2}$  
(ii) Show that $\int_{0}^{1}\mathrm{f}(x)\mathrm{d}x = \ln \left(\frac{25}{2}\right).$  
Cambridge International AS & A Level Mathematics 9709 Paper 31 Q8 November 2011  
7. (i) Show that $(x + 1)$ is a factor of $4x^{3} - x^{2} - 11x - 6.$  
(ii) Find $\int \frac{4x^{2} + 9x - 1}{4x^{3} - x^{2} - 11x - 6}\mathrm{d}x.$  
Cambridge International AS & A Level Mathematics 9709 Paper 33 Q7 November 2015  
8. By first using the substitution $u = \mathrm{e}^{x}$ , show that  
$\int_{0}^{\ln 4}\frac{\mathrm{e}^{2x}}{\mathrm{e}^{2x} + 3\mathrm{e}^{x} + 2}\mathrm{d}x = \ln \left(\frac{8}{5}\right).$  
Cambridge International AS & A Level Mathematics 9709 Paper 33 Q10 November 2014

---  
#### Hodder PM3 **Exercise 8F**  
1. For each of these integrals  
(a) write down the expression to be taken as $u$ and the expression to be taken as $\frac{\mathrm{d}v}{\mathrm{d}x}$  
(b) use the formula for integration by parts to complete the integration. [image]  
2. Use integration by parts to integrate [image]  
3. Find $\int x \sqrt{1 + x} \mathrm{d}x$  
(i) by using integration by parts  
(ii) by using the substitution $u = 1 + x$  
4. Find $\int 2x(x - 2)^4 \mathrm{d}x$  
(i) by using integration by parts  
(ii) by using the substitution $u = x - 2$  
5. (i) By writing $\ln x$ as the product of $\ln x$ and 1, use integration by parts to find $\int \ln x \mathrm{d}x$ .  
(ii) Use the same method to find $\int \ln 3x \mathrm{d}x$ .  
(iii) Write down $\int \ln px \mathrm{d}x$ where $p > 0$ .  
6. Find $\int x^2 \mathrm{e}^x \mathrm{d}x$ .  
7. Find $\int (2 - x)^2 \cos x \mathrm{d}x$ .  
8. Find $\int x \tan^{- 1} x \mathrm{d}x$ .

---
#### Hodder PM3 **Exercise 8G**  
1. Evaluate these definite integrals.  
(i) $\int_{0}^{1}x\mathrm{e}^{3x}\mathrm{d}x$  
(ii) $\int_{0}^{\pi}(x - 1)\mathrm{cos}x\mathrm{d}x$  
(iii) $\int_{0}^{2}(x + 1)\mathrm{e}^{x}\mathrm{d}x$  
(iv) $\int_{1}^{2}\ln 2x\mathrm{d}x$  
(v) $\int_{0}^{\frac{\pi}{2}}x\sin 2x\mathrm{d}x$  
(vi) $\int_{1}^{4}x^{2}\ln x\mathrm{d}x$  
2. (i) Find the coordinates of the points where the graph of $y = (2 - x)\mathrm{e}^{- x}$ cuts the $x-$ and $y-$ axes.  
(ii) Hence sketch the graph of $y = (2 - x)\mathrm{e}^{- x}$  
(iii) Use integration by parts to find the area of the region between the $x-$ axis, the $y-$ axis and the graph $y = (2 - x)\mathrm{e}^{- x}$  
3. (i) Sketch the graph of $y = x\sin x$ from $x = 0$ to $x = \pi$ and shade the region between the curve and the $x-$ axis.  
(ii) Find the area of this region using integration by parts.  
4. Find the area of the region between the $x-$ axis, the line $x = 5$ and the graph $y = \ln x$  
5. Find the area of the region between the $x-$ axis and the graph $y = x\cos x$ from $x = 0$ to $x = \frac{\pi}{2}$  
6. Find the area of the region between the negative $x-$ axis and the graph $y = x\sqrt{x + 1}$  
(i) using integration by parts  
(ii) using the substitution $u = x + 1$  
7. Find  
(i) $\int_{0}^{\sqrt{3}}6x\tan^{-1}x\mathrm{d}x$  
(ii) $\int_{0}^{\frac{1}{2}}x\tan^{-1}(2x)\mathrm{d}x.$  
8. Find the exact value of $\int_{1}^{4}\frac{\ln x}{\sqrt{x}}\mathrm{d}x.$  
Cambridge International AS & A Level Mathematics 9709 Paper 31 Q3 November 2013  
9. The constant $a$ is such that $\int_{0}^{a}x\mathrm{e}^{\frac{1}{2x}}\mathrm{d}x = 6$  
(i) Show that $a$ satisfies the equation  
$x = 2 + \mathrm{e}^{-\frac{1}{2x}}.$  
(ii) By sketching a suitable pair of graphs, show that this equation has only one root.  
(iii) Verify by calculation that this root lies between 2 and 2.5.  
(iv) Use an iterative formula based on the equation in part (i) to calculate the value of $a$ correct to 2 decimal places. Give the result of each iteration to 4 decimal places.  
Cambridge International AS & A Level Mathematics 9709 Paper 3 Q9 November 2008  
10. The diagram shows the curve $y = \mathrm{e}^{-\frac{1}{2x}}\sqrt{(1 + 2x)}$ and its maximum point M. The shaded region between the curve and the axes is denoted by $R$ . [image]  
(i) Find the $x$ coordinate of $M$ .  
(ii) Find by integration the volume of the solid obtained when $R$ is rotated completely about the $x$ -axis. Give your answer in terms of $\pi$ and $e$ .  
Cambridge International AS & A Level Mathematics 9709 Paper 3 Q9 June 2008  
11. The expression $\mathrm{f}(x)$ is defined by $\mathrm{f}(x) = 3x\mathrm{e}^{- 2x}$ .  
(i) Find the exact value of $\mathrm{f}^{\prime}\left(-\frac{1}{2}\right)$ .  
(ii) Find the exact value of $\int_{-\frac{1}{2}}^{0}\mathrm{f}(x)\mathrm{d}x$ .  
Cambridge International AS & A Level Mathematics 9709 Paper 33 Q5 November 2012  
12. The diagram shows the curve $y = x^{\frac{1}{2}}\ln x$ . The shaded region between the curve, the $x$ - axis and the line $x = e$ is denoted by $R$ . [image]  
(i) Find the equation of the tangent to the curve at the point where $x = 1$ , giving your answer in the form $y = mx + c$ .  
(ii) Find by integration the volume of the solid obtained when the region $R$ is rotated completely about the $x$ -axis. Give your answer in terms of $\pi$ and $e$ .  
Cambridge International AS & A Level Mathematics 9709 Paper 32 Q9 June 2012

---
#### Hodder PM3 **Exercise 8H**  
1. Choose an appropriate method and integrate the following. You may find it helpful to discuss in class first which method to use.  
(i) $\int \cos (3x - 1)\mathrm{d}x$  
(ii) $\int \frac{2x + 1}{(x^2 + x - 1)^2}\mathrm{d}x$  
(iii) $\int \mathrm{e}^{1 - x}\mathrm{d}x$  
(iv) $\int \cos 2x\mathrm{d}x$  
(v) $\int \ln 2x\mathrm{d}x$  
(vi) $\int \frac{x}{(x^2 - 1)^3}\mathrm{d}x$  
(vii) $\int \sqrt{2x - 3}\mathrm{d}x$  
(viii) $\int \frac{4x - 1}{(x - 1)^2(x + 2)}\mathrm{d}x$  
(ix) $\int x^3\ln x\mathrm{d}x$  
(x) $\int \frac{5}{2x^2 - 7x + 3}\mathrm{d}x$  
(xi) $\int (x + 1)\mathrm{e}^{x^2 +2x}\mathrm{d}x$  
(xii) $\int \frac{\sin x - \cos x}{\sin x + \cos x}\mathrm{d}x$  
(xiii) $\int x^2\sin 2x\mathrm{d}x$  
(xiv) $\int \sin^3 2x\mathrm{d}x$  
2. Evaluate the following definite integrals.  
(i) $\int_{8}^{24}\frac{\mathrm{d}x}{\sqrt{3x - 8}}$  
(ii) $\int_{8}^{24}\frac{\mathrm{d}x}{3x - 8}$  
(iii) $\int_{8}^{24}\frac{9x}{3x - 8}\mathrm{d}x$  
(iv) $\int_{0}^{\frac{\pi}{2}}\sin^{3}x\mathrm{d}x$  
(v) $\int_{1}^{2}x^{2}\ln x\mathrm{d}x$  
(vi) $\int_{0}^{1}\frac{x^{2}}{\sqrt{1 + x^{3}}}\mathrm{d}x$  
(vii) $\int_{1}^{2}\frac{2\ln x}{x}\mathrm{d}x$  
(viii) $\int_{0}^{\frac{\pi}{3}}x\cos 3x\mathrm{d}x$  
(ix) $\int_{0}^{\frac{\pi}{4}}\frac{\sin x}{\cos^{4}x}\mathrm{d}x$  
(x) $\int_{0}^{1}\frac{x}{e^{2x}}\mathrm{d}x$  
3. Let $\mathrm{f}(x) = \frac{6 + 6x}{(2 - x)(2 + x^2)}$  
(i) Express $\mathrm{f}(x)$ in the form $\frac{A}{2 - x} +\frac{Bx + C}{2 + x^2}.$  
(ii) Show that $\int_{-1}^{1}\mathrm{f}(x)\mathrm{d}x = 3\ln 3.$  
Cambridge International AS & A Level Mathematics 9709 Paper 33 Q8 June 2014  
4. The diagram shows the curve $y = x^{2}\mathrm{e}^{2 - x}$ and its maximum point M. [image]  
(i) Show that the $x$ coordinate of M is 2.  
(ii) Find the exact value of $\int_{0}^{2}x^{2}\mathrm{e}^{2 - x}\mathrm{d}x.$  
Cambridge International AS & A Level Mathematics 9709 Paper 31 Q9 June 2015  
5. The integral $I$ is defined by $I = \int_{0}^{2}4t^{3}\ln (t^{2} + 1)\mathrm{d}t.$  
(i) Use the substitution $x = t^{2} + 1$ to show that $I = \int_{1}^{5}(2x - 2)\ln x\mathrm{d}x.$  
(ii) Hence find the exact value of $I.$  
Cambridge International AS & A Level Mathematics 9709 Paper 31 Q7 June 2011  


## Oxford Complete PM3 Drill

---
**Example 1**  
Find $\int e^{2x + 3} \mathrm{~d} x$ .  

**Example 2**  
Calculate $\int_{0}^{1} e^{2x + 3} \mathrm{~d} x$ .  

**Example 3**  
Calculate $\int_{-\infty}^{1}\mathrm{e}^{2x + 3}\mathrm{d}x$ .  

**Example 4**  
Calculate $\int \sqrt{\mathrm{e}^{x + 1}}\mathrm{d}x$ .  

**Example 5**  
Find the area bounded by the graph of $y = \mathrm{e}^{2x}$ , the $x$ - axis, the $y$ - axis, and the line $x = 1$ .  
[image]  

**Example 6**  
Find $\int \frac{2}{2x - 3}\mathrm{d}x$ and state the values of $x$ for which the answer is valid.  

**Example 7**  
a) Sketch the graph of $y = \frac{1}{x - 2}$ .  
b) Mark on your sketch the two areas represented by $\int_{-2}^{-1}\frac{1}{x - 2}\mathrm{d}x$ and $\int_{5}^{6}\frac{1}{x - 2}\mathrm{d}x$ .  
c) Explain, using the symmetry of the reciprocal function, why $\int_{-2}^{-1}\frac{1}{x - 2}\mathrm{d}x = -\int_{5}^{6}\frac{1}{x - 2}\mathrm{d}x$ .  
d) Calculate the two integrals in part (c) and verify the result.  
[image]  

**Example 12**  
Calculate $\int_{4}^{6}\frac{1}{7 - 2x}\mathrm{d}x$ , giving your answer as a single logarithm (i.e. in the form $\ln k$ where $k$ is real).  

**Example 13**  
Find $\int \cos 2x \mathrm{~d}x$ .  

**Example 14**  
Find $\int \sin \left(3x + \frac{\pi}{4}\right)\mathrm{d}x.$  

**Example 15**  
a) Sketch the graph of $y = \sec x$ and use it to sketch the graph of $y = \sec^2 x$ .  
b) On your sketch, shade the area corresponding to $\int_{0}^{\frac{\pi}{4}}\sec^2 x\mathrm{d}x$ and estimate to 1 significant figure the value of the area.  
c) Calculate $\int_{0}^{\frac{\pi}{4}}\sec^2 x\mathrm{d}x$ .  
[image] [image]  

**Example 16**  
By first sketching an appropriate graph, find the area bounded by the graph of $y = \sin \left(x - \frac{\pi}{3}\right)$ , the $x$ - and $y$ - axes and the line $x = \pi$ .  
[image]  

**Example 17**  
Find the integrals  
a) $\int \cos^{2}x\mathrm{d}x$  
b) $\int 12\sin^{2}x\mathrm{d}x.$  

**Example 18**  
Calculate the exact value of $\int_{0}^{\frac{\pi}{6}} 4 \tan^{2} \theta \mathrm{~d} \theta$ .  

**Example 19**  
a) By writing $2x = 3x - x$ and $4x = 3x + x$ , show that $\sin 3x \cos x = \frac{1}{2} (\sin 2x + \sin 4x)$ .  
b) Hence calculate $\int_{0}^{\frac{\pi}{6}} \sin 3x \cos x \mathrm{~d} x$ .  

**Example 20**  
a) Show that $(3\sin x - \cos x)^2 = 5 - 3\sin 2x - 4\cos 2x.$  
b) Hence calculate $\int_{0}^{\frac{\pi}{2}}(3\sin x - \cos x)^{2}\mathrm{d}x.$  

**Example 21**  
a) Find $\frac{\mathrm{d}}{\mathrm{d}x} (\cos x + x\sin x)$ .  
b) Hence calculate $\int_{0}^{\frac{\pi}{2}}(x\cos x)\mathrm{d}x.$  

**Example 24**  
a) Use the trapezium rule with five intervals to estimate $\int_{0}^{\frac{\pi}{2}}(x \cos x) \mathrm{d}x$ , giving your answer correct to 3 decimal places.  
b) In Example 21, you saw that the exact value of this integral is $\frac{\pi}{2} - 1$ . Calculate the percentage error in the estimate using the trapezium rule with five intervals.  
[image]  

**Example 25**  
a) Use the trapezium rule with five ordinates to estimate $\int_{1}^{3} \frac{1}{x} \mathrm{~d} x$ , giving your answer correct to 3 decimal places.  
b) Show that the exact value of this integral is $\ln 3$ .  
c) Calculate the percentage error in the estimate found in part (a).  

**Example 26**  
a) Use the trapezium rule with two intervals to estimate $\int_{0}^{\frac{1}{2}\pi}\sqrt{1 - \sin x}\mathrm{d}x$ , giving your answer correct to 2 decimal places.  
b) The diagram shows the graph of $y = \sqrt{1 - \sin x}$ . State, with a reason, whether your answer to part (a) is an overestimate or an underestimate of the integral.  
[image]  

**Example 27**  
Use the trapezium rule with two intervals to estimate $\int_{0}^{1}\mathrm{e}^{- x^{2}}\mathrm{d}x$ , giving your answer correct to 2 decimal places.  
[image]  

---  
#### Oxford Complete **Exercise 5.2**  
1. Find the following indefinite integrals and state the values of $x$ for which the answer is valid.  
a) $\int \frac{1}{2x - 1}\mathrm{d}x$  
b) $\int \frac{2}{2x - 1}\mathrm{d}x$  
c) $\int \frac{7}{7x + 3}\mathrm{d}x$  
d) $\int \frac{10}{5 - 2x}\mathrm{d}x$  
e) $\int \frac{-6}{1 - 3x}\mathrm{d}x$  
f) $\int \frac{-2}{6x + 5}\mathrm{d}x$  
g) $\int \frac{-3}{x + 1}\mathrm{d}x$  
h) $\int \frac{1}{7 - x}\mathrm{d}x$  
i) $\int \frac{2}{x + \mathrm{e}}\mathrm{d}x$  
j) $\int \frac{-0.5}{2x + 1}\mathrm{d}x$  
k) $\int \frac{-12}{9x + 16}\mathrm{d}x$  
l) $\int \frac{-2}{10x - 3}\mathrm{d}x$

3. Calculate the following definite integrals. Note that parts (a) to (c) use the same indefinite integrals as you calculated in parts (a) to (c) of question 1.  
a) $\int_{2}^{3}\frac{1}{2x - 1}\mathrm{d}x$  
b) $\int_{5}^{7}\frac{2}{2x - 1}\mathrm{d}x$  
c) $\int_{0}^{1}\frac{7}{7x + 3}\mathrm{d}x$  
d) $\int_{0}^{1}\frac{4}{5 - 2x}\mathrm{d}x$  
e) $\int_{0}^{1}\frac{9}{4 - 2x}\mathrm{d}x$  
f) $\int_{0}^{2}\frac{-7}{5 - x}\mathrm{d}x$  
g) $\int_{2}^{4}\frac{2}{x - 7}\mathrm{d}x$  
h) $\int_{-6}^{-4}\frac{-4}{7 - 2x}\mathrm{d}x$  
i) $\int_{-1}^{1}\frac{6}{5 - 3x}\mathrm{d}x$

5. Find the area bounded by the graph of $y = \frac{1}{3 + x}$ , the $x$ - and $y$ -axes, and the line $x = 3$ .  
6. Find the area bounded by the graph of $y = \frac{-2}{x + 3}$ , the $x$ - and $y$ -axes, and the line $x = 2$ .  
7. Find the area bounded by the graphs of $y = \frac{1}{x - 3}$ , $y = \frac{1}{2x + 3}$ , the $y$ -axis, and the line $x = 2$ .

---
#### Oxford Complete **Exercise 5.3**  

1. Find these integrals.  
a) $\int \cos 2x\mathrm{d}x$  
b) $\int \sin \left(2x + \frac{\pi}{4}\right)\mathrm{d}x$  
c) $\int \sec^2\left(3x + \frac{\pi}{12}\right)\mathrm{d}x$  
d) $\int \cos \left(\pi -x\right)\mathrm{d}x$  
e) $\int \cos \left(\frac{\pi}{2} -\frac{x}{4}\right)\mathrm{d}x$  
f) $\int -\sin \left(2x - \frac{\pi}{4}\right)\mathrm{d}x$  
g) $\int \sec^2\left(\frac{\pi}{12} -5x\right)\mathrm{d}x$  
h) $\int -\frac{1}{2}\sin \left(\frac{1}{2}x\right)\mathrm{d}x$  
i) $\int \cos \left(4 - \frac{1}{3}x\right)\mathrm{d}x$

3. Calculate the following definite integrals. Note that parts (a) to (c) use the same indefinite integral as you calculated in parts (a) to (c) of question 1.  
a) $\int_{0}^{\frac{\pi}{4}}\cos 2x\mathrm{d}x$  
b) $\int_{0}^{\frac{\pi}{2}}\sin \left(2x + \frac{\pi}{4}\right)\mathrm{d}x$  
c) $\int_{0}^{\frac{\pi}{12}}\sec^{2}\left(3x + \frac{\pi}{12}\right)\mathrm{d}x$  
d) $\int_{0}^{\frac{\pi}{4}}\cos 2x\mathrm{d}x$  
e) $\int_{0}^{\pi}\cos \left(\frac{3\pi}{2} -\frac{x}{3}\right)\mathrm{d}x$  
f) $\int_{0}^{\frac{\pi}{2}}\sin \left(3x - \frac{\pi}{4}\right)\mathrm{d}x$  
g) $\int_{\frac{\pi}{12}}^{\frac{\pi}{12}}\sec^{2}\left(\frac{\pi}{12} -3x\right)\mathrm{d}x$  
h) $\int_{\frac{\pi}{4}}^{\frac{\pi}{4}}\frac{1}{3}\cos \left(\frac{1}{2}x\right)\mathrm{d}x$  
i) $\int_{1}^{3}\cos \left(2 - \frac{1}{2}x\right)\mathrm{d}x$

5. A curve passes through the point $\left(\frac{\pi}{4}, 2\right)$ and its gradient function is $\sec^2 x$ . Find the equation of the curve.  
6. Find the area bounded by the graph of $y = \cos \left(x + \frac{\pi}{4}\right)$ , the $x$ - and $y$ -axes, and the line $x = \pi$ .  
7. Find the area bounded by the graphs of $y = \cos \left(x + \frac{\pi}{4}\right), y = \cos \left(x + \frac{\pi}{2}\right)$ , the $y$ -axis, and the line $x = \frac{\pi}{2}$ .  
8. Find the area bounded by the graph of $y = \sec^{2}\left(2x + \frac{\pi}{2}\right)$ , the $x$ -axis, and the lines $x = \frac{\pi}{4}$ and $x = \frac{\pi}{3}$ .

---
#### Oxford Complete **Exercise 5.4**  
1. Find these integrals.  
a) $\int \cos^2 2x\mathrm{d}x$  
b) $\int (\sin x\cos x)\mathrm{d}x$  
c) $\int (\sin^2 x\cos^2 x)\mathrm{d}x$  
d) $\int (\sin x + \cos x)^2\mathrm{d}x$  
e) $\int (\sin x + \cos x)^2\mathrm{d}x$  
f) $\int (\sin x + \cos x)^2\mathrm{d}x$  
g) $\int (\sin x + \cos x)^2\mathrm{d}x$  
h) $\int (\sin x - \cos x)^2\mathrm{d}x$  
i) $\int (\sin x - \cos x)^3\mathrm{d}x$  
j) $\int (\sin x - \cos x)^3\mathrm{d}x$

3. Calculate the following definite integrals. Note that parts (a) to (c) use the same indefinite integral as you calculated in parts (a) to (c) of question 1.  
a) $\int_{0}^{\frac{\pi}{4}}\cos^{2}2x\mathrm{d}x$  
b) $\int_{0}^{\frac{\pi}{2}}\sin^{2}3x\mathrm{d}x$  
c) $\int_{0}^{\frac{\pi}{12}}(1 + \tan^{2}2x)\mathrm{d}x$  
d) $\int_{0}^{\frac{\pi}{2}}(1 - \cos 2x)^{2}\mathrm{d}x$  
e) $\int_{0}^{\pi}(1 + 2\sin x)^{2}\mathrm{d}x$  
f) $\int_{0}^{\frac{\pi}{2}}(\sin x - \cos x)^{2}\mathrm{d}x$

5. A curve passes through the origin and its gradient function is $\cos^2 x$ . Find the equation of the curve.

7. Find the area bounded by the graph of $y = \sec^2 x$ , the $x$ -axis, and the lines $x = \frac{\pi}{6}$ and $x = \frac{\pi}{3}$ .
 
8. Find the area bounded by the graphs of $y = \cos^2 x$ , $y = \sin^2 x$ , the $y$ -axis, and the line $x = \frac{\pi}{4}$ .

10. a) By writing $2x = 5x - 3x$ and $8x = 5x + 3x$ , show that $\sin 3x\cos 5x = \frac{1}{2} (\sin 8x - \sin 2x)$ .  
b) Hence calculate $\int_{0}^{\frac{\pi}{6}}\sin 3x\cos 5x\mathrm{d}x$ .

11. a) Show that $(\sin x + 5\cos x)^2 = 13 + 5\sin 2x + 12\cos 2x$ .  
b) Hence calculate $\int_{0}^{\frac{\pi}{2}}(\sin x + 5\cos x)^{2}\mathrm{d}x$ .  
12. a) Show that $\frac{\mathrm{d}}{\mathrm{d}x} (\cos 2x + 2x\sin 2x - 2x^2\cos 2x) = 4x^2\sin 2x$ .  
b) Hence calculate $\int_{0}^{\frac{\pi}{2}}(x^{2}\sin 2x)\mathrm{d}x$ .  
13. a) Show that $\frac{2\tan\theta}{1 + \tan^2\theta} = \sin 2\theta$ .  
b) Hence calculate $\int_{0}^{\frac{\pi}{6}}\left(\frac{2\tan\theta}{1 + \tan^2\theta}\right)^2\mathrm{d}\theta$ .  
14. a) Show that $\frac{1 - \tan^2 x}{1 + \tan^2 x} = \cos 2x$ .  
Hence calculate  
b) $\int_{0}^{\frac{\pi}{6}}\left(\frac{1 - \tan^2 x}{1 + \tan^2 x}\right)^2\mathrm{d}x$  
c) $\int_{0}^{\frac{\pi}{6}}\left(\frac{1 + \tan^2 x}{1 - \tan^2 x}\right)^2\mathrm{d}x.$

---
#### Oxford Complete **Exercise 5.5**  
1. For each of the following, use the trapezium rule with two intervals to estimate the value of the definite integral to 3 significant figures.  
a) $\int_{0}^{\frac{\pi}{4}}\cos^{3}2x\mathrm{d}x$  
b) $\int_{0}^{\frac{\pi}{4}}\sqrt{1 + \tan^{2}2x}\mathrm{d}x$  
c) $\int_{0}^{1}\frac{\mathrm{e}^{2x}}{1 + \mathrm{e}^{x}}\mathrm{d}x$  
d) $\int_{0}^{\frac{\pi}{4}}\frac{\mathrm{e}^{2x}}{1 + \mathrm{e}^{x}}\mathrm{d}x$  
e) $\int_{0}^{1}\frac{1}{1 + 9x^{2}}\mathrm{d}x$

3. For each of the following, use the trapezium rule with the specified number of intervals to estimate the value of the definite integral to 3 significant figures.  
a) $\int_{0}^{\frac{\pi}{4}}\cos^{3}2x\mathrm{d}x$ (3 intervals)  
b) $\int_{0}^{\frac{\pi}{4}}\sqrt{1 + \sin 3x}\mathrm{d}x$ (4 intervals)  
c) $\int_{0}^{\frac{\pi}{4}}\sqrt{1 + \tan^{2}2x}\mathrm{d}x$ (5 intervals)  
d) $\int_{0}^{1}\sqrt{1 + \tan^{2}2x}\mathrm{d}x$ (5 intervals)  
e) $\int_{1}^{1}\sqrt{1 + \tan^{2}2x}\mathrm{d}x$ (4 intervals)

5. The diagram shows the graph of $y = \sqrt{1 + x^2}$ . The region R is bounded by the curve, the $x$ - and $y$ -axes and the line $x = 2$ .  
a) Use the trapezium rule with six ordinates to obtain an approximation for the area of R, giving your answer to a suitable degree of accuracy.  
b) Explain, with the aid of a sketch, whether the approximation is an overestimate or underestimate.  
[image]

6. The diagram shows the graph of $y = x\mathrm{e}^{- x}$ . The region R is bounded by the curve, the $x$ -axis and the line $x = 2$ .  
a) Use the trapezium rule with 11 ordinates to obtain an approximation for the area of R, giving your answer to 3 significant figures.  
b) Explain, with the aid of a sketch, whether the approximation is an overestimate or underestimate.  
[image]

7. The diagram shows the graph of $y = \frac{1}{1 + x}$ . The region R is bounded by the curve, the $x$ - and $y$ -axes, and the line $x = 2$ .  
a) Use the trapezium rule with i) two intervals and ii) 10 intervals to obtain approximations for the area of R, giving your answers to 3 significant figures.  
b) Calculate the exact value of $\int_{0}^{2}\frac{1}{1 + x}\mathrm{d}x$ and comment on the accuracy of your estimates.  
[image]

---
**Summary exercise 5**  
1. Find the following indefinite integrals.  
a) $\int \mathrm{e}^{2x - 3}\mathrm{d}x$  
b) $\int \frac{-3}{6x + 2}\mathrm{d}x$  
c) $\int \sin 4x\mathrm{d}x$  
d) $\int \sin^2 6x\mathrm{d}x$  
e) $\int \sqrt{\mathrm{e}^{2 - x}}\mathrm{d}x$  
f) $\int \frac{12}{3x - 4}\mathrm{d}x$  
g) $\int (\sin x - 2\cos x)^2\mathrm{d}x$  
h) $\int \frac{-6}{3x + 5}\mathrm{d}x$  
i) $\int -\cos \left(3x + \frac{\pi}{3}\right)\mathrm{d}x$  
2. Calculate the following definite integrals, leaving your answers as exact values.  
a) $\int_{0}^{2}\mathrm{e}^{5x}\mathrm{d}x$  
b) $\int_{0}^{1}\frac{4}{4x + 2}\mathrm{d}x$  
c) $\int_{0}^{\frac{1}{6}x}\sec^{2}\left(2x - \frac{\pi}{6}\right)\mathrm{d}x$  
d) $\int_{0}^{\frac{1}{4}x}(1 - 3\sin 2x)^{2}\mathrm{d}x$  
e) $\int_{0}^{\frac{1}{4}x}\sin \left(\frac{\pi}{4} -\frac{1}{2}x\right)\mathrm{d}x$  
f) $\int_{\ln 2}^{\ln 3}\mathrm{e}^{2x}\mathrm{d}x$  
g) $\int_{0}^{\frac{1}{6}\pi}(\sin^{2}x - \cos^{2}x)\mathrm{d}x$  
h) $\int_{- 1}^{2} - \mathrm{e}^{2x}\mathrm{d}x$  
i) $\int_{- 1}^{1}\frac{5}{3x - 5}\mathrm{d}x$

**EXAM-STYLE QUESTIONS**  
4. Find the area bounded by the graph of $y = \mathrm{e}^{- 2x + 1}$ , the $x$ - and $y$ -axes, and the line $x = 2$ .  
5. Find the area bounded by the graph of $y = \frac{1}{2 + x}$ , the $x$ - and $y$ -axes, and the line $x = 1$ .  
6. A curve passes through the point $\left(\frac{\pi}{4}, 0\right)$ and its gradient function is $\sin^{2}x$ . Find the equation of the curve.  
7. Find the area bounded by the graphs of $y = \frac{1}{x - 5}, y = \frac{1}{2x + 1}$ , the $y$ -axis, and the line $x = 3$ .  
8. Find the area bounded by the graphs of $y = \frac{1}{2x - 7}, y = 2 + \mathrm{e}^{-x}$ , the $y$ -axis, and the line $x = 2$ .  
9. Calculate the following improper integrals, leaving your answers in terms of e where appropriate.  
a) $\int_{0}^{\infty}\mathrm{e}^{-2x}\mathrm{d}x$  
b) $\int_{1}^{\infty}\mathrm{e}^{-0.5x}\mathrm{d}x$  
c) $\int_{-\infty}^{-1}\sqrt{\mathrm{e}^{x}}\mathrm{d}x$  

**EXAM-STYLE QUESTIONS**  
10. The line $y = 4\mathrm{e}^{-2x}$ between $x = 1$ and $x = 2$ is rotated through $360^{\circ}$ about the $x$ -axis. Find the volume of the solid obtained.  
11. a) By writing $x = 4x - 3x$ and $7x = 4x + 3x$ , show that $\sin 3x \sin 4x = \frac{1}{2} (\cos x - \cos 7x)$ .  
b) Hence calculate $\int_{0}^{\frac{1}{2}\pi} \sin 3x \sin 4x \mathrm{d}x$ .  
12. a) Show that $(\sin 2x - 3\cos 2x)^2 = 5 - 3\sin 4x + 4\cos 4x$ .  
b) Hence calculate $\int_{0}^{\frac{1}{2}\pi}(\sin 2x - 3\cos 2x)^2 \mathrm{d}x$ .  
13. a) Show that $\frac{1 + \tan^{2}\theta}{1 - \tan^{2}\theta} = \sec 2\theta$ .  
b) Hence calculate $\int_{0}^{\frac{\pi}{6}}\left(\frac{1 + \tan^{2}\theta}{1 - \tan^{2}\theta}\right)^{2}\mathrm{d}\theta$ .

---

**EXAM-STYLE QUESTIONS -PURE 2**  
14. The diagram shows the graph of $y = \sqrt{1 - \sin x}$ . The region R is bounded by the curve, the $x$ - and $y$ -axes and the line $x = \frac{3\pi}{2}$ . (R is in two sections).  
a) Use the trapezium rule with 7 ordinates to obtain an approximation for the total area of R, giving your answer correct to 2 decimal places.  
b) Explain, with the aid of a sketch, whether the approximation is an overestimate or underestimate.  
[image]  

15. The diagram shows the graph of $y = x\ln x$ . The region R is bounded by the curve, the $x$ -axis, and the line $x = 2$ .  
[image]  
a) Explain why $\int_{0}^{2}x\ln x\mathrm{d}x$ (if you were able to calculate it) would not give the area of R.  
b) Calculate an estimate for the area of R using the trapezium rule and intervals of width 0.5.  

16. Use the trapezium rule with five intervals to find an approximation to  
$$\int_{-2}^{3}|x^{2} - 1|\mathrm{d}x.$$

18. a) Find $\int 2\cos^{2}(3\theta)\mathrm{d}\theta$ .  
b) Find the exact value of  
$$\int_{2}^{3}\frac{1}{2x + 5}\mathrm{d}x.$$  

---

**Example 1**  
[image]  
**Example 2**  
[image]  
**Example 5**  
[image]  
**Example 9**  
Evaluate $\int_{4}^{6}\frac{1}{(x-2)(x-3)}\mathrm{d}x.$  
**Example 10**  
$y = \tan^{- 1}\left(\frac{x}{a}\right)$ Find an expression for $\frac{\mathrm{d}y}{\mathrm{d}x}$  
**Example 11**  
$y = \tan^{- 1}(bx)$ . Find an expression for $\frac{\mathrm{d}y}{\mathrm{d}x}$ .  
**Example 12**  
Find $\int \left(\frac{1}{x^2 + 25}\right)\mathrm{d}x$ .  
**Example 13**  
Find $\int \frac{3}{x^2 - 8x + 17}\mathrm{d}x.$  
**Example 14**  
The diagram shows the graph of $y = \frac{1}{16 + x^2}$ .  
[image]  
Calculate the exact value of the shaded area.  
**Example 17**  
Find $\int \left(\frac{2x}{x^2 + 2}\right)\mathrm{d}x.$  
**Example 18**  
Find $\int \frac{2x^2 - x + 6}{(x + 1)(x^2 + 2)}\mathrm{d}x.$  
**Example 19**  
Find $\int \left(\frac{\mathrm{e}^{2x}}{\mathrm{e}^{2x} + 3}\right)\mathrm{d}x.$  
**Example 26**  
Find $\int (x\ln x)\mathrm{d}x$  
**Example 27**  
Find $\int (\ln x)\mathrm{d}x$  
**Example 32**  
Find $\int \sqrt{4 - x^{2}}\mathrm{d}x$ using the substitution $x = 2$ sin $\theta$  
[image]  
**Example 37**  
Find $\int \frac{1}{(5x - 2)^2}\mathrm{d}x$ using the substitution $u = 5x - 2$  
**Example 38**  
Find $\int_{0}^{\frac{\pi}{4}}\cos 2x\sin^{3}2x\mathrm{d}x$ using the substitution $u = \sin 2x$  
**Example 39**  
[image]

---  

#### Oxford Complete **Exercise 8.1**  
1. By first expressing each rational expression using partial fractions, find  
a) $\int \left(\frac{7}{(x + 3)(2x - 1)}\right)\mathrm{d}x$  
b) $\int \left(\frac{2}{(x + 5)(x + 7)}\right)\mathrm{d}x$  
c) $\int \left(\frac{7}{(x + 5)(x - 2)}\right)\mathrm{d}x$  
d) $\int \left(\frac{2 - x}{(2x + 3)(x + 5)}\right)\mathrm{d}x$  
e) $\int \left(\frac{3 - x}{(2 + 3x)(1 - 4x)}\right)\mathrm{d}x$  
f) $\int \left(\frac{5 - 3x}{(x - 2)(3 - 2x)}\right)\mathrm{d}x$  
g) $\int_{1}^{2}\left(\frac{4}{(x + 3)(x + 5)}\right)\mathrm{d}x$  
h) $\int_{-0.5}^{0.5}\left(\frac{5}{(3 + 2x)(1 - x)}\right)\mathrm{d}x$  
i) $\int_{3}^{4}\left(\frac{5x + 5}{(x - 2)(x + 3)}\right)\mathrm{d}x.$  
2. By first expressing each rational expression using partial fractions, find  
a) $\int \left(\frac{1}{x(x - 1)^2}\right)\mathrm{d}x$  
b) $\int \left(\frac{1}{x(x + 1)^2}\right)\mathrm{d}x$  
c) $\int \left(\frac{8x + 24}{(x + 1)(x - 3)^2}\right)\mathrm{d}x$  
d) $\int_{7}^{12}\left(\frac{4 - x}{(x - 2)^2}\right)\mathrm{d}x$  
e) $\int_{4}^{5}\left(\frac{25}{(2x - 3)^2(1 + x)}\right)\mathrm{d}x$  
f) $\int_{3}^{4}\left(\frac{4}{x^3 - 4x^2 + 4x}\right)\mathrm{d}x.$  
3. By first expressing each improper fraction using partial fractions, find  
a) $\int \left(\frac{x^2 - 2x + 6}{(x + 1)(x - 2)}\right)\mathrm{d}x$  
b) $\int \left(\frac{2x^2 - x + 1}{(x + 1)(x - 3)}\right)\mathrm{d}x$  
c) $\int_{4}^{5}\left(\frac{x^2 - 3x + 10}{x^2 - x - 6}\right)\mathrm{d}x$  
d) $\int_{3}^{4}\left(\frac{10x^2 - 26x + 10}{(2x^2 - 5x)}\right)\mathrm{d}x.$  
4. By first expressing $\frac{2\sqrt{3}}{x^2 - 3}$ in partial fractions, show that $\int_{2\sqrt{5}}^{3\sqrt{5}}\left(\frac{2\sqrt{3}}{x^2 - 3}\right)\mathrm{d}x = \ln \left(\frac{3}{2}\right)$ .  
5. By first expressing $\frac{4x^2 + 9x + 4}{2x^2 + 5x + 3}$ in partial fractions, show that $\int_{0}^{1}\left(\frac{4x^2 + 9x + 4}{2x^2 + 5x + 3}\right)\mathrm{d}x = 2 + \frac{1}{2}\ln \left(\frac{5}{12}\right)$ .  
6. Find the area bounded by the graph of $y = \frac{1}{(x - 3)(x - 2)}$ , the $x$ -axis, the $y$ -axis, and the line $x = 1$ .  
7. Find the area bounded by the graph of $y = \frac{x^3 + 3x^2 - 7x}{(x + 2)(x - 1)^2}$ , the $x$ -axis, and the lines $x = 2$ and $x = 3$ .  
8. Show that the area bounded by the graph of $y = \frac{2x^2 - 4x}{(1 - 2x)(1 - x^2)}$ , the $x$ -axis, and the lines $x = -3$ and $x = -2$ is $\ln (2.1)$ .

---  
#### Oxford Complete **Exercise 8.2**  
5. Calculate the exact value of the following definite integrals.  
a) $\int_{-3}^{3}\frac{1}{9 + x^{2}}\mathrm{d}x$  
b) $\int_{3}^{3}\frac{\sqrt{3}}{3 + x^{2}}\mathrm{d}x$  
c) $\int_{0}^{5}\frac{20}{25 + x^{2}}\mathrm{d}x$  
6. Calculate the exact value of the following definite integrals.  
a) $\int_{0}^{\frac{\sqrt{3}}{2}}\frac{1}{1 + 4x^{2}}\mathrm{d}x$  
b) $\int_{-0.2}^{0.2}\frac{1}{1 + 25x^{2}}\mathrm{d}x$  
c) $\int_{\frac{1}{4}\sqrt{3}}^{\frac{\sqrt{3}}{4}}\left(\frac{8}{1 + 16x^{2}}\right)\mathrm{d}x$

---  
#### Oxford Complete **Exercise 8.3**  
1. Find the following integrals.  
a) $\int \frac{6x^2}{x^3 + 1}\mathrm{d}x$  
b) $\int \frac{\cos 2x}{1 + \sin 2x}\mathrm{d}x$  
c) $\int \frac{x - 2}{x^2 - 4x + 3}\mathrm{d}x$  
d) $\int \frac{\mathrm{e}^{3x}}{4 + 2\mathrm{e}^{3x}}\mathrm{d}x$  
e) $\int \frac{x}{x^{2} + 4}\mathrm{d}x$  
f) $\int \cot x\mathrm{d}x$  
g) $\int_{0}^{\frac{1}{6}\pi}\left(\frac{\cos 2x}{1 + \sin 2x}\right)\mathrm{d}x$  
h) $\int_{0}^{1}\left(\frac{\mathrm{e}^{2x}}{1 + \mathrm{e}^{2x}}\right)\mathrm{d}x$  
i) $\int_{0}^{1}\left(\frac{2x + 5}{(x + 3)(x + 2)}\right)\mathrm{d}x$  
2. Find $\int_{0}^{2}\frac{x - 1}{x^{2} - 2x + 2}\mathrm{d}x.$  
3. a) Show that $\frac{\mathrm{d}}{\mathrm{d}x} (\sin^2 x) = \sin 2x.$  
b) Hence find $\int \frac{1 + \sin 2x}{x + \sin^2 x}\mathrm{d}x.$  
4. a) Show that $\frac{\mathrm{d}}{\mathrm{d}x}\left(\tan x + \frac{1}{3}\tan^3 x\right) = \sec^4 x.$  
b) Hence find $\int_{\frac{\pi}{6}}^{\frac{\pi}{3}}\sec^4 x\mathrm{d}x.$  
5. a) Find $\frac{\mathrm{d}}{\mathrm{d}x} (\tan x - x).$  
b) Hence find $\int_{\frac{\pi}{6}}^{\frac{\pi}{3}}\frac{\tan^2 x}{\tan x - x}\mathrm{d}x.$  
6. Find $\int \frac{\mathrm{e}^{2x} - \mathrm{e}^{-2x}}{\mathrm{e}^{2x} + \mathrm{e}^{-2x}}\mathrm{d}x.$  
7. a) Show that $\frac{1 - \tan x}{1 + \tan x} = \frac{\cos x - \sin x}{\cos x + \sin x}.$  
b) Hence show that $\int_{0}^{\frac{\pi}{4}}\frac{1 - \tan x}{1 + \tan x}\mathrm{d}x = \frac{1}{2}\ln 2.$  
8. a) Show that $\frac{1}{1 + \mathrm{e}^x} = \frac{\mathrm{e}^{-x}}{\mathrm{e}^{-x} + 1}.$  
b) Hence find $\int_{1}^{2}\frac{1}{1 + \mathrm{e}^{x}}\mathrm{d}x,$ giving your answer correct to 3 decimal places.

---
#### Oxford Complete **Exercise 8.4**  
5. Find the area bounded by the graphs of $y = x\mathrm{e}^{- 2x}$ , the $x$ -axis, and the line $x = 2$ (as shown in the diagram).  
[image]  
6. a) Find the area bounded by the graph of $y = x\cos 2x$ the $x$ -axis, and the lines $x = 0$ and $x = \frac{\pi}{6}$  
b) Find the volume of the solid of revolution obtained by rotating this region about the $x$ -axis.  
[image]

#### Oxford Complete **Exercise 8.5**  
1. Find these indefinite integrals using the substitutions given.  
a) $\int \frac{6x}{\sqrt{2x + 1}}\mathrm{d}x;\quad u^{2} = 2x + 1$  
b) $\int x^{2}\sqrt{1 + x^{3}}\mathrm{d}x;\quad u = 1 + x^{3}$  
c) $\int \frac{1}{\sqrt{9 - x^{2}}}\mathrm{d}x;\quad x = 3\sin \theta$  
d) $\int \frac{x}{\sqrt{x + 2}}\mathrm{d}x;\quad u = x + 2$  
e) $\int \frac{1}{25 + 4x^{2}}\mathrm{d}x;\quad x = \frac{5}{2}\tan \theta$  
f) $\int \frac{2\mathrm{e}^{2x} + 1}{\mathrm{e}^{2x} + x}\mathrm{d}x;\quad u = \mathrm{e}^{2x} + x$  
2. Evaluate the following definite integrals using the substitutions given. Note that the first three are integrating the same function as parts (a) to (c) of question 1.  
a) $\int_{0}^{1}\frac{6x}{\sqrt{2x + 1}}\mathrm{d}x;\quad u^{2} = 2x + 1$  
b) $\int_{0}^{2}x^{2}\sqrt{1 + x^{3}}\mathrm{d}x;u = 1 + x^{3}$  
c) $\int_{0}^{\frac{3}{2}}\frac{1}{\sqrt{9 - x^{2}}}\mathrm{d}x;\quad x = 3\sin \theta$  
d) $\int_{0}^{\frac{\pi}{6}}\frac{\cos x}{\sqrt{1 + 2\sin x}}\mathrm{d}x;\quad u = 1 + 2\sin x$  
e) $\int_{0}^{1}(1 + x)\sqrt{2x + x^{2}}\mathrm{d}x;\quad u = 2x + x^{2}$  
f) $\int_{0}^{1}\frac{2e^{2x} + 1}{e^{2x} + x}\mathrm{d}x;\quad u = e^{2x} + x$  
g) $\int_{0}^{\frac{\pi}{3}}\sec^{2}x\tan^{5}x\mathrm{d}x;\quad u = \tan x$  
h) $\int_{0}^{\sqrt{\frac{\pi}{3}}}4x\sin (x^{2})\mathrm{d}x;\quad u = \cos x^{2}$  
3. Find $\int_{2}^{3}\frac{1}{x - \sqrt{x}}\mathrm{d}x$ using the substitution $x = u^{2}$ .  
4. Using the substitution $u = \ln x$ , find the area bounded by the graph of $y = \frac{(\ln x)^{4}}{x}$ , the $x$ -axis, and the lines $x = 1$ and $x = e$ .  
5. Using the substitution $u = 2x + 1$ , find the area bounded by the graph of $y = \frac{x}{\sqrt{2x + 1}}$ , the $x$ -axis, and the line $x = 2$ (as shown in the diagram).  
[image]  
6. Find the area bounded by the graph of $y = 2x\cos \left(x^{2} + \frac{\pi}{6}\right)$ , the $x$ -axis, and the lines $x = 0$ and $x = \sqrt{\frac{\pi}{6}}$ (as shown in the diagram).  
[image]  

---
**Summary exercise 8**  
1. By first expressing each rational expression using partial fractions, find  
a) $\int \left(\frac{5}{(x - 2)(x + 3)}\right)\mathrm{d}x$  
b) $\int \left(\frac{5x + 2}{(2x - 1)(x + 4)}\right)\mathrm{d}x$  
c) $\int \left(\frac{x - 2}{x(x + 1)^2}\right)\mathrm{d}x$  
d) $\int \left(\frac{x^2 - 3x - 1}{(2x - 1)(x + 1)^2}\right)\mathrm{d}x$  
e) $\int \left(\frac{3x^2 - 5x}{x^2 - 1}\right)\mathrm{d}x.$  
**EXAM-STYLE QUESTION**  
2. Show that $\frac{4}{x(x^2 + 4)} = \frac{1}{x} - \frac{x}{x^2 + 4}$ . Using the substitution $u = x^2 + 4$ , find $\int \frac{4}{x(x^2 + 4)}\mathrm{d}x$ .  
3. Find the following integrals.  
a) $\int \frac{4x^3}{x^4 + 6}\mathrm{d}x$  
b) $\int \frac{\cos 3x}{3 - 2\sin 3x}\mathrm{d}x$  
c) $\int \frac{3x - 2}{3x^2 - 4x + 7}\mathrm{d}x$  
d) $\int \frac{e^{5x}}{6 - 5e^{5x}}\mathrm{d}x$  
e) $\int \frac{2x}{x^2 + 9}\mathrm{d}x$  
f) $\int \frac{x^2}{x^3 + 10}\mathrm{d}x$  
g) $\int_0^{\frac{1}{6}\pi}\left(\frac{\cos 3x}{2 + \sin 3x}\right)\mathrm{d}x$  
h) $\int_0^1\left(\frac{e^{3x}}{2 + e^{3x}}\right)\mathrm{d}x$  
i) $\int_0^1\left(\frac{2x + 3}{(x + 1)(x + 2)}\right)\mathrm{d}x$  
4. Find these integrals using integration by parts.  
a) $\int x\mathrm{e}^{3x}\mathrm{d}x$  
b) $\int 4x\cos 2x\mathrm{d}x$  
c) $\int (2x - 3)\mathrm{e}^{x}\mathrm{d}x$  
d) $\int (x^{2} - x + 3)\cos 3x\mathrm{d}x$  
e) $\int_{0}^{1}x^{2}\mathrm{e}^{x - 1}\mathrm{d}x$  
f) $\int_{1}^{e}(x^{2}\ln 4x)\mathrm{d}x$  
5. Find these integrals using the substitutions given.  
a) $\int \frac{6x}{\sqrt{3x - 1}}\mathrm{d}x;\quad u^{2} = 3x - 1$  
b) $\int x^{3}\sqrt{4 + x^{4}}\mathrm{d}x;\quad u = 4 + x^{4}$  
c) $\int \frac{1}{\sqrt{25 - 16x^2}}\mathrm{d}x;\quad x = \frac{5}{4}\sin \theta$  
d) $\int \frac{x}{\sqrt{2x + 7}}\mathrm{d}x;\quad u = 2x + 7$  
e) $\int_{0}^{1}(1 + 6x)\sqrt{x + 3x^{2}}\mathrm{d}x;\quad u = x + 3x^{2}$  
f) $\int_{0}^{1}\frac{\mathrm{e}^{2x} + x}{\mathrm{e}^{2x} + x^{2}}\mathrm{d}x;\quad u = \mathrm{e}^{2x} + x^{2}$  
g) $\int_{0}^{\frac{\pi}{4}}\sec^{2}x\tan^{6}x\mathrm{d}x;\quad u = \tan x$  
h) $\int_{0}^{\frac{\pi}{6}}4x\cos \left(x^{2} + \frac{\pi}{6}\right)\mathrm{d}x;u = \sin \left(x^{2} + \frac{\pi}{6}\right)$  
**EXAM-STYLE QUESTIONS**  
6. The diagram shows the area trapped between the graphs of $y = \frac{x}{(x - 4)^2}$ and $y = x$ . Show that the graphs intersect at $(0, 0)$ and $(3, 3)$ and that the area is $\frac{3}{2} + \ln 4$ .  
[image]  
7. Calculate the exact value of $$\int_{0}^{\frac{\sqrt{3}}{2}}\frac{1}{9 + 4x^{2}}\mathrm{d}x.$$  
8. Calculate the exact value of $$\int_{-3}^{-1}\frac{3}{x^2 + 6x + 13}\mathrm{d}x.$$  
9. Use the substitution $u = 1 + 8\tan x$ to find the exact value of $$\int_{0}^{\frac{1}{4}\pi}\frac{\sqrt{(1 + 8\tan x)}}{\cos^2x}\mathrm{d}x.$$  
[image]  


