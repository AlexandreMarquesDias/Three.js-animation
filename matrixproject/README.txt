Contrôles :
_______________________________
1 : pose 1 
2 : pose 2
3 : pose 3 
4 : pose 4 (neutral pose)
5 : The REAL matrix :p
6 : hide robot
7 : show robot
8 : hide human
9 : show human
0 : animation de course
_______________________________

Tentatives pour le skinning :
image 1 : ici, dans init je fais l'inverse des matrices initiales des cylindres.
image 2 : ici, je calcule Tj = Mj' Mj^-1, pour ensuite l'envoyer, avec buildShaderBoneMatrix(), à l'équation principale dans le vertex shader
image 3 : ici j'applique l'équation du linear blen skinning : je fais la sommation des multiplication de chaque Weight(Wj) avec chaque Bones(Tj), puis je multiplie par la position
Malheureusement je n'ai pas été capable de bien skin au complet mon personnage, j'ai tout de même essayé d'appliquer le plus que possible ce que j'ai compris du LBS.

Bonus content :
-pose 3 (il s'accroche au plancher)
-deuxième animation avec mouvement de caméra cinématique et aussi avec des objets supplémentaires

