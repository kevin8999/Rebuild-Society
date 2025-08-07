---
aliases:
  - Trigonometry
---


# 4 - Precalculus
Precalculus gives you all the prerequisite knowledge needed to understand calculus, a mathematical field dealing with the rate of change and accumulation of quantities.

Most of calculus's applications are in science, engineering, economics, and computer science. They will become very important for reinventing very advanced technology.

The precalculus textbook is called **Precalculus 2e**. If you are accessing this repository digitally, they are stored as:

- [Precalculus 2e [part 1]](../../Media/Mathematics/Precalculus%202e%20(part%201).pdf)
- [Precalculus 2e [part 2]](../../Media/Mathematics/Precalculus%202e%20(part%202).pdf)

After precalculus is [5 - Calculus](5%20-%20Calculus.md).

## Trigonometry Addendum
This is an addendum to the trigonometric section of precalculus. Use this section to aid your learning in trigonometry.

In the modern world, most trigonometric values are calculated automatically using a calculator. However, in a post-modern society, we do not know if you have access to calculators.

Calculating the sine or cosine of an angle without using a calculator is pretty difficult. That's why a [Trigonometric Identities Table](Media/Trigonometric%20Identities%20Table.pdf) was added to ensure that you can apply trigonometric identities with ease.

Some values in the table are marked "DNE". Please note that when we say 'DNE' in trigonometry, it means that a specific angle does not have a defined value for the corresponding trigonometric function. For instance, $\csc(0 \degree)$ is marked as DNE because the cosecant of 0° does not have a defined value.

For commonly used angles, use the unit circle[^circle] given below:

[^circle]: "Unit circle angles color.svg" by Gustavb on Wikipedia. License: Public Domain

![Image of a Unit Circle](Media/Unit%20Circle%20by%20Gustavb.png)

The unit circle can also be found on page 587 (or, page 597 for the digital version) of [Precalculus 2e](../../Media/Mathematics/Precalculus%202e.pdf).

Note that:
- All measurements with $\pi$ are radians.
- All measurements with a number and degree symbol (such as $30\degree$) are measured in degrees.
- Coordinates are measured as $(\sin(r), \cos(r))$ where $r$ is the angle measure in radians. For example, the measurement at $\pi / 3$ radians states that $\sin(\pi /3) = 1 / 2$ and $\cos(\pi / 3) = \sqrt{3} / 2$.

For tangent, use this table:

| Angle (degrees) | Angle (radians) | Tangent (tan)  |
| :-------------: | :-------------: | :------------: |
|   $0 \degree$   |       $0$       |      $0$       |
|  $30 \degree$   |    $\pi / 6$    | $\sqrt{3} / 3$ |
|  $45 \degree$   |    $\pi / 4$    |      $1$       |
|  $60 \degree$   |    $\pi / 6$    |   $\sqrt{3}$   |
|  $90 \degree$   |    $\pi / 2$    |   Undefined    |

Remember that

$$\tan \theta = \frac{\sin\theta}{\cos\theta}$$

where $\theta$ is the measure of the angle.

### Estimating Trigonometric Functions for Precise Angles
If you need more precision (say to the closest tenth of a degree), you can use something called a "Taylor series". Taylor series approximate functions using polynomials. In this case, Taylor series allow us to approximate $\sin$ and $\cos$ without having to use a calculator. The more terms you use for a Taylor series, the more accurate the approximation becomes.

The trigonometric functions $\sin$ and $\cos$ are estimated using the following Taylor series:

$$\begin{align*}
\sin(x) &= x - \frac{x^{3}}{3!} + \frac{x^{5}}{5!} - \frac{x^{7}}{7!} + \frac{x^{9}}{9!} - ... + \frac{(-1)^{n}\cdot x^{2n+1}}{(2n+1)!} \\
\cos(x) &= 1 - \frac{x^{2}}{2!} + \frac{x^{4}}{4!} - \frac{x^{6}}{6!} + \frac{x^{8}}{8!} - ... + \frac{(-1)^{n}\cdot x^{2n}}{(2n)!}
\end{align*}$$
It's important to note that $x$ is measured in radians. If you have any measurements in degrees, please convert them to radians by multiplying by $\pi / 180 \degree$. 

Approximations for other trigonometric and polynomial functions can be found on page 585 (page 593 for the digital version) of [Calculus Volume 2](../../Media/Mathematics/Calculus%20Volume%202.pdf).

