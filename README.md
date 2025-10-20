# Projeto para redução de dimensionalidade em imagens

-- Projeto bem simples realizado no desafio durante um BootCamp com a DIO. Nele apliquei meus conhecimentos aprendido durante o curso: BairesDev - Machine Learning Practitioner

-- Fiz o uso das bibliotecas PIL, numpy e matplotlib o que tornou este projeto bem facil.

-- Este projeto me ajudou a entender melhor o que é a redução de dimensionalidade, introduzir conceitos de manipulação de imagens em Python e praticar o que venho aprendendo.

## Descrição

O notebook realiza os seguintes passos:

1.  Carrega uma imagem a partir de um arquivo (originalmente um `.webp`).
2.  Exibe a imagem original.
3.  Converte a imagem colorida para escala de cinza.
4.  Exibe a imagem em escala de cinza.
5.  Converte a imagem em escala de cinza para uma imagem binária (preto e branco) utilizando um limiar (threshold) pré-definido (128).
6.  Exibe a imagem binária resultante.
7.  Converte as imagens em escala de cinza e binária para arrays NumPy.
8.  Exibe as dimensões (shape) dos arrays NumPy criados.


## Funcionalidades

* Leitura e exibição de imagens.
* Conversão de espaço de cores (Colorido -> Escala de Cinza).
* Binarização de imagem por limiarização (Thresholding).
* Interoperabilidade entre objetos de imagem Pillow e arrays NumPy.
