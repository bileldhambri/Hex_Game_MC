# Hex Game

Hex est un jeu de plateau conçu pour deux joueurs, où l'objectif est de relier les côtés opposés d'une grille hexagonale. Bien que les règles soient simples, le jeu offre une complexité impressionnante, avec plus de cinq milliards de positions possibles sur un plateau de 11x11, soit considérablement plus que pour les échecs. La profondeur stratégique élevée de Hex rend le jeu extrêmement difficile à résoudre pour les ordinateurs, principalement en raison de la complexité de la topologie de la grille hexagonale, qui rend difficile la création d'algorithmes efficaces pour analyser et résoudre le jeu. C'est pourquoi Hex est souvent considéré comme un véritable défi pour les chercheurs en intelligence artificielle et en informatique, qui cherchent à développer de nouvelles approches pour aborder les problèmes complexes de ce genre. En fin de compte, Hex est un jeu de société passionnant et stimulant, qui offre un défi à la fois pour les débutants et les joueurs chevronnés.

## Démarrer une partie

```bash
$ ./main.py player1_type player2_type board_size
```
Exemple

```bash
$ ./main.py h mc 11
```
*player1_type1*/*player1_type2* : 'h' pour le joueur humain et'mc','uct'... pour l'IA, correspondent à la méthode implémentée. 
*board_size* : 7 ou 11

## Équipe
Ce projet a été développé par Dhambri Bilel et Guetif Amen Allah dans le cadre d'un projet académique.