# Vision Blackjack AI

Projet réalisé dans le cadre d'un hackathon étudiant utilisant la vision industrielle et l'IA pour assister un joueur de Blackjack.

Le système utilise une caméra SICK Nova pour détecter les cartes d'une vraie table de Blackjack et une interface Python pour visualiser la partie et fournir une recommandation stratégique optimale.

---

# Objectif du projet

Créer un assistant Blackjack capable de :

- détecter les cartes sur une vraie table
- récupérer les valeurs via un flux réseau (socket)
- afficher les cartes dans une interface graphique
- calculer les scores des joueurs
- recommander l'action optimale (Hit / Stay) selon la stratégie Blackjack

---

# Architecture du projet

Le projet est divisé en plusieurs modules.
