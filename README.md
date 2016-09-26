# test_md
Github with MathJax (Chrome extesion)
========================================

Extension add support for LaTeX equations in GitHub repositories, rendering them with an open source [MathJax](http://mathjax.org/) library. In example, if you had it install you would see the following lovely equation: $e^{i \pi} + 1 = 0$

Right-Click on equation to show MathJax's context menu with additional options, e.g. "Scale All Math..." to instantly scale all equations on a page, "TeX commands" to see the source TeX equation etc.

Extension is published under [New BSD License](https://github.com/orsharir/github-mathjax/blob/master/LICENSE.md) with the source code available [here](https://github.com/orsharir/github-mathjax). This extension is based on the __wonderful__ [wiki_mathjax](https://github.com/bgromov/wiki-mathjax) extension by [Boris Gromov](https://github.com/bgromov), and its license is included as part of LICENSE.md in this repository.

For bug reports and feature requests, please use [Issue tracker](https://github.com/orsharir/github-mathjax/issues).

### INSTALLATION:

Official release available at [Chrome Web Store](https://chrome.google.com/webstore/detail/github-with-mathjax/ioemnmodlmafdkllaclgeombjnmnbima).


Equation Testing

1. block equation $x$

$$x = {-b \pm \sqrt{b^2-4ac} \over 2a}$$
$$x(t)=\frac{-b\pm \sqrt{{b}^{2}-4ac}}{2a}$$
2. inline equation: $({e}^{i\pi}+1=0)$
MathJax
and another numbered one with no label:
$$x+1\over\sqrt{1-x^2}$$
This one uses \nonumber:
$$x+1\over\sqrt{1-x^2}
Equation Testing
$$x+1\over\sqrt{1-x^2}$$
This one uses \nonumber:
$$x+1\over\sqrt{1-x^2}$$

<div>
$$x+1\over\sqrt{1-x^2}$$
This one uses \nonumber:
$$x+1\over\sqrt{1-x^2}$$
</div>
