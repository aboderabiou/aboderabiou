Corection des différents exercices du projet Command line Interface(CLI)
*Exercice n°1*
1) mkdir cli_tmp
2) touch cli_tmp/je_suis_dans_tmp.txt
3) cd cli_tmp
    touch in_cli_tmp
4) mkdir in_cli_tmp
5) rm -rf je_suis_dans_tmp.txt
6) rm -rf cli_tmp
7) mkdir grand_parent parent grand_frere grande_soeur ami connaissances
8) cd grand_frere
9) touch bachir
10) mv bachir ../ami
11) cd ..
        cp -r ami parent
12) rm -rf bob le dossier bob n'existe pas dans la listes des dossiers ce qui fait que lorsqu'on saisi la commande ça n'affiche pas d'erreur.
13) pwd on remarque qu'on est dans le dossier cli_tmp
14) cd ..
15) rm -rf cli_tmp

*Exercice n°2*
1) pwd 
        on remarque que nous somme dans l'acceuil
2) ls 
3) mkdir conteneur
4) on peut ne pas etre dans le dossier conteneur et créer tout les dossier en une seule commande
        mkdir conteneur/voitures ustensiles electronique
5) on peut egalement etre dans le home et exécuter la commande pour créer un fichier dans un sous dossier
        touch conteneur/voitures/mes_voitures.txt
6) cd conteneur/voitures
    echo "benz toyota honda" >mes_voitures.txt
7) cd ../ustensiles
8) touch cuisine.txt 
    echo "marmite casserol cuillère" >cuisine.txt
9) open cuisine.txt ou cat cuisine.txt 
        la premiere commande permet de l'ouvrir dans son éditeur par défaut par contre la seconde commande l'affiche directement dans le terminal
10) cd ..
    ls -at

*Exercice n°3*
1) pwd
2) ls 
3) mkdir actualites politiques
4) mkdir politiques/elections
5) cd politiques/elections
        touch candidats.txt
        echo "housein lourwana rabiou" >candidats.txt
6) cd ../../actualites
    mkdir buzz

*Exercice n°4*
1)pwd
2)touch .configuration
3)ls -a
4)mkdir creation crayons
5) touch crayons/couleurs.txt
6) cd crayons
        cp couleurs.txt colors.txt
7) cd ../creation
        touch gomme.txt
8) mv gomme.txt ../crayons
9) cd /
10) le chemin menant au dossier creation est: /User/rabiou/creation/

*Exercice n°5*
1) mkdir ma_classe
2) touch mes_camarades.txt
    echo "rabiou wahab souphiane omar hassia haoua ramatou imran adamou" >mes_camarades.txt
3) open mes_camarades.txt
4) touch .surveillant
5) ls -a
6) rm -rf .surveillant
7) rm -rf ma_classe

*Exercices n°6,7 et 8*
Pour faire les exercices suivants, il faudrait d'abord au préalable installé homebrew sur la machine a travers le terminal puis par la suite taper la commande: brew install "ce que l'on souhaite installer". Pour la suite il nous suffira d'installer asciiquarium, sl et cmatrix puis juste taper soit asciquarium, sl ou cmatrix pour voir afficher les animations.