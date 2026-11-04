[[Calculus]]

A differential equation is any equation that relates one or more unknown functions and their derivatives.
$$\begin{equation}ay'' + by' + cy = g\left( t \right)\end{equation}$$
### Order

The **order** of a differential equation is the largest derivative present in the differential equation.
$$\begin{equation}{y^{\left( 5 \right)}} + 10y''' - 4y' + 2y = \sin \left( t \right)\end{equation}$$
### Ordinary and Partial Differential Equations

A differential equation is called an **ordinary differential equation**, or **ode,** if it has an unknown function of one real or complex variable, its derivatives and some given functions of that variable in it. Likewise, a differential equation is called a **partial differential equation** if it has unknown multivariable functions and their partial derivatives in it and it is abbreviated by **pde**.
$$\begin{equation}\frac{{{\partial ^3}u}}{{{\partial}x^2\partial t}} = 1 + \frac{{\partial u}}{{\partial y}}\end{equation}$$
### Linear Differential Equations

A **linear differential equation** is any differential equation that can be written as:
$$\begin{equation} {a_n}\left( t \right){y^{\left( n \right)}}\left( t \right) + {a_{n - 1}}\left( t \right){y^{\left( {n - 1} \right)}}\left( t \right) +  \cdots  + {a_1}\left( t \right)y'\left( t \right) + {a_0}\left( t \right)y\left( t \right) = g\left( t \right)\end{equation}$$
Functions that cannot be written in the form above are called **non-linear differential equations**

To become linear, a differential equation must satisfy three strick rules:
1. Neither the function or its derivatives occur to any power other than the first power,
2. There are no products of the function, $y(t)$, and its derivatives,
3. Neither the function or its derivatives are inside another function.

	The coefficients $a_0(t),...,a_n(t)$ and $g(t)$ can be zero or non-zero, constant or non-constant, linear or non-linear functions. They do not affect the linearity of the equation.

#### Homogeneous linear equations

A linear differential equation is **homogeneous** if each term in the equation includes either the dependent variable or one of its derivatives. If this is not the case, so that there is a term that does not include either the dependent variable itself or a derivative of it, the equation is **inhomogeneous** or **heterogeneous**.

### Solutions

**Pay close attention to the intervals!!!**

A **solution** to a differential equation on an interval  $\alpha <t < \beta$ is any function $y(t)$ which satisfies the differential equation in question on the interval $\alpha <t < \beta$

### Initial Conditions

Initial conditions are a set of conditions on the solution that we declare as important. They are often abbreviated as **i.c.** and are in the form of:
$$y\left( {{t_0}} \right) = {y_0}\hspace{0.25in}{\mbox{and/or  }}{y^{\left( k \right)}}\left( {{t_0}} \right) = {y_k}$$
Solutions to “good enough” differential equations are unique and only one solution will meet the given initial conditions. Used for determining the constant of the differential equation. If the independent variable corresponds to time, this information takes the form of initial conditions.
Ode and its initial conditions form **the initial value problem (IVP)**

The **interval of validity** for an IVP is the largest possible interval on which the solution is valid and contains $t_0$.
### Boundary Conditions

For the case of a spatial independent variable we have **boundary conditions**. They are often specified at different values of the independent variable. Ode and boundary conditions form the **boundary value problem**.

A **boundary value problem** has conditions specified at the extremes ("boundaries") of the independent variable in the equation whereas an **initial value problem** has all of the conditions specified at the same value of the independent variable.

### General vs Actual Solution

If the solution is the most general form that the solution can take and do not care about the initial conditions, then it is a **general solution**.

If the solution takes the initial conditions into account while satisfying the differential equation, then it is an **actual solution**.

