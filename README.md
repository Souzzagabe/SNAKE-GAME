# SNAKE-GAME

Este é uma implementação simples do clássico jogo da Cobra (Snake) usando HTML, CSS e JavaScript. O jogo apresenta um campo de jogo baseado em grade, onde o jogador controla uma cobra para coletar itens de comida posicionados aleatoriamente. O objetivo é aumentar o comprimento da cobra enquanto evita colisões com as paredes e com ela mesma.

Como Jogar

Clone ou faça o download do repositório para a sua máquina local.
Abra o arquivo index.html em um navegador web moderno.
Jogabilidade
Use as teclas de seta (Cima, Baixo, Esquerda, Direita) para controlar a direção da cobra.
A cobra se move continuamente na direção escolhida.
Colete os itens de comida para aumentar sua pontuação.
O jogo termina quando a cobra colide com as paredes ou consigo mesma.
Clique no botão "Jogar" na tela de menu para reiniciar o jogo.

Recursos

Itens de comida gerados aleatoriamente com cores diferentes.
Acompanhamento da pontuação.
Tela de fim de jogo com a pontuação final exibida.
Efeitos sonoros quando a comida é coletada.

Visão Geral do Código

O jogo é construído usando o elemento HTML5 <canvas> para renderização de gráficos e JavaScript para a lógica do jogo. Aqui está uma visão geral dos principais componentes:

Movimento da Cobra: A cobra se move continuamente na direção atual, e sua posição é atualizada de acordo.

Geração de Comida: Os itens de comida são gerados aleatoriamente na grade, garantindo que não se sobreponham à cobra.

Detecção de Colisão: O jogo verifica colisões com as paredes e o próprio corpo da cobra. Quando uma colisão é detectada, o jogo termina.

Acompanhamento da Pontuação: A pontuação do jogador aumenta quando ele coleta os itens de comida.

Loop Principal do Jogo: O loop principal do jogo cuida da renderização, movimento, detecção de colisão e pontuação. Ele é executado em intervalos regulares para fornecer uma jogabilidade suave.

Tela de Menu: Uma tela de menu é exibida no início e quando o jogo termina. Ela inclui um botão "Jogar" para reiniciar o jogo.

Efeitos Sonoros: O jogo inclui efeitos sonoros quando a cobra coleta comida.