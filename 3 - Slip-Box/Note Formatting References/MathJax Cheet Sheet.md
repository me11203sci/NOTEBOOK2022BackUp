# MathJax
---
***MathJax*** has similar [syntax](https://math.meta.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-qu%E2%80%8C%E2%80%8Bick-reference) to LaTeX and is similarly used to insert equations into notes quickly.

## Basic Syntax
**In-Line**:
>${e^{i\pi}=-1}$

- Place code between `$...$`.

**Displayed (Centered)**:
>$${i\hbar{\partial\over \partial t}\psi=\hat{H}\psi}$$

- Place code between `$$...$$`.

**Superscript and Subscript**:
>$2^{10}$
>$x_0$

- For use `^` superscript and `_` for subscript.

**Greek Letters**:^[Visit this [link](https://docs.latexbase.com/symbols/) for a directory of symbol names.]
>$\mathbb{\Gamma}$, $\Delta$, $\Omega$, etc. 

- For example, type `\Gamma` to render 𝚪.
- Note that the capitalization or lack thereof dictates whether the letter that gets rendered is capitalized or uncapitalized.

**Fractions**:
> ${x^2+1\over x^2-2}$

- The easy-peasy way is just to type the numerator, `\over`, and then the denominator.


**Font(s)**:
>$\mathbb{ABCDEFG}$

- Useful for denoting sets, type `\mathbb{...}`