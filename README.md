# 1V1-PIERRE-FEUILLES-CISEAUX ON BASE HERE / 0xEF70121033807Db293f2645fE517568cC95910B9

Inscription : Les joueurs TRUMP et POUTINE s'inscrivent en appelant inscrireTrump() et inscrirePoutine().

Choix des joueurs : Chaque joueur choisit entre "pierre", "feuille" ou "ciseaux" en appelant faiteVotreChoix(<choix>) avec la réponse correcte en minuscule.

Résolution : Le jeu détermine le gagnant en comparant les choix des joueurs.

Égalité : Si les choix sont identiques, les joueurs refont leurs choix.

Fin du jeu : Le gagnant est annoncé et le jeu se termine. Vous pouvez recommencer avec reinitialiserJeu() si vous le souhaitez.


Pour suivre le jeu via les logs (événements), voici ce que vous devez savoir :

Logs des choix des joueurs : Lorsque chaque joueur fait son choix, un événement est émis pour l’informer de son choix et de l’état du jeu. Vous verrez des messages comme :

"TRUMP, vous êtes le Joueur 1. Faites votre choix: pierre, feuille ou ciseaux."
"POUTINE, vous êtes le Joueur 2. Faites votre choix: pierre, feuille ou ciseaux."
Log du résultat de la partie : Après chaque tour, vous pouvez suivre l’évolution avec des messages comme :

"Duel engagé entre TRUMP et POUTINE."
"Le gagnant est TRUMP." ou "Il y a une égalité ! Refaites vos choix."
Fin de la partie : Lorsque la partie se termine, un message final est logué pour annoncer le résultat :

"Le gagnant est TRUMP."
"Le jeu est terminé. Merci d'avoir joué !"

Registration: The players TRUMP and POUTINE register by calling inscrireTrump() and inscrirePoutine().

Choice of players: Each player chooses between "pierre", "feuille", or "ciseaux" by calling faiteVotreChoix() with the correct answer in lowercase.

Resolution: The game determines the winner by comparing the players' choices.

Tie: If the choices are identical, the players make their choices again.

End of game: The winner is announced, and the game ends. You can restart the game by calling reinitialiserJeu() if you wish.

To track the game via logs (events), here's what you need to know:

Logs of players' choices: When each player makes their choice, an event is emitted to inform them of their choice and the game state. You'll see messages like:

"TRUMP, you are Player 1. Make your choice: pierre, feuille, or ciseaux." "POUTINE, you are Player 2. Make your choice:pierre, feuille, or ciseaux."

Log of the game result: After each round, you can follow the evolution with messages like:

"A duel has started between TRUMP and POUTINE." "The winner is TRUMP." or "There is a tie! Please make your choices again."

End of game: When the game ends, a final message is logged to announce the result:

"The winner is TRUMP." "The game is over. Thank you for playing!"







