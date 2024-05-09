## Welcome to the strategy turn based anime game

This is a project made for fun purposes, there is no compromisse on completing it.
I had a few names for the project, but I will call it that for now.
I had many inspirations, a mix of XCOM and Pathfinder 2e in gameplay,
some other anime games that I found in darkest corners of the internet,
but I still need to implement everything and I am short on time to
work on this project.
Feel free to fork, or make a contribution if you want.

### "What is this game even about?"

There will be nice characters... and also there I think there will be some
lore that probably no one will even care, it's about crime I guess,
and you can shoot people in a XCOM like gameplay.

### TO DO:
- There is no 3d asset in the game that is not a placeholder, at least adding something would be good.
- Find a way to make the A* pathfinding calculate the shortest route without instantly crashing the game (It is only calculating based on the closest tile).
- Buy the commercial version of the unreal engine genshin shader to use here.
- Finish the Game Develpment Document (GDD)
- Make some concept art of the characters.
- Solve the pathfinding bugs and make it work.
- Implement a menu and a user interface.
- Solve the stairs problem, how is the movement cost be calculated? Will the character teleport from one point to the other? Will it be possible to stop in the middle of the stairs? What if someone passes through the stairs tile but doesn't want to climb the stairs?
- Solve the problem about the path calculation having to be displayed to the player before he presses to move.

### Know bugs:
- Sometimes the pathfinding system sends you to 0;0;0 before sending you to the correct location. A simple check would solve but I don't know if when it happens the one of the locations is excluded.
- For a completely unknow reason an index box (those colored boxes that you have to click to move) spawned in the air.
- I broke the pathfinding while trying to update the pathfinding to work with Z axis, so it will take a while to make it work properly in 3d.

### Keyboard commands:

- `Tab` to pass turn.
- `Num 0` to change camera angle.
- `Num 1` to reset camera.
- `L` to console.log your location.
- `K` to attack/damage (you need to have an enemy selected).
- `W,A,S,D` to move camera.
- `Up,Down,Left,Righy` to rotate the camera.
- `Q,E` to also rotate the camera.

I think that is it for now.

Feel free to send me a message on my discord: kunhah

-------------------------------------------------------------

## Bem vindo ao jogo de estratégia de turnos em anime

Esse projeto foi feito por diversão, não há compromisso em terminar.
Eu tinha alguns possíveis nomes para o projeto, mas vai ser isso até eu encontrar um nome bom.
Eu tive muitas inspirações, uma mistura de XCOM com Pathfinder 2e na gameplay,
e alguns outros jogos de anime que eu encontrei nos cantos mais sombrios da internet,
mas eu ainda preciso implementar tudo isso e to sem tempo pra trabalhar nesse projeto.
Sinta-se livre para fazer um fork, ou contribuir se quiseres.

### "Mas sobre o que é esse jogo ae?"

Vai ter personagens daora... e eu acho que vai ter uma historinha
mas que provavelmente ninguém vai se importar, eu acho que vai ser sobre crime,
e você vai poder atirar em pessoas num gameplay ao estilo XCOM.

### PARA FAZER:
- Temos um total de 0 modelos 3d que não irão ser substituídos depois, ter pelo menos alguns já daria uma coisa a mais.
- Dar um jeito de fazer o algorítimo de encontrar caminho A* calcular a rota mais curta sem crashar o jogo instantaneamente (Só ta calculando se baseando no quadrado mais próximo).
- Comprar a versão comercial do shader que imita o visual de Genshin na unreal.
- Finalizar o documento de desenvolvimento do jogo (GDD).
- Fazer a arte conceitual dos personagens.
- Resolver os bugs do pathfinding e fazer funcionar de uma vez.
- Implementar um menu e uma interface de usuário.
- Resolver o problema das escadas, como o custo de movimentação vai ser calculado? O personagem vai teleportar de uma ponta a outra da escada? Vai ser possível para no meio da escada? E o que acontece se alguém passar no quadrado da escada mas não quiser subir?
- Resolver o problema do calculo do ter que ser mostrado ao usuário antes dele clicar para mover.

### Bugs conhecidos:
- As vezes o pathfinding vai te mandar para a localização 0;0;0 antes de te mandar para a localização certa. Uma simples checagem resolveria, mas eu não sei se uma das localizações é excluída quando acontece.
- Por alguma razão completamente deconhecida uma index box (aquelas caixas coloridas que você tem que clicar pra mover) spawnou no ar.
- Eu quebrei o pathfinding tentando fazer com que ele funcione no eixo Z, então vai levar um tempinho a mais para fazer com que ele funcione em 3d.

### Comandos no teclado:

- `Tab` para passar o turno.
- `Num 0` para mudar o angulo da camera.
- `Num 1` para resetar a camera.
- `L` para dar console.log na sua localização.
- `K` para atacar/dar dano (precisa ter um inimigo selecionado).
- `W,A,S,D` para mover a camera.
- `Up,Down,Left,Righy` para rotacionar a camera.
- `Q,E` para também rotacionar a camera.


Eu acho que é isso por enquanto.

Sinta-se livre pra me mandar mensagem no discord: kunhah

