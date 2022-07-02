# Proposta do projeto

O jogo da velha foi o projeto final do curso prepatório Coding-Tank e processo seletivo para a entrada no curso de Web Full Stack da instituição Let's Code.
-- O curso foi ministrado na linguagem Python e abordou a lógica de programação juntamente com os principais conceitos e ferramentas da linguagem sendo alguns deles a apresentação aos: tipos primitivios, operadores lógicos e condicionais, arrays, loops, funções e dicionários.
-Com esse conhecimento adiquirido foi proposta a criação do jogo da velha utilizando um documento com extensão .ipynb rodando no servidor Jupyter Notebook.O jogo não utiliza nenhum recurso visual avançado e os comandos são digitados na janela de input que aparece na tela. 

## Requisitos obrigatórios

- O jogo é jogado em um tabuleiro 3x3 por dois jogadores.
- O primeiro jogador é representado pelo símbolo O, enquanto o segundo jogador utiliza o símbolo X.
- As jogadas são alternadas, preenchendo uma posição com o seu respectivo símbolo, sempre começando pelo jogador com o símbolo O. 
- Ganha o jogador que conseguir colocar 3 símbolos em linha no tabuleiro, seja na vertical, horizontal ou diagonal.
- O seu objetivo nesse projeto é criar um jogo da velha em Python, onde os jogadores poderão informar suas posições pelo teclado e o tabuleiro será mostrado com um print após cada jogada. 
- Você pode utilizar qualquer recurso que aprendemos até aqui, além do seu conhecimento prévio. O único ponto importante é que não será permitido o uso de bibliotecas.
- Crie uma maneira de checar se há um vencedor depois de cada jogada
- Não faz sentido um jogador conseguir jogar numa posição que já foi ocupada, não é mesmo? Garanta isso no seu código!
- Crie testes para verificar o funcionamento do seu programa.

## Manual do usuário

- Abra o arquivo Projeto Jogo da Velha-Guilherme Oliveira.ipynb utilizando o jupyter notebook. Sugestão de guia para a instalação e uso [Jupyter Notebook](https://jupyter.org/).
- Escolha a linha (1 a 3) e coluna (1 a 3) desejada digitando no campo de input.
- Caso seja digitada uma posição já ocupada a jogada não será realizada. Será apresentada uma mensagem informando o ocorrido e o jogador terá que digitar outra posição.
- Ganha o jogador que conseguir colocar 3 símbolos em linha no tabuleiro, seja na vertical, horizontal ou diagonal. Uma mensagem informando o vencendor será exibida.
- Caso não haja nenhum vencedor ao final de todas as jogadas uma mensagem de empate será exibida.