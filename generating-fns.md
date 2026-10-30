## This is a test

* here's a list
* here's item 2


### Generating Functions and Stirling Numbers

```math
\sum_{n=k}^{\infty} \left\{ \begin{matrix} n \\ k \end{matrix} \right\} \frac{x^n}{n!} = \frac{(e^x - 1)^k}{k!}
```

Ordinary generating function for rising factorials (generating unsigned Stirling numbers of the first kind):

```math
$$P_n(x) = \sum_{k=1}^n \left[ \begin{matrix} n \\ k \end{matrix} \right] x^k = x(x+1)(x+2)\cdots(x+n-1)$$
```

Exponential generating function for Stirling numbers of the second kind
```math
$$\sum_{n=k}^{\infty} \left\{ \begin{matrix} n \\ k \end{matrix} \right\} \frac{x^n}{n!} = \frac{(e^x - 1)^k}{k!}$$
```
Recurrence relation:
```math
$$\left[ \begin{matrix} n \\ k \end{matrix} \right] = (n-1) \left[ \begin{matrix} n-1 \\ k \end{matrix} \right] + \left[ \begin{matrix} n-1 \\ k-1 \end{matrix} \right]$$
```
