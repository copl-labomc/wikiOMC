Guide Lumerical : 

Lumerical FDTD et DGTD sont des solveurs ?lectromagn?tiques de domaine de temps fini. Ils sont capables de r?soudre les ?quations de maxwell 3D, d?analyser l?interaction des rayons UV, visibles et IR avec des structures complexes.
La diff?rence principale entre les deux est que FDTD utilise un maillage rectiligne, tandis que DGTD utilise un maillage non structur? pour mod?liser la g?om?trie.
Ce guide concernera l?utilisation de FDTD. 

La d?marche ? suivre pour chaque simulation: 

1 - D?finir un mat?riau :
Cliquer sur le symbole correspondant dans la barre d'outil. Une fen?tre de base de donn?es de mat?riaux s'ouvre. On peut voir qu'elle contient notamment le nom et la couleur. En cliquant sur un mat?riau, on peut avoir acc?s ? ses caract?ristiques. On peut aussi ajouter notre propre mat?riau en cliquant sur ??add?? et en s?lectionnant le mat?riau souhait?.

2- Ajouter une structure :
Cliquer sur le symbole correspondant dans la barre d?outil. Des formes pr?d?finies sont d?j? disponibles. On peut modifier la forme en faisant un clic droit -> Edit object,  sur la structure dans la fen?tre ??objects tree??.  
Une fen?tre dՎdition appara?t dans laquelle on peut configurer la position ( x y z ) et  les dimensions de l?objet ( x y z span ) dans l?onglet G?ometrie. Dans l?onglet Mat?riau, on d?finit le mat?riau de notre structure. 
NB : Des g?om?tries plus complexes sont aussi disponibles en important des fichiers CAD dans le format GDS II ou STL. 

3 - D?finir les param?tres de simulation. 
Cliquer sur simulation dans la barre d?outil. Des outils de simulation pr?d?finis sont disponibles :  zone de traitement FDTD, maillage. On peut ?diter ces zones en faisant clic droit -> ??Edit Objects?? sur la simulation dans la fen?tre ??Objects Tree??. 
Une fen?tre dՎdition appara?t dans laquelle on peut configurer la dimension 2D ou 3D et le temps de simulation dans l?onglet g?n?ral. Dans l?onglet g?ometrie, on peut configurer la position et la dimension de la zone pour qu?elle s?ajuste ? la dimension de notre objet dՎtude. Dans l?onglet Mesh, on peut sp?cifier une maille plus fine pour avoir une meilleure r?solution ( attention tout de m?me car ?a demande ? l?ordinateur beaucoup de capacit? de m?moire ) 

4 - Ajouter une source de Lumi?re 
Cliquer sur source dans la barre d?outil, certaines pr?d?finies sont d?j? disponibles. Encore une fois, on fait clic droit -> ??Edits Objects?? sur la source dans la fen?tre ??Objects Tree??. 
Une fen?tre appara?t on peut configurer la forme, la direction et la polarisation de la source dans l?onglet g?n?ral. Dans l?onglet g?ometrie, on peut configurer la position et les dimensions de la source afin qu?elle couvre toute la zone de simulation. Dans l?onglet frequency / wavelength on peut choisir, comme son nom l?indique, la valeur de la longueur d?onde et de la fr?quence. 

5- Ajout d?un monitor

Sert ? enregistrer les r?sultats de la simulation. On peut choisir de capturer l?indice de r?fraction, des profils de la puissance de fr?quence, le spectre de transmission et on peut aussi faire une video de la simulation. 
Pour ?diter, clic droit -> Edits Objects sur le monitor dans la fen?tre ??Objects tree??.  
Une fen?tre appara?t on peut configurer l?orientation et la dimension de la zone de r?sultat. ll faut faire en sorte que le monitor soit dans la zone de simulation. 

6 - Lancer la simulation
Cliquer d?abord sur Check pour v?rifier que votre ordinateur dispose d?assez d?espace de stockage pour lancer la simulation. Si le fichier est trop lourd, une solution possible et d? agrandir les dimensions la maille, afin de baisser la r?solution. 
Cliquer sur Run. Une fen?tre s?affiche pour visualiser l?avancer de la simulation. 

7 - Analyser les r?sultats 
Pour voir les r?sultats des diff?rents composants, il faut cliquer sur le composant dans la fen?tre ??objects Tree?? puis dans la fen?tre ??Result view??, faire clic droit -> Visualize sur le r?sultat recherch?. Selon la composante choisie on obtient des r?sultats sous forme de courbe, d?image ou encore de vecteur. On peut aussi faire varier la valeur de certains param?tres dans l?onglet ??parameters?? et visualiser directement les changements par la m?me occasion.