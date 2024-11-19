# Minigame Fórmula 1 em C 🏎

Este é um jogo simples de Fórmula 1 desenvolvido em C, onde o jogador controla um carro em uma pista reta e deve acumular pontuação enquanto realiza o trajeto no modo de 30 segundos ou no modo infinito. O objetivo é controlar a velocidade do carro para desviar de obstáculos e acumular a maior pontuação possível em qualquer modo a fim de estipular recordes. A velocidade com que executa o trajeto faz diferença para sua pontuação final.

## 🎮 Funcionalidades

*Controle de Velocidade*: 
  - Pressione *W* para acelerar.
  - Pressione *S* para desacelerar.
  - Pressione *A* para ir para a esquerda.
  - Pressione *D* para ir para a direita.

*Sistema de Obstáculos*:
  - Desvie de outros carros na pista para evitar colisões.
  - Se colidir com outro carro, será *Game Over*.
  - No modo de 30 segundos, se sua pontuação estiver maior que seu recorde atual, porém você colidir com outro carro antes de finalizar o tempo, seu recorde atual permenecerá o mesmo, pois concluir o trajeto é uma premissa fundamental no jogo.

*Modos de jogo*:
  - 30 segundos: o jogador tem por objetivo percorrer o trajeto manipulando sua velocidade e desviando dos outros carros, tentando chegar ao fim dos 30 segundos realizando a maior pontuação possível. Ao final, é mostrado sua pontuação e se deseja jogar novamente para tentar quebrar seu recorde.
  - Infinito:o jogador tem por objetivo percorrer o trajeto manipulando sua velocidade e desviando dos outros carros de maneira "infinita", até que venha a colidir em algum carro e encerre o jogo. Ao final, é mostrado sua pontuação e se deseja jogar novamente para tentar quebrar seu recorde.

*Pontuação*:
  - O objetivo é desviar dos outros carros e manipular a sua velocidade para que atinja a maior pontuação possível.
  - Seu tempo final será exibido ao final da partida, com a possibilidade de bater seu próprio recorde.

## 🚀 Como Jogar

### 1. Clonar o repositório
- git clone https://github.com/aironvalentim/formula1-minigame.git
- cd formula1-minigame
  
### 2. Compilar o jogo
- Certifique-se de ter um compilador C instalado (por exemplo, gcc). Para compilar o jogo, utilize o comando:
- gcc src/.c -I include -o formula1-minigame

### 3. Executar o jogo
- ./formula1-minigame

## 🛠 Tecnologias Utilizadas
- Linguagem C
- Ambiente de console (CLI)
- Compilador GCC (ou similar)


## 🤝 Contribuições
- Contribuições são bem-vindas! Sinta-se à vontade para abrir um pull request ou relatar problemas na aba Issues.

## 📄 Licença
- Este projeto está licenciado sob a MIT License. Veja o arquivo LICENSE para mais detalhes.

### Integrantes do Grupo

| Nome               | Função             | GitHub             |
|--------------------|--------------------|--------------------|
| Airon Valentim     | Developer          | @aironvalentim     |
| Antônio Tenório    | Developer          | @antoniotfs        |
| Gustavo Ferraz     | Developer          | @gustvcarvalho     |

## Nome da disciplina: 
#### Programação Imperativa e Funcional - 2024.2
## Instituição de ensino: 
#### CESAR School
## Professor:
#### Diego de Freitas
