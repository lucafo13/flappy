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

def drawn_floor() --> Desenha o chão na tela e reposiciona as imagens para criar o efeito de um chão contínuo.

<br>def create_pipe() --> Cria os obstáculos aleatoriamente, escolhendo a altura dos canos e definindo a posição do cano de cima e do cano de baixo.

<br>def move_pipes() --> Move os obstáculos para a esquerda, criando o efeito de que o Pokémon está avançando pelo cenário.

<br>def draw_pipes() --> Desenha os canos na tela, invertendo verticalmente a imagem quando necessário para representar o cano de cima.

<br>def check_collision() --> Verifica se o Pokémon colidiu com algum cano ou saiu dos limites da tela. Caso aconteça, encerra a partida.

<br>def rotate_bird() --> Rotaciona o Pokémon de acordo com seu movimento vertical, fazendo ele inclinar enquanto sobe ou desce.

<br>def bird_animation() --> Controla os frames da animação do Pokémon, alternando entre as imagens disponíveis.

<br>def update_score() --> Verifica e atualiza a maior pontuação alcançada pelo jogador.

<br>def pipe_score_check() --> Verifica quando o Pokémon passa pelos obstáculos e aumenta a pontuação.

<br>while True: --> Mantém o jogo funcionando continuamente, processando eventos, atualizando os elementos e desenhando a tela a cada frame.