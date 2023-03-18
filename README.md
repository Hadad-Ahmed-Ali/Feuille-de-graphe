
# Analyse de la centralité des noeuds

On veut faire un programme qui étant donné un graphe retourne une analyse de la centralité des sommets
du graphe en termes de degré, d'eccentricité, de centralité de proximité et de centralité d'intermédiarité.

Un script centralite.py qui accepte des arguments. Notre programme prendra en entrée un fichier CSV contenant 
les listes d'adjacences définissant un graphe. Notre programme devra afficher les n(=5 par defaut) sommets les 
plus centraux suivant les critères suivant:

       * les plus haut degrés
       * les plus petites excentricités
       * les plus grandes centralité de proximité
       * les plus grandes centralité d'intemédiarité

Notre programme devra également créer des fichiers:

       * degres.csv
       * excentricites.csv
       * cproximites.csv 
       * intermediarites.csv

avec les statistiques correspondantes pour chacun des sommets, triés du plus central au moins central et par 
ordre lexicographique.

# Plan

      I- Création du script
      II- Algorithme de récupération des fichier csv
      III- Algorithmes de mesure de la centralité
           1) Degrés des chaque neouds du graphes
           2) Excentricités de chaque sommets
           3) Centralité de proximité
           4) Centralité d'intemédiarité
      IV- Création des fichier csv
      V-  La sortie du scripte

# Noté bien:

Tous les implémentations ci-dessous doivent être mise dans un même bloc de code pas des différentes bloque comme
je le fais. J'ai repartie les implémentation en bloc pour explicité les différentes partie et travail abordés 
tout au long du travail. Après ça, téléchargé le fichier en extension .py et vous pouvez l’utiliser en l’appelant
le scripte sur un terminal suivit d'un fichier csv qui définit le graphe qu'on veut étudier.
