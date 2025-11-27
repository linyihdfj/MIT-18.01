Problem:
Find two value of $\theta$ so that 
$$
\frac{d}{d\theta}[\cos^2 (\theta^4)] = 0
$$

Solution:
We need to rewrite this equation to see how the three functions composes,
$$
\cos^2(\theta^4) = [\cos(\theta^4)]^2
$$
Then we can use chain rule step by step:
$$
\begin{aligned}
y &= x^2 \\
x &= \cos w \\
w &= \theta^4
\end{aligned}
$$
So,
$$
\begin{aligned}
\frac{dy}{d\theta} &= \frac{dy}{dx} \cdot \frac{dx}{dw} \cdot \frac{dw}{d\theta}\\
&= (2x) \cdot (-\sin w) \cdot (4\theta^3) \\
&=-8\theta^3 \cos (\theta^4) \sin (\theta^4)
\end{aligned}
$$
And we can also get the derivative directly:
$$
y' = 2\cos(\theta^4) \cdot (-\sin (\theta^4)) \cdot (4\theta^3) = -8\theta^3 \cos (\theta^4) \sin (\theta^4)
$$
So the answer will be:
$$
-8\theta^3 \cos (\theta^4) \sin (\theta^4) = 0
$$
It's an easy problem, 
$$
\begin{aligned}
\theta &= 0\\
\cos(\theta^4) &= 0\\
\sin(\theta^4) &= 0
\end{aligned}
$$
Every equation stands for some answers.