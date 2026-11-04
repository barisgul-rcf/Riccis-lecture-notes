[[Differential Equations]]

There is no general formula for the solutions of the most general form of first order differential equations:$$\begin{equation}\frac{{dy}}{{dt}} = f\left( {y,t} \right) \label{eq:eq1} \end{equation}$$
### Linear Equations

$$\begin{equation}\frac{{dy}}{{dt}} + p\left( t \right)y = g\left( t \right)\end{equation}$$
where both $p(t)$ and $g(t)$ are continuous functions. Multiply the equation with the integrating factor $\mu \left( t \right)$. This will give: $$\begin{equation}\mu \left( t \right)\frac{{dy}}{{dt}} + \mu \left( t \right)p\left( t \right)y = \mu \left( t \right)g\left( t \right)\end{equation}$$
Assume $\mu \left( t \right)$ satisfies the equation: $$\begin{equation}\mu \left( t \right)p\left( t \right) = \mu '\left( t \right)
\end{equation}$$
Substitute this to the equation above: $$\begin{equation}\mu \left( t \right)\frac{{dy}}{{dt}} + \mu '\left( t \right)y = \mu \left( t \right)g\left( t \right)\end{equation}$$
The LHS of the equation became the product rule, so: $$\begin{equation}{\left( {\mu \left( t \right)y\left( t \right)} \right)^\prime } = \mu \left( t \right)g\left( t \right)\end{equation}$$
Integrate both sides: $$\begin{equation}\mu \left( t \right)y\left( t \right) + c = \int{{\mu \left( t \right)g\left( t \right)\,dt}}\end{equation}$$
Solve for $y(t)$: $$\begin{equation}y\left( t \right) = \frac{{\int{{\mu \left( t \right)g\left( t \right)\,dt}} + c}}{{\mu \left( t \right)}}\end{equation}$$
By playing around the third equation we find that: $$\begin{equation}\mu \left( t \right) = \,{{\bf{e}}^{\int{{p\left( t \right)\,dt}}}}\end{equation}$$





