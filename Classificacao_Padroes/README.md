# Questão: classificação de padrões
Esta questão, referente ao assunto de classificação de padrões, apresenta o seguinte enunciado:
Considere os dados apresentados na tabela abaixo. Assumindo que as distribuições associadas a cada classe são gaussianas com probabilidades a priori dadas por (P(ω1) =P(ω2) = 1/2) busque solucionar as questões abaixo.

Classe e feature |ω1(x1)|ω1(x2)|ω2(x1)|ω2(x2)
-----------------|------|------|------|------
1                |-5.01 |-8.12 |-0.91 |-0.18
2                |-5.43 |-3.48 |1.30  |-2.06
3                |1.08  |-5.52 |-7.75 |-4.54
4                |0.86  |-3.78 |-5.47 |0.50
5                |-2.67 |0.63  |6.14  |5.72
6                |4.94  |3.29  |3.60  |1.26
7                |-2.51 |2.09  |5.37  |-4.63
8                |-2.25 |-2.13 |7.18  |1.46
9                |5.56  |2.86  |-7.39 |1.17
10               |1.03  |-3.33 |-7.50 |-6.32

<p> a) Estime o vetor média e a matriz de covariância de cada distribuição gaussiana multivariada. </p>
<p>b) Determine a superfície de decisão fazendo $g_1(x)=g_2(x)$, $g_1(x)$ e $g_2(x)$ as funções descriminantes e $x=[x_1,x_2]^{t}$. As funções discriminantes $g_{i}(x)$, i=1,2 podem ser calculadas para estas condições pela equação: $g_i(x) = -\frac{1}{2}\cdot((x-\mu_i)^{t}\cdot\varepsilon_{i}^{-1} \cdot(x-\mu_i))-\frac{1}{2}\cdot ln(|\varepsilon_i|)$</p>
<p>c) Classifique os pontos (padrões) $(1, 2)^{t}$, $(5, 3)^{t}$, $(0, 0)^{t}$, $(1, 0)^{t}$, decidindo pela classe com maior valor das funções discriminantes, isto e, max{gi(x)} ou faça pela região definida pela superfície de separação (função descriminante) </p>

