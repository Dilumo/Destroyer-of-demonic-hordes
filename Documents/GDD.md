# Destroyer of demonic hordes



# Introdução

  Esse jogo pertence a uma seria de jogos de uma página, que tem como objetivo render mais conhecimento básico a mim e facilitar a entrada/volta de pessoas com menos tempo ou interesse para jogos mais complexos.
<!-- /MarkdownTOC -->
# Indice

  - [Documentação](#documentação)
      - [Highconcept](#highconcept)
      - [Enredo](#enredo)
      - [Gameplay](#gameplay)
          - [Regras](#regras) 
          - [Elementos](#elementos)
            - [Inimigos](#inimigos)
            - [Indicadores](#indicadores)
            - [Habilidades](#habilidades)
            - [Recursos](#recursos)
  - [Interface](#interface)
  - [Multiplayer](#multiplayer)
  - [Ideias](#ideias)
  - [Meios](#meios)


<!-- /MarkdownTOC -->

---

<a name="documentação"></a>
# Documentação

<a name="highconcept"></a>
##  Highconcept
  Um jogo de tabuleiro onde você tem que derrotar uma horda de demônios para salvar a cidade de Garnelia.       
<a name="enredo"></a>                      
## Enredo
A grande cidade Garnelia em seus últimos suspiros de desespero, pede a você, nosso herói mágico para se livrar da grande horda de demônios que agora marcha em direção à cidade.
Então cabe a você acabar com esse perigo, mas lembre-se, você não sabe como lançar feitiços a distância, então infelizmente você terá que se teletransportar para o meio da horda, mas não se preocupe, este feitiço é fraco, não dura mais que alguns segundos e então você voltara para o ponto de lançamento. Apenas lembre de evitar de se teletransportar em lugares vazios, isso pode fazer você ficar lá um pouco mais de tempo, e como você sabe, os demônios não gostam muito de você. Vai mago! No pior dos casos você morre!

<a name="gameplay"></a>
## Gameplay 
Com o auxilio de *dois dados* o jogador rodara o primeiro dado para **linha** e o segundo para **coluna**. Assim causando um ataque ao quadrado correspondente a essa coordenada. Acumulando moedas o jogador pode comprar poderes, que serão jogados quando ele atacar se ele assim desejar.
    
  <a name="regras"></a>
  ### Regras:
  - Sempre o primeiro dado jogado sera linha.
  - Quando destruir um demônico o quadrado em que ele estava fica **vazio**.
  - Quadrados vazios não tem mais efeitos especiais.
  - Você leva um de dano quando ataca um quadrado vazio na horizontal ou vertical de outro demônio.
  - Se sua vida chegar a zero você perde.
  - Se você derrotar todos os demônios você ganha.
  
<a name="elementos"></a>
## Elementos
<a name="inimigos"></a>
### Inimigos:
 - ![Minion Demon](https://github.com/Dilumo/Destroyer-of-demonic-hordes/blob/master/Documents/Assets/Minon-Demon.png?raw=true "Minion Demon") <br> 
 **Minion Demon:** Um golpe o mata, receba uma moeda.
 - ![Warrior Demon](https://github.com//Dilumo/Destroyer-of-demonic-hordes/blob/master/Documents/Assets/Warrior-Demon.png?raw=true "Warrior Demon") <br> 
 **Warrior Demon:** Dois golpes o mata, receba duas moedas.
  - ![Witch Demon](https://github.com//Dilumo/Destroyer-of-demonic-hordes/blob/master/Documents/Assets/Witch-Demon.png?raw=true "Witch Demon") <br> 
  **Witch Demon:** Um golpe o mata, revive outro demônio, receba três moedas.
  - ![Explosive Demon](https://github.com//Dilumo/Destroyer-of-demonic-hordes/blob/master/Documents/Assets/Explosive-Demon.png?raw=true "Explosive Demon") <br> 
  **Explosive Demon:** Um golpe o mata, destrói outro demônio, receba um moeda.
<a name="indicadores"></a>
### Indicadores:
  - ![Column](https://github.com//Dilumo/Destroyer-of-demonic-hordes/blob/master/Documents/Assets/Column.png?raw=true "Column") <br> 
  **Column:** Jogue um dado coluna para sofrer o efeito.
  - ![Line](https://github.com//Dilumo/Destroyer-of-demonic-hordes/blob/master/Documents/Assets/Line.png?raw=true "Line") <br> 
  **Line:** Jogue um dado linha para sofrer o efeito.
  - ![Direction](https://github.com//Dilumo/Destroyer-of-demonic-hordes/blob/master/Documents/Assets/Direction.png?raw=true "Direction") 
  <br> **Direction:** Aponta a direção do quadrado que recebera o efeito.
<a name="habilidades"></a>
### Habilidades:
  - ![Horizontal Power](https://github.com//Dilumo/Destroyer-of-demonic-hordes/blob/master/Documents/Assets/Horizontal-Power.png?raw=true "Horizontal Power")<br> 
   **Horizontal Power:** Ao atacar jogue um dado, caso saia maior que quatro acerte um ataque em todos dessa linha, recebendo um de dano.
  - ![Vertical Power](https://github.com//Dilumo/Destroyer-of-demonic-hordes/blob/master/Documents/Assets/Vertical-Power.png?raw=true "Vertical Power")<br> 
  **Vertical Power:** Ao atacar jogue um dado, caso saia maior que dois acerte um ataque em todos dessa coluna, recebendo dois de dano.
<a name="recursos"></a>
### Recursos:
  - ![Coin](https://github.com//Dilumo/Destroyer-of-demonic-hordes/blob/master/Documents/Assets/Coin.png?raw=true "Coin") <br> 
  **Coin:** Inicia o jogo sem moedas.
  - ![Hit Points](https://github.com//Dilumo/Destroyer-of-demonic-hordes/blob/master/Documents/Assets/Hit-Points.png?raw=true "Hit Points") <br> 
  **Hit Points:** Inicia com vinte pontos de vida.

<a name="interface"></a>
# Interface
>![Explicação da interface](https://github.com//Dilumo/Destroyer-of-demonic-hordes/blob/master/Documents/Assets/Interface.png?raw=true "Explicação da interface") <br> 
 > **Fonte:** Acervo pessoal.

<a name="multiplayer"></a>
# Multiplayer
- Os jogadores dividem suas vidas pelo número de participantes.
- Cada demônio dá pontos equivalentes as moedas que daria.
- Pontuação final é dada apartir da somar da vida remanescente, mais os pontos recebidos e bônus de 5 pontos para cada participante morto antes de você.

<a name="ideias"></a>
# Ideias
Entre as ideias para uma extensão do jogo, temos a ideia de colocar um Chefe no final da partida, onde o rodar de dados equivale a um número X de dano, colocar um número maior de tipos de inimigo, colocar um sistema de *drop*, onde teríamos como auxilio  *decks* que seriam separado por modalidade de monstros, fazendo assim cada um deles ter um tipo de drop e por fim termos mais Habilidades, para facilitar a jogabilidade. 

<a name="meios"></a>
# Meios
Usei as dependências da minha casa para produzir esse jogo.
- Inkscape
- Visual Studio Code
- GitHub

>**Atenção!**<br>
>Esse projeto em particular foi feito para o curso online [Introduction to Game Design][1] da escola [California Institute of the Arts][2]. <br>
Por esse motivo seus direitos são de propriedade acadêmica.


[1]:https://www.coursera.org/learn/game-design/home/welcome
[2]:https://www.calarts.edu