## :page_facing_up: Sobre este trabalho

Este trabalho foi adaptado de um projeto encontrado no [Kaggle](https://www.kaggle.com/code/davinsthomas/cnn-adaptive-aug-template), produzido por Davin S. Thomas, e tem como objetivo explorar uma aplicação prática de redes neurais. Para esse contexto, escolheu-se uma aplicação de classificação de imagens usando redes neurais convolucionais (CNN).

## :bulb: Redes Neurais Convolucionais

As redes neurais convolucionais são muito utilizadas em aplicações onde os dados de entrada são bidimensionais, especialmente, para a classificação de imagens. A primeira rede convolucional de sucesso foi desenvolvida por Yann LeCun em 1988 e desde então vem sendo amplamente estudada e tendo diferentes arquiteturas implementadas (cada vez melhores) ao longo dos anos.

Em geral, esse tipo de rede neural é composto por 3 etapas principais:

1. __Convolução__: 

![image info](./images/img-redes-adversarias.png)

Em geral, quando o modelo discriminador está sendo treinado, o modelo gerador deve ser congelado e deve apenas retropropagar os erros para atualizar apenas o discriminador, e o mesmo ocorre na situação inversa. Deve-se para o treinamento quando o equilíbrio de Nash é atingido, ou seja, quando as imagens geradas parecem quase imagens reais.

## :tshirt: Aplicação: dataset fashion_mnist

A aplicação tem como objetivo utilizar o dataset fashion_mnist do Keras, que contém 70.000 imagens de roupas. Essas imagens possuem tamanho 28x28 em tons de cinza, e são associadas a um rótulo de 10 classes diferentes.

Assim, a partir das imagens reais, serão geradas novas imagens falsas pelo modelo gerador (a partir da introdução de um ruído nas imagens), enquanto o modelo discriminador deverá realizar corretamente a classificação das imagens como verdadeiras ou falsas.
