# Errata for *Numerical Analysis: a graduate course*

* Preface
* Chapter 1: Basics of Numerical Computation
  * p. 44, Ex (10): The mean $\mu(S)$ should be equal to $\sum_{i\in S}x_i/n(S)$, not just $\sum_{i\in S}x_i$.
  * p. 54, Ex (6): Last sentence 'Give a bound on $|g^{(5)}(c)|$ for $|c| \leq \frac{1}{4}$'.
* Chapter 2: Computing with matrices and vectors
  * p. 86, Sec 2.1, Ex 7: The functions *k* and *h* are given external functions.
  * p. 96, Sec 2.2.1: Last line of 2nd paragraph: the *a*'s should be *b*'s.
  * p. 62, Algo. 10, line 11: $l_{ik} ← m_{ik}$ assignment should occur on line 9.
  * p. 105, Exercise (1): Should read '...using normal equations or the QR factorization'.
  * p. 105-105, Excercise (4)-(6): Consider 'if $A = Q_1R_1 = Q_2_R_2$', suggest re-writting to avoid a notation conflict with Equation (2.2.9).
  * p. 108, Algo. 19, line 8: $\ell_k$ should be $\ell_{k-1}$
  * p. 129, equation (2.4.14): The last set should be $span\\{r_0,Ar_0,...,A^k r_0\\}$.
  * p. 131, line 5: $x_k-x_0$ should be $x_{k+1}-x_0$
  * p. 158, line 4 from bottom: parentheses should be used for $\rho$: $\rho^{[j]}u^{(j)} = A u^{(j-1)}$ should be  $\rho^{(j)}u^{(j)} = A u^{(j-1)}$.
  * p. 165, 3rd paragraph of text, line 8 of paragraph: "Section 2.2.2.4" should be "Section 2.2.2.5"
  * p. 179, Exercise (7): The suggested splittings lead to a non-conformal partitioning of $RY + YS = \tilde{C} ~ : \tilde{C} = QC\overline{U}^\top$.
* Chapter 3: Solving nonlinear equations
  * P. 184, Ex (7): The interval should be $\[2\times10^{-3},1\]$ instead of $\[10^{-3},1\]$.
  * p. 202, line 6 from bottom, middle of displayed equation: $-2f(x)\nabla f(x)f(x)^{-1}f(x)$ should be $-2f(x)^T\nabla f(x)\nabla f(x)^{-1}f(x)$
  * p. 205, Exercise (10) part (e), line 3: $LM\Vert f(x_k)\Vert > \frac12$ should have the inequality reversed: $LM\Vert f(x_k)\Vert < \frac12$
* Chapter 4: Approximation and interpolation
  * p. 237, line 2 (in Thm. 4.3): the reference to (4.1.10) should be to (4.1.7). The two equations (4.1.7) and (4.1.10) are, however, essentially equivalent.
  * p. 241, Algo. 53, line 4: update to $pval \leftarrow D_k + (t - x_k) \cdot pval$.
  * p. 249, Section 4.1,2, line 9 of paragraph 1: "while the best approximation by polynomials" should be "while the best approximation error by polynomials"
* Chapter 5: Integration and differentiation
  * p. 382, paragraph 1, line 6 of paragraph: "is perhaps 20 because" should be "is perhaps 20 times that of the original code, because"
* Chapter 6: Differential equations
  * p. 141, 2nd last line, displayed equation: the last $v_i$ should be $v_{k,i}$.
  * p. 445, last line: $n h = L$ should be $n h = b-a$
  * p. 446, line 8 of page, displayed equation: The matrix in the displayed equation should be $-b$ instead of $+b$ in the diagonal entries.
  * p. 451, line 1, displayed equation: $-u(x-h,y)$ should be $+u(x-h,y)$ in the numerator. This sign change also aplies to the displayed equations on lines 3, 5, and 7.
  * p. 457, Section 6.3.1.3, paragraph 3, 2nd last line of paragraph: $\kappa_2(B_h A_n)$ should be $\kappa_2(B_h A_h)$; (subscript should be $h$ instead of $n$).
* Chapter 7: Randomness
* Chapter 8: Optimization
* Appendix
* References
* Index

Let me know if you find any errors!
