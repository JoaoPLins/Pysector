# Pysector
this is a space game made in python, it consists of a CO-OP spaceship battle Simulation

Currently things todo 

----Clientside----
UI-> making classes for things on ui.py(?)


OBJECTS -> creating instances for Objects a method to create them, build or buy, and destroy. 


SOUND -> Creating sounds to add to the experience. make it so if current player may be not affectded by sound in some ocasions. maybe add a small plugin for voice, ( to think on it) 


Player -> creating Player.py to make a class only for the player, this will give us some wiggle room in case we want to treat it's phisics differently of the ship, like in case gravity fails?( we migth need to merge this to objects, or make it so players are objects. 


Syicronism clock -> this is a simple concept. a clock the runs on the "Gameloop" and keeps the player always in sync with the game, if it gets way of, it will reload the files like it was recconingting again,( we may need to pay attention to this because we may need to set ways to the server to keep at the same speed that client sees. 

-ServerSide-- 


Sync-clock -> Read above 


PlayerPlacements -> wheree the players are on the map at the current time in the server. 


Items values/Placements -> name explains it.


"server placement" -> Where on the big picture of the map the server currently IS. 


server events -> events that are handled by the server like. SHIP SIGHTED, or DEBREE FIELD, and stuff like that 











PT-BR -> coisas a fazer: 
---ClientSide---
->carregamento de mapa e objetos .
->interação simples com objetos. 
->som
->relogio de sincronia
->movimentação e carregamento de entidades que nao sou o player
->movimentação do player 

---SERVERSIDE---
PARA Alpha1

Sistema de server, (pode ser que a gente possa usar outras linguagens porem no momento vamos assumir que estamos trabalhando somente com o python. 

Fase-1 -> Medio e Grandes servers (esses servers tem host FIXO) neles serao calculados os seguintes: 

->Variaveis dependentes de Tile positions(espaço no mapa). 
->local dos players
->Valores de items 
->"local do server"
->eventos de server
->relogio de sincronia 
