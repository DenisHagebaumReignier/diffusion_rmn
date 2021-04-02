
# diffusion_rmn
Le fichier python ellipsoid.py permet de calculer les rayons a,b,c de l'ellipsoïde contenant la molécule.

Pour calculer ces trois valeurs, il vous faut un fichier contenant les coordonnées xyz de votre molécule dont la géométrie aura été optimisée.
Un tel fichier pour la molécule H2CO ce présente sous cette forme (h2co.xyz) :

4
H2CO
O     0.0000000    0.0000000    1.1932490 
C     0.0000000    0.0000000   -0.0058437 
H    -0.9390560    0.0000000   -0.5937026 
H     0.9390560    0.0000000   -0.5937026 

La première ligne contient le nombre d'atomes
La seconde ligne est un titre quelconque
Les lignes suivantes sont de la forme : Type_atome X Y Z
Type_atome : symbole chimique de l'atome
X, Y, Z : coordonnées cartésiennes de l'atome

Pour lancer le script python ellipsoid.py sur le fichier h2co.xyz, il suffit de taper la commande :
run ellipsoid.py h2co.xyz
