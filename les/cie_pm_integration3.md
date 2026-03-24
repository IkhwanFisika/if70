# PM3 Differential Equation

#### Differential Equations

- **Definition:** An equation that relates a function to its derivatives. They are used to model rates of change in various phenomena (cooling, population growth, motion, etc.).

- **First-Order, Separable Variables**
    - **Form:** A differential equation that can be written as \(\frac{dy}{dx} = f(x)g(y)\), or equivalently \(g(y) \, dy = f(x) \, dx\).
    - **Solution Method (Separation of Variables):**
        1.  Rearrange the equation to get all \(y\) terms on one side with \(dy\) and all \(x\) terms on the other with \(dx\).
        2.  Integrate both sides: \(\int g(y) \, dy = \int f(x) \, dx\).
        3.  Solve the resulting equation for \(y\) to find the general solution, which includes a constant of integration.

- **General and Particular Solutions**
    - **General Solution:** The family of all possible solutions, containing an arbitrary constant \(c\).
    - **Particular Solution:** A single, unique solution obtained by using an **initial condition** (e.g., \(y = y_0\) when \(x = x_0\)) to find the value of \(c\).

- **Modelling with Differential Equations**
    - **Key Steps:**
        1.  **Formulate:** Translate a real-world statement into a mathematical differential equation. Look for keywords like "rate of change," "is proportional to," and define variables clearly. Determine the constant of proportionality from given data.
        2.  **Solve:** Use separation of variables to find the general solution.
        3.  **Interpret:** Use the initial condition to find the particular solution.
        4.  **Analyze:** Use the particular solution to make predictions (e.g., find a value at a given time, find when a certain condition is met, describe the long-term behavior of the model).

## Oxford Complete PM3

---  
**Example 1**  
A body falling through a fluid experiences resistance, causing it to lose speed at a rate proportional to its speed at that instant. Write down a differential equation satisfied by the speed $v$ at time $t$ , and sketch a needle diagram in the first quadrant to illustrate the solution to this differential equation.  
[image]  
**Example 2**  
Water is leaking from a tank. The rate at which the depth of water is decreasing is proportional to the square root of the current depth. Write down a differential equation satisfied by the depth $h$ at time $t$ , and sketch a needle diagram in the first quadrant to illustrate the solution to this differential equation.  
[image]  
**Example 3**  
A differential equation has the form $\frac{dy}{dx} = xy$ . Sketch a needle diagram in all four quadrants to illustrate the solution of this differential equation.  
[image]  
**Example 4**  
A rectangular tank has a base of $5\mathrm{m}^2$ . Water is flowing into the tank at a constant rate of 10 litres per second $(= 0.01\mathrm{m}^3\mathrm{s}^{- 1})$ . At the same time, water is leaking out at a rate proportional to $\sqrt{h}$ where $h$ is the depth of the water at time $t$ . When the depth is 1 metre the water is leaking out at 2 litres per second. Find the differential equation describing the rate of change of $h$ with time $t$ .  
**Example 5**  
Solve $\frac{dy}{dx} = 2y$ .  
**Example 6**  
Solve $\frac{dy}{dx} = 2xy.$  
**Example 7**  
Solve $\frac{dy}{dx} = \cos x.$  
[image]  
**Example 8**  
Solve $\frac{dy}{dx} = \cos^2 y.$  
**Example 9**  
Solve $\frac{dy}{dx} = \frac{3x^2\sin^2y}{(x^3 + 2)}$  
**Example 10**  
Solve $\frac{dy}{dx} = \frac{2}{x^2 - 1}$  
**Example 11**  
Solve $\frac{dy}{dx} = y^2 \ln x$  
**Example 12**  
Find the curve which satisfies $\frac{dy}{dx} = 2y$ and passes through $(0,3)$ .  
**Example 13**  
Find the curve which satisfies $\frac{dy}{dx} = \frac{2}{x^2 - 1}$ and passes through $(2,0)$ .  
[image]  
**Example 14**  
Find the curve which satisfies $\frac{dy}{dx} = \frac{4xy}{(x^2 + 3)}$ and passes through $(0,9)$ .  
[image]  
**Example 15**  
Find the curve which satisfies $\frac{dy}{dx} = \sin x$ sec $y$ and passes through $(0,0)$ .  
[image]  
**Example 16**  
Find the curve which satisfies $\frac{dy}{dx} = xy^2\mathrm{e}^{2x}$ and passes through $(0,1)$ .  
**Example 17**  
Find the curve which satisfies $y^2 \frac{dy}{dx} = x^2 \mathrm{e}^{x^3}$ and passes through the origin.  
**Example 18**  
A tank is draining in such a way that when the height of water in the tank is $h\mathrm{cm}$ , it is decreasing at the rate of $0.5\sqrt{h}\mathrm{cm}\mathrm{s}^{- 1}$ . Initially the water in the tank is at a height of $25\mathrm{cm}$ .  
a) Write down a differential equation which describes this situation.  
b) Solve the differential equation to find $h$ as a function of time.  
c) What is the height of the water after 10 seconds?  
d) How long does it take for the water to reach a height of $5\mathrm{cm}$ ?  
e) Sketch a graph of the height against time for $0\leq t\leq 20$ .  
[image]  
**Example 19**  
The spread of a disease occurs at a rate proportional to the product of the number of people infected and the number not infected. Initially 50 out of a population of 1050 are infected and the disease is spreading at a rate of 10 new cases per day. $\frac{\mathrm{d}n}{\mathrm{d}t} = \frac{n(1050 - n)}{5000}$ .  
a) If $n$ is the number infected after $t$ days, show that $\frac{\mathrm{d}n}{\mathrm{d}t} = \frac{n(1050 - n)}{5000}$ .  
b) Solve this differential equation to find the number of people infected after $t$ days.  
c) How long will it take for 250 people to be infected?  
d) Explain why everyone in the population will eventually be infected.  
**Example 20**  
A stone falls through the air from rest and, $t$ seconds after it was dropped, its speed $v$ satisfies the equation $\frac{\mathrm{d}v}{\mathrm{d}t} = 10 - 0.2v$ .  
a) Show that $v = 50(1 - \mathrm{e}^{-0.2t})$ .  
b) Calculate the time at which the stone reaches a speed of $20\mathrm{m}\mathrm{s}^{-1}$ .  
c) Sketch the graph of $v$ against $t$ and hence show that the velocity of the stone will never be more than $50\mathrm{m}\mathrm{s}^{-1}$ .  
d) Explain what the differential equation tells us would happen if the stone was thrown downwards with a speed of $60\mathrm{m}\mathrm{s}^{-1}$ instead of being dropped.  
[image]  
**Example 21**  
The size of a colony of pests, $n$ , which fluctuates during the year, is modelled by an entomologist with the differential equation $\frac{\mathrm{d}n}{\mathrm{d}t} = 0.2n(0.2 - \cos t)$ , where $t$ is the number of weeks from the start of the observations. There are 400 pests in the colony initially.  
a) Solve the differential equation to find $n$ in terms of $t$ .  
b) Find how many pests there are after 3 weeks.  
c) Show that the number of pests reaches a minimum after approximately 9.6 days, and find the number of pests at that time.  
d) Find how many pests there are after $2\pi$ weeks.  
e) Explain why the model predicts that the number of pests will grow infinitely large over time.  
[image]  
**Example 22**  
A model of the deflation of a sphere of radius $r$ cm assumes that at time $t$ seconds after the start, the rate of decrease of the surface area is proportional to the volume at that time.  
When $t = 0$ $r = 20cm$ and $\frac{\mathrm{d}r}{\mathrm{d}t} = - 3$  
a) Show that $r$ satisfies $\frac{\mathrm{d}r}{\mathrm{d}t} = -0.0075r^2$  
b) Solve this differential equation, obtaining an expression for $r$ in terms of $t$  
c) How long will it take for the sphere to deflate to a radius of $10\mathrm{cm}$  
d) How much longer will it be before the radius is $5\mathrm{cm}$  
[image]  
**Example 23**  
In a chemical reaction a substance $X$ reacts with another substance $Y$ . The masses of substances $X$ and $Y$ after time $t$ seconds are $x$ and $y$ grams respectively.  
It is given that $\frac{dy}{dt} = - 0.5xy$ and $x = 20\mathrm{e}^{- 2t}$ . Also, we know that when $t = 0$ , $y = 50$ .  
a) Form a differential equation in $y$ and $t$ .  
b) Solve this equation to obtain an expression for $y$ in terms of $t$ .  
c) Find the mass of $Y$ that remains as $t$ gets very large.  

---  
#### Oxford Complete **Exercise 10.1**  
1. The rate at which body temperature, $T$ , falls is proportional to the difference between the body temperature $T$ and the temperature $T_0$ of the surroundings. Find a differential equation relating body temperature, $T$ , and time $t$ .  
2. A certain substance is formed in a chemical reaction. The mass of the substance formed $t$ seconds after the start of the reaction is $x$ grams. At any time the rate of formation of the substance is proportional to $(30 - x)$ . Find a differential equation relating $x$ and $t$ .  
3. In studying the spread of a disease, a scientist thinks that the rate of infection is proportional to the product of the number of people infected and the number of people uninfected. If $N$ is the number infected at time $t$ and $P$ is the total number of people in the population, form a differential equation to summarise the scientist's theory.  
4. The rate of increase of a population is proportional to its size at the time. Write down a differential equation to describe this situation. It also known that when the population was 2 million, the rate of increase was 140 000 per day. Find the constant of proportionality in your DE.  
5. Sketch needle diagrams for the DEs in questions 1 to 3.  

---
#### Oxford Complete **Exercise 10.2**  
1. $\frac{dy}{dx} = \frac{x}{y}$  
2. $\frac{dy}{dx} = \frac{x^3}{y}$  
3. $\frac{dy}{dx} = \frac{x^2 + x + 1}{y^2}$  
4. $\frac{dy}{dx} = y(x + 3)$  
5. $\frac{dy}{dx} = \frac{2}{\cos y}$  
6. $\frac{dy}{dx} = \frac{1}{xy}$  
7. $2y\frac{dy}{dx} = 4x^3$  
8. $x^2\frac{dy}{dx} = 2y^3$  
9. $\frac{dy}{dx} = y\cos x$  
10. $\frac{dy}{dx} = 2xe^y$  
11. $\frac{dy}{dx} = 2x\sec y$  
12. $\frac{dy}{dx} = \frac{y^2}{x(x + 2)}$  
13. $\frac{dy}{dx} = \frac{\cos x}{\cos y}$  
14. $\frac{dy}{dx} = \frac{\cos^2 y}{x}$  
15. $2\frac{dy}{dx} = 4x^3 (y^2 - 1)$  
16. $\frac{dy}{dx} = \frac{\cos^2 y}{\cos^2 x}$  
17. $\frac{dy}{dx} = xe^x\sec y$  
18. $2\frac{dy}{dx} = \frac{y^2 - 1}{x^2 + x}$  
19. $\frac{dy}{dx} = y^2\sec^2 x$  
20. $\frac{dy}{dx} = \frac{x(1 + y^4)}{y^3}$  
21. $\frac{dy}{dx} = \left(\frac{x + 3}{x^2 + x}\right)y^2$  
22. $\left(\frac{-2}{y^3}\right)\frac{dy}{dx} = \frac{e^x}{1 + e^{2x}}$ Use the substitution $u = e^x$  
23. $y\frac{dy}{dx} = \sin^3 x\cos^2 x$  
24. $y\frac{dy}{dx} = \frac{27}{(9 + x^2)}$ Use the substitution $x = 3\tan \theta$  

---
#### Oxford Complete **Exercise 10.3**  
Find the particular solution to each of the following differential equations, given the prescribed initial condition. The first nine questions in this exercise use the same DEs as those in questions 1- 9 of Exercise 10.2, for which you should already have found the general solutions.  
1. $\frac{dy}{dx} = \frac{x}{y}; x = 1,y = 2$  
2. $\frac{dy}{dx} = \frac{x^3}{y}; x = 1,y = 2$  
3. $\frac{dy}{dx} = \frac{x^2 + x + 1}{y^2}; x = 0,y = 3$  
4. $\frac{dy}{dx} = y(x + 3); x = 0,y = 5$  
5. $\frac{dy}{dx} = \frac{2}{\cos y}; x = 0,y = \frac{\pi}{2}$  
6. $\frac{dy}{dx} = \frac{1}{xy}; x = 1,y = 2$  
7. $2y\frac{dy}{dx} = 4x^3; x = 2,y = 3$  
8. $2x^2\frac{dy}{dx} = y^3; x = 1,y = 0.5$  
9. $\frac{dy}{dx} = y\cos x; x = \frac{\pi}{2},y = 1$  
10. $\frac{dy}{dx} = \frac{x}{y}; x = 2,y = 0$ (This is the same DE as Q1, but with a different initial condition.)  
11. $\frac{dy}{dx} = \frac{1}{xy}, x = \mathrm{e},y = 1$ This is the same DE as Q6, but with a different initial condition.  
12. A curve passes through the point (1, 2) and its gradient function is $\frac{2x + 1}{2y}$ . Find the equation of the curve.  
13. A curve is such that $\frac{dy}{dx} = \sqrt{\frac{y}{x + 1}}$ and the point (3, 9) lies on the curve. Find the equation of the curve.  
14. A curve is such that $x^{3}\frac{dy}{dx} = \sec y$ and the point $\left(1,\frac{\pi}{6}\right)$ lies on the curve. Find the equation of the curve.  
15. A curve is such that $\mathrm{e}^{y}\frac{dy}{dx} -2\sec^{2}x = 10$ and the point $\left(\frac{\pi}{4},0\right)$ lies on the curve. Find the equation of the curve.  
16. A curve is such that $\sqrt{xy}\frac{dy}{dx} = 1$ and the point (4, 9) lies on the curve. Find the equation of the curve.  
17. A curve is such that $\frac{dy}{dx} = \frac{2\mathrm{e}^{-y}x}{x^{2} + 1}$ and the point (0, 0) lies on the curve. Find the equation of the curve.  
18. A curve is such that $x(x + 1)\frac{dy}{dx} = y$ and the point (1, 3) lies on the curve. Find the equation of the curve.  
19. A curve is such that $\mathrm{e}^{-y}\frac{dy}{dx} = -\mathrm{e}^{3x}$ and the point (0, 0) lies on the curve. Find the equation of the curve.  
20. A curve is such that $x^{3}\frac{dy}{dx} = \cos^{2}y$ and the point $\left(1,\frac{\pi}{4}\right)$ lies on the curve. Find the equation of the curve.  
21. A curve is such that $y\frac{dy}{dx} = x\mathrm{e}^{x^{2}}$ and the point (0, 3) lies on the curve. Find the equation of the curve.  

---
#### Oxford Complete **Exercise 10.4**  
1. A rod has the property that the temperature gradient, $\frac{\mathrm{d}T}{\mathrm{d}x}$ , at a distance $x$ cm from the end of the rod being heated is proportional to the distance $x$ . The end of the rod is heated to a temperature of $400^{\circ}\mathrm{C}$ , and when $x = 50$ we know that $\frac{\mathrm{d}T}{\mathrm{d}x} = -8$ .  
a) Write down a differential equation which is satisfied by the temperature $T$ at a distance $x$ from the end of the rod.  
b) Solve the differential equation to find an expression for the temperature $T$ in terms of $x$ .  
c) Calculate the temperature at the point $50\mathrm{cm}$ from the heated end of the rod.  
d) Calculate how far from the heated end of the rod the temperature reaches $20^{\circ}\mathrm{C}$ .  
2. In a chemical reaction a substance $X$ reacts with another substance $Y$ . The masses of substances $X$ and $Y$ after time $t$ seconds are $x$ and $y$ grams respectively. It is given that $\frac{\mathrm{d}y}{\mathrm{d}t} = -0.1xy$ and $x = 30e^{-3t}$ . Also, when $t = 0$ , $y = 20$ .  
a) Form a differential equation in $y$ and $t$ .  
b) Solve this differential equation to obtain an expression for $y$ in terms of $t$ .  
c) Find the proportion of $Y$ which will remain when $t$ is very large.  
3. Carbon-14 occurs in all living creatures at 1 part in a trillion carbon atoms, but when a creature dies, the carbon atoms are no longer exchanged with the atmosphere. Carbon-14 atoms decay at a rate proportional to the amount remaining at any given time.  
a) If $m$ is the mass of carbon-14 in 1 gram of carbon at any time $t$ years after a creature dies, form a differential equation relating $m$ and $t$ and solve it.  
b) Taking $m = 1$ when $t = 0$ , show that the differential equation is satisfied by $m = e^{-kt}$ .  
c) Carbon-14 is used to date fossils. It has a half- life of 5730 years (every 5730 years the mass of carbon-14 per gram of carbon in the fossil reduces by $50\%$ ). Find the value of $k$ in the expression for $m$ .  
d) A fossil is found to have 0.008 grams of carbon-14 per gram of carbon. Calculate how old the fossil is.  
4. A reservoir in the shape of a cuboid has a base area of $60,000 \mathrm{m}^2$ . Water is seeping from the reservoir at a rate proportional to the depth, and it is known that the reservoir loses water at a rate of 3000 litres per minute when the depth is 10 metres. The depth of water in the reservoir is 8 metres when a heavy storm starts, causing the reservoir to be filled at a constant rate of 1500 litres per second.  
a) Write down a differential equation which is satisfied by the depth of water, $d$ metres, at time $t$ minutes after the storm starts.  
b) Solve the differential equation.  
c) If the storm lasts for two and a half hours, calculate the depth of water in the reservoir when the storm ends.  
5. A colony of bacteria grows at a rate proportional to the size of the colony at any time.  
a) Write down a differential equation satisfied by the number of bacteria $N$ (in millions) after $t$ hours. Initially the colony has 2 million bacteria, and after 6 hours it has 2.5 million bacteria.  
b) Solve the differential equation to find an expression for $N$ in terms of $t$ .  
c) The space in which the colony is housed has room for 10 million bacteria. Calculate the time at which the space reaches saturation.  
6. A body moving through a liquid experiences a resistance to motion which causes it to lose speed at a rate proportional to its speed at any time.  
a) Write down a differential equation satisfied by the speed $v \mathrm{m} \mathrm{s}^{-1}$ after time $t$ seconds.  
Initially the body has a speed of $25 \mathrm{m} \mathrm{s}^{- 1}$ , and after 10 seconds it has a speed of $20 \mathrm{m} \mathrm{s}^{- 1}$ .  
b) Solve the differential equation to find an expression for $v$ in terms of $t$ .  
c) Calculate how long it takes for the body to lose half of its initial speed.  
7. A disease spreads at a rate proportional to the product of the number of people, $n$ , infected and the number of people not yet infected. The population has size $P$ . Initially $5\%$ of the population is infected.  
a) Write down a differential equation which is satisfied by $n$ and the time $t$ . After 3 days it is found that $10\%$ of the population is infected.  
b) Solve this differential equation to find the number of people infected after $t$ days.  
c) How long will it take for half the people to be infected?  
d) Explain why everyone in the population will eventually be infected.  

#### Oxford Complete **Summary exercise 10**  
1. Find the general solution to the following differential equations.  
a) $\frac{dy}{dx} = \frac{x^2}{y^3}$  
b) $\frac{dy}{dx} = 2x\cos^2 y$  
c) $\frac{dy}{dx} = \mathrm{e}^{3x}\sec y$  
d) $\mathrm{xtan}y\frac{dy}{dx} = 1$  
e) $\frac{dy}{dx} = \mathrm{e}^{3x - y}$  
f) $\frac{dy}{dx} = \frac{xy}{x^2 + 1}$  
g) $(x^2 + 6)\frac{dy}{dx} = 8xy$  
h) $\sin 3\theta \frac{\mathrm{d}\theta}{\mathrm{d}x} = (x + 2)\cos 3\theta$  
2. Find the particular solution to the following differential equations, with given initial conditions.  
a) $\frac{dy}{dx} = \frac{3x^2 + x}{4y^3};\quad x = 2,y = 1$  
b) $\frac{dy}{dx} = 2y^2\sin x;\quad x = \pi ,y = 1$  
c) $\frac{dy}{dx} = \mathrm{e}^{3x - y};\quad x = 0,y = 0$  
d) $\frac{\mathrm{d}v}{\mathrm{d}t} = \mathrm{e}^{-t}\sqrt{v};\quad t = 0,v = 9$  
e) $\frac{dy}{dx} = x\mathrm{e}^{x - y};\quad x = 0,y = 0$  
f) $\ln y\frac{dy}{dx} = \frac{x - 1}{x^2 + x};\quad x = 1,y = 1$  
**EXAM-STYLE QUESTIONS**  
3. A curve is such that $\frac{dy}{dx} = \frac{y}{\sqrt{x + 1}}$ and the point $(1,1)$ lies on the curve. Find the equation of the curve.  
4. A curve is such that $\frac{dy}{dx} = x\mathrm{e}^{x}$ sec $y$ and the point $\left(0,\frac{\pi}{6}\right)$ lies on the curve. Find the equation of the curve.  
5. A curve is such that $y\mathrm{e}^{y}\cos^{2}x\frac{dy}{dx} = 1$ and the point $\left(\frac{\pi}{4},0\right)$ lies on the curve. Find the equation of the curve.  
6. A curve is such that $\sqrt{y}\frac{dy}{dx} = \frac{2}{x^2 - 1}$ and the point $(2,0)$ lies on the curve. Find the equation of the curve.  
7. A curve is such that $y\frac{dy}{dx} = \cos^2 x$ and the point $\left(\frac{\pi}{4},0\right)$ lies on the curve. Find the equation of the curve.  
8. A curve is such that $\left(\frac{2y + 1}{y^2 + 1}\right)\frac{dy}{dx} = \frac{1}{x}$ and the point $(1,0)$ lies on the curve. Find the equation of the curve.  
9. The temperature of a hot body decreases at a rate proportional to the difference between its temperature and the air temperature around it. A body is heated to $90^{\circ}C$ and placed in air which is at $20^{\circ}C$ .  
a) Write down a differential equation relating the temperature $T$ of the body and the time $t$ .  
After 4 minutes the body has cooled to $60^{\circ}C$ .  
b) Solve the differential equation to find an expression for the temperature $T$ in terms of $t$ .  
c) Calculate the temperature after 10 minutes.  
d) Calculate how long it takes for the body to get down to within $5^{\circ}C$ of the air temperature.  
10. The resistance a body experiences passing through a liquid is proportional to the square of its speed at any time. The body has a speed of $50\mathrm{m}\mathrm{s}^{-1}$ entering the liquid.  
a) Write down a differential equation relating the speed $\nu$ of the body and the time $t$ . After 4 seconds the body has slowed to $30\mathrm{m}\mathrm{s}^{- 1}$ .  
b) Solve the differential equation to find an expression for the speed $\nu$ in terms of $t$ .  
c) Calculate the speed after 10 seconds.  
d) Calculate how long it takes for the body to slow down to $10\mathrm{m}\mathrm{s}^{- 1}$ .  
11. The spread of a rumour in a large group of people is thought to reach new people at a rate proportional to the product of the number of people who have heard the rumour and the number who have not heard it.  
In a population of 2000 people, initially 50 people have heard the rumour. Two hours later, 300 people have heard it.  
a) Write down a differential equation relating the number of people, $N$ , who have heard the rumour with the time $t$ .  
b) Solve the differential equation to find an expression for $N$ in terms of $t$ .  
c) Calculate how long it takes for the majority of people to have heard the rumour.  
12. a) Show that $\frac{\mathrm{d}\nu}{\mathrm{d}t} = \nu \frac{\mathrm{d}\nu}{\mathrm{d}x}$ where $\nu = \frac{\mathrm{d}x}{\mathrm{d}t}$ .  
The rate at which a body loses speed, $\nu$ , is proportional to its displacement, $x$ , from a fixed point.  
b) Show that the differential equation $$\nu \frac{\mathrm{d}\nu}{\mathrm{d}x} = -kx\mathrm{~describes~this~situation}.$$  
The body has speed $10\mathrm{m}\mathrm{s}^{- 1}$ as it passes through the fixed point and just reaches a point 5 metres from the fixed point as it comes to rest.  
c) Solve the differential equation to find an equation relating $\nu$ and $x$ , showing that $k = 4$ .  
d) Find the speed of the body when it is 3 metres from the fixed point.  
13. A tank contains a solution of a mineral in water. Initially there is 600 litres of water with $12\mathrm{kg}$ of the dissolved mineral. The mixture is drained at a rate of 30 litres per minute and simultaneously pure water is added at a rate of 30 litres per minute. The tank is stirred continuously to keep the mixture uniform at all times.  
a) Form a differential equation which is satisfied by the mass, $m$ kg, of the mineral in the solution at time $t$ minutes.  
b) Solve the differential equation to find an expression for $m$ in terms of $t$ . When the solution contains $8\mathrm{kg}$ of the mineral another $4\mathrm{kg}$ is added, and the process is repeated.  
c) Find the first time at which the solution contains $8\mathrm{kg}$ of the mineral.  
14. The variables $x$ and $y$ are related by the differential equation $$\frac{dy}{dx} = \frac{4y\mathrm{e}^{2x}}{5 + \mathrm{e}^{2x}}$$  
Given that $y = 36$ when $x = 0$ , find an expression for $y$ in terms of $x$ .  
15. The variables $x$ and $\theta$ satisfy the differential equation $$\frac{\mathrm{d}x}{\mathrm{d}\theta} = (x + 4)\sin^2 3\theta ,$$  
and it is given that $x = 0$ when $\theta = 0$ . Solve the differential equation and calculate the value of $x$ when $\theta = \frac{1}{4}\pi$ , giving your answer correct to 3 significant figures.  
16. A large field of area $3\mathrm{km}^2$ is becoming infected with a soil disease. At time $t$ years the area infected is $x\mathrm{km}^2$ and the rate of growth of the infected area is given by the differential equation $\frac{\mathrm{dx}}{\mathrm{dt}} = kx(3 - x)$ , where $k$ is a positive constant. It is given that when $t = 0$ , $x = 0.5$ and that when $t = 2$ , $x = 2$ .  
i) Solve the differential equation and show that $k = \frac{1}{6}\ln 10$  
ii) Find the value of $t$ when there is only 0.5 $\mathrm{km}^2$ of the field not infected giving your answer to 3 significant figures.  
Note: Question 17 is beyond the scope of the Cambridge International syllabus but may aid in your understanding.  
17. A man walks along a pier pulling a toy boat by a rope of length $L$ . The man keeps the rope taut and horizontal. Initially the rope is at right angles to the pier, with the boat at $A$ and the man at $B$ . A little while later the man is at $E$ and the boat is at $C$ . $D$ is the point on the pier such that $CD$ is perpendicular to the pier. $CD = x$ , $BD = y$ .  
[image]  
The path followed by the boat is called a tractrix, and has the property that the rope is always tangential to the path of the boat.  
a) If $y = \mathrm{f}(x)$ is the path of the boat, show that $\frac{\mathrm{dy}}{\mathrm{dx}} = \frac{\sqrt{L^2 - x^2}}{x}$ .  
b) Use the substitution $x = L\cos \theta$ to show that the solution to the differential equation is $$\mathrm{f}(x) = \frac{L\ln x}{(L - \sqrt{(L^2 - x^2)})} -\sqrt{(L^2 - x^2)}$$  
[You may use without derivation that $\int \cos \mathrm{ec}\theta \mathrm{d}\theta = \ln |\cos \mathrm{ec}\theta - \cot \theta |.$ ]  

----------------------------------------------------------------------  


## Hodder PM 3

**Example 9.1**  
An object is moving through a liquid so that the rate at which its velocity decreases is proportional to its velocity at any given instant. When it enters the liquid, it has a velocity of $5\mathrm{ms}^{- 1}$ and the velocity is decreasing at a rate of $1\mathrm{ms}^{- 2}$ . Find the differential equation to model this situation.  
**Example 9.2**  
A model is proposed for the temperature gradient within a star, in which the temperature decreases with respect to the distance from the centre of the star at a rate which is inversely proportional to the square of the distance from the centre. Express this model as a differential equation.  
**Example 9.3**  
The area $A$ of a square is increasing at a rate proportional to the length of its side $s$ . The constant of proportionality is $k$ . Find an expression for $\frac{\mathrm{d}s}{\mathrm{d}t}$ .  
[image]  
**Example 9.4**  
Solve the differential equation $\frac{dy}{dx} = 3x^2 - 2$ .  
**Example 9.5**  
Find, for $y > 0$ , the general solution of the differential equation $\frac{dy}{dx} = xy$ .  
**Example 9.6**  
Find the general solution of the differential equation $\frac{dy}{dx} = \mathrm{e}^{- y}$ .  
**Example 9.7**  
(i) Find the general solution of the differential equation $\frac{dy}{dx} = y^2$ .  
(ii) Find the particular solution for which $y = 1$ when $x = 0$ .  
[image]  
**Example 9.8**  
The motion of an object is such that its acceleration is given by $a = 3$ . If the object starts from rest at the origin, find an expression for its velocity after time $t$ seconds and find the time when the velocity is $8\mathrm{ms}^{-1}$ .  
**Example 9.9**  
Show that $\sin y = x$ is a solution of the differential equation $$\frac{dy}{dx} = \frac{1}{\sqrt{1 - x^2}}$$  
given that $y = 0$ when $x = 0$  

---  
#### Hodder **Exercise 9A**  
1. The differential equation  
$$\frac{\mathrm{d}\nu}{\mathrm{d}t} = 5\nu^2$$  
models the motion of a particle, where $\nu$ is the velocity of the particle in $\mathrm{m} \mathrm{s}^{- 1}$ and $t$ is the time in seconds. Explain the meaning of $\frac{\mathrm{d}\nu}{\mathrm{d}t}$ and what the differential equation tells you about the motion of the particle.  
2. A spark from a firework is moving in a straight line at a speed which is inversely proportional to the square of the distance which the spark has travelled from the firework. Find an expression for the speed (i.e. the rate of change of distance travelled) of the spark.  
3. The rate at which a sunflower increases in height is proportional to the natural logarithm of the difference between its final height $H$ and its height $h$ at a particular time. Find a differential equation to model this situation.  
4. In a chemical reaction in which substance A is converted into substance B, the rate of increase of the mass of substance B is inversely proportional to the mass of substance B present. Find a differential equation to model this situation.  
5. After a major advertising campaign, an engineering company finds that its profits are increasing at a rate proportional to the square root of the profits at any given time. Find an expression to model this situation.  
6. The coefficient of restitution $e$ of a squash ball increases with respect to the ball's temperature $\theta$ at a rate proportional to the temperature, for typical playing temperatures. (The coefficient of restitution is a measure of how elastic, or bouncy, the ball is. Its value lies between zero and one, zero meaning that the ball is not at all elastic and one meaning that it is perfectly elastic.) Find a differential equation to model this situation.  
7. A cup of coffee cools at a rate proportional to the temperature of the coffee above that of the surrounding air. Initially, the coffee is at a temperature of $95^{\circ}\mathrm{C}$ and is cooling at a rate of $0.5^{\circ}\mathrm{C}\mathrm{s}^{- 1}$ . The surrounding air is at $15^{\circ}\mathrm{C}$ . Find a differential equation to model this situation.  
8. The rate of increase of bacteria is modelled as being proportional to the number of bacteria at any time during their initial growth phase. When the bacteria number $2 \times 10^{6}$ they are increasing at a rate of $10^{5}$ per day. Find a differential equation to model this situation.  
9. The acceleration (i.e. the rate of change of velocity) of a moving object under a particular force is inversely proportional to the square root of its velocity. When the speed is $4\mathrm{m}\mathrm{s}^{- 1}$ the acceleration is $2\mathrm{m}\mathrm{s}^{- 2}$ . Find a differential equation to model this situation.  
10. The radius of a circular patch of oil is increasing at a rate inversely proportional to its area $A$ . Find an expression for $\frac{\mathrm{d}A}{\mathrm{d}t}$ .  
11. A poker, $80\mathrm{cm}$ long, has one end in a fire. The temperature of the poker decreases with respect to the distance from that end at a rate proportional to that distance. Halfway along the poker, the temperature is decreasing at a rate of $10^{\circ}\mathrm{C}\mathrm{cm}^{- 1}$ . Find a differential equation to model this situation.  
12. A spherical balloon is allowed to deflate. The rate at which air is leaving the balloon is proportional to the volume $V$ of air left in the balloon. When the radius of the balloon is $15\mathrm{cm}$ , air is leaving at a rate of $8\mathrm{cm}^3 \mathrm{s}^{- 1}$ . Find an expression for $\frac{\mathrm{d}V}{\mathrm{d}t}$ .  
13. A tank is shaped as a cuboid with a square base of side $10\mathrm{cm}$ . Water runs out through a hole in the base at a rate proportional to the square root of the height, $h$ cm, of water in the tank. At the same time, water is pumped into the tank at a constant rate of $2\mathrm{cm}^3 \mathrm{s}^{- 1}$ . Find an expression for $\frac{\mathrm{d}h}{\mathrm{d}t}$ .  

#### Hodder **Exercise 9B**  
1. Solve the following differential equations by integration.  
(i) $\frac{dy}{dx} = x^2$  
(ii) $\frac{dy}{dx} = \cos x$  
(iii) $\frac{dy}{dx} = \mathrm{e}^x$  
(iv) $\frac{dy}{dx} = \sqrt{x}$  
2. Find the general solutions of the following differential equations by separating the variables.  
(i) $\frac{dy}{dx} = xy^2$  
(ii) $\frac{dy}{dx} = \frac{x^2}{y}$  
(iii) $\frac{dy}{dx} = y$  
(iv) $\frac{dy}{dx} = \mathrm{e}^{x - y}$  
(v) $\frac{dy}{dx} = \frac{y}{x}$  
(vi) $\frac{dy}{dx} = x\sqrt{y}$  
(vii) $\frac{dy}{dx} = y^2\cos x$  
(viii) $\frac{dy}{dx} = \frac{x(y^2 + 1)}{y(x^2 + 1)}$  
(ix) $\frac{dy}{dx} = x\mathrm{e}^y$  
(x) $\frac{dy}{dx} = \frac{x\ln x}{y^2}$  

---
#### Hodder **Exercise 9C**  
1. Find the particular solution of each of the following differential equations.  
a) $\frac{dy}{dx} = x^2 -1\qquad y = 2\mathrm{~when~}x = 3$  
b) $\frac{dy}{dx} = x^2 y\qquad y = 1\mathrm{~when~}x = 0$  
c) $\frac{dy}{dx} = x\mathrm{e}^{-y}\qquad y = 0\mathrm{~when~}x = 0$  
d) $\frac{dy}{dx} = y^2\qquad y = 1\mathrm{~when~}x = 1$  
e) $\frac{dy}{dx} = x(y + 1)\quad y = 0\mathrm{~when~}x = 1$  
f) $\frac{dy}{dx} = y^2\sin x\quad y = 1\mathrm{~when~}x = 0$  
2. A cold liquid at temperature $\theta^{\circ}C$ ,where $\theta < 20$ ,is standing in a warm room.The temperature of the liquid obeys the differential equation $$\frac{\mathrm{d}\theta}{\mathrm{d}t} = 2(20 - \theta)$$  
where the time $t$ is measured in hours.  
(i) Find the general solution of this differential equation.  
(ii) Find the particular solution for which $\theta = 5$ when $t = 0$  
(iii) In this case, how long does the liquid take to reach a temperature of $18^{\circ}C$ ?  
3. A population of rabbits increases so that the number of rabbits $N$ (in hundreds), after $t$ years is modelled by the differential equation $$\frac{\mathrm{d}N}{\mathrm{d}t} = N.$$  
(i) Find the general solution for $N$ in terms of $t$ .  
(ii) Find the particular solution for which $N = 10$ when $t = 0$ .  
(iii) What will happen to the number of rabbits when $t$ becomes very large? Why is this not a realistic model for an actual population of rabbits?  
4. An object is moving so that its velocity $\nu \left(=\frac{\mathrm{d}s}{\mathrm{d}t}\right)$ is inversely proportional to its displacement $s$ from a fixed point. If its velocity is $1\mathrm{ms}^{- 1}$ when its displacement is $2\mathrm{m}$ , find a differential equation to model the situation. Find the general solution of your differential equation.  
5. Given that $y = 1$ when $x = 0$ , solve the differential equation $\frac{dy}{dx} = 4x(3y^2 + 10y + 3)$ , obtaining an expression for $y$ in terms of $x$ .  
Cambridge International AS & A Level Mathematics 9709 Paper 31 Q7 June 2015  
6. The temperature of a quantity of liquid at time $t$ is $\theta$ . The liquid is cooling in an atmosphere whose temperature is constant and equal to $A$ . The rate of decrease of $\theta$ is proportional to the temperature difference $(\theta - A)$ . Thus $\theta$ and $t$ satisfy the differential equation $\frac{\mathrm{d}\theta}{\mathrm{d}t} = - k(\theta - A)$ , where $k$ is a positive constant.  
(i) Find, in any form, the solution of this differential equation, given that $\theta = 4A$ when $t = 0$ .  
(ii) Given also that $\theta = 3A$ when $t = 1$ , show that $k = \ln \frac{3}{2}$ .  
(iii) Find $\theta$ in terms of $A$ when $t = 2$ , expressing your answer in its simplest form.  
Cambridge International AS & A Level Mathematics 9709 Paper 32 Q9 November 2009  
7. The variables $x$ and $t$ are related by the differential equation $\mathrm{e}^{2t}\frac{\mathrm{d}x}{\mathrm{d}t} = \cos^2 x$ , where $t \geq 0$ . When $t = 0$ , $x = 0$ .  
(i) Solve the differential equation, obtaining an expression for $x$ in terms of $t$ .  
(ii) State what happens to the value of $x$ when $t$ becomes very large.  
(iii) Explain why $x$ increases as $t$ increases.  
Cambridge International AS & A Level Mathematics 9709 Paper 32 Q7 June 2010  
8. An underground storage tank is being filled with liquid as shown in the diagram. Initially the tank is empty. At time $t$ hours after filling begins, the volume of liquid is $V\mathrm{m}^3$ and the depth of liquid is $h\mathrm{m}$ . It is given that $V = \frac{4}{3} h^3$ .  
[image]  
The liquid is poured in at a rate of $20\mathrm{m}^3$ per hour, but owing to leakage, liquid is lost at a rate proportional to $h^2$ . When $h = 1$ , $\frac{\mathrm{d}h}{\mathrm{d}t} = 4.95$ .  
(i) Show that $h$ satisfies the differential equation $$\frac{\mathrm{d}h}{\mathrm{d}t} = \frac{5}{h^2} -\frac{1}{20}.$$  
(ii) Verify that $\frac{20h^2}{100 - h^2} \equiv -20 + \frac{2000}{(10 - h)(10 + h)}$ .  
(iii) Hence solve the differential equation in part (i), obtaining an expression for $t$ in terms of $h$ .  
Cambridge International AS & A Level Mathematics 9709 Paper 3 Q8 November 2008  
9. Naturalists are managing a wildlife reserve to increase the number of plants of a rare species. The number of plants at time $t$ years is denoted by $N$ , where $N$ is treated as a continuous variable.  
(i) It is given that the rate of increase of $N$ with respect to $t$ is proportional to $(N - 150)$ . Write down a differential equation relating $N$ , $t$ and a constant of proportionality.  
(ii) Initially, when $t = 0$ , the number of plants was 650. It was noted that, at a time when there were 900 plants, the number of plants was increasing at a rate of 60 per year. Express $N$ in terms of $t$ .  
(iii) The naturalists had a target of increasing the number of plants from 650 to 2000 within 15 years.  
Will this target be met?  
Cambridge International AS & A Level Mathematics 9709 Paper 33 Q10 November 2015  
10. The number of birds of a certain species in a forested region is recorded over several years. At time $t$ years, the number of birds is $N$ , where $N$ is treated as a continuous variable. The variation in the number of birds is modelled by $$\frac{\mathrm{d}N}{\mathrm{d}t} = \frac{N(1800 - N)}{3600}.$$  
It is given that $N = 300$ when $t = 0$ .  
(i) Find an expression for $N$ in terms of $t$ .  
(ii) According to the model, how many birds will there be after a long time?  
Cambridge International AS & A Level Mathematics 9709 Paper 31 Q10 June 2011  
11. The variables $x$ and $\theta$ satisfy the differential equation $$2\cos^2\theta \frac{\mathrm{d}x}{\mathrm{d}\theta} = \sqrt{(2x + 1)},$$  
and $x = 0$ when $\theta = \frac{1}{4}\pi$ . Solve the differential equation and obtain an expression for $x$ in terms of $\theta$ .  
Cambridge International AS & A Level Mathematics 9709 Paper 33 Q5 June 2014  
12. The variables $x$ and $y$ are related by the differential equation $$\frac{dy}{dx} = \frac{1}{5} xy^{\frac{1}{2}}\sin \left(\frac{1}{3} x\right).$$  
(i) Find the general solution, giving $y$ in terms of $x$ .  
(ii) Given that $y = 100$ when $x = 0$ , find the value of $y$ when $x = 25$ .  
Cambridge International AS & A Level Mathematics 9709 Paper 33 Q8 November 2014  
13. A tank containing water is in the form of a cone with vertex C. The axis is vertical and the semi- vertical angle is $60^{\circ}$ , as shown in the diagram. At time $t = 0$ , the tank is full and the depth of water is $H$ . At this instant, a tap at C is opened and water begins to flow out. The volume of water in the tank decreases at a rate proportional to $\sqrt{h}$ , where $h$ is the depth of water at time $t$ . The tank becomes empty when $t = 60$ .  
[image]  
(i) Show that $h$ and $t$ satisfy a differential equation of the form $$\frac{\mathrm{d}h}{\mathrm{d}t} = -Ah^{-\frac{3}{2}},$$  
where $A$ is a positive constant.  
(ii) Solve the differential equation given in part (i) and obtain an expression for $t$ in terms of $h$ and $H$ .  
(iii) Find the time at which the depth reaches $\frac{1}{2} H$ .  
[The volume $V$ of a cone of vertical height $h$ and base radius $r$ is given by $V = \frac{1}{3}\pi r^2 h$ .]  
Cambridge International AS & A Level Mathematics 9709 Paper 31 Q10 November 2013  
  
