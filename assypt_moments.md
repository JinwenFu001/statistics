# Assymptotical moments
  
$X_1,\cdots,X_n\ i.i.d.\sim\ F$  
  
$\alpha_k=EX_1^k,\ k\ge 1$  
$\mu_k=E(X_1-\alpha_1)^k$ (Note: $\mu_1=0$)  
  
## Sample moments
  
$a_k=\frac{1}{n}\sum\limits_{i=1}^n X_i^k$  
$m_k=\frac{1}{n}\sum\limits_{i=1}^n (X_i-a_1)^k$  
  
### Assymptotic property for a
  
(1) $a_k\overset{a.s.}{\rightarrow}\alpha_k\ if\ |\alpha_k|<\infty$  
(2) $Ea_k=\alpha_k$  
(3) $Var(a_k)=\frac{\alpha_2k-\alpha_k^2}{n}$  
(4) $\sqrt{n}(a_1-\alpha_1,\cdots,a_n-\alpha_n)\overset{D}{\rightarrow}N(\tilde 0,\Sigma)$ where $\Sigma=(\sigma_{ij}),\ \sigma_{ij}=\alpha_{i+j}-\alpha_i\alpha_j$
