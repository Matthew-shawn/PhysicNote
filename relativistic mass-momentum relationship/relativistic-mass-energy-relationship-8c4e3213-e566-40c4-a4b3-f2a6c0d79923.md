### Relativistic mass-energy relationship
The main purpose of this article is to explore the following formular,


\begin{align} 
E &= mc^2 \label{0.1} \tag{0.1} \\ 
E^2 - p^2c^2 &= m_{0}^{2}c^4 \label{0.2} \tag{0.2} 
\end{align}

- The first equation is the mass-energy equation. 
- The second one is the relativistic momentum-mass equation.


#### Physical quantity

- relativistic mass

\begin{equation}
m = \frac{m_{0}}{\sqrt{1-(\frac{v}{c})^{2}}}=\gamma m_{0} \label{1}
\end{equation}

where $m_{0}$ indicate rest mass.

- relativistic momentum

\begin{equation}
\vec{p}=m \vec{v}=\gamma m_{0} \vec{v}= \frac{m_{0} \vec{v}}{\sqrt{1-(\frac{v}{c})^{2}}} \label{2}
\end{equation}

- force (theorem of momentum)

\begin{equation}
\begin{split}
F &= \frac{d\vec{p}}{dt}=\frac{d(m\vec{v})}{dt} \\
&=\vec{v}\frac{dm}{dt}+m\frac{d\vec{v}}{dt} \label{3}
\end{split}
\end{equation}

<font color = red> attention: </font>*relativistic mass varies with velocity*

#### Relativistic kinetic energy and mass-energy equation

In Newtonian mechanics,

- Translational kinetic energy

\begin{equation}
E_{k} = \frac{1}{2}mv^2 \label{4}
\end{equation}

- Rotational kinetic energy

\begin{equation}
E_{k} = \frac{1}{2}I\omega^{2} 
\end{equation}

In relativistic mechanics, We still use the work done on the particle to represent the increment of the particle's kinetic energy (using eq.\eqref{3})

\begin{equation}
\begin{split}
E_{k} &= \int^{v}_{0} \vec{F} \cdot d{\vec{r}} \\
&= \int^{v}_{0} \frac{d(m\vec{v})}{dt} \cdot d{\vec{r}}=\int^{v}_{0} {d(m\vec{v})} \cdot \vec{v} \\
&=\int^{v}_{0}m\vec{v} \cdot d{\vec{v}} + \vec{v} \cdot \vec{v}dm \\
&=\int^{v}_{0}mvdv+v^2dm.
\end{split}
\end{equation}

From eq.\eqref{1}, we have

\begin{equation}
\begin{split}
m^2(1-\frac{v^2}{c^2})&=m_{0}^{2}\\
\rightarrow m^2c^2-m^2v^2&=m_{0}^{2}c^2 \label{7}
\end{split}
\end{equation}

differentiate both sides of the eq.\eqref{7}, we can easily get

\begin{equation}
\begin{split}
2mdm(c^2-&v^2)-2m^{2}vdv=0 \\
\rightarrow c^2dm&=v^2dm+mvdv. \label{8}
\end{split}
\end{equation}

Look back to eq.\eqref{6}, we can substitute eq.\eqref{8} into it

\begin{equation}
\begin{split}
E_{k}&=\int_{m_{0}}^{m}c^2dm \\
&=(m-m_{0})c^2 \label{9},
\end{split}
\end{equation}

which means that when an object moves from rest to velocity $\vec{v}$, the energy it adds is the above eq.\eqref{9}. Then, we can easily simplify eq.\eqref{9} to

\begin{equation}
E = mc^2. \tag{0.1}
\end{equation}

Besides, we can get the speed of particle expressed by $E_{k}$ from eq.\eqref{9} and \eqref{1}

\begin{equation}
v^2=c^2[1-(1+\frac{E_{k}}{m_{0}c^2})^{-2}].
\end{equation}

It indicates that when the kinetic energy of a particle increases due to a force doing work on it, the velocity also increases. However, the velocity could not increase all the time. The upper limitation of the speed is $c$.

When $v \ll c$, we can obtain
\begin{equation}
\begin{split}
\frac{1}{\sqrt{1-\frac{v^2}{c^2}}} \approx 1+\frac{1}{2}\frac{v^2}{c^2}+ \ldots \approx 1+\frac{1}{2}\frac{v^2}{c^2}.
\end{split}
\end{equation}

Then, we take it into eq.\eqref{9}, we have
\begin{equation}
\begin{split}
E_{k}&=[(1+\frac{v^2}{c^2})-1]m_{0}c^2 \\
&=\frac{1}{2}m_{0}v^2 ,
\end{split}
\end{equation}

which turns back to the form of Newtonian mechanics
\begin{equation}
E_{k}=\frac{1}{2}mv^2 \tag{4}.
\end{equation}

#### Relativistic momentum-mass relation

From
\begin{cases}
E = m c^2 \\
\vec{p} = m \vec{v}
\end{cases}

we can get

\begin{equation}
\vec{v} = \frac{c^2}{E}\vec{p}.
\end{equation}

Concerning eq.\eqref{1} and mass-energy equation, we can obtain

\begin{equation}
\begin{split}
E = \gamma m_{0}& c^2 \\
\rightarrow E^2(1-\frac{v^2}{c^2})&=m_{0}^{2}c^4 \\
E^2(1-\frac{c^2 p^2}{E^2})&=m_{0}^{2}c^4. \\
\end{split}
\end{equation}

which is

\begin{equation}
E^2-p^2c^2=m_{0}^{2}c^4. \tag{0.2}
\end{equation}

Thus, we get the mass-momentum-energy equation. And that's how we define rest mass.  We can see it from a more intuitive way 

\begin{figure}[h]
\centering
\includegraphics[width=0.8\textwidth]{https://cdn.mathpix.com/snip/images/lq_U4nFSXmx-fTnSqSe8vIXdUkdkziRGCEAdqQMkOWE.original.fullsize.png}
\label{19}
\caption{Right triangle of mass-momentum relation}
\end{figure}

For a particle of kinetic energy $E_{k}$, we have

\begin{equation}
E_{k} = E - E_{0}. \label{15}
\end{equation}

As we can see from the figure above (concerning eq.\eqref{15}), 

\begin{equation}
\begin{split}
E^2=p^2c^2+m_{0}^{2}&c^4 \\
\rightarrow E_{k}^2+2E_{k}m_{0}c^2=&p^2c^2. \label{16}
\end{split}
\end{equation}

When $v\ll c$, which means $E_{k}\ll m_{0}c^2$, we can ignore $E_{k}^{2}$ in eq.\eqref{16}. Thus, we can get

\begin{equation}
E_{k}=\frac{p^2}{2m_{0}}.
\end{equation}

which turns back to Newtonian mechanics.
