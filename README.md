# Athlete Performance Tracker / Controle de Desempenho de Atletas

This Python program allows you to track the performance of athletes in a series of games. It collects the athlete's name, the number of games they played, and the number of goals scored in each game. At the end, it prints a summary of the player's performance and allows you to view specific details of their games.

Este programa em Python permite que você acompanhe o desempenho de atletas em uma série de jogos. Ele coleta o nome do atleta, o número de jogos que ele jogou e os gols feitos em cada jogo. Ao final, exibe um resumo do desempenho do jogador e permite visualizar detalhes específicos de cada jogo.

## Features / Funcionalidades
- Allows you to input athlete information (name, games played, and goals scored). / Permite inserir informações do atleta (nome, jogos jogados e gols feitos).
- Displays a summary of all athletes and their performance. / Exibe um resumo do desempenho de todos os atletas.
- Lets you view detailed statistics for any athlete. / Permite visualizar as estatísticas detalhadas de qualquer atleta.

## Usage / Como Usar
1. Run the program. / Execute o programa.
2. Enter the athlete's name, the number of games they played, and the goals scored in each game. / Insira o nome do atleta, o número de jogos que ele jogou e os gols feitos em cada jogo.
3. After entering all the data, it will display a summary of the athletes' statistics. / Após inserir todos os dados, será exibido um resumo das estatísticas dos atletas.
4. You can query a specific athlete's statistics by entering their code (shown in the list). / Você pode consultar as estatísticas de um atleta específico inserindo o código (mostrado na lista).
5. To stop, enter `999`. / Para parar, insira `999`.

## Example / Exemplo
```bash
Athlete name: John Doe
How many games did John Doe play: 3
Goals scored in game 1: 2
Goals scored in game 2: 1
Goals scored in game 3: 3
Do you want to continue? [Y/N] Y

Athlete name: Jane Smith
How many games did Jane Smith play: 2
Goals scored in game 1: 4
Goals scored in game 2: 2
Do you want to continue? [Y/N] N

   cod name       goals                total
--------------------------------------------------
     1 John Doe    2, 1, 3              6
     2 Jane Smith  4, 2                 6

Show data of which player? [999 to stop] 1
 -- PLAYER STATS --
In game 1, scored 2 goals
In game 2, scored 1 goal
In game 3, scored 3 goals




Nome do atleta: João
Quantas partidas João jogou: 3
Gols feitos na partida 1: 2
Gols feitos na partida 2: 1
Gols feitos na partida 3: 3
Deseja continuar? [S/N] S

Nome do atleta: Maria
Quantas partidas Maria jogou: 2
Gols feitos na partida 1: 4
Gols feitos na partida 2: 2
Deseja continuar? [S/N] N

   cod nome       gols                total
--------------------------------------------------
     1 João       2, 1, 3              6
     2 Maria      4, 2                 6

Mostrar dados de qual jogador? [999 para parar] 1
 -- LEVANTAMENTO DOS JOGADORES --
No jogo 1, fez 2 gols
No jogo 2, fez 1 gol
No jogo 3, fez 3 gols

Requirements / Requisitos
Python 3.x / Python 3.x