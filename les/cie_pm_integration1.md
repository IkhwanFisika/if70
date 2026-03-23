# PM1 Integration

### 1. Basic Integration Rules

**Indefinite Integral (Antiderivative)**
If $F'(x) = f(x)$, then the indefinite integral is:
$$\int f(x) \, dx = F(x) + C$$
where $C$ is the constant of integration.

**General Rules**
- **Constant multiple rule**:
  $$\int k f(x) \, dx = k \int f(x) \, dx$$
- **Sum/Difference rule**:
  $$\int [f(x) \pm g(x)] \, dx = \int f(x) \, dx \pm \int g(x) \, dx$$

**Standard Integrals**
$$
\begin{aligned}
\int k \, dx &= kx + C \\
\int x^n \, dx &= \frac{x^{n+1}}{n+1} + C, \quad n \neq -1 \\
\int \frac{1}{x} \, dx &= \ln|x| + C, \quad x \neq 0 \\
\int e^x \, dx &= e^x + C \\
\int \cos x \, dx &= \sin x + C \\
\int \sin x \, dx &= -\cos x + C \\
\int \sec^2 x \, dx &= \tan x + C
\end{aligned}
$$

---

### 2. Integration of Linear Composites $f(ax + b)$

For $a \neq 0$:
$$
\begin{aligned}
\int (ax + b)^n \, dx &= \frac{1}{a} \cdot \frac{(ax + b)^{n+1}}{n+1} + C, \quad n \neq -1 \\
\int e^{ax+b} \, dx &= \frac{1}{a} e^{ax+b} + C \\
\int \frac{1}{ax+b} \, dx &= \frac{1}{a} \ln|ax+b| + C \\
\int \cos(ax+b) \, dx &= \frac{1}{a} \sin(ax+b) + C \\
\int \sin(ax+b) \, dx &= -\frac{1}{a} \cos(ax+b) + C \\
\int \frac{1}{\cos^2(ax+b)} \, dx &= \frac{1}{a} \tan(ax+b) + C
\end{aligned}
$$

---

### 3. Integration by Substitution

If $u = g(x)$ and $\frac{du}{dx} = g'(x)$, then:
$$
\int f(g(x)) \, g'(x) \, dx = \int f(u) \, du
$$

For definite integrals, change the limits:
$$
\int_{x=a}^{b} f(g(x)) \, g'(x) \, dx = \int_{u=g(a)}^{g(b)} f(u) \, du
$$

This reverses the chain rule.

---

### 4. Definite Integrals

**Definition** (as limit of sums):
$$
\int_a^b f(x) \, dx = \lim_{n \to \infty} \sum_{i=1}^n f(x_i^*) \, \Delta x
$$

**Fundamental Theorem of Calculus**:
If $F'(x) = f(x)$, then:
$$
\int_a^b f(x) \, dx = F(b) - F(a)
$$

**Properties**:
$$
\begin{aligned}
\int_a^b k f(x) \, dx &= k \int_a^b f(x) \, dx \\
\int_a^b [f(x) \pm g(x)] \, dx &= \int_a^b f(x) \, dx \pm \int_a^b g(x) \, dx \\
\int_a^b f(x) \, dx &= -\int_b^a f(x) \, dx \\
\int_a^c f(x) \, dx &= \int_a^b f(x) \, dx + \int_b^c f(x) \, dx
\end{aligned}
$$

---

### 5. Area Under a Curve

- If $f(x) \ge 0$ on \([a, b]\), area between $y = f(x)$ and the $x$-axis is:
  $$
  A = \int_a^b f(x) \, dx
  $$
- If $f(x) \le 0$ on \([a, b]\), area is:
  $$
  A = -\int_a^b f(x) \, dx
  $$
- Total area (where curve crosses axis):
  $$
  A = \int_a^b |f(x)| \, dx
  $$

---

### 6. Area Between Curve and y‑Axis

If $x = f^{-1}(y)$ is invertible on $c \le y \le d$, area between curve and $y$-axis is:
$$
A = \int_c^d |f^{-1}(y)| \, dy
$$
Alternatively, for $x = g(y) \ge 0$:
$$
A = \int_c^d g(y) \, dy
$$

---

### 7. Volume of Revolution

**About the $x$-axis** (disc method):
$$
V = \pi \int_a^b [f(x)]^2 \, dx
$$
where region from $y = f(x)$, $x = a$, $x = b$ is rotated about the $x$-axis.

**About the $y$-axis**:
If $x = g(y)$ is invertible:
$$
V = \pi \int_c^d [g(y)]^2 \, dy
$$

---

### 8. Applications of Integration

- **Net change**: If $R(t)$ is a rate of change, then:
  $$
  \int_a^b R(t) \, dt = \text{total change in quantity from } t = a \text{ to } t = b
  $$
- **Particular solutions**: Given $f'(x)$ and an initial condition $f(a) = b$, the constant of integration can be determined.
- **Second derivatives**: Given $f''(x)$ and conditions on $f'$ and $f$, integrate twice to find $f(x)$.

---

This summary captures the core definitions and properties from the integration chapters in the provided files.

# Drill IB Math AI Haese

#### IB AI Haese **EXERCISE 22B** : Basic Integration

1. Find:  
a. $\int (x^{2} + 3x - 2)dx$  
b. $\int (2x^{2} - 3x + 1)dx$  
c. $\int (- x^{3} + 4x^{2} - 3)dx$  
d. $\int (\frac{1}{2} x + x^{2} + x^{3})dx$  
e. $\int (x^{4} - x^{2} - x + 2)dx$  
f. $\int (4x^{2} + \frac{1}{x})dx$  
g. $\int (2\sqrt{x} -\frac{3}{\sqrt{x}})dx$  
h. $\int (\frac{1}{3x} -\frac{2}{x^{2}})dx$  
i. $\int (x\sqrt{x} - 9)dx$  
j. $\int (3x^{-\frac{3}{2}} + x^{\frac{1}{4}})dx$  
  
2. Integrate with respect to $x$ :  
a. $2e^{x} - 3x$  
b. $\frac{4}{x} +x^{2} - e^{x}$  
c. $5e^{x} + \frac{1}{2} x^{2}$  
d. $3\sin x - 2$  
e. $4x - 2\cos x$  
f. $\sin x - 2\cos x + e^{x}$  
g. $x^{2}\sqrt{x} - 10\sin x$  
h. $\frac{x(x - 1)}{3} +\frac{1}{\cos^{2}x}$  
i. $-\sin x + 2\sqrt{x}$  
  
3. Find $y$ if:  
a. $\frac{dy}{dx} = 6$  
b. $\frac{dy}{dx} = 4x^{2}$  
c. $\frac{dy}{dx} = \frac{1}{x^{2}}$  
d $\frac{dy}{dx} = \frac{2}{\sqrt[3]{x}}$  
e. $\frac{dy}{dx} = 2x^{3} - 4$  
f. $\frac{dy}{dx} = 4x^{3} + 3x^{2}$  
g. $\frac{dy}{dx} = 2 - \frac{1}{x}$  
h. $\frac{dy}{dx} = \sin x + 2\cos x$  
i. $\frac{dy}{dx} = 2e^{x} - 5 + x$  
  
4. Find:  
a. $\int (2e^{t} - 4\sin t)dt$  
b. $\int (3\cos t - \frac{1}{t})dt$  
c. $\int (5\sin t - \sqrt{t})dt$  
d. $\int (\frac{1}{\cos^{2}x} +2\sin x)dx$  
e. $\int (\theta -\sin \theta)d\theta$  
f. $\int (\frac{2}{\theta} -\frac{1}{\cos^{2}\theta})d\theta$  
  
5. Find:  
a. $\int(2x+1)^{2}dx$  
b. $\int\left(x+\frac{1}{x}\right)^{2}dx$  
c. $\int\frac{1-4x}{x\sqrt{x}}dx$  
d. $\int\frac{2x-1}{\sqrt{x}}dx$  
e. $\int\left(\sqrt{x}-\frac{1}{\sqrt{x}}\right)^{2}dx$  
f. $\int\frac{1-x^{2}}{x}dx$  
g. $\int\left(\frac{2}{x}+1\right)^{2}dx$  
h. $\int\frac{x^{2}-4x+10}{x}dx$  
i. $\int\frac{3x^{3}-2x^{2}+5}{x^{2}}dx$  
  
6. Find $f(x)$ if:  
a. $f^{\prime}(x) = (1 - 2x)^{2}$  
b. $f^{\prime}(x) = \sqrt{x} -\frac{2}{\sqrt{x}}$  
c. $f^{\prime}(x) = \frac{x^{2} - 5}{x^{2}}$  
  
7. Find:  
a. $\int \left(\sqrt{x} +\frac{1}{2}\cos x\right)dx$  
b. $\int \left(2e^{x} - 4\sin x\right)dx$  
c. $\int \left(3\cos x - \sin x\right)dx$  
  
8. Find:  
a. $\int \left(x^{2} - \frac{1}{x}\right)^{2}dx$  
b. $\int \frac{x^{2} - 4x + 2}{\sqrt{x}} dx$  
c. $\int \sqrt{x}\left(3x - 1\right)^{2}dx$  
  
---  
  
#### IB AI Haese **EXERCISE 22C** : Curve equation from gradient
  
1. Find $f(x)$ given that:  
a. $f^{\prime}(x) = 2x - 1 \mathrm{and} f(0) = 3$  
b. $f^{\prime}(x) = 2 + \frac{1}{\sqrt{x}} \mathrm{and} f(1) = 1$  
c. $f^{\prime}(x) = \sqrt{x} -2 \mathrm{and} f(4) = 0$  
  
2. A curve has gradient function $\frac{dy}{dx} = x - 2x^2$ and passes through (2, 4). Find the equation of the curve.  
  
3. A curve has gradient function $\frac{dy}{dx} = 1 - e^x$ and passes through $(3,e^3)$ . Find the equation of the curve.  
  
4. Find $f(x)$ given that:  
a. $f^{\prime}(x) = x^{2} - 4\cos x \mathrm{and} f(0) = 3$  
b. $f^{\prime}(x) = \sqrt{x} -\frac{2}{\cos^{2}x} \mathrm{and} f(\pi) = 0$  
  
5. A curve has gradient function $f^{\prime}(x) = ax + 1$ where $a$ is a constant. Find $f(x)$ given that $f(0) = 3$ and $f(3) = - 3$ .  
  
6. A curve has gradient function $f^{\prime}(x) = ax^{2} + bx$ where $a,b$ are constants. Find $f(x)$ given that $f(- 1) = - 2$ , $f(0) = 1$ , and $f(1) = 4$ .  
  
7. Find $f(x)$ given that:  
a. $f^{\prime \prime}(x) = 2x + 1, f^{\prime}(1) = 3, \text{and} f(2) = 7$  
b. $f^{\prime \prime}(x) = 15\sqrt{x} +\frac{3}{\sqrt{x}}, f^{\prime}(1) = 12, \text{and} f(0) = 5$  
c. $f^{\prime \prime}(x) = \cos x, f^{\prime}\left(\frac{\pi}{2}\right) = 0, \text{and} f(0) = 3$  
d. $f^{\prime \prime}(x) = 2x \text{and the points} (1, 0) \text{and} (0, 5) \text{lie on the curve} y = f(x).$  
  
8. Suppose $f^{\prime \prime}(x) = 3e^{- x}$ $f(1) = \frac{3}{e}$ and $f(3) = \frac{3}{e^{3}} - 2$ . Find $f(x)$  
  
---  
  
#### IB AI Haese **EXERCISE 22D** : Integration by Substitution
1. Find:  
a. $\int (2x + 5)^{3}dx$  
b. $\int (4x - 3)^{7}dx$  
c. $\int 3(1 - x)^{4}dx$  
d. $\int \frac{1}{(3 - 2x)^{2}} dx$  
e. $\int \frac{4}{(2x - 1)^{4}} dx$  
f. $\int \sqrt{3x - 4} dx$  
g. $\int \frac{10}{\sqrt{1 - 5x}} dx$  
h. $\int \frac{4}{\sqrt{3 - 4x}} dx$  
i. $\int \frac{5}{(3x - 2)^{3}} dx$  
2. Find $y = f(x)$ given $\frac{dy}{dx} = \sqrt{2x - 7}$ and that $f(8) = 11$ .  
3. The function $f(x)$ has gradient function $f^{\prime}(x) = \frac{4}{\sqrt{1 - x}}$ , and the curve $y = f(x)$ passes through the point $(- 3, - 11)$ .  
Find the point on the graph of $y = f(x)$ with $x$ - coordinate $- 8$ .  
4. Find:  
a. $\int 3(2x - 1)^{2}dx$  
b. $\int (4x - 5)^{2}dx$  
c. $\int (1 - 3x)^{3}dx$  
d. $\int (2 - 5x)^{2}dx$  
e. $\int 4\sqrt{5 - x} dx$  
f. $\int (7x + 1)^{4}dx$  
5. Find an expression for $y$ given that $\frac{dy}{dx} = x - \frac{5}{(1 - x)^{2}}$ and that the curve passes through (2, 0).  
6. Integrate with respect to $x$ :  
a. sin 3x  
b. $2\cos (- 4x) + 1$  
c. $3\sin 2x - e^{- x}$  
d. $3\cos \frac{\pi}{2}$  
e. $2\sin (2x + \frac{\pi}{6})$  
f. $- 3\cos \left(\frac{\pi}{4} - x\right)$  
g. $e^{2x} - \frac{2}{\cos^{2}(\frac{\pi}{2})}$  
h. $2\sin 3x + 5\cos 4x$  
i. $\frac{4}{\cos^{2}(\frac{\pi}{3} - 2x)}$  
j. cos 2x + sin 2x  
k. $\frac{1}{2}\cos 8x - 3\sin x$  
l. cos2x  
7. Find:  
a. $\int (2e^{x} + 5e^{2x})dx$  
b. $\int (3e^{5x - 2})dx$  
c. $\int (e^{7 - 3x})dx$  
d. $\int (e^{x} + e^{- x})^{2}dx$  
e. $\int (e^{- x} + 2)^{2}dx$  
f. $\int \frac{(e^{2x} - 5)^{2}}{e^{x}} dx$  
8. Find an expression for $y$ given that $\frac{dy}{dx} = (1 - e^{x})^{2}$ , and that the graph has $y$ - intercept 4.  
9. Find $f(x)$ given $f^{\prime}(x) = 2e^{- 2x}$ and $f(0) = 3$  
10. Suppose $f^{\prime}(x) = p\sin {\frac{x}{2}}$ $f(0) = 1$ , and $f(2\pi) = 0$ .Find $p$ and hence $f(x)$  
11. Consider a function $g$ such that $g^{\prime \prime}(x) = - \sin 2x$  
Show that the gradients of the tangents to $y = g(x)$ when $x = \pi$ and $x = - \pi$ are equal.  
12. A curve has gradient function $\sqrt{x} +\frac{1}{2} e^{- 4x}$ and passes through (1, 0). Find the equation of the function.  
13. Find:  
a. $\int\frac{6}{x+4}dx$  
b. $\int\frac{1}{2x-1}dx$  
c. $\int\frac{5}{1-3x}dx$  
d. $\int\left(4+\frac{1}{5x-2}\right)dx$  
e. $\int\left(1-2x+\frac{4}{x-3}\right)dx$  
f. $\int\left(\sin2x-\frac{3}{1-2x}\right)dx$  
14. To find $\int \frac{1}{4x} dx$ , Tracy's answer was $\int \frac{1}{4x} dx = \frac{1}{4}\ln |4x| + c.$  
Nadine's answer was $\int \frac{1}{4x} dx = \frac{1}{4}\int \frac{1}{x} dx = \frac{1}{4}\ln |x| + c.$  
Which of them has found the correct answer? Prove your statement.  
15. Show that $\frac{3x - 1}{x + 2}$ may be written in the form $3 - \frac{7}{x + 2}$ . Hence find $\int \frac{3x - 1}{x + 2} dx.$  
16. Find $f(x)$ given $f^{\prime}(x) = 2x - \frac{2}{1 - x}$ and $f(- 1) = 3$  

---  
  
#### IB AI Haese **EXERCISE 22E** : Integration by Substitution 2
  
1. Differentiate $(2x^{2} - 5x)^{3}$ , and hence find $\int (4x - 5)(2x^{2} - 5x)^{2}dx$ .  
  
2. Differentiate $\sin (x^{2})$ , and hence find $\int x\cos (x^{2})dx$ .  
  
3. Differentiate $\ln (5 - 3x + x^{2})$ , and hence find $\int \frac{4x - 6}{5 - 3x + x^{2}} dx$ .  
  
4. Use the substitution given to perform each integration:  
a. ${\int 3x^{2}(x^{3}+1)^{4}d x\quad\mathrm{using}\quad u=x^{3}+1}$  
b. ${\int x^{2}e^{x^{3}+1}d x\quad\mathrm{using}\quad u=x^{3}+1}$  
c. ${\int \sin^{4}x\cos x d x\quad\mathrm{using}\quad u=\sin x}$  
d. ${\int 2x\cos(x^{2}-3)d x\quad\mathrm{using}\quad u=x^{2}-3}$  
  
5. Integrate by substitution:  
a. ${4x^{3}(2+x^{4})^{3}}$  
b. ${\frac{2x}{\sqrt{x^{2}+3}}}$  
c. ${\frac{6x^{2}}{(2x^{3}-1)^{4}}}$  
d. ${(x^{3}+2x+1)^{4}(3x^{2}+2)}$  
e. ${\frac{x}{(1-x^{2})^{5}}}$  
f. ${\frac{x+2}{(x^{2}+4x-3)^{2}}}$  
  
6. Find:  
a. ${\int-2e^{1-2x}d x}$  
b. ${\int2x e^{x^{2}}d x}$  
c. ${\int\frac{e^{\sqrt{x}}}{\sqrt{x}}d x}$  
  
7. Find:  
a. ${\int\frac{2x}{x^{2}+1}d x}$  
b. ${\int\frac{x}{2-x^{2}}d x}$  
c. ${\int\frac{2x-3}{x^{2}-3x}d x}$  
  
8. Integrate with respect to $x$ :  
a. ${x^{2}(3-x^{3})^{2}}$  
b. ${x\sqrt{1-x^{2}}}$  
c. ${x e^{1-x^{2}}}$  
d. ${\frac{(\ln x)^{3}}{x}}$  
e. ${(2x-1)e^{x-x^{2}}}$  
f. ${\frac{1-x^{2}}{x^{3}-3x}}$  
  
9. Integrate with respect to $x$ :  
a. ${\sin^{7}x\cos x}$  
b. ${\cos^{5}x\sin x}$  
c. ${\frac{\sin x}{\sqrt{\cos x}}}$  
d. ${\tan x}$  
e. ${\sqrt{\sin x}\cos x}$  
f. ${\frac{\cos x}{(2+\sin x)^{2}}}$  
g. ${\frac{\sin x}{1-\cos x}}$  
h. ${\frac{\cos 2x}{\sin 2x-3}}$  
i. ${x\sin(x^{2})}$  
  
10. Find:  
a. $\int \frac{e^{\tan x}}{\cos^{2}x} dx$  
b. $\int \cos^{3}x dx$  
c. $\int \sin^{3}2x\cos 2x dx$  
  
---  
  
#### IB AI Haese **REVIEW SET 22A**  
  
1. Find the derivative of $x^{4} - x^{2}$ , and hence find $\int (2x^{3} - x)dx$ .  
  
2. Find the derivative of $\sin \left(\frac{\pi}{3} - 2x\right)$ , and hence find $\int \cos \left(\frac{\pi}{3} - 2x\right)dx$ .  
  
3. Find:  
a $\int \left(\sqrt{x} -\frac{2}{x^{2}}\right)dx$  
b $\int \left(2x - \frac{3}{\sqrt[3]{x}}\right)dx$  
c $\int \frac{6x + 5}{\sqrt{x}} dx$  
  
4 Integrate with respect to $x$ :  
a $\frac{4}{\sqrt{x}}$  
b $\frac{1}{3} x^{3} + 2x$  
c $\frac{1 - 2x}{x^{3}}$  
  
5. Find:  
a $\int (-3x^{4} + 6x^{2})dx$  
b $\int \frac{3x^{3} - x^{2} - 1}{x^{2}} dx$  
c $\int (2x - \sqrt{x})^{2}dx$  
d $\int \left(4e^{x} - \frac{3}{x}\right)dx$  
e $\int \sin (4x - 5)dx$  
f $\int e^{4 - 3x}dx$  
  
6. Find $y$ if:  
a $\frac{d y}{d x} = 3e^{-x} - 2\sin \left(\frac{\pi}{2} -x\right)$  
b $\frac{d y}{d x} = \cos 4x - \frac{1}{2} x^{2}$  
  
7. Given that $f^{\prime}(x) = 3x^{2} - 4x + 1$ and $f(0) = 2$ , find $f(x)$ .  
  
8. The curve $y = f(x)$ shown alongside has gradient function $f^{\prime}(x) = ax + 3$ . Find the equation of the curve.  
  
9. Given that $f^{\prime}(x) = 3e^{2x}$ and $f(0) = 2$ , find $f(x)$ .  
  
10. Find:  
a $\int \frac{x^{2} - 7}{x} dx$  
b $\int \left(e^{2x - 3} - \frac{2}{3x - 1}\right)dx$  
c $\int \left((4 - 3x)^{3} + \sin (-2x)\right)dx$  
  
11. A curve has gradient function $f^{\prime}(x) = a\cos 3x$ where $a$ is a constant. $f(0) = - 1$ and $f(\frac{\pi}{4}) = 1$ . Find $a$ and hence $f(x)$ .  
  
12. Find the derivative of $\sqrt{x^{2} - 4}$ , and hence find $\int \frac{x}{\sqrt{x^{2} - 4}} dx$ .  
  
13. Find $\int x\sin \left(x^{2} + \frac{\pi}{3}\right)dx$ using $u = x^{2} + \frac{\pi}{3}$ .  
  
14. Integrate by substitution:  
a $\int \frac{2x}{\sqrt{x^2 - 5}} dx$  
b $\int 4xe^{-x^2} dx$  
  
---  
  
**REVIEW SET 22B**  
  
1. Find the derivative of $6e^{- 2x}$ , and hence find $\int e^{- 2x} dx$ .  
  
2. Find the derivative of $\ln (2x + 1)$ , and hence find $\int \frac{1}{2x + 1} dx$ .  
  
3. Integrate with respect to $x$ :  
a. $\frac{x^2 - 2}{x^2}$  
b. $(3x - 4)^2$  
c. $4 - 2x^2$  
  
4. Find:  
a. $\int \left(x^{\frac{1}{3}} + 3\right) dx$  
b. $\int (3x^2 - 2) dx$  
c. $\int (3 + 2x)^2 dx$  
  
5. Given that $f'(x) = x^2 - 3x + 2$ and $f(1) = 3$ , find $f(x)$ .  
  
6. Find $y$ if:  
a. $\frac{dy}{dx} = (x^2 - 1)^2$  
b. $\frac{dy}{dx} = 400 - 20x^{-\frac{1}{2}}$  
  
7. Find:  
a. $\int (2x^3 - 5x + 7) dx$  
b. $\int (3x - \frac{1}{x}) dx$  
c. $\int (2e^{-x} + 3) dx$  
d. $\int 4\cos 2x dx$  
e. $\int (3 + e^{2x - 1})^2 dx$  
f. $\int \frac{1}{\cos^2(\frac{\pi}{4} - x)} dx$  
  
8. Find $f(x)$ given $f'(x) = \frac{2}{x} - 1$ and $f(2) = e$ .  
  
9. A curve has gradient function $\frac{dy}{dx} = ax^2 + b\sqrt{x - 1}$ where $a, b$ are constants.  
Find the equation of the curve given that it contains the points (1, 4), (2, 4), and (5, 1).  
  
10. Find $f(x)$ given $f'(x) = \frac{3}{\sqrt{4 - 3x}}$ and $f(- 4) = 0$ .  
  
11. Find:  
a. $\int \frac{1}{3 - 2x} dx$  
b. $\int \frac{4}{5x + 1} dx$  
  
12. By differentiating $(3x^2 + x)^3$ , find $\int (3x^2 + x)^2 (6x + 1) dx$ .  
  
13. Integrate by substitution:  
a $\int \frac{2x}{\sqrt{x^2 - 5}} dx$  
b $\int 4xe^{-x^2} dx$  
  
14. Find $\int \frac{x}{x^2 - 9} dx$ using the substitution:  
a. $u = x^{2} - 9$  
b. $x = 3\sin t$  
c. $\int \frac{\sin x}{\cos^4 x} dx$  
d. $\int \sin^3 x dx$  

---

#### IB AI Haese **EXERCISE 23A** : Definite Integral
  
**1. Find:**  
a. $\int_{1}^{4}\sqrt{x} dx$ and $\int_{1}^{4}-\sqrt{x} dx$   
b. $\int_{0}^{1}x^{7}dx$ and $\int_{0}^{1}(-x^{7})dx$  
  
**2. Find:**  
a. $\int_{0}^{1}x^{2}dx$  
b. $\int_{1}^{2}x^{2}dx$  
c. $\int_{0}^{2}x^{2}dx$  
d. $\int_{0}^{1}3x^{2}dx$  
  
**3. Find:**  
a. $\int_{0}^{2}(x^{3} - 4x)dx$  
b. $\int_{2}^{3}(x^{3} - 4x)dx$  
c. $\int_{0}^{3}(x^{3} - 4x)dx$  
  
**4. Find:**  
a. $\int_{0}^{1}2x^{2}dx$  
b. $\int_{0}^{1}\sqrt{x}dx$  
c. $\int_{0}^{1}(2x^{2} + \sqrt{x})dx$  
  
**5. Evaluate:**  
a. $\int_{0}^{1}x^{3}dx$  
b. $\int_{0}^{2}(x^{2} - x)dx$  
c. $\int_{0}^{2}(3x^{2} - x + 6)dx$  
d. $\int_{1}^{4}\left(x - \frac{3}{\sqrt{x}}\right)dx$  
e. $\int_{1}^{4}(x + 2\sqrt{x})dx$  
f. $\int_{4}^{9}\frac{x - 3}{\sqrt{x}}dx$$  
g. $\int_{1}^{3}\frac{1}{x^{2}}dx$  
h. $\int_{1}^{2}(x + 3)^{2}dx$  
i. $\int_{1}^{4}\left(x^{2} + \frac{1}{x}\right)dx$  
  
6. Find $m$ such that $\int_{m}^{2m}(2x - 1)d x = 4$  
  
**7. Find:**  
a. $\int_{0}^{1}(3x + 1)^{4}dx$  
b. $\int_{2}^{6}\frac{1}{\sqrt{2x - 3}}dx$  
c. $\int_{-3}^{0}\sqrt{1 - x}dx$  
  
**8. Evaluate:**  
a. $\int_{0}^{1}e^{x}dx$  
b. $\int_{0}^{3}(2e^{x} - 3)dx$  
c. $\int_{0}^{2}e^{3x}dx$  
d. $\int_{0}^{1}e^{1 - x}dx$  
e. $\int_{0}^{\ln 4}e^{x}(e^{x} - 2)dx$  
f. $\int_{1}^{2}(e^{-x} + 1)^{2}dx$  
  
**9. Evaluate:**  
a. $\int_{0}^{\frac{\pi}{6}}\cos x dx$  
b. $\int_{\frac{\pi}{3}}^{\frac{\pi}{2}}\sin x dx$  
c. $\int_{\frac{\pi}{4}}^{\frac{\pi}{3}}\frac{1}{\cos^{2}x} d$x  
d. $\int_{0}^{\frac{\pi}{6}}\sin 3x dx$  
e. $\int_{\frac{\pi}{6}}^{\frac{\pi}{2}}\cos (x - \frac{\pi}{3})dx$  
f. $\int_{\frac{\pi}{4}}^{\frac{\pi}{2}}\sin (2x - \frac{\pi}{4})dx$  
  
10. Evaluate: $\int_{0}^{\frac{\pi}{6}}(\sin 3x - \cos x)dx$  
11. Write $\int_{3}^{12}\frac{1}{x} dx$ as a single logarithm.  

**12. Find:**  
a. $\int_{-6}^{-2}\frac{1}{x} dx$  
b. $\int_{-1}^{5}\frac{1}{x + 4} dx$  
c. $\int_{1}^{8}\frac{2}{3x + 4} dx$  
d. $\int_{-4}^{0}\frac{4}{5 - 2x} dx$  
  
13. Show that $\frac{4x + 1}{x - 1}$ may be written in the form $4 + \frac{5}{x - 1}$ .  
Hence show that $\int_{3}^{5}\frac{4x + 1}{x - 1} dx = 8 + 5\ln 2.$  

**14. Evaluate using technology:**  
a. $\int_{1}^{3}\ln x dx$  
b. $\int_{-1}^{1}e^{-x^{2}}dx$  
c. $\int_{\frac{\pi}{4}}^{\frac{\pi}{6}}\sin (\sqrt{x})dx$  
d. $\int_{2}^{3}\frac{1 + \sqrt{x}}{x^{2} + 1} dx$   
e. $\int_{-1}^{1}\tan (x^{2})dx$  
f. $\int_{-2}^{1}(2^{x} - x^{3})dx$  

---  
#### IB AI Haese **EXERCISE 23B** : Definite Integral 2  
**1. Evaluate:**  
a. $\int_{1}^{2} 2x(x^2 - 1)^3 \, dx$  
b. $\int_{1}^{2} \frac{x}{(x^2 + 2)^2} \, dx$  
c. $\int_{0}^{1} x^2 e^{x^3 + 1} \, dx$  
d. $\int_{0}^{3} x \sqrt{x^2 + 16} \, dx$  
e. $\int_{1}^{2} xe^{-2x^2} \, dx$  
f. $\int_{2}^{3} \frac{x}{2 - x^2} \, dx$  

---  

**2. Evaluate:**   
a. $\int_{0}^{\frac{\pi}{3}} \frac{\sin x}{\sqrt{\cos x}} \, dx$  
b. $\int_{0}^{\frac{\pi}{6}} \sin^2 x \cos x \, dx$ 

---  

#### IB AI Haese **EXERCISE 23C** : Area Under The Graph  

1. Find the shaded area using:  
a a geometric argument b integration.  
[image]  
  
2. Find the area of each region described below using:  
i a geometric argument ii integration  
a the region enclosed by $y = 5$ , the $x$ - axis, $x = - 6$ , and $x = 0$  
b the region enclosed by $y = x$ , the $x$ - axis, $x = 4$ , and $x = 5$  
c the region enclosed by $y = - 3x$ , the $x$ - axis, $x = - 3$ , and $x = 0$  
  
3. Find the area of the region bounded by:  
a $y = x^{2}$ , the $x$ - axis, and $x = 1$  
b $y = x^{3}$ , the $x$ - axis, $x = 1$ , and $x = 4$  
c $y = \frac{1}{2} x^{2} - 1$ , the $x$ - axis, $x = 2$ , and $x = 3$  
  
4. The graph of $y = - x^{2} + x + 6$ is shown alongside.  
a Find the coordinates of A and B.  
b Hence find the shaded area.  
[image]  
  
5 Find the area enclosed by each curve and the $x$ - axis:  
$$  
y = -x^{2} + 7x - 10\qquad \text{b} y = -2x^{2} + 2x + 4\qquad \text{c} y = 3 - x^{2}  
$$  
  
6. Show that the area enclosed by $y = \sin x$ and the $x$ - axis from $x = 0$ to $x = \pi$ is 2 units2.  
  
7. Find the area of the region bounded by $y = \cos x$ , the $x$ - axis, $x = 0$ , and $x = \frac{\pi}{2}$ .  
  
8. Find the area enclosed by one arch of the curve $y = \cos 3x$ and the $x$ - axis.  
  
9. The graph alongside shows $y = \tan x$ for $-\frac{\pi}{2} < x < \frac{\pi}{2}$ .  
A is the point on the graph with $y$ - coordinate 1.  
a Find the $x$ - coordinate of A.  
b Find $\int \tan x dx$ .  
c Hence find the shaded area.  
[image]  
  
10. Find the area of the region bounded by:  
a $y = \frac{1}{x^2}$ , the $x$ - axis, $x = 1$ , and $x = 2$  
b $y = e^{x}$ , the axes, and $x = 1$  
c $y = 2 - \frac{1}{\sqrt{x}}$ , the $x$ - axis, and $x = 4$  
d the axes and $y = \sqrt{9 - x}$  
e $y = e^{x} + e^{- x}$ , the $x$ - axis, $x = - 1$ , and $x = 1$ .  
  
11. Use technology to find, correct to 3 significant figures:  
a the $x$ - coordinates of A and B  
b the shaded area.  
[image]  
  
12. a Show that $\frac{d}{dx}\left(\frac{\sin x}{1 + \cos x}\right) = \frac{1}{1 + \cos x}$ .  
b Hence find the area of the region bounded by $y = \frac{1}{1 + \cos x}$ , the $x$ - axis, $x = 0$ , and $x = 2$ .  
[image]  
  
13. a Find $b$ , correct to 4 decimal places.  
[image]  
b Find the exact value of $a$ .  
[image]  
c Find $k$ , correct to 4 decimal places.  
d Find $k$ such that area $A$ and area $B$ are equal.  
[image]  
  
---  
#### IB AI Haese **EXERCISE 23D** : Area 2  
1. Find the shaded area:  
[image]  
  
2. Find the total area enclosed by the function $y = f(x)$ and the $x$ - axis for:  
$$  
f(x) = x^{3} - 9x \qquad \text{b} \quad f(x) = -x(x - 2)(x - 4).  
$$  
  
3. a Explain why the total area shaded is not equal to  
$$  
\int_{1}^{7}f(x)dx.  
$$  
b Write an expression for the total shaded area in terms of integrals.  
[image]  
[image]  
  
4. For the graph of $y = f(x)$ alongside, $\int_{- 2}^{4}f(x)dx = - 6$ . Which region is larger, A or $B?$ Explain your answer.  
[image]  
  
5 The area of the region bounded by $f(x) = - \frac{9}{x}$ , the $x$ - axis, $x = 3$ , and $x = k$ , is $9\ln 2$ units. Find the value of $k$ .  
  
6. a Sketch the graph of $y = 2\sin x + 1$ for $0\leqslant x\leqslant 2\pi$  
b Find the area between the $x$ - axis and the part of $y = 2\sin x + 1$ that is below the $x$ - axis on $0\leqslant x\leqslant 2\pi$ .  
  
7. Suppose $f(x) = \frac{1}{x^{2} + 5x + 4}$ . Use technology to:  
a sketch the graph of $y = f(x)$  
b find the area of the region bounded by $y = f(x)$ , the $x$ - axis, $x = - 3$ , and $x = - 2$ .  
  
8. The cross- section of a roof gutter is defined by $f(x) = 0.02x^{4} - 0.4x^{2} - 2.5$ , for $- 5\leqslant x\leqslant 5\mathrm{cm}$  
a Find the cross- sectional area of the gutter.  
b The gutter is $20\mathrm{m}$ long. How much water can it hold in total?  
  
---  
  
#### IB AI Haese **EXERCISE 23E** : Area to y-axis  
  
1. The graph of $f(x) = \sqrt{x-1}$ is shown alongside.  
a Find $f^{-1}(y)$.  
b Hence find the shaded area.  
[image]  
  
2. Find the shaded area:  
[image]  
  
3. Find the area of the region bounded by:  
a $x = \frac{1}{2}y^{2} + 1$, the y-axis, and the lines $y = 1$ and $y = 2$  
b $x = \sqrt{y + 5}$, the y-axis, and the lines $y = -1$ and $y = 4$.  
  
4. Find the exact area of the region bounded by:  
a $y = \sqrt{x}$, the y-axis, and the lines $y = 2$ and $y = 3$  
b $y = \frac{1}{x}$, the y-axis, and the lines $y = -1$ and $y = -3$  
c $y = \frac{x}{2-x}$, the y-axis, and the lines $y = 1$ and $y = 4$.  
  
---  
  
#### IB AI Haese **EXERCISE 23F.1** : Volume of Solid Revolution
  
1. Find the volume of the solid formed when the following are revolved through $2\pi$ about the $x$ - axis:  
a $y = 2x$ for $0\leqslant x\leqslant 3$  
b $y = \sqrt{x}$ for $0\leqslant x\leqslant 4$  
c $y = x^{3}$ for $1\leqslant x\leqslant 2$  
d $y = x^{\frac{3}{2}}$ for $1\leqslant x\leqslant 4$  
e $y = x^{2}$ for $2\leqslant x\leqslant 4$  
f $y = \sqrt{25 - x^{2}}$ for $0\leqslant x\leqslant 5$  
g $y = \frac{1}{x - 1}$ for $2\leqslant x\leqslant 3$  
h $y = x + \frac{1}{x}$ for $1\leqslant x\leqslant 3$  
  
2. Find the volume of revolution when the shaded region is revolved through $2\pi$ about the $x$ - axis.  
[image]  
  
3. a Describe the solid of revolution when the shaded region is revolved about the $x$ - axis.  
b Find the equation of the line (AB) in the form $y = mx + c$ .  
c Find a formula for the volume of the solid using $V = \pi \int_{a}^{b}y^{2}dx.$  
[image]  
[image]  
  
4. [image]  
A circle with centre $(0, 0)$ and radius $r$ units has equation $x^{2} + y^{2} = r^{2}$ .  
a If the shaded region is revolved about the $x$ - axis, what solid is formed?  
b Show that the volume of revolution is $\frac{4}{3}\pi r^{3}$ .  
  
5. Find the volume of revolution when the following regions are revolved through $2\pi$ about the $x$ - axis:  
$$  
y = \sqrt{\sin x} \text{for} 0 \leqslant x \leqslant \pi \qquad b \quad y = \frac{1}{\cos x} \text{for} 0 \leqslant x \leqslant \frac{\pi}{3}  
$$  
  
6. Use technology to find, correct to 3 significant figures, the volume of the solid of revolution formed when these functions are rotated through $2\pi$ about the $x$ - axis:  
$$  
y = \ln x \text{for} 1 \leqslant x \leqslant 5 \qquad b \quad y = 4 \sin 2x \text{for} 0 \leqslant x \leqslant \frac{\pi}{4}  
$$  
$$  
y = \frac{x^{3}}{x^{2} + 1} \text{for} 1 \leqslant x \leqslant 3 \qquad d \quad y = e^{\sin x} \text{for} 0 \leqslant x \leqslant 2.  
$$  
  
---  
  
#### IB AI Haese **EXERCISE 23F.2** : Volume of Solid Revolution to y-axis
  
1. Find the volume of the solid formed when the following are revolved through $2\pi$ about the $y$ - axis:  
a $y = x^{2}$ , $x \geq 0$ , between $y = 0$ and $y = 4$  
b $y = \sqrt{x}$ between $y = 1$ and $y = 4$  
c $y = \ln x$ between $y = 0$ and $y = 2$  
d $y = \sqrt{x - 2}$ between $x = 2$ and $x = 11$  
e $y = (x - 1)^{3}$ between $x = 1$ and $x = 3$ .  
  
2. Find the volume of revolution when the shaded region is revolved through $2\pi$ about the $y$ - axis.  
[image]  
  
3. Find exactly the volume of the solid of revolution formed by revolving the relation $\frac{x^{2}}{9} + \frac{y^{2}}{16} = 1$ , $x \geq 0$ through $360^{\circ}$ about the $y$ - axis.  
  
4. A wooden bowl is made in the shape of a paraboloid by revolving the curve $y = \frac{1}{4} x^{2}$ , $x \geq 0$ , between $y = 0$ and $y = 4$ through $2\pi$ about the $y$ - axis. Find the capacity of the bowl.  
[image]  
  
5. The shaded region is rotated through $360^{\circ}$ about the $y$ - axis.  
a Find the volume of revolution.  
b A hemispherical bowl of radius $8\mathrm{cm}$ contains water to a depth of $3\mathrm{cm}$ . Find the volume of water in the bowl.  
[image]  
  
6. The outer casing of an hourglass is a cylinder with diameter $3\mathrm{cm}$ and height $8\mathrm{cm}$ . The inner casing which contains the sand is formed by rotating the curve $y^{2} = 8x^{3} - 0.2$ , $- 4 \leq y \leq 4$ about the $y$ - axis. Use technology to find the volume of air between the inner and outer casings.  
[image]  
  
---  
  
#### IB AI Haese **EXERCISE 23G** : Problem Solving using Integration  
  
1. The rate of traffic flow past a pedestrian crossing between 8 am and 8:30 am is given by  
$$  
R(t) = \frac{t^3}{80} -\frac{t^2}{2} +4t + 40\mathrm{~cars~per~minute},  
$$  
where $t$ is the number of minutes after 8 am, $0\leq t\leq 30$  
The graph of $R(t)$ against $t$ is shown alongside.  
a Find the rate of traffic flow at 8:20 am.  
b Use the graph to estimate the time at which the traffic flow was greatest.  
c Copy the graph, and shade the region corresponding to $\int_{10}^{15}R(t)dt$ . Explain what this region represents.  
d How many cars passed the crossing between 8 am and 8:30 am?  
[image]  
  
2. Evan is happily paddling until his kayak strikes a sharp rock.  
Water begins to leak in at the rate $R_{1}(t) = 5 - 5e^{- 0.2t}$ litres per minute, where $t$ is the time in minutes.  
Evan tries to bail the water out of the kayak, removing the water at the rate  
$R_{2}(t) = 6 - 6e^{- 0.1t}$ litres per minute.  
a After 2 minutes, at what rate is water:  
i leaking into the kayak  
ii being bailed from the kayak?  
b Is the amount of water in the kayak increasing or decreasing after 2 minutes? Explain your answer.  
c Evaluate the following integrals, and interpret their meaning:  
$$  
\mathrm{~i~}\int_{0}^{3}R_{1}(t)d t\qquad \mathrm{~ii~}\int_{2}^{5}R_{2}(t)d t\qquad \mathrm{~iii~}\int_{0}^{8}[R_{1}(t) - R_{2}(t)]d t  
$$  
d How much water is in the kayak after 10 minutes?  
  
3. Answer the Opening Problem on page 584.  
  
4. The rate of power consumption of the United Kingdom can be modelled by the function  
$$  
E(t) = 13\sin \left(\frac{(t + 3)\pi}{3}\right) + 70\cos \left(\frac{(t - 1)\pi}{6}\right) + 196 \mathrm{~TWh~per~month}  
$$  
where $t$ is the number of months after January 1st, $0\leqslant t\leqslant 12$  
a Use technology to help sketch the function.  
b Find the following quantities and explain what they represent:  
$$  
\mathrm{~i~}\int_{3}^{4}E(t)d t\qquad \mathrm{~ii~}\int_{5}^{8}E(t)d t\qquad \mathrm{~iii~}\int_{0}^{12}E(t)d t  
$$  
  
---  
  
#### IB AI Haese **REVIEW SET 23A**  
  
1. Find the exact value of:  
$$  
\int_{-2}^{0}(1 - 3x)d x\qquad \mathrm{~b~}\int_{0}^{\frac{1}{2}}(x - \sqrt{x})d x\qquad \mathrm{~c~}\int_{1}^{2}(x^{2} + 1)^{2}d x  
$$  
  
2. Find the exact value of:  
$$  
\int_{-5}^{-1}\sqrt{1 - 3x}d x\qquad \mathrm{~b~}\int_{0}^{\frac{\pi}{2}}\cos {\frac{x}{2}}d x\qquad \mathrm{~c~}\int_{2}^{6}{\frac{2}{x}}d x  
$$  
  
3. Find $\frac{d}{dx} (e^{- 2x}\sin x)$ and hence evaluate $\int_{0}^{\frac{\pi}{2}}\left[e^{- 2x}(\cos x - 2\sin x)\right]dx.$  
  
4. Evaluate correct to 6 significant figures:  
$$  
\int_{3}^{4}\frac{x}{\sqrt{2x + 1}} d x\qquad \mathrm{~b~}\int_{0}^{1}x^{2}e^{x + 1}d x\qquad \mathrm{~c~}\int_{0}^{\pi}\sin (x^{2})d x  
$$  
  
5. a Find $\int 2x(x^{2} + 1)^{3}dx$ using the substitution $u = x^{2} + 1$  
b Hence evaluate:  
$$  
\mathrm{~i~}\int_{0}^{1}2x(x^{2} + 1)^{3}d x\qquad \mathrm{~ii~}\int_{-1}^{2} - x(1 + x^{2})^{3}d x  
$$  
  
6. Find $\int_{0}^{1}x^{2}e^{1 - x^{3}}dx$ using an appropriate substitution.  
  
7. Find the shaded area:  
[image]  
[image]  
  
8. Find the area of the region bounded by:  
a $y = x^{2}$ , the $x$ - axis, $x = 2$ , and $x = 5$  
b $y = \sqrt{5 - x}$ , the $x$ - axis, $x = 1$ , and $x = 2$  
c $y = \sin \frac{x}{3}$ , the $x$ - axis, $x = \pi$ , and $x = 2\pi$ .  
  
9. Does $\int_{- 1}^{3}f(x)dx$ represent the area of the shaded region? Explain your answer.  
[image]  
  
10. Determine $k$ given that the enclosed region has area $5\frac{1}{3}$ units².  
[image]  
  
11. Find the shaded area:  
[image]  
  
12. Consider the function $f(x) = \sqrt{\frac{1}{x}} - 1$ . Use technology to:  
a sketch the graph of $y = f(x)$  
b find the area bounded by $y = f(x)$ and the $y$ - axis, between $y = 1$ and $y = \sqrt{3}$ .  
  
13. Find the volume of the solid of revolution formed when the following curves are revolved through $360^{\circ}$ about the $x$ - axis:  
a $y = x$ between $x = 4$ and $x = 10$  
b $y = x + 1$ between $x = 4$ and $x = 10$  
c $y = \sqrt{\sin x}$ for $0\leqslant x\leqslant \pi$ .  
  
14. Find the volume of the solid of revolution formed when the shaded region is revolved through $360^{\circ}$ about the $x$ - axis:  
[image]  
  
15. Find the volume of the solid of revolution formed when the following are rotated through $2\pi$ about the $y$ - axis:  
a $y = \sqrt{x}$ between $y = 1$ and $y = 2$  
b $y = \sqrt[3]{x^{2}}$ between $y = 2$ and $y = 3$ .  
  
16. Bettina is filling a watering can with water from a tap. The water enters at the rate $R_{1}(t) = 6.4$ litres per minute.  
Bettina's watering can starts empty, and has capacity 16 litres. Unfortunately it has a hole in the bottom, so it leaks water at the rate $R_{2}(t) = 2.5 - 1.25e^{- 0.2t}$ litres per minute, where $t$ is the time in minutes.  
a Evaluate the following integrals, and interpret their meaning:  
$$  
\mathrm{~i~}\int_{0}^{\frac{1}{2}}R_{2}(t)d t\qquad \mathrm{~ii~}\int_{0}^{1}[R_{1}(t) - R_{2}(t)]d t  
$$  
b How long will it take for the watering can to be full? Give your answer to the nearest second.  
  
---  
  
#### IB AI Haese **REVIEW SET 23B**  
  
1. Find the exact value of:  
$$  
\int_{2}^{3}\frac{1}{\sqrt{3x}} dx\qquad \mathrm{~b~}\int_{1}^{4}(x - \frac{1}{2} x^{2})dx\qquad \mathrm{~c~}\int_{0}^{1}(x^{2} + \frac{1}{3})^{2}dx  
$$  
  
2. Find the exact value of:  
$$  
\int_{2}^{3}\frac{1}{\sqrt{3x - 4}} dx\qquad \mathrm{~b~}\int_{2e}^{3e}\frac{4}{x + e} dx\qquad \mathrm{~c~}\int_{\frac{\pi}{4}}^{\frac{\pi}{2}}(2\sin x + 1)dx  
$$  
  
3. Find the values of $b$ such that $\int_{0}^{b}\cos x dx = \frac{1}{\sqrt{2}}, 0< b< \pi .$  
  
4. Evaluate correct to 4 significant figures:  
a. $\int_{-2}^{0}4e^{-x^{2}}dx$  
b. $ \int_{0}^{1}\frac{10x}{\sqrt{3x + 1}} dx$  
c. $\int_{0}^{\frac{\pi}{3}}\cos^{2}\left(\frac{x}{2}\right)dx$    
  
5. Find $\int_{0}^{\frac{\pi}{6}}\frac{\cos x}{(1 + \sin x)^{3}} dx$ using an appropriate substitution.  
  
6. Find the area of the region bounded by:  
a $y = x^{3} + 1$ ,the $x$ - axis, $x = 1$ ,and $x = 3$  
b $y = \frac{1}{x}$ ,the $x$ - axis, $x = 3$ ,and $x = 9$  
c $y = e^{2x}$ ,the $x$ - axis, $x = 0$ ,and $x = 2$  
d $y = - 2 - 2\cos 3x$ and the $x$ - axis from $x = - \frac{\pi}{3}$ to $x = \frac{\pi}{3}$  
  
7. Use technology to find:  
a the $x$ - coordinates of $\mathrm{P}$ and Q  
b the shaded area.  
[image]  
  
8. OABC is a rectangle and the two shaded regions are equal in area. Find $k$ .  
[image]  
  
9. The shaded region has area $\frac{1}{2}$ unit². Find the value of $m$ .  
[image]  
  
10. Find the area enclosed by:  
a $y = \frac{1}{x}$ ,the $y$ - axis, $y = 2$ ,and $y = 4$  
b $y = x^{3} + 2$ ,the $y$ - axis, $y = 3$ ,and $y = 6$  
  
11. The graph of $y = \sqrt{4 - x}$ is shown alongside.  
a Find the coordinates of A and B.  
b Find the shaded area by considering it as the area between the curve and:  
i the $x$ - axis  
ii the $y$ - axis.  
Comment on your answers.  
[image]  
  
12. Find the volume of the solid of revolution formed when the following curves are rotated about the $x$ - axis:  
$$  
y = \frac{4}{x} \text{ between } x = 1 \text{ and } x = 2 \qquad \text{b} \quad y = \sqrt{9 - x^2}, \quad 0 \le x \le 3.  
$$  
  
13. Use technology to find the volume of the solid of revolution formed when the following curves are rotated about the $x$ - axis:  
$$  
y = \sin x \text{ between } x = 0 \text{ and } x = \pi  
$$  
$$  
y = \ln (2x) \text{ between } x = 1.5 \text{ and } x = 4.5.  
$$  
  
14. a Find the derivative of $\frac{\cos x}{\sin x}$ .  
b Find the volume of revolution when $y = \frac{1}{\sin x}$ is rotated through $360^{\circ}$ about the $x$ - axis for $\frac{\pi}{4} \le x \le \frac{3\pi}{4}$ .  
  
15. The shape of a vase is found by revolving the curve $y = \frac{1}{2} x^{\frac{5}{2}}$ , $0 \le x \le 4$ through $360^{\circ}$ about the $y$ - axis. The units are in centimetres.  
a Find the height of the vase.  
b Find the volume of the vase.  
c The vase is filled with water to a height of $10 \mathrm{cm}$ . Find the amount of water in the vase.  
[image]  
  
16. Over the course of a day, the rate of solar energy being transferred into Callum's solar panels is given by $E(t) = 2 \sin \left(\frac{t - 5}{5}\right) + \frac{1}{2} \sin \left(\frac{t - 5}{4}\right) \mathrm{kW}$ where $t$ is the time in hours after midnight, $5 \le t \le 20$ .  
Find the following quantities and explain what they represent:  
a. $\int_{5}^{12}E(t)dt$  
b. $\int_{12}^{20}E(t)dt$  
c. $\int_{5}^{20}E(t)dt$  

## Hodder PM1  

**Example 7.1**  
Given that $\frac{\mathrm{d}y}{\mathrm{d}x} = 3x^{2} + 4x + 3$  
(i) find the general solution of this differential equation  
(ii) find the equation of the curve with this gradient function which passes through $(1,10)$.  

**Example 7.2**  
A curve is such that $\frac{\mathrm{d}y}{\mathrm{d}x} = 3\sqrt{x} +\frac{8}{x^2}$ . Given that the point (4, 20) lies on the curve, find the equation of the curve.  

**Example 7.3**  
The gradient function of a curve is $\frac{\mathrm{d}y}{\mathrm{d}x} = 4x - 12$ .  
(i) The minimum $y$ value is 16. By considering the gradient function, find the corresponding $x$ value.  
(ii) Use the gradient function and your answer from part   
(i) to find the equation of the curve.  

**Example 7.4**  
Find the area under the curve $y = 6x^{5} + 6$ between $x = - 1$ and $x = 2$ .  

**Example 7.5**  
Find the area between the curve $y = 20 - 3x^{2}$ , the $x$ - axis and the lines $x = 1$ and $x = 2$ .  

**Example 7.6**  
Find the area under the curve $y = 4x^3 + 4$ between $x = - 1$ and $x = 2$ .  

**Example 7.7**  
Evaluate the definite integral $\int_{4}^{9}x^{\frac{3}{2}}\mathrm{d}x$ .  

**Example 7.8**  
Evaluate $\int_{1}^{2}\left(\frac{3}{x^{4}} -\frac{1}{x^{2}} +4\right)\mathrm{d}x.$  

**Example 7.9**  
Find $\int (2x^{3} - 3x + 4)\mathrm{d}x$ .  

**Example 7.10**  
Find the indefinite integral $\int \left(x^{\frac{3}{2}} + \sqrt{x}\right)\mathrm{d}x$ .  

**Example 7.11**  
Find the area of the region bounded by the curve with equation $y = \frac{2}{x^2} - 3$ , the lines $x = 2$ and $x = 4$ , and the $x$ - axis.  

**Example 7.12**  
Find the area between the curve and the $x$ - axis for the function $y = x^2 + 3x$ between $x = - 1$ and $x = 2$ .  

**Example 7.13**  
Find the area enclosed by the line $y = x + 1$ and the curve $y = x^{2} - 2x + 1$ .  

**Example 7.14**  
Find the area between the curve $y = x - 1$ and the $y$ - axis between $y = 0$ and $y = 4$ .  

**Example 7.15**  
Find $\int \frac{3}{\sqrt{5 - 2x}} \mathrm{~d} x$ .  

**Example 7.16**  
Find $\int \frac{3}{\sqrt{5 - 2x}} \mathrm{~d} x$ . [Duplicated numbering in original; text as shown]  

**Example 7.17**  
Evaluate $\int_{0}^{9}\frac{1}{\sqrt{x}}\mathrm{d}x$ .  

**Example 7.18**  
The region between the curve $y = x^{2}$ , the $x$ - axis and the lines $x = 1$ and $x = 3$ is rotated through $360^{\circ}$ about the $x$ - axis. Find the volume of revolution which is formed.  

**Example 7.19**  
The region between the curve $y = x^{2}$ , the $y$ - axis and the lines $y = 2$ and $y = 5$ is rotated through $360^{\circ}$ about the $y$ - axis. Find the volume of revolution which is formed.  

**Example 7.20**  
Figure 7.34 shows the shaded region bounded by the curve $y = 16 - x^{2}$ and the line $y = 7$ . [image]  

Find the volume of the solid obtained when the shaded region is rotated completely about the $x$ - axis.  

---  
#### Hodder PM1 **Exercise 7A**  
1. Given that $\frac{\mathrm{d}y}{\mathrm{d}x} = 6x^2 + 5$   
(i) find the general solution of the differential equation   
(ii) find the equation of the curve with gradient function $\frac{\mathrm{d}y}{\mathrm{d}x}$ and which passes through (1, 9)   
(iii) hence show that $(- 1, - 5)$ also lies on the curve.  
2. The gradient function of a curve is $\frac{\mathrm{d}y}{\mathrm{d}x} = 4x$ and the curve passes through the point (1, 5).   
(i) Find the equation of the curve.   
(ii) Find the value of $y$ when $x = -1$ .  
3. The curve $C$ passes through the point (2, 10) and its gradient at any point is given by $\frac{\mathrm{d}y}{\mathrm{d}x} = 6x^2$ .   
(i) Find the equation of the curve $C$ .   
(ii) Show that the point $(1, -4)$ lies on the curve.  
4. A stone is thrown upwards out of a window, and the rate of change of its height ( $h$ metres) is given by $\frac{\mathrm{d}h}{\mathrm{d}t} = 15 - 10t$ where $t$ is the time (in seconds). When $t = 0$ , $h = 20$ .   
(i) Show that the solution of the differential equation, under the given conditions, is $h = 20 + 15t - 5t^2$ .   
(ii) For what value of $t$ does $h = 0$ ? (Assume $t \geq 0$ .)  
5.   
(i) Find the general solution of the differential equation $\frac{\mathrm{d}y}{\mathrm{d}x} = 5$ .   
(ii) Find the particular solution which passes through the point (1, 8).   
(iii) Sketch the graph of this particular solution.  
6. The gradient function of a curve is $3x^2 - 3$ . The curve has two stationary points. One is a maximum with a $y$ value of 5 and the other is a minimum with a $y$ value of 1.   
(i) Find the value of $x$ at each stationary point. Make it clear in your solution how you know which corresponds to the maximum and which to the minimum.   
(ii) Use the gradient function and one of your points from part   
(i) to find the equation of the curve.   
(iii) Sketch the curve.  
7. A curve passes through the point (4, 1) and its gradient at any point is given by $\frac{\mathrm{d}y}{\mathrm{d}x} = 2x - 6$ .   
(i) Find the equation of the curve.   
(ii) Draw a sketch of the curve and state whether it passes under, over or through the point (1, 4).

9. A curve is such that $\frac{\mathrm{d}y}{\mathrm{d}x} = \sqrt{x}$ . Given that the point (9, 20) lies on the curve, find the equation of the curve.  
10. A curve is such that $\frac{\mathrm{d}y}{\mathrm{d}x} = \frac{2}{x^2} - 3$ . Given that the point (2, 10) lies on the curve, find the equation of the curve.  
11. A curve is such that $\frac{\mathrm{d}y}{\mathrm{d}x} = \sqrt{x} + \frac{1}{x^2}$ . Given that the point (1, 5) lies on the curve, find the equation of the curve.  
12. A curve is such that $\frac{\mathrm{d}y}{\mathrm{d}x} = 3x^2 + 5$ . Given that the point (1, 8) lies on the curve, find the equation of the curve.  
13. A curve is such that $\frac{\mathrm{d}y}{\mathrm{d}x} = 3\sqrt{x} - 9$ and the point (4, 0) lies on the curve.   
(i) Find the equation of the curve.   
(ii) Find the $x$ coordinate of the stationary point on the curve and determine the nature of the stationary point.

15. A cubic function has a $y$ - intercept at (0, 2). When $x = 1$ , $y = 3$ , $\frac{\mathrm{d}y}{\mathrm{d}x} = 2$ and $\frac{\mathrm{d}^2y}{\mathrm{d}x^2} = 0$ . Find the equation of the original curve, and sketch the curve.  
16. A curve $y = \mathrm{f}(x)$ passes through the points (0, 1) and (1, -8), and has a turning point at $x = -1$ . Given that $\frac{\mathrm{d}^3y}{\mathrm{d}x^3} = 24x + 24$ , find the equation of the curve.  
17. The equation of a curve is such that $\frac{\mathrm{d}y}{\mathrm{d}x} = \frac{3}{\sqrt{x}} - x$ . Given that the curve passes through the point (4, 6), find the equation of the curve. Cambridge International AS & A Level Mathematics 9709 Paper 12 Q1 November 2009  
18. A curve is such that $\frac{\mathrm{d}y}{\mathrm{d}x} = 4 - x$ and the point $\mathrm{P}(2,9)$ lies on the curve. The normal to the curve at $\mathrm{P}$ meets the curve again at $\mathrm{Q}$ . Find   
(i) the equation of the curve,   
(ii) the equation of the normal to the curve at $\mathrm{P}$ ,   
(iii) the coordinates of $\mathrm{Q}$ . Cambridge International AS & A Level Mathematics 9709 Paper 1 Q9 November 2007

20. A curve $y = \mathrm{f}(x)$ has a stationary point at (3, 7) and is such that $\mathrm{f''}(x) = 36x^{- 3}$ .   
(i) State, with a reason, whether this stationary point is a maximum or a minimum.   
(ii) Find $\mathrm{f'}(x)$ and $\mathrm{f}(x)$ . Cambridge International AS & A Level Mathematics 9709 Paper 13 Q8 November 2014

---

#### Hodder PM1 **Exercise 7B**  
1. Find the following indefinite integrals.   
(i) $\int 3x^{2}\mathrm{d}x$   
(ii) $\int (5x^{4} + 7x^{6})\mathrm{d}x$   
(iii) $\int (6x^{2} + 5)\mathrm{d}x$   
(iv) $\int (x^{3} + x^{2} + x + 1)\mathrm{d}x$   
(v) $\int (11x^{10} + 10x^{9})\mathrm{d}x$   
(vi) $\int (3x^{2} + 2x + 1)\mathrm{d}x$ (vii) $\int (x^{2} + 5)\mathrm{d}x$  (viii) $\int 5\mathrm{d}x$ (ix) $\int (6x^{2} + 4x)\mathrm{d}x$ (x) $\int (x^{4} + 3x^{2} + 2x + 1)\mathrm{d}x$

3. Find the following indefinite integrals.   
(i) $\int 10x^{- 4}\mathrm{d}x$   
(ii) $\int (2x - 3x^{- 4})\mathrm{d}x$   
(iii) $\int (2 + x^{3} + 5x^{- 3})\mathrm{d}x$   
(iv) $\int (6x^{2} - 7x^{- 2})\mathrm{d}x$   
(v) $\int 5x^{\frac{1}{4}}\mathrm{d}x$   
(vi) $\int \frac{1}{x^{4}}\mathrm{d}x$ (vii) $\int \sqrt{x}\mathrm{d}x$ (viii) $\int (2x^{4} - \frac{4}{x^{2}})\mathrm{d}x$

5. Evaluate the following definite integrals.   
(i) $\int_{1}^{2}2x\mathrm{d}x$   
(ii) $\int_{0}^{3}2x\mathrm{d}x$   
(iii) $\int_{1}^{3}3x^{2}\mathrm{d}x$   
(iv) $\int_{5}^{5}x\mathrm{d}x$   
(v) $\int_{5}^{6}(2x + 1)\mathrm{d}x$   
(vi) $\int_{-1}^{2}(2x + 4)\mathrm{d}x$  
(vii) $\int_{3}^{5}(3x^{2} + 2x)\mathrm{d}x$   
(viii) $\int_{1}^{1}x^{5}\mathrm{d}x$  
(ix) $\int_{-2}^{-1}(x^{4} + x^{3})\mathrm{d}x$  
(x) $\int_{-1}^{1}x^{3}\mathrm{d}x$  
(xi) $\int_{-5}^{4}(x^{3} + 3x)\mathrm{d}x$  
(xii) $\int_{-3}^{-2}5\mathrm{d}x$

7. Evaluate the following definite integrals.   
(i) $\int_{1}^{4}3x^{-2}\mathrm{d}x$   
(ii) $\int_{2}^{4}8x^{-3}\mathrm{d}x$   
(iii) $\int_{1}^{4}12x^{\frac{1}{2}}\mathrm{d}x$   
(iv) $\int_{-3}^{-1}\frac{6}{x^{3}}\mathrm{d}x$   
(v) $\int_{0.5}^{2}\left(\frac{x^{2} + 3x + 4}{x^{4}}\right)\mathrm{d}x$   
(vi) $\int_{4}^{0}\left(\sqrt{x} - \frac{1}{\sqrt{x}}\right)\mathrm{d}x$

9. The graph of $y = 2x$ is shown here. The shaded region is bounded by $y = 2x$ , the $x$ -axis and the lines $x = 2$ and $x = 3$ .   
(i) Find the coordinates of the points A and B in the diagram.   
(ii) Use the formula for the area of a trapezium to find the area of the shaded region.   
(iii) Find the area of the shaded region as $\int_{2}^{3}2x\mathrm{d}x$ , and confirm that your answer is the same as that for part   
(ii).   
(iv) The method of part   
(ii) cannot be used to find the area under the curve $y = x^{2}$ bounded by the lines $x = 2$ and $x = 3$ . Why? [image]  

11.   
(i) Sketch the curve $y = x^{2}$ for $- 1\leqslant x\leqslant 3$ and shade the area bounded by the curve, the lines $x = 1$ and $x = 2$ and the $x$ - axis.   
(ii) Find, by integration, the area of the region you have shaded.  
12.   
(i) Sketch the curve $y = 4 - x^{2}$ for $- 3\leqslant x\leqslant 3$   
(ii) For what values of $x$ is the curve above the $x$ - axis?   
(iii) Find the area between the curve and the $x$ - axis when the curve is above the $x$ - axis.

14.   
(i) Sketch the graph of $y = (x - 2)^{2}$ for values of $x$ between $x = - 1$ and $x = +4$ . Shade the area under the curve, between the $y$ - axis and $x = 2$   
(ii) Calculate the area you have shaded.

16. The diagram shows the graph of $y = \sqrt{x} +\frac{1}{\sqrt{x}}$ for $x > 0$ . The shaded region is bounded by the curve, the $x$ - axis and the lines $x = 1$ and $x = 9$ . Find its area. [image]
17. 
18.   
(i) Sketch the curves $y = x^{2}$ and $y = x^{3}$ for $0\leqslant x\leqslant 2$ .   
(ii) Which is the higher curve within the region $0< x< 1$ ?   
(iii) Find the area under each curve for $0\leqslant x\leqslant 1$ .   
(iv) Which would you expect to be greater, $\int_{1}^{2}x^{2}\mathrm{d}x$ or $\int_{1}^{2}x^{3}\mathrm{d}x$ ? Explain your answer in terms of your sketches, and confirm it by calculation.

20.   
(i) Sketch the curve $y = x^{2} - 1$ for $- 3\leqslant x\leqslant 3$ .   
(ii) Find the area of the region bounded by $y = x^{2} - 1$ , the line $x = 2$ and the $x$ axis.   
(iii) Sketch the curve $y = x^{2} - 2x$ for $- 2\leqslant x\leqslant 4$ .   
(iv) Find the area of the region bounded by $y = x^{2} - 2x$ , the line $x = 3$ and the $x$ - axis.   
(v) Comment on your answers to parts   
(ii) and

(iv).  
22.   
(i) Shade, on a suitable sketch, the region with an area given by $\int_{- 1}^{2}(9 - x^{2})\mathrm{d}x$ .   
(ii) Find the area of the shaded region.  

23.   
(i) Sketch the curve with equation $y = x^{2} + 1$ for $- 3\leqslant x\leqslant 3$ .   
(ii) Find the area of the region bounded by the curve, the lines $x = 2$ and $x = 3$ , and the $x$ - axis.   
(iii) Predict, with reasons, the value of $\int_{- 3}^{- 2}(x^{2} + 1)\mathrm{d}x$ .   
(iv) Evaluate $\int_{- 3}^{- 2}(x^{2} + 1)\mathrm{d} x$ .

25.   
(i) Sketch the curve with equation $y = x^{2} - 2x + 1$ for $- 1 \leq x \leq 4$ .   
(ii) State, with reasons, which area you would expect from your sketch to be larger: $\int_{- 1}^{3}(x^{2} - 2x + 1) \mathrm{d}x \quad \text { or } \quad \int_{0}^{4}(x^{2} - 2x + 1) \mathrm{d}x.$   
(iii) Calculate the values of the two integrals. Was your answer to part   
(ii) correct?

27.   
(i) Sketch the curve with equation $y = x^{3} - 6x^{2} + 11x - 6$ for $0 \leq x \leq 4$ .   
(ii) Shade the regions with areas given by (a) $\int_{1}^{2}(x^{3} - 6x^{2} + 11x - 6) \mathrm{d}x$ (b) $\int_{3}^{4}(x^{3} - 6x^{2} + 11x - 6) \mathrm{d}x.$   
(iii) Find the values of these two areas.   
(iv) Find the value of $\int_{1}^{1.5}(x^{3} - 6x^{2} + 11x - 6) \mathrm{d}x$ . What does this, taken together with one of your answers to part   
(iii), indicate to you about the position of the maximum point between $x = 1$ and $x = 2$ ?

29. Find the area of the region enclosed by the curve $y = 3\sqrt{x}$ , the $x$ -axis and the lines $x = 0$ and $x = 4$ .
30. 
31. A curve has equation $y = \frac{4}{\sqrt{x}}$ .   
(i) The normal to the curve at the point $(4, 2)$ meets the $x$ -axis at $P$ and the $y$ -axis at $Q$ . Find the length of $PQ$ , correct to 3 significant figures.   
(ii) Find the area of the region enclosed by the curve, the $x$ -axis and the lines $x = 1$ and $x = 4$ . Cambridge International AS & A Level Mathematics 9709 Paper 1 Q9 June 2005

33. A curve is such that $\frac{\mathrm{d}y}{\mathrm{d}x} = \frac{16}{x^{3}}$ , and $(1, 4)$ is a point on the curve.   
(i) Find the equation of the curve.   
(ii) A line with gradient $- \frac{1}{2}$ is a normal to the curve. Find the equation of this normal, giving your answer in the form $ax + by = c$ .   
(iii) Find the area of the region enclosed by the curve, the $x$ -axis and the lines $x = 1$ and $x = 2$ . Cambridge International AS & A Level Mathematics 9709 Paper 1 Q10 November 2005

35. The diagram shows a curve for which $\frac{\mathrm{d}y}{\mathrm{d}x} = -\frac{k}{x^3}$ , where $k$ is a constant. The curve passes through the points (1, 18) and (4, 3). [image]   
(i) Show, by integration, that the equation of the curve is $y = \frac{16}{x^2} + 2$ . The point P lies on the curve and has $x$ coordinate 1.6.   
(ii) Find the area of the shaded region. Cambridge International AS & A Level Mathematics 9709 Paper 1 Q9 June 2008

37. The equation of a curve is $y = 2x + \frac{8}{x^2}$ .   
(i) Obtain expressions for $\frac{\mathrm{d}y}{\mathrm{d}x}$ and $\frac{\mathrm{d}^2y}{\mathrm{d}x^2}$ .   
(ii) Find the coordinates of the stationary point on the curve and determine the nature of the stationary point.   
(iii) Show that the normal to the curve at the point $(-2, -2)$ intersects the $x$ -axis at the point $(-10, 0)$ .   
(iv) Find the area of the region enclosed by the curve, the $x$ -axis and the lines $x = 1$ and $x = 2$ . Cambridge International AS & A Level Mathematics 9709 Paper 1 Q10 June 2007  
---  
#### Hodder PM1 **Exercise 7C**  
1. Sketch each of these curves and find the area between the curve and the $x$ - axis between the given bounds.   
(i) $y = x^{3}$ between $x = -3$ and $x = 0$   
(ii) $y = x^{2} - 4$ between $x = -1$ and $x = 2$   
(iii) $y = x^{5} - 2$ between $x = -1$ and $x = 0$   
(iv) $y = 3x^{2} - 4x$ between $x = 0$ and $x = 1$   
(v) $y = x^{4} - x^{2}$ between $x = -1$ and $x = 1$   
(vi) $y = 4x^{3} - 3x^{2}$ between $x = -1$ and $x = 0.5$ (vii) $y = x^{5} - x^{3}$ between $x = -1$ and $x = 1$ (viii) $y = x^{2} - x - 2$ between $x = -2$ and $x = 3$ (ix) $y = x^{3} + x^{2} - 2x$ between $x = -3$ and $x = 2$ (x) $y = x^{3} + x^{2}$ between $x = -2$ and $x = 2$  
2.   
(i) (a) Find $\int_{\frac{1}{4}}^{\frac{1}{4}}\left(\frac{1}{x^{3}} - 8\right)\mathrm{d}x.$ (b) Find $\int_{\frac{1}{2}}^{1}\left(\frac{1}{x^{3}} - 8\right)\mathrm{d}x.$   
(ii) Hence find the total area of the regions bounded by the curve $y = \frac{1}{x^{3}} - 8$ , the lines $x = \frac{1}{4}$ and $x = 1$ and the $x$ - axis.  
3.   
(i) (a) Find $\int_{0}^{4}2x(\sqrt{x} -2)\mathrm{d}x.$ (b) Find $\int_{4}^{9}2x(\sqrt{x} -2)\mathrm{d}x.$   
(ii) Hence find the total area of the regions bounded by the curve $y = 2x(\sqrt{x} -2)$ , the line $x = 9$ and the $x$ -axis.

---  
#### Hodder PM1 **Exercise 7D**  
1. The diagram shows the curve $y = x^{2}$ and the line $y = 9$ . The enclosed region has been shaded.   
(i) Find the two points of intersection (labelled A and B).   
(ii) Using integration, show that the area of the shaded region is 36 square units. [image]

3.
(i) Sketch the curves with equations $y = x^{2} + 3$ and $y = 5 - x^{2}$ on the same axes, and shade the enclosed region.   
(ii) Find the coordinates of the points of intersection of the curves.   
(iii) Find the area of the shaded region.

5.
(i) Sketch the curve $y = x^{3}$ and the line $y = 4x$ on the same axes.   
(ii) Find the coordinates of the points of intersection of the curve $y = x^{3}$ and the line $y = 4x$ .   
(iii) Find the total area of the region bounded by $y = x^{3}$ and $y = 4x$ .

7.
(i) Sketch the curves with equations $y = x^{2}$ and $y = 4x - x^{2}$ .   
(ii) Find the coordinates of the points of intersection of the curves.   
(iii) Find the area of the region enclosed by the curves.

9.
(i) Sketch the curves $y = x^{2}$ and $y = 8 - x^{2}$ and the line $y = 4$ on the same axes.   
(ii) Find the area of the region enclosed by the line $y = 4$ and the curve $y = x^{2}$ .   
(iii) Find the area of the region enclosed by the line $y = 4$ and the curve $y = 8 - x^{2}$ .   
(iv) Find the area enclosed by the curves $y = x^{2}$ and $y = 8 - x^{2}$ .  
10.
(i) Sketch the curve $y = x^{2} - 6x$ and the line $y = -5$ .   
(ii) Find the coordinates of the points of intersection of the line and the curve.   
(iii) Find the area of the region enclosed by the line and the curve.  
11.
(i) Sketch the curve $y = x(4 - x)$ and the line $y = 2x - 3$ .   
(ii) Find the coordinates of the points of intersection of the line and the curve.   
(iii) Find the area of the region enclosed by the line and the curve.  
12. Find the area of the region enclosed by the curves with equations $y = x^{2} - 16$ and $y = 4x - x^{2}$ .  
13. Find the area of the region enclosed by the curves with equations $y = -x^{2} - 1$ and $y = -2x^{2}$ .  
14.  
(i) Sketch the curve with equation $y = x^{3} + 1$ and the line $y = 4x + 1$ .   
(ii) Find the areas of the two regions enclosed by the line and the curve.  
15. The diagram shows the curve $y = 5x - x^{2}$ and the line $y = 4$ . Find the area of the shaded region. [image]  
16. The diagram shows the curve $y = (x - 2)^2$ and the line $y + 2x = 7$ , which intersect at points A and B. [image] Find the area of the shaded region. Cambridge International AS & A Level Mathematics 9709 Paper 12 Q9 June 2010  
17. The diagram shows the curve $y = x^{3} - 6x^{2} + 9x$ for $x\geq 0$ . The curve has a maximum point at A and a minimum point on the $x$ - axis at B. The normal to the curve at C(2, 2) meets the normal to the curve at B at the point D. [image]   
(i) Find the coordinates of A and B.   
(ii) Find the equation of the normal to the curve at C.   
(iii) Find the area of the shaded region. Cambridge International AS & A Level Mathematics 9709 Paper 1 Q11 June 2009  

#### Hodder PM1 **Exercise 7E**  
Find the area of the region bounded by each of these curves, the $y$ - axis and the lines $y = a$ and $y = b$ .  
1. $y = 3x + 1,a = 1,b = 7$ [image]  
2. $y = \sqrt{x - 2},a = 0,b = 2$ [image]  
3. $y = \sqrt[3]{x},a = 0,b = 2$  
4. $y = \sqrt{x} -1,a = 0,b = 2$  
5. $y = \sqrt[4]{x},a = 1,b = 2$  
6. $y = \sqrt[3]{x} -2,a = -1,b = 1$  
---  
#### Hodder PM1 **Exercise 7F**  
1. Evaluate the following indefinite integrals.  
(i) $ \int (x + 5)^4 \, dx $  
(ii) $ \int (x + 7)^8 \, dx $  
(iii) $ \int \frac{1}{(x - 2)^6} \, dx $  
(iv) $ \int \sqrt{x - 4} \, dx $  
(v) $ \int (3x - 1)^3 \, dx $  
(vi) $ \int (5x - 2)^6 \, dx $  
(vii) $ \int 3(2x - 4)^5 \, dx $  
(viii) $ \int \sqrt{4x - 2} \, dx $  
(ix) $ \int \frac{4}{(8 - x)^2} \, dx $  
(x) $ \int \frac{3}{\sqrt{2x - 1}} \, dx $  
---  
2. Evaluate the following definite integrals.  
(i) $ \int_1^5 \sqrt{x - 1} \, dx $  
(ii) $ \int_1^3 (x + 1)^3 \, dx $  
(iii) $ \int_{-1}^4 (x - 3)^4 \, dx $  
(iv) $ \int_0^3 (4 - 2x)^5 \, dx $  
(v) $ \int_5^9 \sqrt{x - 5} \, dx $  
(vi) $ \int_2^{10} \sqrt{x - 1} \, dx $

4. The graph of $y = (x - 2)^3$ is shown here.   
(i) Evaluate $\int_{2}^{4}(x - 2)^{3}\mathrm{d}x$   
(ii) Without doing any calculations, state what you think the value of $\int_{0}^{2}(x - 2)^{3}\mathrm{d}x$ would be. Give reasons.   
(iii) Confirm your answer by carrying out the integration. [image]

5. The graph of $y = (x - 1)^4 - 1$ is shown here. [image]   
(i) Find the area of the shaded region $A$ by evaluating $\int_{- 1}^{0}((x - 1)^{4} - 1)\mathrm{d}x$   
(ii) Find the area of the shaded region $B$ by evaluating an appropriate integral.   
(iii) Write down the area of the total shaded region.   
(iv) Why could you not just evaluate $\int_{- 1}^{2}((x - 1)^{4} - 1)\mathrm{d}x$ to find the total area?

7. Find the area of the shaded region for each of the following graphs. [image]

8. The equation of a curve is such that $\frac{\mathrm{d}y}{\mathrm{d}x} = \frac{6}{\sqrt{3x - 2}}$ . Given that the curve passes through the point $\mathrm{P}(2,9)$ , find   
(i) the equation of the normal to the curve at $\mathrm{P}$   
(ii) the equation of the curve.

10. A curve has equation $y = \mathrm{f}(x)$ . It is given that $\mathrm{f}^{\prime}(x) = \frac{1}{\sqrt{(x + 6)}} +\frac{6}{x^{2}}$ and that $\mathrm{f}(3) = 1$ . Find $\mathrm{f}(x)$ . Cambridge International AS & A Level Mathematics 9709 Paper 11 Q2 November 2013

12. The diagram shows the curve $y = (3 - 2x)^{3}$ and the tangent to the curve at the point $(\frac{1}{2},8)$ . [image]   
(i) Find the equation of this tangent, giving your answer in the form $y = mx + c$ .   
(ii) Find the area of the shaded region. Cambridge International AS & A Level Mathematics 9709 Paper 11 Q10 November 2013

14. The diagram shows part of the curve $y = \frac{8}{\sqrt{3x + 4}}$ . The curve intersects the $y$ - axis at $A(0, 4)$ . The normal to the curve at $A$ intersects the line $x = 4$ at the point $B$ . [image]   
(i) Find the coordinates of $B$ .   
(ii) Show, with all necessary working, that the areas of the regions marked $P$ and $Q$ are equal. Cambridge International AS & A Level Mathematics 9709 Paper 11 Q10 June 2015

16. The diagram shows parts of the graphs of $y = x + 2$ and $y = 3\sqrt{x}$ intersecting at points $A$ and $B$ . [image]   
(i) Write down an equation satisfied by the $x$ coordinates of $A$ and $B$ . Solve this equation and hence find the coordinates of $A$ and $B$ .   
(ii) Find by integration the area of the shaded region. Cambridge International AS & A Level Mathematics 9709 Paper 13 Q9 November 2014  
---  
#### Hodder PM1 **Exercise 7G**  
Evaluate the following improper integrals.  
1. $\int_{0}^{1} \frac{1}{\sqrt{x}} \, dx$  
2. $\int_{1}^{\infty} \frac{1}{x^3} \, dx$  
3. $\int_{1}^{\infty} \frac{2}{x^2} \, dx$  
4. $\int_{-\infty}^{-2} \frac{2}{x^3} \, dx$  
5. $\int_{1}^{\infty} \frac{1}{x^2} \, dx$  
6. $\int_{0}^{4} \frac{6}{\sqrt{x}} \, dx$  
---  
#### Hodder PM1 **Exercise 7H**  
1. Describe the solid of revolution obtained by a rotation through $360^{\circ}$ of   
(i) a rectangle about one side   
(ii) a semicircle about its diameter   
(iii) a circle about a line outside the circle.  
2. Calculate the volume of the solid obtained in Figure 7.27, leaving your answer as a multiple of $\pi$ . [image]

4. In each part of this question a region is defined in terms of the curves which form its boundaries. Draw a sketch of the region and find the volume of the solid obtained by rotating it through $360^{\circ}$ about the $x$ - axis.  
(i) $y = 2x$ , the $x$ - axis and the lines $x = 2$ and $x = 5$  
(ii) $y = 4x^{2}$ , the $x$ - axis and the lines $x = 1$ and $x = 2$  
(iii) $y = x^{3}$ , the $x$ - axis and the lines $x = -2$ and $x = 2$  
(iv) $y = \sqrt{x}$ , the $x$ - axis and the lines $x = 1$ and $x = 9$  
(v) $y = 4x - x^{2}$ , the $x$ - axis and the lines $x = 1$ and $x = 3$  
(vi) $y = \frac{1}{x^{2}}$ , the $x$ - axis and the lines $x = 2$ and $x = 5$  
(vii) $y = \frac{1}{\sqrt{x}}$ , the $x$ - axis and the lines $x = 1$ and $x = 4$

6. In each part of this question a region is defined in terms of the curves which form its boundaries. Draw a sketch of the region and find the volume of the solid obtained by rotating it through $360^{\circ}$ about the $y$ - axis.  
(i) $y = 3x$, the y-axis and the lines $y = 3$ and line $y = 6$  
(ii) $y = x - 3$, the y-axis and the x-axis and line $y = 6$  
(iii) $y = x^{2} - 2$, the y-axis and the lines $y = 4$

8. A mathematical model for a large garden pot is obtained by rotating through $360^{\circ}$ about the $y$ - axis the part of the curve $y = 0.1x^{2}$ which is between $x = 10$ and $x = 25$ and then adding a flat base. Units are in centimetres.   
(i) Draw a sketch of the curve and shade in the cross-section of the pot, indicating which line will form its base.   
(ii) Garden compost is sold in litres. How many litres will be required to fill the pot to a depth of $45\mathrm{cm}$ ? (Ignore the thickness of the pot.)

10.
(i) Sketch the curve $y = 18 - 3x^{2}$ and the line $y = 6$ on the same diagram. Shade the region bounded by the curve $y = 18 - 3x^{2}$ and the line $y = 6$ .   
(ii) Calculate the volume of the solid obtained when the shaded region is rotated about (a) the $y$ - axis (b) the $x$ - axis.

12. Sketch the curve $y = x^{2} + 3$ and shade the region bounded by the curve and the line $y = 4$ . Find the volume of the solid obtained when this shaded region is rotated completely about the $x$ - axis, giving your answer in terms of $\pi$ .

14. The diagram shows the circle $x^{2} + y^{2} = 25$ and the line $x = 4$ . [image] Find the volume of the solid obtained when this shaded region is rotated completely about the $y$ - axis, giving your answer in terms of $\pi$ .

16. The diagram shows the curve $y = 3x^{\frac{1}{4}}$ . The shaded region is bounded by the curve, the $x$ - axis and the lines $x = 1$ and $x = 4$ . [image] Find the volume of the solid obtained when this shaded region is rotated completely about the $x$ - axis, giving your answer in terms of $\pi$ . Cambridge International AS & A Level Mathematics 9709 Paper 1 Q2 June 2007

18. The diagram shows part of the curve $y = \frac{a}{x}$ , where $a$ is a positive constant. [image] Given that the volume obtained when the shaded region is rotated through $360^{\circ}$ about the $x$ - axis is $24\pi$ , find the value of $a$ . Cambridge International AS & A Level Mathematics 9709 Paper 12 Q2 June 2010

20. The diagram shows part of the curve $y = (1 + 4x)^{\frac{1}{2}}$ and a point $\mathrm{P}(6,5)$ lying on the curve. The line PQ intersects the $x$ - axis at $\mathrm{Q}(8,0)$ . [image] Show that PQ is a normal to the curve. Find, showing all necessary working, the exact volume of revolution obtained when the shaded region is rotated through $360^{\circ}$ about the $x$ - axis. [In part
(ii) you may find it useful to apply the fact that the volume, $V$ , of a cone of base radius $r$ and vertical height $h$ , is given by $V = \frac{1}{3}\pi r^2 h$ .] Cambridge International AS & A Level Mathematics 9709 Paper 11 Q11 November 2015  
12 The diagram shows the line $y = 1$ and part of the curve $y = \frac{2}{\sqrt{x + 1}}$ . [image] Show that the equation $y = \frac{2}{\sqrt{x + 1}}$ can be written in the form $x = \frac{4}{y^2} - 1$ . Find $\int \left(\frac{4}{y^2} - 1\right)\mathrm{d}y$ . Hence find the area of the shaded region. The shaded region is rotated through $360^{\circ}$ about the $y$ - axis. Find the exact value of the volume of revolution obtained. Cambridge International AS & A Level Mathematics 9709 Paper 11 Q11 June 20


##Complete
**Example 1**
Given $\frac{\mathrm{d}y}{dx$  } = 9x^{2} - 4x + 3x^{\frac{1}{2}} - 7$ , find $y$ .
**Example 2**
Given $f^{\prime}(x) = x(3x - 4)^{2}$ , find $f(x)$
[image]
**Example 3**
Find the equation of the curve that passes through the point $(4, - 1)$ and where
$$\frac{\mathrm{d}y}{dx$  } = \frac{5x^2 + 1}{\sqrt{x}}.$$
**Example 4**
A curve is such that $\mathrm{f}^{\prime}(x) = \frac{10}{x^{3}} - 4$ and the point $(- 1,2)$ lies on the curve. Find the equation of the curve.
[image]
**Example 5**
A curve is such that $\frac{\mathrm{d}^{2}y}{dx$  ^{2}} = - 6x$ and the curve has a maximum point at $(1,2)$ Find the equation of the curve.
**Example 6**
Find $\int (4x - 3)^5 \mathrm{~d}x$ .
**Example 7**
Find $\int \frac{4}{(1 - 2x)^7} \mathrm{~d}x$ .
**Example 8**
$$\int \frac{6}{\sqrt{(4x + 9)}} \mathrm{~d}x$$
**Example 9**
Find $\int_{1}^{4} (3x^{2} + 2x) dx$   .
**Example 10**
Find $\int_{1}^{4} (3x - 1)(x + 2) dx$   .
**Example 11**
Find the area bounded by the curve with equation $y = (2 - x)(3 + x)$ , the positive $x$ - axis and the $y$ - axis.
[image]
**Example 12**
Find the area bounded by the curve with equation $y = x(x - 4)$ and the $x$ - axis.
[image]
**Example 13**
Find the area bounded by the curve with equation $y = x(x + 2)(x - 2)$ and the $x$ - axis.
[image]
**Example 14**
Find the area bounded by the curve with equation $y = (x + 3)^{2}$ and the lines $x = -4$ and $x = -1$ .
**Example 15**
The diagram shows a sketch of the curve with equation $y = x(5 - x)$ and the line $y = 2x$ . Work out the shaded area.
[image]
**Example 16**
The diagram shows the curve $y = x^{2} + 2x$ and the line $y = - x$ . Work out the area of the shaded region.
[image]
**Example 17**
Find the area of the finite region bounded by $y = x^{2}$ and $y = x - x^{2}$ .
[image]
**Example 18**
Show that the improper integral $\int_{1}^{\infty} \frac{2}{x^{3}} dx$   has a value and find that value.
**Example 19**
Show that only one of the following improper integrals has a finite value and find that value.
$$\int_{-\infty}^{0}\frac{2}{x^{5}}dx$   
$b)}\int_{-\infty}^{2}\frac{2}{x^{5}}dx$  
**Example 20**
Find the volume obtained when the shaded region is rotated through $360^{\circ}$ about the $x$ -axis.
[image]
**Example 21**
Find the volume obtained when the shaded region is rotated through $360^{\circ}$ about the $x$ - axis.
[image]
**Example 22**
The diagram shows the line $y = 1$ , the line $y = 4$ and part of the curve $y = 3x^2$ . The shaded region is rotated through $360^{\circ}$ about the $y$ - axis. Find the exact value of the volume of revolution obtained.
[image]

---
#### Complete PM1 **Exercise 10.1**
1. Find $y$ given $\frac{\mathrm{d}y}{dx$  }$ in each case.
a) $2x$  
b) $x^{7}$  
c) $3x^{2}$  
d) $-15$  
e) $x - x^{3}$  
f) $10x + 8x^{7}$  
g) $5 - \frac{1}{2} x$  
h) $x(x^{4} - 6)$  
i) $\sqrt{x}$  
j) $(2x - 3)^{2}$  
k) $\frac{2x^{2} + 7x}{x}$  
l) $\frac{12}{x^{2}} - \frac{6}{x^{3}}$
2. Find $f(x)$ given $f^{\prime}(x)$ in each case.
a) $\frac{9}{8} x^{\frac{1}{2}}$  
b) $-2x$  
c) $\frac{\sqrt{x}}{3}$  
d) $12x^{5}$  
e) $3 - x - 2x^{5}$  
f) $\left(\frac{1}{x^{2}} +5\right)^{2}$  
g) $\frac{4}{\sqrt[3]{x}}$  
h) $\frac{24x^{3} - 8x}{x}$  
i) $(x - 4)(x + 7)$  
j) $- \frac{5}{6}$  
k) $x^{2} + x^{-2}$  
l) $\frac{14x^{8} - 3}{x^{2}}$

4. Find
a) $\int 6xdx$    
b) $\int 4x + 1dx$    
c) $\int 4x^{- \frac{1}{2}}dx$    
d) $\int 7x^{- 8}dx$    
e) $\int (x + 4)^{2}dx$    
f) $\int \frac{4x^{- \frac{3}{4}}}{3}dx$    
g) $\int (9 - 6x)dx$    
h) $\int \frac{2x + 5x^{3}}{x}dx$    
i) $\int 2x(1 - x)^{2}dx$    
j) $\int \frac{(2x + 1)^{2}}{\sqrt{x}}dx$    
k) $\int \left(\frac{3}{\sqrt{x}} -\sqrt{x^{3}}\right)dx$    
l) $\int \sqrt{x} -(\sqrt{x} +5)^{2}dx$

#### Complete PM1 **Exercise 10.2**
1. Find the equation of each curve, given $\frac{\mathrm{d}y}{dx$  }$ and a point on the curve.
a) $\frac{dy}{dx}$ = 3x^2 - 6x + 2$ point $= (-2, -10)$  
b) $\frac{dy}{dx}$ = (1 - 2x)^2$ point $= (1,8)$  
c) $\frac{dy}{dx}$ = x(2x + 5)$ point $= (5, -1)$  
d) $\frac{dy}{dx}$ = \sqrt{x}\left(\sqrt{x} - 3\right)$ point $= (9,12)$  
e) $\frac{dy}{dx}$ = \frac{9x^3 - 3x}{x}$ point $= (-5,4)$  
f) $\frac{dy}{dx}$ = (3x - 1)(5x + 2)$ point $= (-4, -6)$

3. A curve is such that $\frac{\mathrm{d}y}{dx$  } = \frac{5}{\sqrt{x}} - 10\sqrt{x^3}$ and the point $(1, -6)$ lies on the curve. Find the equation of the curve.
4. 
5. A curve passes through the point (7, 10) and its gradient function is $\frac{6}{x^3} + 2$ . Find the equation of the curve.
6. 
7. The curve $C$ , with equation $y = f(x)$ passes through the point $(-2, -1)$ and $f'(x) = x(3 - x)$ . Find the equation of $C$ in the form $y = f(x)$ .
8. 
9. A curve is such that $\frac{\mathrm{d}^2y}{dx$  ^2} = -8x$ . The curve has a maximum point when $x = 1$ , and the point $(2, -1)$ lies on the curve. Find the equation of the curve.
10. 
11. $f'(x) = 8x^3 - 4 + 3x^{\frac{-1}{2}}$ and $f(4) = 3$ , find $f(x)$ .
12. 
13. Given that $\frac{\mathrm{d}^2y}{dx$  ^2} = -3x + 2$ and that when $x = -1$ , $\frac{\mathrm{d}y}{dx$  } = 5$ and $y = 0$ , find $y$ in terms of $x$ .
14. 
15. The curve $C$ passes through the point $(3, 10)$ and its gradient at any point is given by $\frac{\mathrm{d}y}{dx$  } = 6x^2 - 4x + 3$ .
a) Find the equation of the curve $C$ .  
b) Show that the point $(2, -21)$ lies on the curve.
17. A curve is such that $\frac{\mathrm{d}^2y}{dx$  ^2} = 6x$ . The curve has a maximum point when $x = -1$ , and the point $(3, -2)$ lies on the curve. Find the equation of the curve.
18. The gradient of a curve is given by $\frac{\mathrm{d}y}{dx$  } = ax + b$ . Given that the curve passes through $(0, 0)$ , $(1, 1)$ and $(- 2, 16)$ , find the equation of the curve.


#### Complete PM1 **Exercise 10.3**
1. Find
a) $\int (3x - 2)^4 dx$  
b) $\int (2x - 5)^3 dx$  
c) $\int 3(2x + 1)^5 dx$  
d) $\int (1 - 5x)^6 dx$  
e) $\int \frac{1}{(3x + 1)^2} dx$  
f) $\int \frac{2}{(1 - x)^5} dx$  
g) $\int 3\sqrt{1 - 4x} dx$  
h) $\int \frac{1}{\sqrt{2x + 3}} dx$  
i) $\int \frac{4}{(3 - 2x)^3} dx$  
j) $\int 8(4x + 3)^7 dx$  
k) $\int 4\sqrt[3]{3 - 2x} dx$  
l) $\int \frac{3}{\sqrt{1 - 2x}} dx$
2. Find
a) $\int_{1}^{3} (2x - 3)^4 dx$  
b) $\int_{0}^{2} \sqrt{2x + 1} dx$  
c) $\int_{-1}^{4} \frac{1}{(3x + 2)^2} dx$  
d) $\int_{1}^{2} \frac{4}{(3 - x)^5} dx$

#### Complete PM1 **Exercise 10.4**
1. Evaluate
a) $\int_{1}^{4} 4x^3 dx$  
b) $\int_{-2}^{0} 5x^4 dx$  
c) $\int_{1}^{3} (x^2 - 4) dx$  
d) $\int_{0}^{2} (3x^2 - 2x) dx$  
e) $\int_{1}^{9} \frac{1}{2\sqrt{x}} dx$  
f) $\int_{1}^{2} \frac{x^2 - 1}{x^4} dx$  
g) $\int_{1}^{2} (2x - 1)(x + 2) dx$  
h) $\int_{-1}^{2} (2x - 3)^2 dx$  
i) $\int_{1}^{4} \frac{4x - 3}{\sqrt{x}} dx$  
j) $\int_{1}^{8} \frac{3x - 2}{x^{\frac{2}{3}}} dx$  
k) $\int_{0}^{3} \sqrt{(3 - x)} dx$  
l) $\int_{0}^{3} \frac{4x + 1}{x^{3}} dx$
2. Find
$$\int_{-1}^{3}(6x^{2} - 2x)dx$    
$$\int_{-3}^{2}(3x^{2} + 8x + 1)dx$  
3. Evaluate
$$\int_{0}^{3}\frac{4x + 1}{x^{3}}dx$    
$$\int_{0}^{3}\sqrt{(3 - x)}dx$

---   

#### Complete PM1 **Exercise 10.5**
1. Find the area of each of the shaded regions.
[image]
2. For each, find the area bounded by the curve and the $x$ -axis. First, sketch the curve.
a) $y = 3x^{2} - 3$  
b) $y = x(x + 2)(x - 1)$  
c) $y = x^{3} - 5x^{2} - 6x$  
d) $y = 1 - 4x^{2}$
3. Find the area bounded by the curve $y = \sqrt{x}$ , the $y$ -axis and the lines $y = 1$ and $y = 3$ .
4. Find the area bounded by the curve $y = x^{3}$ , the $x$ -axis and the lines $x = -1$ and $x = 2$ .
5. Find the area bounded by the curve $x = (y + 3)(y - 1)$ and the $y$ -axis.
6. Find the area bounded by the curve $y = 2\sqrt{x}$ , the $x$ -axis and the lines $x = 1$ and $x = 9$ .
7. a) Draw the graph of $x + y = 5$ and find the area bounded by the line $x + y = 5$ , the $x$ -axis and the $y$ -axis.  
b) Check this area using integration.
8. The diagram shows part of the curve with equation $y = \frac{16}{\sqrt{x}} + \sqrt{x}$ . Find the area bounded by the curve, the lines $x = 1$ , $x = 4$ and the $x$ -axis. [image]
9. [image] Find the area of the shaded region.
10. The diagram shows part of the curve with equation $y = (x - 5)(x + 2)(x - 3)$ .  
a) Write down the coordinates of $A$ and $B$ .  
b) Show that the equation may be written as $y = x^{3} - 6x^{2} - x + 30$ .  
c) Find the total shaded area. [image]

---

#### Complete PM1 **Exercise 10.6**
1. Find the shaded areas.
[image] [image]
2. Find the area of the region bounded by the curve with equation $y = x^{2}$ and the curve with equation $y = 2x - x^{2}$ .
3. [image] The diagram shows the curve $y = 9 - x^2$ and the line $y = 5$ . Find the shaded area.
4. [image] The diagram shows parts of the curves $y = x^2$ and $y = x^4$ . Find the shaded area.
5. Find the area between the curve with equation $y = x(x - 1)$ and the line $y = 3x$ .
6. a) Show that the curve $y = 2x^2 + 3$ and the curve $y = 10x - x^2$ meet at the points where $x = 3$ and $x = \frac{1}{3}$ .  
b) Find the area between these two curves.
7. [image] Find the area bounded by the curve $y = x^2 - 3x + 8$ and the line $y = x + 5$ .
8. [image] The diagram shows part of the curve with equation $y = \frac{1}{x^2} +x$ . At point $P$ on the curve, $x = 1$ and at point $Q$ on the curve, $x = 2$ . Find the shaded area.
9. [image] The diagram shows the curve with equation $y = 25 + 2x - x^2$ . The straight line with equation $y = x + 5$ cuts the curve in two places. Find the exact area of the shaded region.
10. [image] Find the area bounded by the two curves.


#### Complete PM1 **Exercise 10.7**
1. Show that only one of the following improper integrals has a finite value and find that value.
a. $\int_{0}^{1}\frac{4}{\sqrt{x}}dx$   
b) $\int_{1}^{2}\frac{4}{\sqrt{x}}dx$  
2. Find  
a) $\int_{2}^{3}x^{3}dx$   
b) $\int_{2}^{3}x^{-3}dx$  
c) Hence, find whether the following integrals exist and, if they do, find their value.
$\int_{2}^{3}x^{3}dx$   
d)$\int_{2}^{3}x^{-3}dx$  
3. a) Find, in terms of $a$ and $b$ , the value of the integral $\int_{a}^{b} \frac{6}{x^{2}} \mathrm{~d} x$ .  
b) Show that only one of the following improper integrals has a finite value and find that value.  
i) $\int_{0}^{9}\frac{6}{x^{2}}dx$  
ii)$\int_{9}^{9}\frac{6}{x^{2}}dx$  
4. For each of the following improper integrals, find the value of the integral or explain briefly why it does not have a value.  
a) $\int_{27}^{27}\sqrt[3]{x}dx$  
b) $\int_{27}^{27}\frac{1}{\sqrt[3]{x^{2}}}dx$  
5. Explain briefly why $\int_{0}^{100}3x^{-\frac{1}{2}}dx$   is an improper integral.
6. For each of the following improper integrals, find the value of the integral or explain briefly why it does not have a value.  
a) $\int_{0}^{100}3x^{-\frac{1}{2}}dx$  
b) $\int_{0}^{100}3x^{-\frac{3}{2}}dx$  
c) $\int_{100}^{100}3x^{-\frac{1}{2}}dx$

#### Complete PM1 **Exercise 10.8**
1. [image] Find the volume obtained when the shaded region is rotated through $360^{\circ}$ about the $x$ - axis.
2. [image] Find the volume obtained when the shaded region is rotated through $360^{\circ}$ about the $x$ - axis.
3. [image] Find the volume obtained when the shaded region is rotated through $360^{\circ}$ about the $y$ -axis.
4. [image] Find the volume obtained when the shaded region is rotated through $360^{\circ}$ about the $y$ - axis.
5. [image] Find the volume obtained when the shaded region is rotated through $360^{\circ}$ about the $x$ - axis.
6. Find the volume obtained when region bounded by the curve $y = x(3 - x)$ and the $x$ -axis is rotated through $360^{\circ}$ about the $x$ -axis.
7. [image] Find the volume obtained when the shaded region is rotated through $360^{\circ}$ about the $x$ - axis.
8. [image] Find the volume obtained when the shaded region is rotated through $360^{\circ}$ about the $y$ -axis.
9. The curve $y^{2} = x$ and the line $y = x$ meet at the points $A$ and $B$ .  
a) Find the coordinates of the points $A$ and $B$ .  
b) Sketch the curve $y^{2} = x$ and the line $y = x$ on one set of axes.  
c) Find the volume obtained when the region between the line and the curve is rotated through $360^{\circ}$ about the $x$ -axis.
10. [image] Find the volume obtained when the shaded region is rotated through $360^{\circ}$ about the $x$ -axis. Give your answer to the nearest whole number.
11. [image] The diagram shows the lines $y = 2$ and $y = 5$ and part of the curve $y = 2x^{2} + 1$ . The shaded region is rotated through $360^{\circ}$ about the $y$ -axis. Find the exact value of the volume of revolution obtained.
12. The area between curve $y^{2} = x(4 - x)^{2}$ and the $x$ -axis is rotated through $360^{\circ}$ about the $x$ -axis. Find the exact value of the volume of the solid of revolution formed by this rotation.
13. The diagram shows part of the curve $y^{2} = 32x$ and part of the curve $y = x^{3}$ . The shaded region is rotated through $360^{\circ}$ about the $x$ -axis. Find the exact value of the volume of revolution obtained. [image]

**Summary Exercise**
1. Find these integrals.
a) $\int 12x^2dx$  
b) $\int \left(\frac{3}{x^2} -2x\right)dx$  
c) $\int (6 - x)^2dx$   
d) $\int 2\sqrt{x}\left(1 + \sqrt{x}\right)^2dx$   
e) $\int \frac{x + 5x^7}{x^3}dx$   
f) $\int \left(\frac{2}{\sqrt[3]{x}} -14\sqrt{x^5}\right)dx$   
2. Find the equation of the curve, given $\frac{\mathrm{d}y}{dx$  }$ and a point on the curve.
a) $\frac{d}{dx} = 9x^2 -2x + 1&, point = (-3,5)
b) $\frac{dy}{dx} = \frac{4x^4 - 5x}{x}, point = (-1, -2)  
c) $\frac{dy}{dx} = \left(\sqrt{x} +3\right)^2$, point = (4,2)  
d) $\frac{dy}{dx} = 8x - \frac{7}{x^2}$,  point = (1, -4)  
3. Given that $\mathrm{f}^{\prime}(x) = 2x^{2} - x + 3\sqrt{x}$ and $\mathrm{f}(4) = 0$ find $\mathrm{f}(x)$

**EXAM-STYLE QUESTIONS**
4. Find an expression for $y$ in terms of $x$ if $\frac{\mathrm{d}y}{dx$  } = (3x - 5)(x - 1)$ and $y = 0$ when $x = 5$
5. Find
a) $\int \left(x + \frac{1}{x}\right)^2dx$   
b) $\int \frac{2x^4 + 3}{x^4}dx$   
c) $\int \frac{x^2(x - 1)^2}{x}dx$   
d) $\int \sqrt{(7 - x)}dx$  
6. Find $\int_{-2}^{-1}\frac{1}{(3x + 2)^5}dx$  .$
7. Show that only one of the following improper integrals has a finite value and find that value.
a) $int \frac{1}{\sqrt{x}}dx$   
b) $\int \frac{1}{\sqrt{x}}dx$  
8. Find in terms of $p$ and $q$ the value of the integral $\int_{p}^{q}\frac{3}{x^{4}}dx$  .$

9. Show that only one of the following improper integrals has a finite value and find that value.
$$\mathrm{a)} \int_{0}^{1}\frac{3}{x^{4}}dx$   \mathrm{b)} \int_{1}^{3}\frac{3}{x^{4}}dx$

11. For each of the following integrals explain briefly why it is an improper integral.
a $\int_{0}^{1}\frac{1}{x}dx$   
b)$\int_{0}^{1}\frac{1}{x^{2}}dx$   
c) $\int_{0}^{27}\frac{1}{4x^{-3}}dx$    
d) Find whether each of the integrals has a finite value and, where possible, find its value.

13. [image] The diagram shows the curve $y = x(x - 1)$ . Find the total shaded area.

15. Find the area bounded by the curve $y = 3x^{2} - 2x + 1$ , the $x$ -axis and the lines $x = 1$ and $x = 2$ . First draw a sketch.

17. Find the area bounded by the curve $y = 2 + x - x^{2}$ and the line $y = x + 1$ .

19. [image] The diagram shows the curve $y = x(4 - x)$ and the line $y = 3$ . Find the shaded area.

21. [image] The diagram shows a sketch of the curve $y = 3x - x^{2}$ and the line $y = - 2x$ . Find the area of the shaded region.

23. Find the value of $\int_{-4}^{4}x^{3}dx$   and explain the significance of the answer.

25. a) Sketch the curve $y = x(x^{2} - 1)$ showing clearly where the curve crosses the $x$ -axis.
b) Find the area between the curve and the $x$ -axis.  
c) Find the volume obtained when the area bounded by the curve and the positive $x$ -axis is rotated $360^{\circ}$ about the $x$ -axis.

27. [image] Find the volume generated when the shaded area is rotated through $360^{\circ}$ about the $x$ - axis.

29. [image] The diagram shows the line $y = 1$ and part of the curve with equation $y^{2} = 4 - x$ .
a) Find the volume obtained when the shaded region is rotated through $360^{\circ}$ about the $x$ -axis.  
b) Find the volume obtained when the shaded region is rotated through $360^{\circ}$ about the y-axis.

31. [image] The diagram shows the region enclosed by the curve with equation $y = \frac{6}{x}$ , the $y$ - axis and the lines $y = 2$ and $y = 3$ . Find, in terms of $\pi$ , the volume obtained when this region is rotated through $360^{\circ}$ about the $y$ - axis.
  
33. Find the area enclosed by the curve $y = \frac{2x^3 + 3}{x^2}$ , the line $x = \frac{1}{2}$ and the line $x = 4$ .
  
35. [image] The diagram shows the line $y = 4$ and part of the curve with equation $y = \sqrt{x + 4}$ .
a) Show that the equation $y = \sqrt{x + 4}$ can be written in the form $x = y^2 - 4$ .  
b) Find the area of the shaded region.  
c) Find the volume obtained when the shaded region is rotated through $360^{\circ}$ about the $y$ -axis.

37. The region bounded by the curve $4y = x^2$ , the line $x = 4$ and the line $y = 1$ , is rotated through $360^{\circ}$ about the $x$ -axis. Find the volume of the solid formed.

39. The area bounded by the curve $y = 15kx - 15x^2$ and the $x$ -axis is rotated through $360^{\circ}$ about the $x$ -axis, where $k$ is an integer. The volume of the solid formed is $240\pi$ . Find the value of $k$ .
