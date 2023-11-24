Exercice sur la visualisation de données

1/ Charger le jeu de donnée
2/ Changer le type de 'nombre de séance' de texte à numérique
3/ Dans la colonne poste, filtrer uniquement les valeurs LAT, ATT, M, DC
4/ Splitter la colonne 'Semaine' en trois colonne
    - une col 'sem' contenenant le 'sem'
    - une col 'num sem' contenant le numero de la semaine
    - une col 'année semaine' contenant l'année de la semaine
5/ supprimer la colonne 'sem'
6/ Créer une nouvelle colonne 'HID 15' qui corespond à
    - la somme de 'Distance z3', 'Distance z4' et 'Distance z5'
7/ Créer une nouvelle collone conditionnel 'is_week_end' qui verifie
    la condition suivante: si la ligne de la colonne 'Jour' est
    un samedi ou dimanche alors écrire 'oui' sinon ecrire 'non'

GRAPHIQUE 1:
SCATTER PLOT:
    X: Dist
    Y: HID16
    Couleur: Poste
Ajouter une mediane pour HID16 et Dist
Inserer un carré vers transparent au dessus des deux mediane
Inserer un carré rouge transparent en dessous des deux mediane
Inserer une slider de zoom

GRAPHIQUE 2:
LONGITUDINAL:
Créer un graphique du suivi de la distance moyenne
parcourue par match (Period Name = nom du match)

GRAPHIQUE 3:
Fréquence:
Créer un graphique pour exprimer la fréquence
de distribution des valeurs pour les postes

GRAPHIQUE 4:
Créer un tableau dynamique permettant de mettre les colonnes suivante:
- Dist, HID 16, HID 21, Sup 24 (moyenne)
- Le tableau est dynamique sur deux étages: poste et jour de la semaine
- Inserer une mise en forme conditionnelle sur l'arrière plan pour la Dist
- Inserer une barre d'objectif par rapport à la valeur max pour HID21
- Colorer l'arriere plan de la colonne HID 16 en vert clair
- Faire une mise en forme pour sup 24 en affichant un bouton
rouge pour la valeur superieur a 150

