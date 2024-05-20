# Auteurs du Projet :
Antonio CHIMARD  Noémie DESAILLY & Yannick DAI

# Nom du Jeu vidéo
Motor Up : Jeu de moto à deux joueurs

## Description & règle du Jeu:
Ce Jeu multijoueur (à deux joueurs) est représenté par deux écrans l'un pour le joueur 1 et l'autre pour le joueur 2 et le principe de celui-ci sera de faire tenir la moto en équilibre sur la roue arrière tout en effectuant des sauts pour éviter des obstacles qui apparaîtront sur la route de la moto.
La moto sera contrôlable par le joueur par des touches claviers (détaillé) dans une section (Commandes joueur).

<< Un joueur a perdu >>
- Premier cas : Lorsque sa moto à ses deux roues posées sur la route ou lorsque l'angle d'inclinaison de la moto par rapport au sol et supérieur à 90°
- Second cas : La moto du joueur entre en collision avec l'obstacle présente sur la route

Remarque : Lorsque l'inclinaison de la moto est critique, le jeu signale avec un avertissement "Warning !" et mettra la moto du joueur concerné d'une couleur pour indiquer qu'il est à la limite du Game Over.

<< But du Jeu >>
Faire le plus grand score, c'est-à-dire rester le plus longtemps dans la partie !

# Listes des bibliothèque nécessaire pour le projet :
<< Bibliothèque SFML >>  
Ligne de commande à entrer dans le terminal (sous Ubuntu ou Debian) :
    apt install libsfml-dev


# Mise en marche :
<< Compilation >>  
Ligne de commande à entrer dans le terminal :
    make
<< Exécution >>
Ligne de commande à entrer dans le terminal :
	 ./game


# Commandes joueur :
<< Commandes : >>
Joueur 1 :
    Touche q : Incliner la moto vers l’arrière (sur la roue arrière)
    Touche d : Incliner la moto vers l’avant (sur la roue arrière)
    Touche Espace : Effectuer un saut
             		 
Joueur 2 :
    Touche flèche de gauche : Incliner la moto vers l’arrière (sur la roue arrière)
    Touche flèche de droite : Incliner la moto vers l’avant (sur la roue arrière)
    Touche Entrée : Effectuer un saut

# Source
<< Musique de fond >>
https://pixabay.com/fr/music/search/bike/?genre=jeux%2520vid%25C3%25A9o
Heavy Rock Attack - 1 minute edit
Abydos_Music

# Fichier test.cpp
<< Compilation >>  
Ligne de commande à entrer dans le terminal :
    ./cmd.sh
<< Exécution >>
Ligne de commande à entrer dans le terminal :
	 ./tests_methodes_classes 