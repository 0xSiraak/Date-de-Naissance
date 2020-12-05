# Date-de-Naissance
Un petit TP (en python) que j'ai eu à faire en cours afin de retrouver son jour de naissance (lundi, mardi, etc...) avec sa date de naissance

Le code est entièrement fait pa moi hormis la formule de calcul : "`(j + code_mois[m-1] + (a+a//4) - int(m<=2) * bisextile) % 7 # calcul afin de trouver le jour`", qui était donné dans l'énoncé de mon devoir

Le script a été uniquement testé avec la version 3.7.4 de Python et pour l'utiliser vous aurez besoin de la librairie "sys".<br/>Pour l'éxécuter : python3 date.py 01/01/2001
