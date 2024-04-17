**4.3.4 Estimativa de máxima verossimilhança**

  Para estimar os parâmetros do modelo, adaptamos um algoritmo proposto por Anderson
(1973). A logo-verossimilhança para o modelo espacial linear t-Student é dado por

$\mathcal{L}(\theta)=Log(K_{n}(\eta))-\frac{1}{2}log|\Sigma|-\frac{1}{2{n}}(1+{n}\eta)log(1+c(\eta)\delta)$

**com** $log(K_{n}(\eta))=\frac{n}{2}log(\frac{c(\eta)}{\Pi})+log\Gamma(\frac{1+{n}\eta}{2\eta}), \delta = (\boldsymbol{Y} - \boldsymbol{X}\beta)^T\Sigma^{-1}(\boldsymbol{Y} - \boldsymbol{X}\beta)$ **e** $c(\eta)=/eta/(1 - 2 \eta), 0 < \eta < \frac{1}{2}$. **Conforme observado por Zellner (1976), a função logo-verossimilhança (4.4) é uma função decrescente de** $\eta$, **e então não pode estimado por máximo verossimilhança.  Veja também De Bastiani et al. (2015).**

 **As funções escores para o modelo espacial linear t-Student são fornecidas por** $U_\theta(\theta)=( U_\beta^T,U_Φ^T)^T$, **em que**

$U_\beta=\partial\mathcal{L}(\theta)/\partial\beta=w(\delta)\boldsymbol{X}^T\Sigma^{-1}\epsilon$ **and** $U_Φ=\partial\mathcal{L}(\theta)/\partialΦ$, **com o j-ésimo elemento de U_Φ, dado por** $U_{{\phi}_{j}}=\partal\mathcal{$
