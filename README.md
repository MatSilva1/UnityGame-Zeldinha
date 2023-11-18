# UnityGame-Zeldinha

## Um jogo inspirado em The Legend of Zelda: Link's Awakening (versão Nintendo Switch), este projeto foi parte do curso Unity na plataforma DIO

### Neste reposiótio você encontra o projeto Unity + código fonte e uma build para OS Windows

Definimos os seguintes requisitos na arquitetura do código:
  - Event listeners para otimização/organização de código 
  - Constructors para os inimigos (houve um ganho na velocidade de desenvolvimento) 
  - Finite State Machine para evitar um unico arquivo com código gigante, separei cada estado do personagem (andar, pular e atacar) em seu respectivo arquivo e criei um script para controlar os estados, onde é instanciado o script referente a ação que o jogador deseja performar
