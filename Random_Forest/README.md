#💡Projeto: classificação de um bom pagador de empréstimo ou não 

Este trabalho tem como objetivo classificar um cliente como um bom pagador ou não de um empréstimo, utilizando o algoritmo Random Forest da biblioteca SciKit-Learn.
O dataset utilizado se chama `German Credit Risk` e foi retirado do Kaggle neste [link](https://www.kaggle.com/datasets/kabure/german-credit-data-with-risk). Ele possui as seguintes colunas:


*   ID: Id do cliente
*   Age: idade do cliente
*   Sex: sexo do cliente (masculino ou feminino)
*   Job: 0 (não qualificado e não residente), 1 (não qualificado e residente), 2 (qualificado), 3 (altamente qualificado)
*   Housing: own (casa própria), rent (casa alugada), free ("grátis")
*   Saving accounts: little (pouco), moderate (moderado), quite rich (um pouco rico), rich (rico)
*   Checking account: little (pouco), moderate (moderado), quite rich (um pouco rico), rich (rico)
*   Credit amount: quantidade de crédito
*   Duration: duração do empréstimo (em meses)
*   Purpose: propósito do empréstimo
*   Risk: se o risco de fazer o empréstimo é bom (good) ou ruim (bad)
