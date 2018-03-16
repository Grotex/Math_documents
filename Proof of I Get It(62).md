# Proof of I Get It(62)

## Result

Let ![](http://latex.codecogs.com/gif.latex?x\\in[0,1],r\\in[1,\\infty\).)

Prove that

![](http://latex.codecogs.com/gif.latex?x-x^r\\leq1-\\frac{\\ln(r)}{r}.)

## Proof

Let ![](http://latex.codecogs.com/gif.latex?f(x)=x-x^r.)

Then ![](http://latex.codecogs.com/gif.latex?f'(x)=1-rx^{r-1},) it has only one root ![](http://latex.codecogs.com/gif.latex?r^{-\\frac{1}{r-1}}\\in[0,1].)

So ![](http://latex.codecogs.com/gif.latex?f(x)\\leq[f(r^{-\\frac{1}{r-1}})]=r^{-\\frac{1}{r-1}}-r^{-\\frac{r}{r-1}}=r^{-\\frac{1}{r-1}}(1-\\frac{1}{r}).)

If we can prove

![](http://latex.codecogs.com/gif.latex?(P):r^{-\\frac{1}{r-1}}(1-\\frac{1}{r})\\leq1-\\frac{\\ln(r)}{r},)

Then all can be done.

![](http://latex.codecogs.com/gif.latex?(P)) is equivalent to ![](http://latex.codecogs.com/gif.latex?(r-1)\\ln(\\frac{r-\\ln(r)}{r-1})+\\ln(r)\\geq0.)

If ![](http://latex.codecogs.com/gif.latex?r\\leq2,\\ln(r-1)\\leq0,(P)) is obvious.
(Remeber,![](http://latex.codecogs.com/gif.latex?r-\\ln(r)\\geq1) always occurs)

So we consider ![](http://latex.codecogs.com/gif.latex?r\\geq2.)

Because ![](http://latex.codecogs.com/gif.latex?\\ln(\\frac{r-\\ln(r)}{r-1})\\geq\\frac{\\frac{r-\\ln(r)}{r-1}-1}{\\frac{r-\ln(r)}{r-1}}=\\frac{1-\\ln(r)}{r-\\ln(r)}.)

So ![](http://latex.codecogs.com/gif.latex?(r-1)\\ln(\\frac{r-\\ln(r)}{r-1})+\\ln(r))
![](http://latex.codecogs.com/gif.latex?\\geq(r-1)\\frac{1-\\ln(r)}{r-\\ln(r)}+\ln(r))
![](http://latex.codecogs.com/gif.latex?=\\frac{r+\\ln(r)-(\\ln(r))^2-1}{r-\\ln(r)}.)

Let ![](http://latex.codecogs.com/gif.latex?g(r)=r+\\ln(r)-(\\ln(r))^2-1,) then ![](http://latex.codecogs.com/gif.latex?g'(r)=\\frac{r+1-2\\ln(r)}{r}.)

Let ![](http://latex.codecogs.com/gif.latex?h(r)=r+1-2\\ln(r),) then ![](http://latex.codecogs.com/gif.latex?h'(r)=\\frac{r-2}{r}\\geq0.)

So ![](http://latex.codecogs.com/gif.latex?h(r)\\geq(h(2))=3-2\\ln(2)>0,g'(r)=\\frac{h(r)}{r}>0;)

![](http://latex.codecogs.com/gif.latex?g(r)>g(2)=1+\\ln(2)-(\\ln(2))^2=1+\\ln(2)(1-\\ln(2))>0;)

![](http://latex.codecogs.com/gif.latex?(r-1)\\ln(\\frac{r-\\ln(r)}{r-1})+\\ln(r)\\geq\\frac{g(r)}{r-\\ln(r)}>0.)

So ![](http://latex.codecogs.com/gif.latex?(P)) occurs, all done.

Q.E.D.

## Reference
https://artofproblemsolving.com/community/c6h1371684p7560009
https://artofproblemsolving.com/community/c390681h1372537
