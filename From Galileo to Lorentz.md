# From Galileo to Lorentz

In this article, I will mainly discuss the development of space transformation, which is written as "From Galileo to Lorentz". The latter one, Lorentz transformation will be studied in a more detailed way.

## Galileo transformation

In a three-dimension space, a particle can be express as $(x_1, x_2, x_3)$ when the time is $t$ in a specific frame of reference $K$. In another frame of reference $K^{\prime}$ which is moving at the speed of $v$ along the $x_{1}$ direction relative to $K$, the coordinate of the particle is $(x_{1^{\prime}}, x_{2^{\prime}}, x_{3^{\prime}})$ and its time is $t^{\prime}$. According to preliminary concept of time and space, we should have the following relation
$$
x_{1^{\prime}} = x_{1}-vt \ \ \ \ 
x_{2^{\prime}} = x_{2} \ \ \ \
x_{3^{\prime}} = x_{3} \\
t^{\prime} = t
$$
 which is also called as **Galileo transformation**.

In Galileo transformation, the change of particle's speed can be written as
$$
\frac{dx_{1^{\prime}}}{dt^{\prime}} = \frac{dx_{1}}{dt} - v \ \ \ 
\frac{dx_{2^{\prime}}}{dt^{\prime}} = \frac{dx_{2}}{dt} \ \ \ 
\frac{dx_{3^{\prime}}}{dt^{\prime}} = \frac{dx_{3}}{dt}
$$
while its acceleration is the same
$$
\frac{d^{2}x_{i^{\prime}}}{dt^{\prime2}} = \frac{d^{2}x_{i}}{dt^{2}} \ \ \ (i=1,2,3)
$$
In Newton's second law
$$
F_{i} = m\frac{d^{2}x_{i}}{dt^{2}}  \ \ \ (i = 1, 2, 3)
$$
it only contains acceleration but no velocity. Thus, in Gelileo transformation, the form of Newton's law is invariant.

## Minkowski space

In Minkowski space, we have gauge tensor
$$
\begin{equation}
    g_{\alpha\beta} = g^{\alpha\beta} =
    \begin{bmatrix}
    1 & & & \\
    & -1 & & \\
    & & -1 & \\
    & & & -1
    \end{bmatrix}
\end{equation}
$$
or
$$
\begin{equation}
    g_{\alpha\beta} = g^{\alpha\beta} =
    \begin{bmatrix}
    1 & & & \\
    & 1 & & \\
    & & 1 & \\
    & & & -1
    \end{bmatrix}
\end{equation}
$$
which is totally equivalent to each other.

## Lorentz transformation

The main difference between pseudo-Euclidean space (like Minkowski space) and Euclidean space is that the dot product of vector in Minkowski space has subtracted terms due to its specific gauge tensor. 

Let's get the coordinate transformation matrix in Minkowski space. (Only consider 1+1 dimension Minkowski space for simplicity) The vectors in this space can be written as 
$$
\left\{
        \begin{array}{**lr**}
        \vec{x}&=&x^{0}\vec{e_{0}}+x^{1}\vec{e_{1}}  \\
        \vec{y}&=&y^{0}\vec{e_{0}}+y^{1}\vec{e_{1}}  \\
        \end{array}

\right.
$$
the dot product of vector is
$$
\vec{x} \cdot \vec{y} = x^{0}y^{0}-x^{1}y^{1}
$$
As the definition of $g_{\alpha\beta}$ , we have
$$
\left\{
        \begin{array}{**lr**}
        \vec{e_{1}} \cdot \vec{e_{0}}&=&0  \\
        \vec{e_{0}} \cdot \vec{e_{0}}&=&1  \\
        \vec{e_{1}} \cdot \vec{e_{1}}&=&-1
        \end{array}

\right.
$$
Now, we turn it into a new coordinate $\vec{e}_{1^{\prime}},\vec{e}_{0^{\prime}}$
$$
\left\{
        \begin{array}{**lr**}
        \vec{e}_{0^{\prime}} &=& A^{0}_{0^{\prime}} \vec{e}_{0} + A^{1}_{0^{\prime}} \vec{e}_{1}  \\
        \vec{e}_{1^{\prime}} &=& A^{0}_{1^{\prime}} \vec{e}_{0} + A^{1}_{1^{\prime}} \vec{e}_{1}  \\
        \end{array}

\right.
$$
To make sure the form of dot product invariant, we must have
$$
\left\{
        \begin{array}{**lr**}
        \vec{e}_{1^{\prime}} \cdot \vec{e}_{0^{\prime}}&=&0  \\
        \vec{e}_{0^{\prime}} \cdot \vec{e}_{0^{\prime}}&=&1  \\
        \vec{e}_{1^{\prime}} \cdot \vec{e}_{1^{\prime}}&=&-1
        \end{array}

\right.
$$
Substitute the equation (10) into equation (11) and considering equation (9), we have
$$
A^{0}_{1^{\prime}}A^{0}_{0^{\prime}}-A^{1}_{1^{\prime}}A^{1}_{0^{\prime}}= 0 & \\
(A^{0}_{0^{\prime}})^{2}-(A^{1}_{0^{\prime}})^{2} = 1 & \\
(A^{0}_{1^{\prime}})^{2}-(A^{1}_{1^{\prime}})^{2} = -1 &
$$
Let $A^{0}_{0^{\prime}} = a,\ A^{1}_{1^{\prime}} = b$, we have
$$
&\frac{A^{1}_{0^{\prime}}}{a} = \frac{A^{0}_{1^{\prime}}}{b} = \beta \\
&\Rightarrow A^{1}_{0^{\prime}} = a\beta \qquad A^{0}_{1^{\prime}} = b\beta \\
&\Rightarrow a^{2}(1-\beta^{2}) = 1 \qquad b^{2}(1-\beta^{2})
$$
Thus, we have 
$$
a = \frac{1}{\pm \sqrt{1-\beta^2}} \qquad b = \frac{1}{\pm \sqrt{1-\beta^2}} \\
\Rightarrow A^{0}_{0^{\prime}} = \frac{1}{\pm \sqrt{1-\beta^2}} \qquad A^{1}_{0^{\prime}} = \frac{\beta}{\pm \sqrt{1-\beta^2}} \\
A^{0}_{1^{\prime}} = \frac{\beta}{\pm \sqrt{1-\beta^2}} \qquad A^{1}_{1^{\prime}} = \frac{1}{\pm \sqrt{1-\beta^2}}
$$
Then, we can get
$$
\left\{
        \begin{array}{**lr**}
        \vec{e}_{0^{\prime}} &=& \frac{\vec{e}_{0}+\beta \vec{e}_{1}}{\pm \sqrt{1-\beta^2}}  \\
        \vec{e}_{1^{\prime}} &=& \frac{\beta \vec{e}_{0}+ \vec{e}_{1}}{\pm \sqrt{1-\beta^2}}  \\
        \end{array}

\right.
$$
In the first equation, minus sign means the time axis is reverse, that is time reverse; In the second equation, minus sign means space reverse.

Not concerning the time reverse and space reverse, we should only consider the plus sign, thus we have
$$
\left\{
        \begin{array}{**lr**}
        \vec{e}_{0^{\prime}} &=& \frac{\vec{e}_{0}+\beta \vec{e}_{1}}{ \sqrt{1-\beta^2}}  \\
        \vec{e}_{1^{\prime}} &=& \frac{\beta \vec{e}_{0}+ \vec{e}_{1}}{ \sqrt{1-\beta^2}}  \\
        \end{array}

\right.
$$
This is the space-time transformation equation under the demand of the invariance of light velocity. The covariant component of the 2-dimension vector $\bold{x}$ has the same transformation form of coordinate basis vector.
$$
\left\{
        \begin{array}{**lr**}
       {x}_{1^{\prime}} &=& \frac{{x}_{1}+\beta {x}_{0}}{ \sqrt{1-\beta^2}}  \\
       {x}_{0^{\prime}} &=& \frac{{x}_{0}+ \beta {x}_{1}}{ \sqrt{1-\beta^2}}  \\
        \end{array}

\right.
$$
Considering the special gauge vector, we can easily have the transformation of  x's covariant component and the contravariant one.
$$
x_{\alpha} = g_{\alpha \beta}x^{\beta}
$$
Therefore, only the time component keep the original form, while the other space component reverse.
$$
\left\{
        \begin{array}{**lr**}
       {x}^{1^{\prime}} &=& \frac{{x}^{1}-\beta {x}^{0}}{ \sqrt{1-\beta^2}}  \\
        {x}^{0^{\prime}} &=& \frac{{x}^{0}- \beta {x}^{1}}{ \sqrt{1-\beta^2}}  \\
        \end{array}

\right.
$$
Then, we substitute the following equation into eq.(19).
$$
x^{0}=ct \quad \quad x^{0^{\prime}}=ct^{\prime}
$$
and let $x^{1}=x, x^{1^{\prime}}=x^{\prime}$, we have
$$
\left\{
        \begin{array}{**lr**}
        {x}^{\prime} &=& \frac{{x}-\beta ct}{ \sqrt{1-\beta^2}}  \\
        t^{\prime} &=& \frac{t- \frac{\beta}{c} {x}}{ \sqrt{1-\beta^2}}  \\
        \end{array}

\right.
$$
Here we get the $Lorentz \ \ Transformation$. It corresponds to the rotation of $x$ and $ct$ axis in $(x,\ ct)$  plane.

In $3+1$ dimension, if $K^{\prime}$ coordinate system moves in the direction of $x$ axis relative to $K$ coordinate system, we have
$$
\left\{
        \begin{array}{**lr**}
        {x}^{\prime} = \frac{{x}-\beta ct}{ \sqrt{1-\beta^2}}  \\
        t^{\prime}   = \frac{t- \frac{\beta}{c} {x}}{ \sqrt{1-\beta^2}}  \\
        y^{\prime}   = y \\
        z^{\prime}   = z
        \end{array}

\right.
$$


In order to clarify the meaning of $\beta$ , let's consider an object fixed on $x^{\prime} = 0$ in $K^{\prime}$ coordinate system. From the first equation of eq.(21) , we have that when $t = 0$, $x = 0$; when time comes to t, we have the following relation
$$
x-\beta ct = 0
$$
Therefore, the velocity of the object is
$$
v = \frac{x}{t}=\beta c
$$
As the object is fixed on the $K^{\prime}$ coordinate system, $v$ is the speed of $K^{\prime}$ relative to $K$.  Further, we get
$$
\beta = \frac{v}{c}
$$
Obviously, when $\beta \ll 1 (v \ll c)$, $Lorentz \ \ Transformation$  is back to $Galileo  \ \ Transformation$. In $Lorentz \ \ Transformation$, the form of Maxwell equation is invariant.

