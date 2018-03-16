# Strengthen The Copson's Inequality

## There is the result

For all real ![](http://latex.codecogs.com/gif.latex?a_1,a_2,...,a_n) we have

![](http://latex.codecogs.com/gif.latex?\\sum_{i=1}^\\infty(\\sum_{k=i}^\\infty\\frac{a_k}{k})^2\\leq4\\sum_{i=1}^\\infty(1-\\frac{R}{\\sqrt{i}})a_i^2.)

There ![](http://latex.codecogs.com/gif.latex?R=1-\frac{1}{4}\zeta(\frac{3}{2}).)
(assuming all series converge)

## Copson's Ineq

The Copson's Ineq is:

For all real ![](http://latex.codecogs.com/gif.latex?a_1,a_2,...,a_n) and ![](http://latex.codecogs.com/gif.latex?p>1) we have

![](http://latex.codecogs.com/gif.latex?\\sum_{i=1}^\\infty(\\sum_{k=i}^\\infty\\frac{a_k}{k})^p\\leq(p^p)\\sum_{i=1}^\\infty(a_i^p).)

Let ![](http://latex.codecogs.com/gif.latex?p=2) we get

![](http://latex.codecogs.com/gif.latex?\\sum_{i=1}^\\infty(\\sum_{k=i}^\\infty\\frac{a_k}{k})^2\\leq4\\sum_{i=1}^\\infty(a_i^2).)

So my ineq is a strengthend form.

## Proof

With Cauchy-Buniakowsky-Schwarz Inequality we have

![](http://latex.codecogs.com/gif.latex?(\\sum_{k=i}^\\infty\\frac{a_k}{k})^2\\leq\\sum_{k=i}^\\infty\\frac{1}{k\\sqrt{k}}\\sum_{k=i}^\\infty\\frac{a_k^2}{\\sqrt{k}}=b_i\\sum_{k=i}^\\infty\\frac{a_k^2}{\\sqrt{k}}.)

There ![](http://latex.codecogs.com/gif.latex?b_i=\\sum_{k=i}^\\infty\\frac{1}{k\\sqrt{k}}.)

So

![](http://latex.codecogs.com/gif.latex?\\sum_{i=1}^\\infty(\\sum_{k=i}^\\infty\\frac{a_k}{k})^2\\leq\\sum_{i=1}^\\infty(b_i)\\sum_{k=i}^\\infty\\frac{a_k^2}{\\sqrt{k}}=\\sum_{i=1}^\\infty\\frac{a_i^2}{\\sqrt{i}}\\sum_{k=1}^i(b_k)=\\sum_{i=1}^\\infty\\frac{a_i^2}{\\sqrt{i}}\\sum_{k=1}^i\\sum_{n=k}^\\infty\\frac{1}{n\\sqrt{n}}.)
