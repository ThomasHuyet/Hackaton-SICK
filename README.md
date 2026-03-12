# Vision Blackjack AI

Projet réalisé lors d’un hackathon combinant **vision industrielle**, **Python** et **stratégie Blackjack**.

Le système observe une vraie table de Blackjack filmée par une caméra (SICK Nova), récupère les cartes détectées et reproduit la partie dans une interface graphique qui aide les joueurs à prendre la décision optimale.

## Principe du projet

1. Une caméra filme une table de Blackjack réelle.
2. Le système de vision détecte les cartes.
3. Les valeurs sont envoyées à l'application Python via socket.
4. L'interface graphique reconstruit la partie.
5. Une stratégie Blackjack recommande **Hit** ou **Stay**.

## Interface

L'interface est développée en **Python avec Tkinter**.

Elle permet de :

- démarrer une partie
- tirer une carte (Hit)
- passer son tour (Stay)
- visualiser les cartes et les scores
- afficher la recommandation stratégique

## Technologies utilisées

- Python
- Tkinter
- Socket TCP
- Vision industrielle SICK Nova

## Structure du projet

- **BlackjackApp.py** : interface graphique et gestion du jeu
- **Connection.py** : communication avec le système de vision
- **GameState.py** : gestion de l'état de la partie
- **BlackJackStrategy.py** : stratégie Blackjack
- **test_blackjack.py** : tests de la logique

## Lancer le projet
python src/BlackjackApp.py
