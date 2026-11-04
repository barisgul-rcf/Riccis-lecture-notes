[[Vector Calculus]]
## Gradiant

The **gradient** of a scalar-valued function f(x,y,z) is the vector field
$$\begin{equation*}
\text{grad}\,f=\nabla f
= \frac{\partial f}{\partial x}\hat{\mathbf{i}}
+\frac{\partial f}{\partial y}\hat{\mathbf{j}}
+\frac{\partial f}{\partial z} \hat{\mathbf{k}}
\end{equation*}$$
The input $f\text{,}$ for the gradient is a scalar valued-function, while the output $\nabla f\text{,}$ is a vector-valued function. It measures the rate and direction of change in a scalar field. Analogous to scalar multiplication.
## Divergence

The **divergence** of a vector field $\mathbf{F}(x,y,z)$  is the scalar-valued function
$$\begin{equation*}
\text{div}\,\mathbf{F}=\nabla\cdot\mathbf{F}
= \frac{\partial F_1}{\partial x}
+\frac{\partial F_2}{\partial y}
+\frac{\partial F_3}{\partial z}
\end{equation*}$$
The input $\mathbf{F}$ for the divergence is a vector-valued function and the output $\nabla\times\mathbf{F}\text{,}$ is a scalar-valued function. It measures the scalar of a source or sink at a given point in a vector field. Analogous to dot product.

## Curl

The **curl** of a vector field $\mathbf{F}(x,y,z)$ is the vector field
$$\begin{equation*}
\text{curl}\,\mathbf{F}= \nabla\times\mathbf{F}
= \Big(\frac{\partial F_3}{\partial y} -\frac{\partial F_2}{\partial z}\Big)\hat{\mathbf{i}}
-\Big(\frac{\partial F_3}{\partial x} -\frac{\partial F_1}{\partial z}\Big)\hat{\mathbf{j}}
+\Big(\frac{\partial F_2}{\partial x} -\frac{\partial F_1}{\partial y}\Big)\hat{\mathbf{k}}
\end{equation*}$$
The input $\mathbf{F}$ for the curl is a vector-valued function, and the output $\nabla\times\mathbf{F}$ is again a vector-valued function. It measures the tendency to rotate about a point in a vector field in $\mathbb{R^3}$. Analogous to cross product.

