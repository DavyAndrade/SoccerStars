# Soccer Stars

A ideia é, ambos os jogadores possuem escolhas (Chute, Drible, Passe, Bloqueio, Desarme e Interceptação) que podem ser feitas num campo dividido em 5 partes. Para esse exemplo, vou usar:

- Grande Área Defensiva (GAD)
- Meio-Campo Defensivo (MCD)
- Meio-Campo Central (MCC)
- Meio-Campo Ofensivo (MCO)
- Grande Área Ofensiva (GAO)

O jogo começa no meio-campo, onde o jogador com a posse apenas pode fazer duas escolhas: Passe ou Drible

O oponente, ás cegas (da escolha do adversário) deve escolher entre Interceptação ou Desarme. Se escolher a opção certa, o oponente recupera a posse e o turno continua na zona que ocorreu o confronto. Isso é, se eu roubei a bola no meio-campo, o róximo turno vai ser no meio-campo.

Se o oponente errar a escolha, avança para a próxima zona.

## Zonas e Escolhas

Passe - Todas as áreas
Drible - Todas as áreas
Chute - Apenas MCO e GAO

Interceptação - Todas as áreas
Desarme - Todas as áreas
Bloqueio - MCD e GAD

Se o jogador com a posse chutar ao gol e o oponente não bloquear, a bola vai ao gol, onde o jogador que chutou deve escolher o canto em que chutou assim como o goleiro deve escolher um canto para defender (Esquerda, Meio, Direita). Se o goleiro acertar o canto, defendeu, senão, gol.

Se o jogador com a posse passar pela última zona com passe/drible (o que significa que passou por todos os defensores), resta apenas chutar ao gol.
