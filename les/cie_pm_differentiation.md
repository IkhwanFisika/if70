# PM1 - Differentiation


### A. Core Concept: What is Differentiation?

Differentiation is a branch of calculus that deals with the **rate of change** of one quantity with respect to another. At its heart is the **derivative**.

- **The Derivative ($f'(x)$ or $\frac{dy}{dx}$):** A measure of how a function's output value changes as its input changes. Geometrically, it represents the **gradient of the tangent line** to the curve at a specific point.
- **The Limit Definition (First Principles):** The derivative is formally defined as the limit of the slope of a chord between two points as the distance between them approaches zero.
    $$f'(x) = \lim_{h \to 0} \frac{f(x+h) - f(x)}{h}$$
    If this limit exists, $f$ is said to be **differentiable** at $x$.

---

### B. Fundamental Rules of Differentiation

#### 1. The Power Rule
If $f(x) = ax^n$, then $f'(x) = na x^{n-1}$.

#### 2. The Constant Rule
If $f(x) = c$ (a constant), then $f'(x) = 0$.

#### 3. Constant Multiple Rule
If $g(x) = c \cdot f(x)$, then $g'(x) = c \cdot f'(x)$.

#### 4. Sum and Difference Rule
If $h(x) = f(x) \pm g(x)$, then $h'(x) = f'(x) \pm g'(x)$.

#### 5. The Chain Rule
If $h(x) = f(g(x))$, then $h'(x) = f'(g(x)) \cdot g'(x)$.
- *Alternative Notation:*
  - If $y = f(u)$ and $u = g(x)$, then $\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx}$.
  - or If $y=au^n$ where $u=f(x)$, then $y'=nau^{n-1} \cdot u'$



---


### C. Applications of Differentiation

This is where the power of calculus is truly revealed.

#### 1. Tangents and Normals
- **Tangent Line:** The gradient of tangent $m_t = f'(x_0)$.
  equation of tanget line: $y - y_0 = m_t(x - x_0)$
- **Normal Line:** $m_n = -\frac{1}{m_t}$ .

#### 2. Increasing and Decreasing Functions
For a function $f(x)$ on an interval:
- **Increasing:** if $f'(x) > 0$ (the graph is rising).
- **Decreasing:** if $f'(x) < 0$ (the graph is falling).
- **Stationary Point (Critical Point):** if $f'(x) = 0$.

#### 3. Stationary Points and Curve Sketching
Points where $f'(x) = 0$ are potential local maxima or minima. Their nature is determined by the **Second Derivative ($f''(x)$)** or a sign chart of $f'(x)$.

- **Local Maximum:** $f'(x) = 0$ and $f''(x) < 0$ (curve is concave down).
- **Local Minimum:** $f'(x) = 0$ and $f''(x) > 0$ (curve is concave up).
- **Point of Inflection:** $f''(x) = 0$ and changes sign. This is where the curve changes its concavity. (Note: $f'(x)$ may or may not be zero).

#### 4. Optimization
- change the function into one variable by substituting other known equation
- set $y'= 0$ to the to be optimized (max/min) function, get $x$
- substitute to $y$ to get **the max/min value**

#### 5. Rates of Change
- **Kinematics:** If $s(t)$ is position, then:
    - Velocity, $v(t) = s'(t)$.
    - Acceleration, $a(t) = v'(t) = s''(t)$.
- **Related Rates:** Finding how the rate of change of one quantity is related to the rate of change of another (e.g., how fast the water level rises as a balloon is filled).

---

### VI. Key Theorems

- **Rolle's Theorem:** If a function is continuous on $[a, b]$, differentiable on $(a, b)$, and $f(a) = f(b)$, then there exists at least one $c$ in $(a, b)$ such that $f'(c) = 0$.
- **Mean Value Theorem:** If a function is continuous on $[a, b]$ and differentiable on $(a, b)$, then there exists at least one $c$ in $(a, b)$ such that $f'(c) = \frac{f(b)-f(a)}{b-a}$. (The instantaneous rate of change equals the average rate of change at some point).
- **L'Hôpital's Rule:** A method for evaluating limits of indeterminate forms (like $\frac{0}{0}$ or $\frac{\infty}{\infty}$). It states that for such forms:
  $$\lim_{x \to c} \frac{f(x)}{g(x)} = \lim_{x \to c} \frac{f'(x)}{g'(x)}$$ (provided the right-hand limit exists).

  Here is a focused summary on the differentiation of parametric functions, building on the foundation of the previous summary.



# Drill PM1 Differentiation


#### Oxford AL **Exercise 8.4**

**1. Find the derived function in each case.**


a) $\mathrm{f}(x) = x^{7} + x^{3}$

b) $\mathrm{f}(x) = 6x^{8} - 4x$

c) $\mathrm{f}(x) = 3x^{2} + 5x - 9$

d) $\mathrm{f}(x) = (3x + 7)(2x - 9)$

e) $\mathrm{f}(x) = x^{-4}(x^{2} + x^{6})$

f) $\mathrm{f}(x) = 5x^{2}(3x^{2} - 7x - 2)$

g) $\mathrm{f}(x) = \frac{x^{5} + x^{8}}{x^{2}}$

h) $\mathrm{f}(x) = \frac{9x^{7} - 2x^{5}}{x^{3}}$

i) $\mathrm{f}(x) = \frac{x^{7} + 2x}{x^{5}}$

j) $\mathrm{f}(x) = (5 - x)^{2}$

**2. Find $\frac{\mathrm{d}y}{\mathrm{d}x}$ in each case.**


a) $y = x^{4} + \frac{1}{x} -\frac{3}{\sqrt{x}}$

b) $y = \frac{10x^{6} - 3x^{5}}{2x^{2}}$

c) $y = \frac{7x + 3 + \sqrt{x}}{x}$

d) $y = \left(\sqrt{x} +\frac{1}{\sqrt{x}}\right)^{2}$

e) $y = 2x^{3}(1 - 4x - 8x^{2})$

f) $y = (\sqrt{x} +3)(2\sqrt{x} +5)$

g) $y = \frac{5\sqrt{x} - 3x}{\sqrt{x}}$

h) $y = x^{-\frac{1}{2}} + 4x^{-\frac{3}{2}} - x^{\frac{1}{2}}$

i) $y = \frac{(2x - 3)^{2}}{x^{2}}$

j) $y = \frac{4}{x} +\frac{3}{x^{2}}$

**3. Find**


a) $\frac{\mathrm{d}}{\mathrm{d}x}\left(3x^{4} - 2x^{3} + 5x^{2} - x - 1\right)$

b) $\frac{\mathrm{d}}{\mathrm{d}x}\left(x^{\frac{2}{3}} + \sqrt{x}\right)$

c) $\frac{\mathrm{d}}{\mathrm{d}x} 4\sqrt{x} (3\sqrt{x} +x)$

d) $\frac{\mathrm{d}}{\mathrm{d}x}\left(\frac{7x - 4 - 2x^{5}}{x^{3}}\right)$

e) $\frac{\mathrm{d}}{\mathrm{d}x}\left(x^{2} + 7\right)^{2}$

f) $\frac{\mathrm{d}}{\mathrm{d}x}\left(ax^{2} + bx + c\right)$

g) $\frac{\mathrm{d}}{\mathrm{d}x}\sqrt{x} (x^{2} + 8)$

h) $\frac{\mathrm{d}}{\mathrm{d}x}\left(\frac{12x^{2} - x^{3}}{3x^{5}}\right)$

**4. Find $\mathrm{f}^{\prime}(x)$ in each case.**


a) $\mathrm{f}(x) = \frac{6}{\sqrt[3]{x}} +4\sqrt{x}$

b) $\mathrm{f}(x) = \frac{1}{3} x^{\frac{3}{2}} - \frac{1}{5} x^{\frac{5}{2}}$

c) $\mathrm{f}(x) = x(x - 2)^2$

d) $\mathrm{f}(x) = \frac{x + 3}{\sqrt{x}}$

e) $\mathrm{f}(x) = \frac{12x^3 - 5x}{3x^4}$

f) $\mathrm{f}(x) = (\sqrt{x} - 4)^2$

g) $\mathrm{f}(x) = 5x - \frac{1}{2\sqrt{x}}$

h) $\mathrm{f}(x) = \frac{(\sqrt{x} - x)^2}{\sqrt{x}}$

---
#### Oxford AL **Exercise 8.5 : ChainRule**

**1. Find $\frac{dy}{dx}$ in each case.**


a) $y = \sqrt{4x - 1}$

b) $y = (x^2 + 4)^5$

c) $y = \frac{1}{(1 - x)^3}$

d) $y = \frac{5}{2x + 7}$

e) $y = \frac{3}{\sqrt{5 + 2x}}$

f) $y = \frac{2}{3 - 4x}$

g) $y = \frac{1}{\sqrt[3]{4x - 3}}$

h) $y = \sqrt{5 + 3x^3}$

i) $y = \frac{6}{2x^2 + 3x}$

j) $y = \frac{1}{2(1 - 3x^2)^4}$

**2. Differentiate each expression with respect to $x$.**


a) $\frac{1}{9x + 8}$

b) $\sqrt{8 - 7x}$

c) $\sqrt{2x^4 + 7}$

d) $\frac{3}{\sqrt{3 - x^2}}$

e) $\frac{1}{(4x - 5)^4}$

f) $\frac{2}{\sqrt[4]{5 + 3x}}$

g) $(3x^2 - 2)^4$

h) $\sqrt{5x - 2x^2}$

i) $\frac{1}{x(5 - 3x^2)}$

j) $\frac{1}{1 + \sqrt{x}}$  

---
#### Oxford AL **Exercise 8.6 : Gradient of Tangent**

1. Find the gradient of the tangent to the curve $y = 5x^{3} + 3x^{2} - x + 4$ at the point (1, 11).
2. Find the gradient of the tangent to the curve $y = x^{3} - 8x^{2} - 7$ where $x = -2$ .
3. Find the coordinates of the points on the curve with equation $y = 2x^{3} + 3x^{2} - 12x$ where the gradient is 24.
4. Find the gradient of the tangent to the curve $y = 2x^{2} + 3x + 1$ at each of the points where the curve meets the line $y = 4(x + 1)$ .
5. Find the gradient of the tangent to the curve $y = (2x + 3)^{2}$ at the point where $x = 0$ .
6. Find the gradient of the tangent to the curve $y = (x + 2)(x - 3)$ at each of the points where the curve crosses the $x$ -axis.
7. Find the coordinates of the points on the curve $y = 2x^{3} - 15x + 7$ where the gradient is 9.
8. Find the values of $x$ where the tangents to the curve $y = x^{3} - x^{2} - 42x - 7$ are parallel to the line $y = -2x$ .
9. Find the coordinates of the points on the curve $y = x^{4} + 2x^{3}$ where the gradient is parallel to the $x$ -axis.
10. The gradient of the tangent to the curve $y = 2x^{3} + ax^{2} - x + 3$ at the point $x = 1$ is 3. Find the value of $a$ .
11. Find the $y$ - coordinate and the gradient of $y = (x - 3)^2$ when $x = -2$ .
12. Find the gradient of the tangent to the curve $y = \frac{(4x - 1)^2}{x^2}$ at the point $(-1, 25)$ .
13. Find the coordinates of the points on the curve $y = 6 + 9x - 3x^2 - x^3$ where the gradient is 9.
14. Find the gradient of the tangent to the curve $y = (\sqrt{x} + 3)(3\sqrt{x} - 5)$ at the point where $x = 1$ .
15. Find the coordinates of the point on the curve $y = \frac{2x - 5 + \sqrt{x}}{x}$ where the gradient is zero.
---
#### Oxford AL **Exercise 8.7 : Second Derivative**

1. Find $\frac{\mathrm{d}^2y}{\mathrm{d}x^2}$ in each case.  
a) $y = 2x^2 +4x^3$  
b) $y = 3x^9 -7x$  
c) $y = (2x + 1)(x - 8)$  
d) $y = x^{-3}(x + 5x^7)$  
e) $y = 6x^3 (2x^2 -x + 1)$  
f) $y = (9 - x)^5$  
g) $y = \frac{x^5 + x^4}{x^2}$  
h) $y = \frac{24x^7 - 9x^4}{3x^3}$  
i) $y = 2x^3 + \frac{3}{x}$  
  
2. Find $\mathrm{f}^{\prime \prime}(x)$ in each case.  
a) $\mathrm{f}(x) = \frac{8x^2 - x}{2x^3}$  
b) $\mathrm{f}(x) = \frac{3x - 5 + \sqrt{x}}{x}$  
c) $\mathrm{f}(x) = \frac{7\sqrt{x} - 8x}{\sqrt{x}}$  
d) $\mathrm{f}(x) = (\sqrt{x} - 1)(4\sqrt{x} + 3)$  
e) $\mathrm{f}(x) = 8x^{-\frac{1}{4}}$  
f) $\mathrm{f}(x) = \sqrt{4x - 3}$  
g) $\mathrm{f}(x) = \frac{3}{x^4} +\frac{6}{x^2}$  
h) $\mathrm{f}(x) = \frac{x^{12}}{x^4}$  
i) $\mathrm{f}(x) = \frac{12}{\sqrt{x}}$  

3. Given that $y = 8x^3 - 3x + \frac{4}{x}$ , find the value of $\frac{\mathrm{d}^2y}{\mathrm{d}x^2}$ when $x = -2$ .
4. Given that $\mathrm{f}(x) = \frac{4}{\sqrt{3x - 2}}$ find the value of $\mathrm{f}^{\prime \prime}(2)$
5. Find $\frac{\mathrm{d}^2y}{\mathrm{dx}^2}$ when $\frac{\mathrm{dy}}{\mathrm{dx}} = 1 - 7x^2$
6. Given that $y = 6x^3 - 2x^2$ , show that $\frac{\mathrm{d}^2y}{\mathrm{dx}^2} - 4\frac{\mathrm{dy}}{\mathrm{dx}} + 20 = 4(4 + 13x - 18x^2)$
7. Given that $\mathrm{f}^{\prime}(x) = \frac{5}{(5 - 2x)^8}$ find $\mathrm{f}^{\prime \prime}(x)$
8. Given that $\mathrm{f}(x) = 2x^4 - 3x^3 - x^2$ find the value of
a) $\mathrm{f}^{\prime}(3)$
b) $\mathrm{f}^{\prime \prime}(-2)$
c) $\frac{1}{\mathrm{f}(1)}$
9. Given that $y = ax^4 - 3x^2$ and $\frac{\mathrm{d}^2y}{\mathrm{dx}^2} = 42$ when $x = 2$ , determine the value of $a$
10. Given that $\frac{\mathrm{dy}}{\mathrm{dx}} = \frac{6x - 1}{2x^4}$ find the value of $\frac{\mathrm{d}^2y}{\mathrm{dx}^2}$ when $x = -1$
---

#### Oxford AL **Exercise 8.8 : Tangent and Normal**

1. Find the equation of the tangent to the curve  
a) $y = x^{3} - 6x + 3$ at the point $(2, - 1)$  
b) $y = 2x^{4} + 9x^{3} + x$ when $x = -2$  
c) $y = (x - 7)(x + 4)$ at the point when $x = 1$  
d) $y = \frac{x^{4} - 3x^{3}}{x}$ at the point $(1, - 2)$  
e) $y = \sqrt{x} (x^{2} - 1)$ at the point $(1, 16)$  
f) $y = \sqrt[3]{x}$ at the point when $x = 8$ .  

2. Find the equation of the normal to the curve\
a) $y = 7x^{2} - 8x + 9$ when $x = 2$\
b) $y = 5x^{3} + x^{2} - 2$ at the point $(-1, -6)$\
c) $y = (3x + 10)^{2}$ at the point $(-3,1)$\
d) $y = 2x^{2}(6 - x)$ when $x = 5$\
e) $y = \frac{6x^{2} - x^{3}}{2x^{4}}$ when $x = -2$\
f) $y = \frac{3}{\sqrt{2x + 1}}$ at the point $(4,1)$ .

3. The curve $y = 2x^{3} + 6x - 5$ crosses the $y$ -axis at the point $P$ . Find the equation of the tangent to the curve at the point $P$ .

4. Find the equation of the tangent and the normal to the curve $y = 2x^{3} - x$ at the point where $x = 2$ .

5. Find the equations of the tangents to the curve $y = x^{2} - x - 12$ at each of the points where the curve crosses the $x$ -axis.

6. a) Find the coordinates of the points on the curve $y = x^{2} - x + 2$ at which the gradients are 3 and $-3$ .\
b) Find the equations of the tangents at these points.\
c) Show that these tangents intersect at the point $\left(\frac{1}{2}, -\frac{1}{2}\right)$ .

7. a) Find the equation of the tangent to the curve $y = 5 - 2x - x^{2}$ at the point $(1, 2)$ .
b) This tangent meets the $x$ -axis at $P$ and the $y$ -axis at $Q$ . Find the area of triangle $OPQ$ .

8. The curve $y = (5 - x)(2 + x)$ crosses the $x$ -axis at points $A$ and $B$ . The tangents at the points $A$ and $B$ meet at point $C$ . Find the coordinates of $C$ .

9. The normal to the curve $y = \sqrt{x} +\sqrt[3]{x}$ at the point where $x = 1$ meets the axes at $(p, 0)$ and $(0, q)$ . Find $p$ and $q$ .

10. The normals at the points $(0, 0)$ and $(1, 2)$ to the curve $y = x + x^{3}$ meet at point $P$ . Find the coordinates of $P$ .
---
#### Oxford AL **EXAM-STYLE QUESTIONS**

1. Find $\frac{\mathrm{d}y}{\mathrm{d}x}$ when
a) $y = x(x + 3)^2$\
b) $y = 6\sqrt{x} +\frac{3}{\sqrt[3]{x}}$\
c) $y = \frac{2x^6 - 8x^3}{2x^2}$\
d) $y = \sqrt{3 - 2x^2}$  

2. Find $f^{\prime}(x)$ when  
a. $f(x)=\frac{9\sqrt[3]{x^{2}}+\sqrt{x}}{x}$  
b. $f(x)=\frac{1}{2}x^{3}\Big(x-4x^{2}+\frac{6}{x}\Big)$  
c. $f(x)=\frac{3}{(5x-2)^{2}}$  
d. $f(x)=\Big(\sqrt{x}-\frac{1}{\sqrt{x}}\Big)^{2}.$  

3. Find the gradient of the tangent to the curve $y = 5 - 3x + x^3$ at the point (1, 3).

4. Find the equation of the normal to the curve $y = \sqrt{x} (\sqrt{x} -2)$ at the point where $x = 9$ .

5. Given that $y = 3x^3 -ax^2$ and $\frac{\mathrm{d}^2y}{\mathrm{d}x^2} = 54$ when $x = 2$ , work out the value of $a$ .

6. Given that $y = 4x^2 -x^3$ , show that  
    $\frac{\mathrm{d}^2y}{\mathrm{d}x^2} +\frac{\mathrm{d}y}{\mathrm{d}x} -3y = 8 + 2x -15x^2 +3x^3.$

7. The curve $y = \sqrt{9 - 4x}$ cuts the $y$ -axis at the point $P$ . Find the equation of the tangent to the curve at the point $P$ .

8. Find the points on the curve $y = x^3 +3x^2 -4$ where the tangent is parallel to the line $y = 9x - 2$ .

9. Find the equation of the normal to the curve $y = 3x^2$ at the point $(t, 3t^2)$ .

10. a) Find the equation of the tangent to the curve $y = x(2 - x)$ at the origin.\
b) Find a point on the curve where the tangent is perpendicular to the tangent at the origin.\

11. Differentiate $\frac{7x\sqrt{x} - 8x}{\sqrt{x}}$ with respect to $x$ .

12. If $\frac{\mathrm{d}y}{\mathrm{d}x} = \frac{x}{(5 - 3x^2)^6}$ , show that $\frac{\mathrm{d}^2y}{\mathrm{d}x^2} = \frac{5 + 33x^2}{(5 - 3x^2)^7}$ .

13. Find the equations of the tangents to the curve $y = x^3 -6x^2 +12x + 2$ which are parallel to the line $y = 5 + 3x$ .

14. a) Find the equations of the tangent and the normal to the curve $y = 4\sqrt{x}$ at the point $P(9, 12)$ .
The tangent and normal to the curve at $P$ cut the $x$ - axis at $Q$ and $R$ .  
b) Find the area of triangle $PQR$ .

15. Given that $\mathrm{f}(x) = 3x^4 +5x^3 -6x^2$ , find the value of  
a. $f^{\prime}(-2)\qquad$  
b. $f^{\prime \prime}(\frac{1}{2})$  
c. $\frac{24}{\mathrm{~f}(-1)}.$

16. Given that $y = ax^2 +3x - a^2$ has a gradient of 5 when $x = -2$ , find the value of $y$ when $x = -3$ .
---
#### Oxford AL **Exercise 9.1 : Increasing/Decreasing Function**

1. For each of the following functions find the range of values of $x$ for which $\mathrm{f}(x)$ is increasing.  
a) $\mathrm{f}(x) = x^{2} - 6x$  
b) $\mathrm{f}(x) = 8 + 3x - 2x^{2}$  
c) $\mathrm{f}(x) = x^{3} - 48x + 2$  
d) $\mathrm{f}(x) = 2x^{3} - 9x^{2} + 12x - 3$  
e) $\mathrm{f}(x) = 3x^{2} - 2x^{3}$  
f) $\mathrm{f}(x) = 3x^{3} - 9x + 1$  
  
2. Find the range of values of $x$ for which $y$ is decreasing.  
a) $y = x^{2} - x + 2$  
b) $y = 9 - 2x - x^{2}$  
c) $y = 3x^{2} + 6x + 5$  
d) $y = x^{3} - 5x^{2} + 3x - 4$  
e) $y = 2x^{3} - 54x - 1$  
f) $y = x^{3} - 6x^{2} - 15x + 7$  
  
3. Find the range of values of $x$ for which $y$ is increasing.  
a) $y = 5x^{2} + 5x$  
b) $y = 3 + 16x - 4x^{2}$  
c) $y = x^{3} - 3x - 4$  
d) $y = 6x^{2} - 6x - 7$  
e) $y = 4 - 12x + 9x^{2} - 2x^{3}$  
f) $y = 3x^{3} - 18x^{2} + 18x - 2$  
  
4. Find the range of values of $x$ for which $f(x)$ is decreasing.  
a) $f(x) = 9x^{2} - 2x^{3}$  
b) $f(x) = 2 - 5x - 10x^{2}$  
c) $f(x) = x^{3} + 6x^{2} + 12x - 1$  
d) $f(x) = 5x^{3} - 15x - 3$  
e) $f(x) = 4x^{2} - 12x^{3}$  
f) $f(x) = x(10 - 2x)(16 - 2x)$  
---
#### Oxford AL **Exercise 9.2 : Stationary Points**

1. For each of the following functions, find the coordinates of the stationary points and determine their nature.  
a) $y = x^{2} - 2x + 5$  
b) $y = 3 + x - x^{2}$  
c) $y = 2x^{2} + 4x - 3$  
d) $y = x^{3} - 5x^{2} + 3x + 1$  
e) $y = x^{4} - 2x^{2} - 2$  
f) $y = 9 + 24x - 2x^{3}$  
  
2. For each of the following functions, find the coordinates of the stationary points and determine their nature. Sketch the curve.  
a) $y = x^{2} - 8x + 12$  
b) $y = x^{2} - x^{3}$  
c) $y = 4x^{3} - x^{4}$  
d) $y = x^{2} - 2x + 7$  
e) $y = x^{3}(x - 2)$  
f) $y = 20 + 15x - x^{2} - \frac{x^{3}}{3}$  
  
3. For each of the following functions, find the coordinates of the stationary points and determine their nature.  
a) $\mathrm{f}(x) = 2x^{3} - 3x^{2}$  
b) $\mathrm{f}(x) = 2x^{3} - 9x^{2} + 12x + 4$  
c) $\mathrm{f}(x) = x + \frac{1}{x},x\neq 0$  
d) $\mathrm{f}(x) = \frac{x^{2} + 9}{2x}$  
  
4. Find the coordinates of the stationary points of the curve $y = x^{\frac{1}{2}}\left(\frac{3}{4} -x\right)$ and determine their nature.  
  
5. Find the coordinates of the stationary points of the curve $y = (3x - 2)^{3} - 9x$ and determine their nature.  
  
6. Find the coordinates of the stationary points of the curve $y = \frac{1 + 54x^{3}}{x^{2}}$ and determine their nature.  
  
7. Find the coordinates of the stationary points of the curve $y = x^{4} - 2x^{3} + x^{2} - 2$ and determine their nature. Sketch the curve.  
  
8. Show that the curve $y = 3x^{3} - 5x^{2} + 3x + 4$ has no stationary points.  
  
9. $\mathrm{f}(x) = 3x^{2} + 2x + 5$ $\mathrm{g}(x) = x^{3} - 4x^{2} - 3x + 6$  
a) Show that there is one value of $x$ for which $\mathrm{f}(x)$ and $\mathrm{g}(x)$ both have the same stationary value.  
b) On the same axes sketch the graphs of $\mathrm{f}(x)$ and $\mathrm{g}(x)$  
  
10. The curve $y = ax^{2} + bx + c$ has a minimum when $x = \frac{1}{2}$ and passes through the points (2, 0) and (1, -3). Find the values of $a, b$ and $c$ .  
---
#### Oxford AL **Exercise 9.3 : Optimization**  
  
1. A farmer has a rectangular piece of land for pigs. One of the sides of the rectangle is a wall. The other three sides have fencing. The fencing is $80\mathrm{m}$ in length. Find the maximum possible area of this rectangular piece of land.  
  
2. An open box with a square base has a total surface area of $300\mathrm{cm}^2$ Find the greatest possible volume of the box.  
  
3. Fig. 1 shows a square sheet of metal of side $40\mathrm{cm}$ . A square $x\mathrm{cm}$ by $x\mathrm{cm}$ is cut from each corner. The sides are then bent upwards to form an open box as shown in Fig. 2. Find the value of $x$ that maximises the volume of the box.  
  
4. Given that $x + y = 3$ , find the least possible value of $x^{2} + 14y$ .  
  
5. The diagram shows a sporting track made up of a rectangle with semicircles at each end. The rectangle has dimensions $p$ metres by $2r$ metres where $r$ is the radius of each semicircle. The perimeter of the track is $1400\mathrm{m}$ . The track has a maximum area for this perimeter. Find the value of $p$ and the value of $r$ .  
  
6. Find the maximum possible value of $x^{2}y$ if $x + 2y = 8$ .  
  
7. A cylinder with an open top has radius $r\mathrm{cm}$ and a volume of $512\pi \mathrm{cm}^3$ .  
a) Write down the surface area of the cylinder in terms of $r$ .  
b) Find the minimum surface area. Leave your answer in terms of $\pi$ .  
c) Find the value of $r$ and the height of the cylinder.  
  
8. A sector of a circle, radius $r$ has a perimeter of $20\mathrm{cm}$ . The angle of the sector is $\theta$ radians and the area is $A\mathrm{cm}^2$ . Find the maximum possible area of the sector.  
  
9. A tank in the shape of a right circular cylinder with no top has a surface area of $3\pi \mathrm{m}^2$ . What height and base radius will maximise the volume of the cylinder?  
  
10. The diagram shows a semicircle on top of a rectangle. The perimeter of the shape is $20\mathrm{cm}$ . Find the maximum area of the rectangle.  
  
11. $W = pq$ and $2p + 5q = 100$ . Find the maximum value of $W$ .  
  
12. An open tank made of metal is in the shape of a cuboid with a square base. The volume of the tank is $13.5\mathrm{m}^3$ . Find the dimensions of the tank that uses as little metal as possible.  
  
#### Oxford AL **Exercise 9.4 : Rate**  
  
1. A spherical balloon is being blown up so that its radius increases at a rate of $0.4 \mathrm{~cm} \mathrm{~s}^{-1}$ . Find the rate of increase of the surface area of the balloon when the radius is $20 \mathrm{~cm}$ .  
  
2. The radius of a circular ink blob is increasing at a rate of $5 \mathrm{~cm} \mathrm{~s}^{-1}$ . Find the exact rate of increase of the circumference of the circle.  
  
3. The side of a cube is increasing at $0.2 \mathrm{~cm} \mathrm{~s}^{-1}$ . Find the rate of increase of the volume when the length of the side is $4 \mathrm{~cm}$ .  
  
4. A spherical balloon is inflated so that its volume increases at a rate of $50 \mathrm{~cm} \mathrm{~s}^{-1}$ . Find the rate of increase of the radius of the balloon when the radius is $12 \mathrm{~cm}$ .  
  
5. The side of a cube is decreasing at a rate of $0.4 \mathrm{~cm} \mathrm{~s}^{-1}$ . Find the rate of decrease of the surface area when the length of the side is $3 \mathrm{~cm}$ .  
  
6. A cone has a height of $7\mathrm{cm}$ . The radius of the base of the cone is increasing at a rate of $8\mathrm{cm}\mathrm{s}^{- 1}$ . Find the rate of change of the volume of the cone when the base radius is $5\mathrm{cm}$ .  
  
7. The volume of a cube is increasing at the rate of $12\mathrm{cm}^3\mathrm{s}^{- 1}$ . Find the rate of increase of the surface area of the cube when the side of the cube is $7\mathrm{cm}$ .  
  
8. The surface area of a cube is increasing at $0.3\mathrm{m}^2\mathrm{s}^{- 1}$ . Find the rate of increase of the volume of the cube when the length of the side is $5\mathrm{m}$ .  
  
9. A cuboid has a square base. The height of the cuboid is twice the length of the side of the base. The surface area of the cuboid is increasing at a rate of $10 \mathrm{cm}^2\mathrm{s}^{- 1}$ . Find the rate of increase of the volume of the cuboid when the height of the cuboid is $12 \mathrm{cm}$ .  
  
10. Paint is poured onto a table, forming a circle which increases at a rate of $2.5 \mathrm{cm}^2\mathrm{s}^{- 1}$ . Find the rate the radius is increasing when the area of the circle is $20\pi \mathrm{cm}^2$ .  
  
#### Oxford AL **Summary Exercise 9 Differentiation**  
  
1. Find the values of $x$ for which $y = 3x^{2} - 2x + 7$ is an increasing function.  
  
2. Find the range of values of $x$ for which $y = 3x^{2} - 2x^{3}$ is decreasing.  
  
3. Find the range of values of $x$ for which $f(x) = x^{3} + x^{2} - x + 5$ is decreasing.  
  
4. $f(x) = x^{2} + px + 3$ $f(x)$ has a turning point when $x = -3$ . Find the value of $p$ .  
  
5. Find the turning point of the curve $y = \frac{x^{3} + 2}{x}$ and determine its nature.  
  
6. a) Find the coordinates of the turning points on the curve $y = 2x^{3} + 3x^{2} - 12x + 6$ and determine their nature.  
b) Find the range of values of $x$ for which $y$ is increasing.  
c) Sketch the graph of $y$ .  
  
7. Find the coordinates of the stationary points of the curve $y = (x + 1)(2x - 1)^{2}$ and determine their nature. Sketch the curve.  
  
8. The diagram shows a shape made from a rectangle and a semicircle. $y + \frac{1}{4} x(\pi + 2) = 25$  
a) Show that the area $A$ square metres of the shape is given by $A = 100x - 2x^{2} - \frac{1}{2}\pi x^{2}$ .  
b) Find the maximum value of $A$ and explain why this value is a maximum.  
  
9. Triangle $ABC$ is a right- angle triangle with angle $ACB = 90^{\circ}$ . $AC + BC = 6$ cm. Show that the maximum area of the triangle is $4.5$ cm².  
  
10. The diagram shows a cuboid with a square base. Find the maximum volume of the cuboid if the sum of the height and the length of the base is $12$  cm.  
  
11. A solid cylinder with radius $x$ cm has a volume of $1000$ cm³.  
a) Show that the total surface area of the cylinder is given by $A = 2\pi x^{2} + \frac{2000}{x}$ .  
b) Find the minimum total surface area. Give your answer to 1 decimal place.  
  
12. The curve with equation $y = (2x + 1)(x^{2} - k)$ has a stationary point where $x = 1$ .  
a) Find $k$ .  
b) Find the coordinates of the stationary points and determine their nature.  
  
13. The radius of a sphere is increasing at a rate of $2$ m s⁻¹. Find the exact rate of increase of the volume when the radius is equal to $4$ m.  
  
14. The volume of a cube is increasing at the rate of $10$ cm³ s⁻¹. Find the rate of increase of the surface area of the cube when the side of the cube is $8$ cm.  
  
15. A spherical balloon is being blown up so that its volume increases at a constant rate of $1.5$ cm³ s⁻¹. Find the rate of increase of the radius of the balloon when the volume is $56$ cm³.  
  
16. A sector of a circle, radius $r \mathrm{cm}$ , has an area of $100 \mathrm{cm}^2$ . Find the minimum value for the perimeter.  
  
17. The equation of a curve is $y = x^3 - 5x^2 + 7x - 14$ .  
i) Find the coordinates of the stationary points on the curve.  
ii) Find the equation of the tangent to the curve at the point where the curve intersects the $y$ -axis.  
iii) Find the set of values for $x$ for which $x^3 - 5x^2 + 7x - 14$ is an increasing function of $x$ .  
  
18. The equation of a curve is $y = 4x^3 + px^2 + qx$ where $p$ and $q$ are positive constants.  
i) Show that the curve has only one stationary point when $p = 2\sqrt{q}$ .  
ii) In the case where $p = \frac{1}{2}$ and $q = -6$ , find the set of values of $x$ for which $y$ is a decreasing function of $x$ .  
  
19. The equation of a curve is $y = 5x^2 + \frac{3}{x}$ .  
i) Obtain an expression for $\frac{dy}{dx}$ .  
ii) A point is moving along the curve in such a way that the $x$ -coordinate is increasing at a constant rate of 0.04 units per second. Find the rate of change of the $y$ -coordinate when $x = 2$ .  
  
20. The function $\mathrm{f}(x)$ is defined for $x \leq \frac{4}{3}$ by $\mathrm{f}(x) = \sqrt[3]{(4 - 3x)}$ .  
i) Find $\mathrm{f}'(x)$ and $\mathrm{f}''(x)$ .  
The first, second and third terms of a geometric progression are $\mathrm{f}(1), \mathrm{f}'(1)$ and $\mathrm{kf}''(1)$ .  
ii) Find the value of the constant $k$ .  



#### Hodder AL **Exercise 6H : Second Derivative**
1.  Use the chain rule to differentiate the following functions.  
  
    (i) $ y = (x + 2)^3 $  
    (ii) $ y = (2x + 3)^4 $  
    (iii) $ y = (x^2 - 5)^3 $  
    (iv) $ y = (x^3 + 4)^5 $  
    (v) $ y = (3x + 2)^{-1} $  
    (vi) $ y = \frac{1}{(x^2 - 3)^3} $  
    (vii) $ y = (x^2 - 1)^{\frac{3}{2}} $  
    (viii) $ y = \left(\frac{1}{x} + x\right)^3 $  
    (ix) $ y = \left(\sqrt{x} - 1\right)^4 $  

2.  Given that $ y = (3x - 5)^3 $  
  
    (i) find $ \frac{dy}{dx} $  
    (ii) find the equation of the tangent to the curve at $ (2, 1) $  
    (iii) show that the equation of the normal to the curve at $ (1, -8) $ can be written in the form  
    \[ 36y + x + 287 = 0. \]  
  
3.  Given that $ y = (2x - 1)^4 $  
  
    (i) find $ \frac{dy}{dx} $  
    (ii) find the coordinates of any stationary points and determine their nature  
    (iii) sketch the curve.  
  
4.  Given that $ y = (x^2 - x - 2)^4 $  
  
    (i) find $ \frac{dy}{dx} $  
    (ii) find the coordinates of any stationary points and determine their nature  
    (iii) sketch the curve.  
5.  The length of a side of a square is increasing at a rate of 0.2 cm s$^{-1}$.    
    At what rate is the area increasing when the length of the side is 10 cm?  
  
6.  The force $ F $ newtons between two magnetic poles is given by the formula    
    \[F = \frac{1}{500r^2},\]    
    where $ r $ m is their distance apart.    
    Find the rate of change of the force when the poles are 0.2 m apart and the distance between them is increasing at a rate of 0.03 m s$^{-1}$.  
  
7.  The radius of a circular fungus is increasing at a uniform rate of 5 cm per day. At what rate is the area increasing when the radius is 1 m?    
---
#### Hodder AL **Exercise 6F : Chain Rule**
1.  Use the chain rule to differentiate the following functions.  
  
    (i) $ y = (x + 2)^3 $  
    (ii) $ y = (2x + 3)^4 $  
    (iii) $ y = (x^2 - 5)^3 $  
    (iv) $ y = (x^3 + 4)^5 $  
    (v) $ y = (3x + 2)^{-1} $  
    (vi) $ y = \frac{1}{(x^2 - 3)^3} $  
    (vii) $ y = (x^2 - 1)^{\frac{3}{2}} $  
    (viii) $ y = \left(\frac{1}{x} + x\right)^3 $  
    (ix) $ y = \left(\sqrt{x} - 1\right)^4 $  
  
2.  Given that $ y = (3x - 5)^3 $  
  
    (i) find $ \frac{dy}{dx} $  
    (ii) find the equation of the tangent to the curve at $ (2, 1) $  
    (iii) show that the equation of the normal to the curve at $ (1, -8) $ can be written in the form  
    \[ 36y + x + 287 = 0. \]  
  
3.  Given that $ y = (2x - 1)^4 $  
  
    (i) find $ \frac{dy}{dx} $  
    (ii) find the coordinates of any stationary points and determine their nature  
    (iii) sketch the curve.  
  
4.  Given that $ y = (x^2 - x - 2)^4 $  
  
    (i) find $ \frac{dy}{dx} $  
    (ii) find the coordinates of any stationary points and determine their nature  
    (iii) sketch the curve.  
3.  You are given that $ y = x^4 - 8x^2 $.
    (i) Find $\frac{dy}{dx}$.  
    (ii) Find $\frac{d^2y}{dx^2}$.  
    (iii) Find any stationary points and identify their nature.  
    (iv) Hence sketch the curve.  
  
4.  Given that $ y = (x - 1)^2(x - 3) $  
    (i) multiply out the right-hand side and find $\frac{dy}{dx}$  
    (ii) find the position and nature of any stationary points  
    (iii) sketch the curve.  
  
5.  Given that $ y = x^2(x - 2)^2 $  
    (i) multiply out the right-hand side and find $\frac{dy}{dx}$  
    (ii) find the position and nature of any stationary points  
    (iii) sketch the curve.  
  
6.  The function $ y = px^3 + qx^2 $, where $ p $ and $ q $ are constants, has a stationary point at $(1, -1)$.  
    (i) Using the fact that $(1, -1)$ lies on the curve, form an equation involving $ p $ and $ q $.  
    (ii) Differentiate $ y $ and, using the fact that $(1, -1)$ is a stationary point, form another equation involving $ p $ and $ q $.  
    (iii) Solve these two equations simultaneously to find the values of $ p $ and $ q $.  
  
7.  You are given that $ f(x) = 4x^2 + \frac{1}{x} $.  
    (i) Find $ f'(x) $ and $ f''(x) $.  
    (ii) Find the position and nature of any stationary points.  

8.  For the function $ y = x - 4\sqrt{x} $,  
    (i) find $\frac{dy}{dx}$ and $\frac{d^2y}{dx^2}$ and  
    (ii) find the coordinates of the stationary points and determine its nature.  
  
9.  The equation of a curve is $ y = 6\sqrt{x} - x\sqrt{x} $.  
    Find the $x$ coordinates of the stationary points and determine their nature.  
  
10. For the curve $ x^{\frac{5}{2}} - 10x^{\frac{3}{2}} $,  
    (i) find the values of $x$ for which $y = 0$ and show that there are no other values of $x$ for which $y = 0$.  
    (ii) show that there is a minimum turning point on the curve when $x = 6$ and calculate this value of $x$.  

# PM3 - Differentiation

### A. Rules of Differentiation
#### 6. Product Rule
If $h(x) = u \cdot v$, then $h'(x) = u'v + uv'$.

#### 7. Quotient Rule
If $h(x) = \frac{u}{v}$ (where $v \neq 0$), then $h'(x) = \frac{u'v - uv'}{v^2}$.

---
### B. Derivatives of Special Functions

#### 1. Trigonometric Functions
- $\frac{d}{dx}(\sin x) = \cos x$
- $\frac{d}{dx}(\cos x) = -\sin x$
- $\frac{d}{dx}(\tan x) = \sec^2 x$
- $\frac{d}{dx}(\csc x) = -\csc x \cot x$
- $\frac{d}{dx}(\sec x) = \sec x \tan x$
- $\frac{d}{dx}(\cot x) = -\csc^2 x$

#### 2. Exponential and Logarithmic Functions
- $\frac{d}{dx}(e^x) = e^x$
- $\frac{d}{dx}(\ln x) = \frac{1}{x}$ (for $x > 0$)
  


#### 3. Inverse Trigonometric Functions
- $\frac{d}{dx}(\tan^{-1} x) = \frac{1}{1+x^2}$


---

### C. Implicit Differentiation

Used when you cannot (or don't want to) solve for $y$ explicitly in terms of $x$.
1.  Differentiate both sides of the equation with respect to $x$.
2.  Whenever you differentiate a term containing $y$, apply the chain rule: multiply by $\frac{dy}{dx}$ (e.g., $\frac{d}{dx}(y^2) = 2y \frac{dy}{dx}$).
3.  Collect all $\frac{dy}{dx}$ terms on one side of the equation and solve for $\frac{dy}{dx}$.

---
### D. Differentiation of Parametric Functions

In many contexts, especially in physics and advanced geometry, the relationship between $x$ and $y$ is not defined directly (e.g., $y = f(x)$) but through a third variable, called a **parameter** (usually $t$ or $\theta$).

- **Definition:** Both $x$ and $y$ are expressed as separate functions of a parameter.
  $$x = f(t) \quad \text{and} \quad y = g(t)$$

The formula is derived from the chain rule:
$$\frac{dy}{dx} = \frac{dy/dt}{dx/dt}, \quad \text{provided} \quad \frac{dx}{dt} \neq 0$$   

---

# Drill PM3 Differentiation

---
#### Hodder Exercise 4A : Product and Quotion Rule
1.  Differentiate the following using the product rule or the quotient rule.  
    (i) $y = (x^2 - 1)(x^3 + 3)$  
    (ii) $y = x^5(3x^2 + 4x - 7)$  
    (iii) $y = x^2(2x + 1)^4$  
    (iv) $y = \frac{2x}{3x - 1}$  
    (v) $y = \frac{x^3}{x^2 + 1}$  
    (vi) $y = (2x + 1)^2(3x^2 - 4)$  
    (vii) $y = \frac{2x - 3}{2x^2 + 1}$  
    (viii) $y = \frac{x - 2}{(x + 3)^2}$  
    (ix) $y = (x + 1)\sqrt{x - 1}$  

---

3.  Given that $y = (x + 1)(x - 2)^2$  
    (i) find $\frac{dy}{dx}$  
    (ii) find any stationary points and determine their nature  
    (iii) sketch the curve.  

---

4.  Given that $y = \frac{x - 3}{x - 4}$  
    (i) find $\frac{dy}{dx}$  
    (ii) find the equation of the tangent to the curve at the point $(6, 1.5)$  
    (iii) find the equation of the normal to the curve at the point $(5, 2)$  
    (iv) use your answer from part (i) to deduce that the curve has no stationary points, and sketch the graph.  

---

7.  A curve has the equation $y = \frac{x^2}{2x + 1}$.  
    Find the coordinates of the stationary points on the curve and identify their nature.

---
#### Hodder Exercise 4B : Diff of Exponential
1.  Differentiate the following.  
    (i) $y = 3 \ln x$  
    (ii) $y = \ln(4x)$  
    (iii) $y = \ln(x^2)$  
    (iv) $y = \ln(x^2 + 1)$  
    (v) $y = \ln\left(\frac{1}{x}\right)$  
    (vi) $y = x \ln x$  
    (vii) $y = x^2 \ln(4x)$  
    (viii) $y = \ln\left(\frac{x+1}{x}\right)$  
    (ix) $y = \ln\sqrt{x^2 - 1}$  
    (x) $y = \frac{\ln x}{x^2}$  

2.  Differentiate the following.  
    (i) $y = 3e^x$  
    (ii) $y = e^{2x}$  
    (iii) $y = e^{x^2}$  
    (iv) $y = e^{(x+1)^2}$  
    (v) $y = xe^{4x}$  
    (vi) $y = 2x^3e^{-x}$  
    (vii) $y = \frac{x}{e^x}$  
    (viii) $y = (e^{2x} + 1)^3$  

3.  Knowing how much rain has fallen in a river basin, hydrologists are often able to give forecasts of what will happen to a river level over the next few hours. In one case it is predicted that the height $h$, in metres, of a river above its normal level during the next 3 hours will be $0.12e^{0.9t}$, where $t$ is the time elapsed, in hours, after the prediction.  
    (i) Find $\frac{dh}{dt}$, the rate at which the river is rising.  
    (ii) At what rate will the river be rising after 0, 1, 2 and 3 hours?  

6.  Given that $y = \frac{e^x}{x}$  
    (i) find $\frac{dy}{dx}$  
    (ii) find the coordinates of any stationary points on the curve  
    (iii) sketch the curve.  

8.  You are given that the curve $y = \frac{x}{e^x}$ has one stationary point.   
    (i) Find the exact coordinates of this point.   
    (ii) Determine whether this point is a maximum or a minimum point.   

9.  Given that $f(x) = \frac{\ln x}{x}, \, x > 0$  
    (i) write down the coordinates of the point where the graph of $y = f(x)$ crosses the $x$-axis  
    (ii) find the exact coordinates of the stationary point of the curve $y = f(x)$  
    (iii) sketch the curve of $y = f(x)$.  
---
#### Hodder Exercise 4C : Diff of Trigonometric F.
1.  Differentiate each of the following.  
    (i) $2 \cos x + \sin x$  
    (ii) $\tan x + 5$  
    (iii) $\sin x - \cos x$  
  
2.  Use the product rule to differentiate each of the following.  
    (i) $x \tan x$  
    (ii) $\sin x \cos x$  
    (iii) $e^x \sin x$  
  
3.  Use the quotient rule to differentiate each of the following.  
    (i) $\frac{\sin x}{x}$  
    (ii) $\frac{e^x}{\cos x}$  
    (iii) $\frac{x + \cos x}{\sin x}$  
  
4.  Use the chain rule to differentiate each of the following.  
    (i) $\tan(x^2 + 1)$  
    (ii) $\sin 2x$  
    (iii) $\ln(\sin x)$  
  
5.  Use an appropriate method to differentiate each of the following.  
    (i) $\sqrt{\cos x}$  
    (ii) $e^x \tan x$  
    (iii) $\sin 4x^2$  
    (iv) $e^{\cos 2x}$  
    (v) $\frac{\sin x}{1 + \cos x}$  
    (vi) $\ln(\tan x)$  
  
6.  (i) Differentiate $y = x \cos x$.  
    (ii) Find the gradient of the curve $y = x \cos x$ at the point where $x = \pi$.  
    (iii) Find the equation of the tangent to the curve $y = x \cos x$ at the point where $x = \pi$.  
    (iv) Find the equation of the normal to the curve $y = x \cos x$ at the point where $x = \Pi$.  

10.  [s06/2/3] The equation of a curve is $y = x + 2 \cos x$. Find the $x$ coordinates of the stationary points of the curve for $0 \leq x \leq 2\pi$, and determine the nature of each of these stationary points.
---

12.  [s07/3/4] The curve with equation $y = e^{-x} \sin x$ has one stationary point for which $0 \leq x \leq \pi$.  
    (i) Find the $x$ coordinate of this point.  
    (ii) Determine whether this point is a maximum or a minimum point.  

---

13.  [s08/3/3] The curve $y = \frac{e^x}{\cos x}$, for $-\frac{1}{2}\pi < x < \frac{1}{2}\pi$, has one stationary point. Find the $x$ coordinate of this point.

---
#### Hodder Exercise 4D : Diff of Implicit F.
1.  Differentiate each of the following with respect to $x$.  
    (i) $y^4$  
    (ii) $x^2 + y^3 - 5$  
    (iii) $xy + x + y$  
    (iv) $\cos y$  
    (v) $e^{(y+2)}$  
    (vi) $xy^3$  
    (vii) $2x^2y^5$  
    (viii) $x + \ln y - 3$  
    (ix) $xe^y - \cos y$  
    (x) $x^2 \ln y$  
    (xi) $xe^{\sin y}$  
    (xii) $x \tan y - y \tan x$  

2.  Find the gradient of the curve $xy^3 = 5 \ln y$ at the point $(0, 1)$.

3.  Find the gradient of the curve $e^{\sin x} + e^{\cos y} = e + 1$ at the point $\left(\frac{\pi}{2}, \frac{\pi}{2}\right)$.

4.  (i) Find the gradient of the curve $x^2 + 3xy + y^2 = x + 3y$ at the point $(2, -1)$.  
    (ii) Hence find the equation of the tangent to the curve at this point.  

5.  Find the coordinates of all the stationary points on the curve $x^2 + y^2 + xy = 3$.

6.  A curve has the equation $(x - 6)(y + 4) = 2$.  
    (i) Find an expression for $\frac{dy}{dx}$ in terms of $x$ and $y$.  
    (ii) Find the equation of the normal to the curve at the point $(7, -2)$.  
    (iii) Find the coordinates of the point where the normal meets the curve again.  
    (iv) By rewriting the equation in the form $y - a = \frac{b}{x - c}$, identify any asymptotes and sketch the curve.  

7.  A curve has the equation $y = x^x$ for $x > 0$.  
    (i) Take logarithms to base $e$ of both sides of the equation.  
    (ii) Differentiate the resulting equation with respect to $x$.  
    (iii) Find the coordinates of the stationary point, giving your answer to 3 decimal places.  
    (iv) Sketch the curve for $x > 0$.  
  
8.  [s06/2/5] The equation of a curve is $3x^2 + 2xy + y^2 = 6$. It is given that there are two points on the curve where the tangent is parallel to the $x$-axis.  
    (i) Show by differentiation that, at these points, $y = -3x$.  
    (ii) Hence find the coordinates of the two points.  
  
9.  [s11/31/5] The curve with equation $6e^{2x} + ke^y + e^{2y} = c$, where $k$ and $c$ are constants, passes through the point P with coordinates $(\ln 3, \ln 2)$.  
    (i) Show that $58 + 2k = c$.  
    (ii) Given also that the gradient of the curve at P is $-6$, find the values of $k$ and $c$.  
  
10. [s08/2/7] The equation of a curve is $x^2 + y^2 - 4xy + 3 = 0$.  
    (i) Show that $\frac{dy}{dx} = \frac{2y - x}{y - 2x}$.  
    (ii) Find the coordinates of each of the points on the curve where the tangent is parallel to the $x$-axis.  
  
11. [s09/32/3] The equation of a curve is $x^3 - x^2y - y^3 = 3$.  
    (i) Find $\frac{dy}{dx}$ in terms of $x$ and $y$.  
    (ii) Find the equation of the tangent to the curve at the point $(2, 1)$, giving your answer in the form $ax + by + c = 0$.  
  
12. [s08/3/6] The equation of a curve is $xy(x + y) = 2a^3$, where $a$ is a non-zero constant. Show that there is only one point on the curve at which the tangent is parallel to the $x$-axis, and find the coordinates of this point.  
---
#### Hodder Exercise 4E : Diff of Parametric F.

1.  For each of the following curves, find $\frac{dy}{dx}$ in terms of the parameter.  
    (i) $x = 3t^2$  
    (ii) $x = \theta - \cos \theta$  
    (iii) $y = 2t^3$  
    (iv) $y = \theta + \sin \theta$  
    (v) $x = t + \frac{1}{t}$  
    (vi) $x = 3\cos \theta$  
    (vii) $y = 2\sin \theta$  
    (viii) $y = t - \frac{1}{t}$  
  
2.  A curve has the parametric equations $x = \tan \theta$, $y = \tan 2\theta$. Find  
    (i) the value of $\frac{dy}{dx}$ when $\theta = \frac{\pi}{6}$  
    (ii) the equation of the tangent to the curve at the point where $\theta = \frac{\pi}{6}$  
    (iii) the equation of the normal to the curve at the point where $\theta = \frac{\pi}{6}$  
  
3.  A curve has the parametric equations $x = t^2$, $y = 1 - \frac{1}{2t}$ for $t > 0$. Find  
    (i) the coordinates of the point P where the curve cuts the x-axis  
    (ii) the gradient of the curve at this point  
    (iii) the equation of the tangent to the curve at P  
    (iv) the coordinates of the point where the tangent cuts the y-axis  
  
4.  A curve has parametric equations $x = at^2$, $y = 2at$, where a is constant. Find  
    (i) the equation of the tangent to the curve at the point with parameter t  
    (ii) the equation of the normal to the curve at the point with parameter t  
    (iii) the coordinates of the points where the normal cuts the x- and y-axes  
  
5.  A curve has parametric equations $x = \cos \theta$, $y = \cos 2\theta$.  
    (i) Show that $\frac{dy}{dx} = 4\cos \theta$.  
    (ii) By writing $\frac{dy}{dx}$ in terms of $x$, show that $\frac{d^2y}{dx^2} - 4 = 0$.  
  
6.  The parametric equations of a curve are $x = at$, $y = \frac{b}{t}$, where a and b are constant. Find in terms of a, b and t  
    (i) $\frac{dy}{dx}$  
    (ii) the equation of the tangent to the curve at the general point $(at, \frac{b}{t})$  
    (iii) the coordinates of the points X and Y where the tangent cuts the x- and y-axes.  
    (iv) Show that the area of triangle OXY is constant, where O is the origin.  
  
7.  A particle P moves in a plane so that at time t its coordinates are given by $x = 4\cos t$, $y = 3\sin t$. Find  
    (i) $\frac{dy}{dx}$ in terms of t  
    (ii) the equation of the tangent to the curve at the general point $(at, \frac{b}{t})$  
    (iii) the coordinates of the points X and Y where the tangent cuts the x- and y-axes.  
    (iv) Show that the area of triangle OXY is constant, where O is the origin.  
  
8.  A particle P moves in a plane so that at time t its coordinates are given by $x = 4\cos t$, $y = 3\sin t$. Find  
    (i) $\frac{dy}{dx}$ in terms of t  
    (ii) the equation of the tangent to the curve at the general point $(at, \frac{b}{t})$  
    (iii) the coordinates of the points X and Y where the tangent cuts the x- and y-axes.  
    (iv) Show that the area of triangle OXY is constant, where O is the origin.  
  
9.  [w11/21/7] The parametric equations of a curve are $x = e^{3t}$, $y = t^2e^t + 3$.  
    (i) Show that $\frac{dy}{dx} = \frac{t(t+2)}{3e^{2t}}$.  
    (ii) Show that the tangent to the curve at the point $(1, 3)$ is parallel to the x-axis.  
    (iii) Find the exact coordinates of the other point on the curve at which the tangent is parallel to the x-axis.  
  
10. [w13/31/4] The parametric equations of a curve are $x = e^{-t}\cos t$, $y = e^{-t}\sin t$.  
    Show that $\frac{dy}{dx} = \tan(t - \frac{1}{4}\pi)$.  
  
11. [s07/2/3] The parametric equations of a curve are  
    $$x = 3t + \ln(t - 1), \quad y = t^2 + 1, \quad \text{for } t > 1.$$  
    (i) Express $\frac{dy}{dx}$ in terms of $t$.  
    (ii) Find the coordinates of the only point on the curve at which the gradient of the curve is equal to 1.  
  
12. [s09/2/4] The parametric equations of a curve are  
    $$x = 4\sin\theta, \quad y = 3 - 2\cos 2\theta,$$  
    where $-\frac{1}{2}\pi < \theta < \frac{1}{2}\pi$. Express $\frac{dy}{dx}$ in terms of $\theta$, simplifying your answer as far as possible.  
  
13. [w09/22/4] The parametric equations of a curve are  
    $$x = 1 - e^{-t}, \quad y = e^t + e^{-t}.$$  
    (i) Show that $\frac{dy}{dx} = e^{2t} - 1$.  
    (ii) Hence find the exact value of $t$ at the point on the curve at which the gradient is 2.  
  
14. [s06/3/3] The parametric equations of a curve are  
    $$x = 2\theta + \sin 2\theta, \quad y = 1 - \cos 2\theta.$$  
    Show that $\frac{dy}{dx} = \tan \theta$.  
  
15. [s09/3/6] The parametric equations of a curve are  
    $$x = a\cos^3 t, \quad y = a\sin^3 t,$$  
    where $a$ is a positive constant and $0 < t < \frac{1}{2}\pi$.  
    (i) Express $\frac{dy}{dx}$ in terms of $t$.  
    (ii) Show that the equation of the tangent to the curve at the point with parameter $t$ is  
    $$x\sin t + y\cos t = a\sin t\cos t.$$  
    (iii) Hence show that, if this tangent meets the $x$-axis at $X$ and the $y$-axis at $Y$, then the length of $XY$ is always equal to $a$.  
---


#### Oxford AL Exercise 4.1 : Diff of Exponential F.

1.  Differentiate  
    a) $\mathrm{e}^{2x}$  
    d) $\mathrm{e}^{8 - x}$  
    g) $3\mathrm{e}^{2x - 1}$  
    j) $\mathrm{e}^{\frac{3}{x}}$  
  
2.  Find $\frac{\mathrm{d}y}{\mathrm{d}x}$ when  
    a) $y = \mathrm{e}^{-2x}$  
    d) $y = -8\mathrm{e}^{\sqrt{x}}$  
    g) $y = \mathrm{e}^{4x} + \mathrm{e}^{-x}$  
    j) $y = (2\mathrm{e}^{3x} - 1)^{2}$  
  
3.  Find the gradient of the tangent to the curve $y = 5\mathrm{e}^{2x}$ at the point (0, 5).  
  
4.  Find the exact value of the gradient of the tangent to the curve $y = \mathrm{e}^{x} - 6\sqrt{x}$ when $x = 1$ .  
  
5.  Find the coordinates of the minimum point on the curve with equation $y = \mathrm{e}^{x} - x$ .  
  
6.  Find the coordinates of the turning point on the curve $y = 2x - \mathrm{e}^{2x} + 3$ and determine whether this point is a maximum or a minimum point.  

---

#### Oxford AL Exercise 4.2 : Diff of ln(x)

1.  Differentiate  
    a) $\ln 4x$  
    b) $\ln (1 - x^2)$  
    c) $\ln (3 + 5x)$  
    d) $\ln (x^3 + 2)$  
    e) $\ln (e^x - 7)$  
    f) $\ln \sqrt{x}$  
    g) $\ln (6x - 3)^4$  
    h) $\ln (4x^2 + 2x)$  
    i) $\ln \frac{1}{x^2}$  
    j) $3\ln 4x$  
    k) $2\ln \frac{1}{x}$  
    l) $6\ln \frac{9x - 2}{3}$  
  
2.  Find $\frac{\mathrm{d}y}{\mathrm{d}x}$ when  
    a) $y = 8\ln 3x$  
    b) $y = \ln 2x^3$  
    c) $y = \ln (2 - 4x)$  
    d) $y = 6\ln \frac{x}{2}$  
    e) $y = \ln \sqrt{(2x + 1)}$  
    f) $y = \ln (5x)^{10}$  
    g) $y = \ln (3e^x - 2x)$  
    h) $y = 9\ln (x^2 + 3x)^2$  
    i) $y = 5\ln \left(7 - \frac{2}{x}\right)$  
    j) $y = 4\ln \sqrt{(x^2 - 8x)}$  
    k) $y = \ln e^{5x}$  
    l) $y = \ln \frac{7}{(x + 3)^6}$  
  
3.  Find the gradient of the tangent to the curve $y = 4 + \ln x$ at the point (1, 4).  
  
4.  Find the gradient of the tangent to the curve $y = \ln (x^2 + 1)$ when $x = 3$ .  
  
5.  Find the exact coordinates of the point on the curve $y = \ln 3x$ where the gradient is $\frac{1}{2}$ .  
  
6.  Find the coordinates of the turning point on the curve $y = x - \ln x$ , and determine whether this point is a maximum or a minimum point.  
  
---  
  
#### Oxford AL Exercise 4.3 : Product Rule
  
1.  Use the product rule to find $\frac{\mathrm{d}y}{\mathrm{d}x}$ when  
    a) $y = x\mathrm{e}^{x}$  
    b) $y = (4x - 1)(x^{2} - 5)$  
    c) $y = x^{2}\sqrt{x^{2} + 1}$  
    d) $y = \sqrt{x}(\ln x)$  
    e) $y = x^{2}(2x + 5)^{7}$  
    f) $y = \sqrt{x}(x - 3)^{2}$  
    g) $y = \mathrm{e}^{2x}(4x + 1)$  
    h) $y = x(x + 3)^{4}$  
    i) $y = x^{2}\ln x$  
    j) $y = x^{2}(x + 3)^{3}$  
    k) $y = \mathrm{e}^{x}(2x - 1)^{4}$  
    l) $y = \frac{x}{x + 1}$  
    m) $y = 6\mathrm{e}^{\sqrt{x}}(x + 4)$  
    n) $y = 4x^{3}\mathrm{e}^{2x}$  
    o) $y = 2\mathrm{e}^{x}\ln 2x$  
    p) $y = \frac{x - 2}{x + 2}$  
    q) $y = \frac{2x + 3}{1 - 5x}$  
    r) $y = (x^{2} + 1)\ln (x^{2} + 1)$  
  
2.  Find the gradient of the tangent to the curve $y = x^{2}\mathrm{e}^{- x}$ at the point $\left(1,\frac{1}{\mathrm{e}}\right)$ .  
  
3.  Find the equation of the tangent to the curve $y = x(1 + x^{2})^{3}$ when $x = 2$ .  
  
4.  Show that $\frac{\mathrm{d}y}{\mathrm{d}x} = \frac{2x^{2} + 4x - 1}{\sqrt{(x^{2} - 1)}}$ when $y = (x + 4)\sqrt{(x^{2} - 1)}$ .  
  
5.  Find the exact coordinates of the turning point on the curve $y = \mathrm{e}^{x}(1 + x)$ and determine whether this point is a maximum or a minimum point.  
  
---  
  
#### Oxford AL Exercise 4.4  : Quotient Rule
  
1.  Use the quotient rule to find $\frac{\mathrm{d}y}{\mathrm{d}x}$ when  
    a) $y = \frac{2x}{x + 3}$  
    b) $y = \frac{e^{2x}}{x}$  
    c) $y = \frac{x^2}{x + 4}$  
    d) $y = \frac{x}{1 + x^2}$  
    e) $y = \frac{3x}{2 - x}$  
    f) $y = \frac{3x^2}{2e^x - x}$  
    g) $y = \frac{3x - 4}{2x + 1}$  
    h) $y = \frac{3x + 5}{(x + 1)^2}$  
    i) $y = \frac{6x^2}{2 - x}$  
    j) $y = \frac{4x}{(1 - x)^3}$  
    k) $y = \frac{x^2 + 1}{x - 2}$  
    l) $y = \frac{5x^2}{\ln x}$  
    m) $y = \frac{x^3}{\sqrt{(1 - 2x^2)}}$  
    n) $y = \frac{3x + x^4}{2x^2 + 1}$  
    o) $y = \frac{x}{1 + \sqrt{x}}$  
    p) $y = \frac{x^2 + 6}{2x - 7}$  
    q) $y = \frac{\sqrt{(x + 1)^5}}{x}$  
    r) $y = \frac{1 - 2x^2}{\sqrt{(1 + 2x^2)}}$  
  
2.  If $y = \frac{x^2}{2x - 3}$ find the values of $x$ at the points where $\frac{\mathrm{d}y}{\mathrm{d}x} = 0$ .  
  
3.  Find the equation of the normal to the curve $y = \frac{3x^2}{2x - 1}$ at the point (2, 4).  
  
4.  If $y = \frac{x}{x - 1}$ , find $\frac{\mathrm{d}^2y}{\mathrm{d}x^2}$ .  
  
5.  Show that the coordinates of the turning point on the curve $y = \frac{x + 3}{\sqrt{(1 + x^2)}}$ are $\left(\frac{1}{3}, \sqrt{10}\right)$ .  
  
6.  Show that if $y = \frac{7\ln x - x^3}{e^{3x}}$ then $\frac{\mathrm{d}y}{\mathrm{d}x} = \frac{7}{e^3}$ when $x = 1$ .  
  
---  

#### Oxford AL Exercise 4.5 : Diff of Trigonometric F.
  
1.  Find $\frac{\mathrm{d}y}{\mathrm{d}x}$ when  
    a) $y = \sin 5x$  
    b) $y = 6\tan \frac{x}{2}$  
    c) $y = \cos (x^{2} + 2x)$  
    d) $y = 4\tan^{2}x$  
    e) $y = \sin (x^{3} - 7)$  
    f) $y = 5\tan 4x$  
    g) $y = \cos^{3}x$  
    h) $y = \sin 2x\cos x$  
    i) $y = x^{2}\tan 3x$  
    j) $y = \frac{\cos 2x}{x^{2}}$  
    k) $y = \sin^{3}3x\cos x$  
    l) $y = 4\tan \sqrt{x}$  
  
2.  a) If $y = (\cos 2x - \sin x)^2$ , show that $\frac{\mathrm{d}y}{\mathrm{d}x} = -(\cos 2x - \sin x)(2\sin 2x + \cos x)$ .  
    b) If $y = \mathrm{e}^{x}\tan x$ , show that $\frac{\mathrm{d}y}{\mathrm{d}x} = \mathrm{e}^{x}(\sec^{2}x + \tan x)$ .  
    c) If $y = \ln (\cos x)$ , show that $\frac{\mathrm{d}y}{\mathrm{d}x} = -\tan x$ .  
    d) If $y = x\mathrm{e}^{\sin x}$ , show that $\frac{\mathrm{d}y}{\mathrm{d}x} = \mathrm{e}^{\sin x}(x\cos x + 1)$ .  
  
3.  Find the gradient of the tangent to the curve $y = 3\sin 2x$ when $x = \frac{\pi}{3}$ .  
  
4.  Find the equation of the normal to the curve $y = x - \sin x$ at the point $\left(\frac{\pi}{2}, \frac{\pi}{2} - 1\right)$ .  
  
5.  Show that $\frac{\mathrm{d}^2y}{\mathrm{d}x^2} = -\frac{1}{2}\sec^2 x$ when $y = \ln \sqrt{\cos x}$ .  
  
6.  Find the coordinates of the turning points on the curve $y = 2\sin x + \cos 2x$ for $0< x< \pi$ and determine whether these points are maximum or minimum points.  
  
7.  Show that the maximum value of the curve $y = x - 2\sin x$ for $0\leq x\leq 2\pi$ is $\frac{5\pi}{3} +\sqrt{3}$ and find the minimum value of the curve.  
  
8.  If $y = \ln \sqrt{1 - \cos x}$ , show that $\frac{\mathrm{d}^2y}{\mathrm{d}x^2} = \frac{1}{2(\cos x - 1)}$ .  
  
---  
  
#### Oxford AL Exercise 4.6 : Diff of Implicit F.
  
1.  Find $\frac{\mathrm{d}y}{\mathrm{d}x}$ in terms of $x$ and $y$ when  
    a) $x^{2} + 2y - y^{2} = 5$  
    b) $x\cos y = y^{2} + x$  
    c) $y = 5\tan^{-1}3x$  
    d) $x^{3} + xy^{2} = 5x$  
    e) $x^{2} + y^{2} = y$  
    f) $2xy - 3y = y^{2} - 7x$  
    g) $x\ln y = 1 + x$  
    h) $y = e^{x}\tan^{-1}x$  
    i) $x^{2} + y^{2} + 2x - 4y + 4 = 0$  
    j) $x^{4} + x^{2}y^{2} - y^{4} = 5$  
    k) $x\sin y - y\sin x = 8$  
    l) $e^{x + y} = 2x$  
    m) $y = x\tan^{-1}x$  
    n) $y + y^{3} = x - x^{2}$  
    o) $xe^{y} + 2y = 1$  
    p) $y = x\ln y$  
    q) $y = \frac{1}{4}\tan^{-1}2x$  
    r) $\sin y + x^{2}y^{3} = 2y + \cos x.$  
  
2.  Find the gradients of the tangents to the curve $x^{2} + 6y^{2} = 10$ when $x = 2$ .  
  
3.  Find the equation of the tangent to the curve $x^{3} + y^{3} = 2xy$ at the point (1, 1).  
  
4.  Show that $\frac{\mathrm{d}y}{\mathrm{d}x} = \frac{2y^{2} - 2xy^{3}}{3x^{2}y^{2} - 4xy - 3}$ when $x^{2}y^{3} - 2xy^{2} = 3y$ .  
  
5.  Given that $\ln (xy) = x^{2} + y^{2}$ , show that $\frac{\mathrm{d}y}{\mathrm{d}x} = \frac{y(2x^{2} - 1)}{x(1 - 2y^{2})}$ .  
  
6.  If $y = \tan^{-1}(1 - 2x)$ , find, in its simplest form, an expression for $\frac{\mathrm{d}y}{\mathrm{d}x}$ .  
  
7.  The parametric equations of a curve are $x = 2t + 3, y = t^2 - 4$ . Find the gradient of the curve at the point for which $x = 5$ .  
  
8.  The parametric equations of a curve are $x = 3t, y = \frac{3}{t}$ . Find the equation of the normal to the curve at the point $(-1, -9)$ . Give your answer in the form $ax + by + c = 0$ , where $a, b$ , and $c$ are integers.  
  
9.  Show that $\frac{\mathrm{d}y}{\mathrm{d}x} = \frac{\sin\theta}{1 + \cos\theta}$ when $x = a(\theta +\sin \theta)$ and $y = a(1 - \cos \theta)$ , where $a$ is a constant.  
  
10. The parametric equations of a curve are $x = 2t, y = 4t^3 - 8t^2$ . Find the two values of $t$ for which $\frac{\mathrm{d}y}{\mathrm{d}x} = 0$ .  
  
11. The parametric equations of a curve are $x = 5\cos 3t, y = 2\sin 3t, 0< t< \frac{\pi}{2}$ .  
    a) Find $\frac{\mathrm{d}y}{\mathrm{d}x}$ in terms of $t$ .  
    b) Find the coordinates of the stationary point on the curve.  
  
---  
  
#### Oxford AL Summary Exercise 4  
  
1.  Find $\frac{\mathrm{d}y}{\mathrm{d}x}$ when  
    a) $y = \mathrm{e}^{-5x}$  
    b) $y = \ln (4x^2 +5)$  
    c) $y = \tan^{-1}(4x)$  
    d) $y = \frac{x - 1}{2x - 3}$  
    e) $y = \frac{\sin x}{e^x}$  
    f) $y = (x + 1)^2 (x - 2)^3$  
    g) $y = \frac{x^2}{\sqrt{(x^2 - 1)}}$  
    h) $y = 6\ln \sqrt{(3x - 4)}$  
    i) $y = xy^2 -x^3$  
    j) $y = 7\ln \mathrm{e}^{2x}$  
    k) $y = \frac{x\mathrm{e}^x}{\ln x}$  
    l) $y = x^2\sqrt{(1 + x^2)}$  
    m) $x = 3t - 5$ $y = \frac{1}{t}$  
    n) $y = -2\mathrm{e}^{\sqrt{x}}$  
    o) $2x^3 +3xy^2 -y^3 = 6$  
    p) $y = \frac{(2e^x - 3)^2}{\mathrm{e}^x}$  
    q) $y = \mathrm{e}^{\tan^2x}$  
    r) $y = x^2\mathrm{e}^{3x - 2}$  
    s) $x = 1 + 2\cos \theta ,\quad y = 3 - 6\sin \theta$  
    t) $y = \log_{e}(3x + 1)$  
    u) $x = (t + 2)^4$ $y = 8t^3 -2t$  
    v) $y = x\ln x$  
    w) $y = \frac{\sqrt{x}}{1 - x^2}$  
    x) $x^3 +xy^2 -y^3 = 1$  
    y) $y = \frac{1}{5}\tan^{-1}10x.$  
  
2.  Find the exact coordinates of the point on the curve $y = 3x\mathrm{e}^{2x}$ at which $\frac{\mathrm{d}^2y}{\mathrm{d}x^2} = 0$ .  
  
3.  Show that if $y = \ln (\sin \sqrt{x})$ then $\frac{\mathrm{d}y}{\mathrm{d}x} = \frac{\cot\sqrt{x}}{2\sqrt{x}}$ .  
  
4.  The parametric equations of a curve are $x = (1 + t)^2, y = (1 - t)^2.$  
    a) Express $\frac{\mathrm{d}y}{\mathrm{d}x}$ in terms of $t$ , simplifying your answer.  
    b) Find the point on the curve where the gradient is parallel to the $x$ -axis.  
  
5.  Find the equation of the tangent to the curve $y = \frac{x^2 + 2x}{x^2 - 3}$ at the point (2, 8).  
  
6.  The equation of a curve is $x \ln y^3 = 6$ . Find the gradient of the curve at the point (2, e).  
  
7.  A curve has equation $2x^2 + y^2 + 5x - 3y = 1$ . Find the equation of the normal to the curve at the point $(-1, 4)$ . Give your answer in the form $ax + by + c = 0$ , where $a, b, c$ are integers.  
  
8.  Show that if $y = 4 \tan^{-1} \left(\frac{x}{2}\right)$ , then $\frac{\mathrm{d}y}{\mathrm{d}x} = \frac{8}{4 + x^2}$  
  
9.  If $y = \tan^{-1} 2x$ , find an expression for $\frac{\mathrm{d}^2 y}{\mathrm{d}x^2}$ .  
  
10. The parametric equations of a curve are $x = t^2, y = t^3$ . Find the equation of the tangent to the curve at the point (1, 1).  
  
11. The curve with equation $y = \frac{\cos x}{e^x}$ has one stationary point in the interval $0 \leq x \leq \pi$ . Find the exact $x$ coordinate of this point.  
  
12. If $y = 2 \cos (\ln x)$ , show that  
    $$x^2 \frac{\mathrm{d}^2 y}{\mathrm{d}x^2} + x \frac{\mathrm{d}y}{\mathrm{d}x} + y = 0$$  
  
13. Given that $y = \frac{5x^2 - 10x + 9}{(x - 1)^2}, x \neq 1$ , show that  
    $$\frac{\mathrm{d}y}{\mathrm{d}x} = -\frac{8}{(x - 1)^3}$$  
  
14. The parametric equations of a curve are $x = t + 1, y = 4 - t^2$ . Find the equation of the normal to the curve at the point where $x = 2$ .  
  
15. If $y = \sqrt{5x^2 + 3}$ , find the value of $\left(\frac{\mathrm{d}y}{\mathrm{d}x}\right)^2$ when $x = -1$ .  
  
16. Find the exact coordinates of the stationary point on the curve with equation $y = x \ln 3x$ , giving your answer in terms of $e$ .  
  
17. Prove that there are no stationary points on the curve $y = \frac{ax + b}{cx + d}$ where $a, b, c$ , and $d$ are constants and $ad \neq bc$ .  
  
18. Prove that if $y = e^{-x} \sin 2x$ , then $4 \frac{\mathrm{d}^2 y}{\mathrm{d}x^2} + 4 \frac{\mathrm{d}y}{\mathrm{d}x} + 17y = 0$ .  
  
19. By differentiating $\frac{1}{\sin 2\theta}$ , show that if $y = \csc 2\theta$ then $\frac{\mathrm{d}y}{\mathrm{d}\theta} = -2 \csc 2\theta \cot 2\theta$ .  
  
20. Show that the curve with equation $y = \sin x - 8 \tan x$ cannot have any stationary values.  
  
21. The equation of a curve is $x^2 - y^2 - 5x + 3y + 13 = 0$ .  
    a) Find $\frac{\mathrm{d}y}{\mathrm{d}x}$ in terms of $x$ and $y$ .  
    b) Find the values of $y$ at the stationary points.  
  
22. The parametric equations of a curve are given by $x = (t^2 - 2)^2, y = t(t - 6)$ . Find the coordinates of the stationary point of the curve.    


#### IB_Haese aExercise 18B.2 : Chain Rule
1.  Write in the form $au^m$, clearly stating what $u$ is:  
    a $(2x - 3)^5$  
    b $\frac{1}{x^2 - 3x}$  
    c $\frac{1}{(2x - 1)^2}$  
    d $\sqrt{3 - 2x}$  
    e $\frac{2}{\sqrt{9 - 2x}}$  
    f $\frac{4}{(3 - x)^3}$  
  
2.  Differentiate $y = (2x + 3)^3$ by:  
    a using the chain rule with $u = 2x + 3$  
    b expanding $y = (2x + 3)^3$ then differentiating term-by-term.  
  
3.  Find the derivative function $\frac{dy}{dx}$ for:  
    a $y = (4x - 5)^2$  
    b $y = 6(5 - x)^3$  
  
4.  Find the gradient of the tangent to:  
    a $y = \sqrt{1 - x^2}$ at $x = \frac{1}{2}$  
    b $y = \frac{1}{(2x - 1)^4}$ at $x = 1$  
    c $y = \frac{4}{x + 2\sqrt{x}}$ at $x = 4$  
    Check your answers using technology.  
  
5.  The gradient function of $f(x) = (2x - b)^a$ is $f'(x) = 24x^2 - 24x + 6$. Find the constants $a$ and $b$.  
  
6.  Suppose $y = \frac{a}{\sqrt{1 + bx}}$ where $a, b \in \mathbb{R}$. At the point $(3, 1)$, $\frac{dy}{dx} = -\frac{1}{8}$. Find $a$ and $b$.  
  
7.  Suppose $f(x) = 3\left(ax - \frac{b}{x}\right)^3$. Given that $f(\frac{3}{2}) = 3$ and $f'(\frac{3}{2}) = 30$, find $a$ and $b$.  
  
---  
  
#### IB_Haese Exercise 18C : Product Rule
  
1.  Use the product rule to differentiate:  
    a $f(x) = x(x - 1)$  
    b $f(x) = 2x(x + 1)$  
    c $f(x) = x^2\sqrt{x + 1}$  
    d $f(x) = (x + 3)(x - 1)$  
    e $f(x) = x\sqrt{x^2 - 1}$  
    f $f(x) = x(x + 1)^2$  
  
2.  Find $\frac{dy}{dx}$ using the product rule:  
    a $y = x^2(2x - 1)$  
    b $y = 4x(2x + 1)^3$  
    c $y = x^2\sqrt{3 - x}$  
    d $y = \sqrt{x}(x - 3)^2$  
    e $y = 5x^2(3x^2 - 1)^2$  
    f $y = \sqrt{x}(x - x^2)^3$  
  
3.  Find the gradient of the tangent to:  
    a $y = x^4(1 - 2x)^2$ at $x = -1$  
    b $y = \sqrt{x}(x^2 - x + 1)^2$ at $x = 4$  
    c $y = x\sqrt{1 - 2x}$ at $x = -4$  
    d $y = x^3\sqrt{5 - x^2}$ at $x = 1$.  
  
4.  Consider $y = \sqrt{x(3 - x)^2}$.  
    a Show that $\frac{dy}{dx} = \frac{(3 - x)(3 - 5x)}{2\sqrt{x}}$.  
    b Find the $x$-coordinates of all points on $y = \sqrt{x(3 - x)^2}$ where the tangent is horizontal.  
    c State the domain of $\frac{dy}{dx}$. Discuss how it differs from the domain of the original function.  
  
5.  Suppose $y = -2x^2 (x + 4)$. For what values of $x$ does $\frac{dy}{dx} = 10$?  
  
6.  Suppose $y = (x + 3)(x - 2)^2$. For what values of $x$ does $\frac{dy}{dx} = -7$?  
  
7.  Find the value of $x$ for which the tangent to $f(x) = ax\sqrt{1 - x}$, $a \neq 0$ has gradient:  
    a 0  
    b a.  
  
8.  Find the values of $a$ such that $f(x) = x^2\sqrt{x^2 + a}$ and $f'(-2) = -\frac{34}{3}$.  
  
---  
  
#### IB_Haese Exercise 18D : Quotient Rule  
  
1.  Use the quotient rule to find $\frac{dy}{dx}$ if:  
    a $y = \frac{1 + 3x}{2 - x}$  
    b $y = \frac{x^2}{2x + 1}$  
    c $y = \frac{x}{\sqrt{1 - 3x}}$  
    d $y = \frac{\sqrt{x}}{1 - 2x}$  
    e $y = \frac{x^2 - 3}{3x - x^2}$  
    f $y = \frac{x}{\sqrt{1 - 3x}}$  
  
2.  Find:  
    a $\frac{d}{dx}\left(\frac{x + 1}{3 - x}\right)$  
    b $\frac{d}{dx}\left(\frac{x^3}{2x - 1}\right)$  
    c $\frac{d}{dx}\left(\frac{\sqrt{x}}{3 - x^2}\right)$  
    d $\frac{d}{dx}\left(\frac{-x^2}{\sqrt{x^2 + 3}}\right)$  
  
3.  Find the gradient of the tangent to:  
    a $y = \frac{x}{1 - 2x}$ at $x = 1$  
    b $y = \frac{x^3}{x^2 + 1}$ at $x = -1$  
    c $y = \frac{\sqrt{x}}{2x + 1}$ at $x = 4$  
    d $y = \frac{x^2}{\sqrt{x^2 + 5}}$ at $x = -2$.  
  
4.  Suppose $f(x) = \frac{x}{\sqrt{x - 1}}$. Find $f'(x)$ using the quotient rule. Check your answer by writing $f(x) = \frac{x - 1}{\sqrt{x - 1}} + \frac{1}{\sqrt{x - 1}}$ and then differentiating.  
  
5.  a If $y = \frac{2\sqrt{x}}{1 - x}$, show that $\frac{dy}{dx} = \frac{x + 1}{\sqrt{x}(1 - x)^2}$.  
    b For what values of $x$ is $\frac{dy}{dx}$: i zero ii undefined?  
  
6.  a If $y = \frac{x^2 + 6}{2x + 1}$, show that $\frac{dy}{dx} = \frac{2x^2 + 2x - 12}{(2x + 1)^2}$.  
    b For what values of $x$ is $\frac{dy}{dx}$: i zero ii undefined?  
  
7.  a If $y = \frac{x^2 - 3x + 1}{x + 2}$, show that $\frac{dy}{dx} = \frac{x^2 + 4x - 7}{(x + 2)^2}$.  
    b For what values of $x$ is $\frac{dy}{dx}$: i zero ii undefined?  
  
---  
  
#### IB_Haese Exercise 18E : Diff of Exponential F.   
  
1.  Find the gradient function for $f(x)$ equal to:  
    a $e^{4x}$  
    b $e^{x} + 3$  
    c $e^{- 2x}$  
    d $\frac{x}{e^{2}}$  
    e $2e^{- \frac{x}{2}}$  
    f $1 - 2e^{- x}$  
    g $4e^{\frac{x}{2}} - 3e^{- x}$  
    h $\frac{e^{x} + e^{- x}}{2}$  
    i $e^{- x^{2}}$  
    j $\frac{1}{e^{x}}$  
    k $10(1 + e^{2x})$  
    l $20(1 - e^{- 2x})$  
    m $e^{2x + 1}$  
    n $\frac{x}{e^{4}}$  
    o $e^{1 - 2x^{2}}$  
    p $e^{- 0.02x}$  
  
2.  Find the derivative of:  
    a $x e^{x}$  
    b $x^{3}e^{- x}$  
    c $\frac{e^{x}}{x}$  
    d $\frac{x}{e^{x}}$  
    e $x^{2}e^{3x}$  
    f $\frac{e^{x}}{\sqrt{x}}$  
    g $20xe^{- 0.5x}$  
    h $\frac{e^{x} + 2}{e^{- x} + 1}$  
  
3.  Find the gradient function for $y$ equal to:  
    a $(2 + e^{x})^{4}$  
    b $\sqrt{e^{x} - 1}$  
    c $(e^{x} + e^{-x})^{\frac{3}{2}}$  
    d $\frac{1}{\sqrt{e^{2x} + 2}}$  
  
4.  Find the gradient of the tangent to:  
    a $y = (e^{x} + 2)^{4}$ at $x = 0$  
    b $y = \sqrt{e^{2x} + 10}$ at $x = \ln 3$  
  
5.  The graph of $f(x) = \sqrt{6 - e^{x}}$ is shown alongside.  
    a State the domain of the function.  
    b The point P has $y$-coordinate 2. Find exactly:  
        i the coordinates of P  
        ii the gradient of the tangent at P.  
  
6.  Given $f(x) = e^{kx} + x$ and $f'(0) = -8$ find $k$.  
  
7.  a By substituting $e^{\ln 2}$ for 2 in $y = 2^{x}$, find $\frac{dy}{dx}$.  
    b Show that if $y = b^{x}$ where $b > 0$, $b \neq 1$, then $\frac{dy}{dx} = b^{x} \times \ln b$.  
    c Find $\frac{dy}{dx}$ for: i $y = 5^{x}$ ii $y = 8 \times 10^{x}$  
  
8.  The tangent to $f(x) = x^{2}e^{- x}$ at point P is horizontal. Find the possible coordinates of P.  
  
9.  Suppose $S(x) = \frac{1}{2} (e^{x} - e^{- x})$ and $C(x) = \frac{1}{2} (e^{x} + e^{- x})$.  
    a Show that $[C(x)]^{2} - [S(x)]^{2} = 1$.  
    b Show that $\frac{d}{dx} [S(x)] = C(x)$.  
    c Find $\frac{d}{dx} [C(x)]$ in terms of $S(x)$.  
    d If $T(x) = \frac{S(x)}{C(x)}$, find $\frac{d}{dx} [T(x)]$ in terms of $C(x)$.  
  
---  
  
#### IB_Haese Exercise 18F : Diff of ln(x)  
  
1.  Find the gradient function of:  
    a $y = \ln (7x)$  
    b $y = \ln (2x + 1)$  
    c $y = \ln (x - x^2)$  
    d $y = 3 - 2\ln x$  
    e $y = x^2\ln x$  
    f $y = \frac{\ln x}{2x}$  
    g $y = e^x\ln x$  
    h $y = (\ln x)^2$  
    i $y = \sqrt{\ln x}$  
    j $y = e^{-x}\ln x$  
    k $y = \sqrt{x}\ln (2x)$  
    l $y = -4\ln (1 - x)$  
    m $y = \frac{2\sqrt{x}}{\ln x}$  
    n $y = x\ln (x^2 + 1)$  
    o $y = \frac{\ln x}{x^2}$  
  
2.  Given $f(x) = \ln (kx)$ where $k \neq 0$, find $f'(x)$. Use the laws of logarithms to explain why this derivative does not depend on the value of $k$.  
  
3.  Find $\frac{dy}{dx}$ for:  
    a $y = x\ln 5$  
    b $y = \ln (x^3)$  
    c $y = \ln (x^4 + x)$  
    d $y = \ln (10 - 5x)$  
    e $y = [\ln (2x + 1)]^3$  
    f $y = \frac{\ln(4x)}{x}$  
    g $y = \ln \left(\frac{1}{x}\right)$  
    h $y = \frac{1}{\ln x}$  
  
4.  Differentiate with respect to $x$:  
    a $y = \ln (x e^{-x})$  
    b $y = \ln \left[\frac{x^2}{(x + 2)(x - 3)}\right]$  
  
5.  Use the laws of logarithms to help differentiate with respect to $x$:  
    a $y = \ln \sqrt{1 - 2x}$  
    b $y = \ln \left(\frac{1}{2x + 3}\right)$  
    c $y = \ln \left(e^x \sqrt{x}\right)$  
    d $y = \ln \left(x \sqrt{2 - x}\right)$  
    e $y = \ln \left(\frac{x + 3}{x - 1}\right)$  
    f $y = \ln \left(\frac{x^2}{3 - x}\right)$  
  
6.  Differentiate with respect to $x$:  
    a $f(x) = \ln \left((3x - 4)^3\right)$  
    b $f(x) = \ln \left(x(x^2 + 1)\right)$  
    c $f(x) = \ln \left(\frac{x^2 + 2x}{x - 5}\right)$  
  
7.  Find the gradient of the tangent to $y = x \ln x$ at the point where $x = e$.  
  
8.  Suppose $f(x) = a \ln (bx^2)$ where $f(e) = 3$ and $f'(1) = 6$. Find the constants $a$ and $b$.  
  
9.  Suppose $f(x) = ax \ln (bx)$ where $f(1) = 12$ and $f'(1) = 16$. Find the constants $a$ and $b$.  
  
10. Find the point(s) at which the tangent to $y = \ln (15 - x^2)$ has gradient 1.  
  
---  
  
#### IB_Haese Exercise 18G : Diff of Trigonpometric F.  
  
1.  Find $\frac{dy}{dx}$ for:  
    a $y = \sin 2x$  
    b $y = \sin x + \cos x$  
    c $y = \cos 3x - \sin x$  
    d $y = \sin (x + 1)$  
    e $y = \cos (3 - 2x)$  
    f $y = \tan 5x$  
    g $y = \sin \frac{x}{2} - 3 \cos x$  
    h $y = 4 \sin x - \cos 2x$  
    i $y = \frac{1}{2} \cos 6x - 5 \sin 4x$  
  
2.  Differentiate with respect to $x$:  
    a $x^2 + \cos x$  
    b $\tan x - 3 \sin x$  
    c $e^{x} \cos x$  
    d $e^{- x} \sin x$  
    e $e^{2x} \tan x$  
    f $\ln (\sin x)$  
    g $3 \tan \pi x$  
    h $\cos \frac{x}{2}$  
    i $3 \tan 2x$  
    j $x \cos x$  
    k $\frac{\sin x}{x}$  
    l $x \tan x$  
    m $e^{\cos \sqrt{x}}$  
    n $\frac{2\sqrt{x}}{\tan x}$  
    o $\cos x + \sin 2x$  
  
3.  Differentiate with respect to $x$:  
    a $\sin (x^{2})$  
    b $\cos \sqrt{x}$  
    c $\sqrt{\cos x}$  
    d $\sin (e^{x})$  
    e $\sin^{2}x$  
    f $\cos^{3}x$  
    g $5\cos^{2}2x$  
    h $\cos x\sin 2x$  
    i $\cos (\cos x)$  
    j $\cos^{3}4x$  
    k $\frac{2}{\sin^{2}4x}$  
    l $\frac{1}{3}\tan^{2}2x$  
  
4.  Find the gradient of the tangent to:  
    a $f(x) = \sin^{3}x$ at the point where $x = \frac{2\pi}{3}$  
    b $f(x) = \tan (2x - \frac{\pi}{6})$ at the point where $x = \frac{\pi}{6}$  
    c $f(x) = \cos x\sin x$ at the point where $x = \frac{\pi}{4}$  
  
5.  Consider the function $f(x) = 2\cos^{2}x + 2\sin^{2}x + 1$.  
    a Find $f'(x)$.  
    b Explain your answer to a.  
  
6.  a Show that $\frac{\cos\theta + i\sin\theta}{e^{i\theta}}$ is a constant by showing that its derivative is zero.  
    b Find the value of this constant by substituting $\theta = 0$.  
    c Hence establish Euler's formula: $e^{i\theta} = \cos \theta + i\sin \theta$.  
  
---  
  
#### IB_Haese Exercise 18H : Seecond Derivative   
  
1.  Find $f''(x)$ given that:  
    a $f(x) = 3x^{2} - 6x + 2$  
    b $f(x) = \frac{2}{\sqrt{x}} - 1$  
    c $f(x) = 2x^{3} - 3x^{2} - x + 5$  
    d $f(x) = \frac{2 - 3x}{x^{2}}$  
    e $f(x) = (1 - 2x)^{2}$  
    f $f(x) = \frac{x + 2}{2x - 1}$  
  
2.  Find $\frac{d^{2}y}{dx^{2}}$ given that:  
    a $y = x - x^{3}$  
    b $y = x^{2} - \frac{5}{x^{2}}$  
    c $y = 2 - \frac{3}{\sqrt{x}}$  
    d $y = \frac{4 - x}{x}$  
    e $y = (x^{2} - 3x)^{2}$  
    f $y = x^{2} - x + \frac{1}{1 - x}$  
    g $y = e^{3x} + 2x$  
    h $y = \frac{1 - e^{- x}}{x}$  
    i $y = \frac{3 - x}{xe^{x}}$  
  
3.  Given $f(x) = x^{3} - 2x + 5$, find:  
    a $f(2)$  
    b $f'(2)$  
    c $f''(2)$  
  
4.  Find the value(s) of $x$ such that $f''(x) = 0$, given:  
    a $f(x) = 2x^{3} - 6x^{2} + 5x + 1$  
    b $f(x) = x^{4} - 10x^{3} + 36x^{2} - 72x + 108$  
  
5.  Consider the function $f(x) = 2x^{3} - x$. Copy and complete the table alongside by indicating whether $f(x)$, $f'(x)$, and $f''(x)$ are positive $(+)$, negative $(-)$, or zero $(0)$ at the given values of $x$.  
    (Table for x = -1, 0, 1)  
  
6.  Given $f(x) = x^{2} - \frac{1}{x}$, find:  
    a $f(1)$  
    b $f'(1)$  
    c $f''(1)$  
  
7.  Given $f(x) = 3e^{x} - 2x$, find:  
    a $f(1)$  
    b $f'(1)$  
    c $f''(1)$  
  
8.  Find $\frac{d^{2}y}{dx^{2}}$ given that:  
    a $y = 3\tan x$  
    b $y = x\sin x$  
    c $y = \sin^{2}3x$  
    d $y = \frac{\cos^{2}x - x}{x^{2}}$  
    e $y = e^{- x}\sin x$  
    f $y = \tan (x^{2})$  
  
9.  Suppose $y = Ae^{kx}$ where $A$ and $k$ are constants. Show that:  
    a $\frac{dy}{dx} = ky$  
    b $\frac{d^{2}y}{dx^{2}} = k^{2}y$  
  
10. Suppose $f(x) = 2\sin^{3}x - 3\sin x$  
    a Show that $f'(x) = -3\cos x\cos 2x$  
    b Find $f''(x)$  
  
11. Given $f(x) = \frac{2}{3}\sin 3x$, find $f''\left(\frac{2\pi}{9}\right)$.  
  
12. Find $\frac{d^2y}{dx^2}$ given:  
    a $y = -\ln x$  
    b $y = x\ln x$  
    c $y = (\ln x)^2$  
  
13. If $y = 2e^{3x} + 5e^{4x}$, show that $\frac{d^2y}{dx^2} - 7\frac{dy}{dx} + 12y = 0$.  
  
14. If $y = \sin (2x + 3)$, show that $\frac{d^2y}{dx^2} +4y = 0$.  
  
15. If $y = 2\sin x + 3\cos x$, show that $\frac{d^2y}{dx^2} +y = 0$.  
  
---  
  
#### IB_Haese REVIEW SET 18A : Derivative  
  
1.  Find $f'(x)$ given that $f(x)$ is:  
    a $5x^{3}$  
    b $x^{6} - 5x$  
    c $7x^{2} - \frac{3}{x}$  
    d $3x - \frac{4}{x^2}$  
    e $2x\sqrt{x}$  
    f $4\sqrt{x} - \frac{1}{\sqrt{x}}$  
  
2.  Find $\frac{dy}{dx}$ for:  
    a $y = 3x^2 - x^4$  
    b $y = \frac{x^3 - x}{x^2}$  
    c $y = x^2\sqrt{x - 2}$  
  
3.  a Find $f'(x)$ given $f(x) = \frac{x}{\sqrt{x^2 + 1}}$  
    b At what point on the curve $y = f(x)$ does the tangent have gradient 1?  
  
4.  Find $\frac{dy}{dx}$ if:  
    a $y = e^{x^3 + 2}$  
    b $y = \ln \left(\frac{x + 3}{x^2}\right)$  
    c $y = x^3 e^{2x}$  
  
5.  Find the gradient of the tangent to:  
    a $f(x) = -x^2 +4x - 2$ at $(-3, -23)$  
    b $y = (2 - 3x)^5$ at $x = 1$  
  
6.  Differentiate with respect to $x$:  
    a $5x - 3x^{-1}$  
    b $(3x^2 +\sqrt{x})^4$  
    c $(x^2 +1)(1 - x^2)^3$  
  
7.  Find all points on the curve $y = 2x^3 +3x^2 - 10x + 3$ where the gradient of the tangent is 2.  
  
8.  Differentiate with respect to $x$:  
    a $\sin 5x\ln x$  
    b $\sin x\cos 2x$  
    c $e^{-2x}\tan x$  
  
9.  Find the gradient of the tangent to $y = \sin^2 x$ at the point where $x = \frac{\pi}{3}$.  
  
10. Consider the function $f(x) = \frac{x^2 - 4x - 1}{e^x}$.  
    a Find $f'(x)$.  
    b Find the gradient of the tangent to $y = f(x)$ at $x = 1$.  
    c For what values of $x$ is the tangent to $y = f(x)$ horizontal?  
  
11. Given $y = 3e^{x} - e^{-x}$, show that $\frac{d^{2}y}{dx^{2}} = y$.  
  
12. Find the derivative with respect to $x$ of:  
    a $f(x) = (x^{2} + 3)^{4}$  
    b $g(x) = \frac{\sqrt{x + 5}}{x^{2}}$  
    c $h(x) = \frac{e^{4x}}{1 - 2x}$  
  
13. The graph of $y = \sin x \cos x$ is shown alongside.  
    a Find $\frac{dy}{dx}$.  
    b Show that $y = \frac{1}{2} \sin 2x$ has the same derivative.  
    c Find the gradient of the illustrated tangent.  
  
14. For $f(x) = 2 \sin x + \cos 2x$, find:  
    a $f(\frac{\pi}{2})$  
    b $f'(\frac{\pi}{2})$  
    c $f''(\frac{\pi}{2})$  
  
15. Find the gradient of the tangent to $y = 3 \tan \frac{x}{2}$ at $x = \frac{\pi}{3}$.  
  
16. Find $\frac{d^{2}y}{dx^{2}}$ for:  
    a $y = \frac{1}{8} x^{4} + \frac{1}{6} x^{3} - \frac{1}{4} x^{2}$  
    b $y = xe^{-x}$  
  
17. For the function $f(x) = \sqrt{x} \cos 4x$:  
    a Find $f'(x)$ and $f''(x)$.  
    b Hence find: i $f'(\frac{\pi}{16})$ ii $f''(\frac{\pi}{8})$  
  
---  

#### IB_Haese REVIEW SET 18B :   
  
1.  Find $f'(x)$ given that $f(x)$ is:  
    a $3x^{2} - 7x + 4$  
    b $(x + 5)^{2}$  
    c $2\sqrt{x} - \frac{3}{x}$  
    d $6x^{2}\sqrt{x}$  
  
2.  Find $\frac{dy}{dx}$ for:  
    a $y = 2x^{3} - 6x^{2} + 7x - 4$  
    b $y = \frac{3}{x} - \frac{5}{x^{3}}$  
    c $y = \frac{15}{\sqrt[3]{x}}$  
  
3.  If $f(x) = 7 + x - 3x^{2}$, find:  
    a $f(3)$  
    b $f'(3)$  
    c $f''(3)$  
  
4.  Differentiate with respect to $x$:  
    a $y = x^{3}\sqrt{1 - x^{2}}$  
    b $y = \frac{x^{2} - 3x}{\sqrt{x + 1}}$  
    c $y = x^{3} - x + \frac{1}{\sqrt{x}}$  
  
5.  a Find $\frac{dy}{dx}$ for $y = xe^{x}$.  
    b Find all points on the curve $y = xe^{x}$ where the gradient of the tangent is $2e$.  

# End
