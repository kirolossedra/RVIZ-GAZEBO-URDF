# First: Creating Inertias

### 1. **Inertia Matrix for a Sphere**
For a solid sphere of mass \(m\) and radius \(r\), the inertia matrix is:

$$
\mathbf{I} = \frac{2}{5} m r^2 \begin{bmatrix}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{bmatrix}
$$

### 2. **Inertia Matrix for a Box**
For a rectangular box of mass \(m\) with dimensions \(a \times b \times c\), the inertia matrix is:

$$
\mathbf{I} = \frac{m}{12} \begin{bmatrix}
b^2 + c^2 & 0 & 0 \\
0 & a^2 + c^2 & 0 \\
0 & 0 & a^2 + b^2
\end{bmatrix}
$$

### 3. **Inertia Matrix for a Cylinder**
For a solid cylinder of mass \(m\), radius \(r\), and height \(h\) with its axis along the \(z\)-axis, the inertia matrix is:

$$
\mathbf{I} = \frac{m}{12} \begin{bmatrix}
3r^2 + h^2 & 0 & 0 \\
0 & 3r^2 + h^2 & 0 \\
0 & 0 & 6r^2
\end{bmatrix}
$$

These equations represent the inertia matrices for a solid sphere, rectangular box, and solid cylinder, respectively, in their standard forms.


| Equation | Description |
|----------|-------------|
| $$E = mc^2$$  | Energy-mass equivalence |
| $$a^2 + b^2 = c^2$$ | Pythagorean theorem |



You're right! Here’s the table with LaTeX formatting for the variables:

| Shape            | Inertia Matrix                                                                                  | Variables                                           |
|------------------|-------------------------------------------------------------------------------------------------|-----------------------------------------------------|
| **Solid Sphere** | $${\begin{bmatrix} 1 & 0 & 0 \\ 0 & 1 & 0 \\ 0 & 0 & 1 \end{bmatrix}\}$$        | \(m\): Mass of the sphere, \(r\): Radius of the sphere |
| **Rectangular Box** | \(\frac{m}{12} \begin{bmatrix} b^2 + c^2 & 0 & 0 \\ 0 & a^2 + c^2 & 0 \\ 0 & 0 & a^2 + b^2 \end{bmatrix}\) | \(m\): Mass of the box, \(a\): Length along \(x\)-axis, \(b\): Width along \(y\)-axis, \(c\): Height along \(z\)-axis |
| **Solid Cylinder** | \(\frac{m}{12} \begin{bmatrix} 3r^2 + h^2 & 0 & 0 \\ 0 & 3r^2 + h^2 & 0 \\ 0 & 0 & 6r^2 \end{bmatrix}\)   | \(m\): Mass of the cylinder, \(r\): Radius of the base, \(h\): Height of the cylinder |

