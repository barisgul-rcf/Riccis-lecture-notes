[[Differential Equations]]

There is no general formula for the solutions of the most general form of first order differential equations:$$\begin{equation}\frac{{dy}}{{dt}} = f\left( {y,t} \right)\end{equation}$$
## Linear Equations
$$\begin{equation}\frac{{dy}}{{dt}} + p\left( t \right)y = g\left( t \right)\end{equation}$$
where both $p(t)$ and $g(t)$ are continuous functions. Multiply the equation with the integrating factor $\mu \left( t \right)$. This will give: $$\begin{equation}\mu \left( t \right)\frac{{dy}}{{dt}} + \mu \left( t \right)p\left( t \right)y = \mu \left( t \right)g\left( t \right)\end{equation}$$
Assume $\mu \left( t \right)$ satisfies the equation: $$\begin{equation}\mu \left( t \right)p\left( t \right) = \mu '\left( t \right)
\end{equation}$$
Substitute this to the equation above: $$\begin{equation}\mu \left( t \right)\frac{{dy}}{{dt}} + \mu '\left( t \right)y = \mu \left( t \right)g\left( t \right)\end{equation}$$
The LHS of the equation became the product rule, so: $$\begin{equation}{\left( {\mu \left( t \right)y\left( t \right)} \right)^\prime } = \mu \left( t \right)g\left( t \right)\end{equation}$$
Integrate both sides: $$\begin{equation}\mu \left( t \right)y\left( t \right) + c = \int{{\mu \left( t \right)g\left( t \right)\,dt}}\end{equation}$$
Solve for $y(t)$: $$\begin{equation}y\left( t \right) = \frac{{\int{{\mu \left( t \right)g\left( t \right)\,dt}} + c}}{{\mu \left( t \right)}}\end{equation}$$
By playing around the third equation we find that: $$\begin{equation}\mu \left( t \right) = \,{{\bf{e}}^{\int{{p\left( t \right)\,dt}}}}\end{equation}$$
Solutions to first order differential equations will have a single unknown constant in them and so we will need exactly one initial condition to find the value of that constant and hence find the solution that we were after. The initial condition for first order differential equations will be of the form: $$y\left( {{t_0}} \right) = {y_0}$$
## Nonlinear First Order Differential Equations

### Separable Equations
$$\begin{equation}N\left( y \right)\frac{{dy}}{{dx}} = M\left( x \right)\end{equation}$$
In order for a differential equation to be separable all the $y$ in the differential equation must be multiplied by the derivative and all the $x$ in the differential equation must be on the other side. Integrate both sides with respect to $x$ to get: $$\int{{N\left( y \right)\frac{{dy}}{{dx}}\,dx}} = \int{{M\left( x \right)\,dx}}$$
Use the following substitution: $$u = y\left( x \right)\hspace{0.25in}du = y'\left( x \right)\,dx = \frac{{dy}}{{dx}}\,dx$$$$\begin{equation}\int{{N\left( u \right)\,du}} = \int{{M\left( x \right)\,dx}}\end{equation}$$
If you are lucky do the integration and then back substitute for the u. If one or both integrals turn out to be indecipherable then forget this method.
##### Not so rigorous method (mathematicians must close their eyes):
Separate the derivative:$$N\left( y \right)dy = M\left( x \right)dx$$
Now we integrate both sides: $$\begin{equation}\int{{N\left( y \right)dy}} = \int{{M\left( x \right)dx}}\end{equation}$$

### Exact Equations
$$\begin{equation} M\left( {x,y} \right) + N\left( {x,y} \right)\frac{{dy}}{{dx}} = 0\end{equation}$$
**It is important that it must be in this form!** There must be an “= 0” on one side and the sign separating the two terms must be a “+”. Now imagine a function that looks like $\Psi\left(x,y\right)$ where: $${\Psi _x} = M\left( {x,y} \right)\hspace{0.25in}\,\,\,\,\,\,\,\,\,\,\,\,{{and }}\,\,\hspace{0.25in}{\Psi _y} = N\left( {x,y} \right)$$
If this function exists then our equation is **exact**. We can write the differential equation as: $$\begin{equation} {\Psi _x} + {\Psi _y}\frac{{dy}}{{dx}} = 0\end{equation}$$
Using the chain rule: $$\frac{d}{{dx}}\left( {\Psi \left( {x,y\left( x \right)} \right)} \right) = 0$$
Then the implicit solution is: $$\begin{equation} \Psi \left( {x,y} \right) = c\end{equation}$$
##### Exactness Test:
Assume that the differential equation is exact. Somewhere out there is a continuous function $\Psi\left(x,y\right)$ that satisfies: 
$$\begin{align*}{\Psi _x} & = M\\ {\Psi _y} & = N\end{align*}$$
$$\begin{align*}{\Psi _{x\,y}} & = {\left( {{\Psi _x}} \right)_y} = {\left( M \right)_y} = {M_y}\\ {\Psi _{y\,x}} & = {\left( {{\Psi _y}} \right)_x} = {\left( N \right)_x} = {N_x}\end{align*}$$
Therefore if a differential equation is exact and $\Psi\left(x,y\right)$ and its first order derivatives meets the continuity conditions then we have: $$\begin{equation} {M_y} = {N_x}\end{equation}$$
If this is not true then the equation cannot be exact. But it does not guarantee exactness since we need to assume $\Psi\left(x,y\right)$ meets continuity conditions.

### Bernoulli Differential Equations
$$y' + p\left( x \right)y = q\left( x \right){y^n}$$
where $p(x)$ and $q(x)$ are continuous functions. If $n = 0$ or $n=1$ then the equation is a [[First Order Differential Equations#Linear Equations|linear equation]]. If not, divide the differential equation by $y^n$: $${y^{ - n}}\,y' + p\left( x \right){y^{1 - n}} = q\left( x \right)$$
Now do this substitution, $v = {y^{1 - n}}$ and determine what $y'$ is in terms of our substitution by differentiating both sides of the substitution with respect to $x$: $$v' = \left( {1 - n} \right){y^{ - n}}y'$$
Now plug this to the equation with the original substitution to obtain: $$\frac{1}{{1 - n}}v' + p\left( x \right)v = q\left( x \right)$$
The equation has been [[#Linear Equations|linearised]]. Solve for $v$ and plug it back into the substitution and solve for $y$.

### Substitutions

First substitution (homogenous differential equations):$$y' = F\left( {\frac{y}{x}} \right)$$
Use the substitution $v\left( x \right) = \frac{y}{x}$ and take the derivative: $$y' = v + xv'$$
Then: $$\begin{align*}v + xv' & = F\left( v \right)\\ x v' & = F\left( v \right) - v\hspace{0.25in} \Rightarrow \hspace{0.25in}\frac{{dv}}{{F\left( v \right) - v}} = \frac{{dx}}{x}\end{align*}$$
which is a [[#Separable Equations|separable differential equation]].

Second substitution: $$y' = G\left( {ax + by} \right)$$
Use the substitution $v = ax + by\hspace{0.25in} \Rightarrow \hspace{0.25in}v' = a + by'$ and plug this into the equation: $$\begin{align*}\frac{1}{b}\left( {v' - a} \right) & = G\left( v \right)\\ v' & = a + bG\left( v \right)\hspace{0.25in} \Rightarrow \hspace{0.25in}\frac{{dv}}{{a + bG\left( v \right)}} = dx\end{align*}$$
### Autonomous Differential Equations (Time Invariant Systems If the Independent Variable is Time)
$$\frac{{dy}}{{dt}} = f\left( y \right)$$
The only place that the independent variable ($t$) appears is in the derivative. Values of $y$ where the rate of changi is zero ($f(y) = 0$) are called **equilibrium solutions (critical points)**. At these points, the system is constant over time. ($y(t) = c$)

An autonomous differential equation is [[#Separable Equations|separable]] and that a solution can be found by integrating $$\int \dfrac{dy}{f(y)} = t + C$$ This integral is often difficult or impossible to solve, so look at [[Differential Equations#Direction Fields|direction fields]] to investigate the solution. If $𝑓⁡(𝑦_0) = 0$ for some value $y = y_0$ then this will also be a solution to the differential equation. 

#### Stability of Equilibria

 1. **Stable (Sink / Attractor):** Solutions near the equilibrium move _toward_ it as time goes on.
2. **Unstable (Source / Repeller):** Solutions near the equilibrium move _away_ from it.
3. **Semi-stable:** Solutions move toward it from one side and away from it from the other. 

To determine if an equilibrium point is stable or unstable, take the derivative of the rate of change function with respect to $y$ and evaluate at $y = c$.

If $f'(c) < 0$: The point is **asymptotically stable**. (or sink)

If  $f'(c) > 0$: The point is **unstable**. (or source)

If $f'(c) = 0$: Check the signs of $f(y)$ on both signs of $c$. If it has the same signs on both sides then it it **semi-stable**.

A stable equilibrium point simply ensures that nearby solutions stay within a bounded distance over time, an asymptotically stable equilibrium point goes further by requiring those solutions to eventually converge directly to the equilibrium state as time approaches infinity.

### Euler's Method
$$\begin{equation}\frac{{dy}}{{dt}} = f\left( {t,y} \right)\hspace{0.25in}y\left( {{t_0}} \right) = {y_0}\end{equation}$$
$${y_{n + 1}} = {y_n} + f\left( {{t_n},{y_n}} \right) \cdot \left( {{t_{n + 1}} - {t_n}} \right)$$
Define ${f_n} = f\left( {{t_n},{y_n}} \right)$:  $$\begin{equation}{y_{n + 1}} = {y_n} + {f_n} \cdot \left( {{t_{n + 1}} - {t_n}} \right)\end{equation}$$
If we assume the step sizes between the points $t_0, t_1, t_2, ...$ are of a uniform size of $h$: $${t_{n + 1}} - {t_n} = h$$
Then the next approximation becomes: $$\begin{equation}{y_{n + 1}} = {y_n} + h\,{f_n}\end{equation}$$
