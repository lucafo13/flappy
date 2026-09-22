# FlappyMon 

# Integrantes

**Davi Lucas**
<br>

**Edelcio Miguel**

# Objetivo

O jogo é uma versão de flappy bird, fundida com a sequencia de jogos da Game Freak e, seguindo a mesma finalidade do original, o jogador de planar entre os canos para aumentar sua pontuação.


# Arquitetura

```
FLAPPY_BIRD_PYTHON/
├── flappy.py
├── flappy_update.py         
├── assets/   
├── sound/
├── README.md   


```
# Controles:

**SPACE** --> Controla basicamente o jogo inteiro, fazendo o jogador planar entre os obstáculos.

<br>

# Funcionamento

O jogo funciona apartir da biblioteca pygame.

<br>
**def drawn_floor()** -->   
**def create_pipe()** --> Cria os obstáculos aleatóriamente, escolhendo, na função, a altura tanto do cano de cima, quanto do cano de baixo 
**move_pipes** --> Move os  obstáculos para a direção do jogador, causando o efeito de que o pokémon está se movendo  
****

