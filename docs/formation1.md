# Ce document est utilisé pour former les collègues du lycée à l'utilisation de l'environnement Thonny / Python / modules "maison"

 1. Où se trouve le raccourci vers thonny

 2. Prise en main : 
qqs instructions dans le shell:
    3+4
print("hello world")

fichier .py : Hello world
bouton run et sauvegarde du fichier -> dans USER/python

3) qqs trucs sur python :
- variable -> affichage dans thonny ?
x = 4
y = x + 1
print(y)

- typage et ce que provoque l’absence de typage (3*’m’, ‘3’+’m’, 3+’m’) (comment lire les erreurs détaillées en rouge par python) 
- input / print
- retour sur les pb de typage : formule magique : ...=float(input(« ... »)) 

4) librairies :
- comment les appeler (deux façons : avec ou sans le « as ») 
Est-ce nécessaire d'indiquer les deux façons? On peut balancer " from truc import * " partout non?

- 2-3 exemples avec les librairies classiques (math.pi, math.sqrt…)
- 2-3 exemples avec les librairies « maison » (entree_tk pour répondre au probleme levé précédemment?
    

5) python avec les élèves : prise en main
- où les élèves doivent-ils enregistrer leur travail ?
- ctrl +/ crl molette pour zoomer
- le fait que la config est enregistrée automatiquement quand on quitte thonny
- view > variables
- debug et les différents types de « pas à pas »
- exemple de programme :

xA=input("Abscisse de A ? ")
yA=input("Ordonnée de A ? ")
xB=input("Abscisse de B ? ")
yB=input("Ordonnée de B ? ")
xM=(float(xA)+float(xB))/2
yM=(float(yA)+float(yB))/2
print("Coordonnées du milieu : ("+str(xM)+" ; "+str(yM)+")")

→ exo : le refaire et l’améliorer en ajoutant de quoi afficher la distance AB
→ on peut demander exactement la même chose à une classe à condition d’écrire au tableau la « formule magique »

6) un peu plus loin : 
- comment envoyer du code aux élèves ? / comment récupérer du code qu’ils ont fait ?
- comment peut-on (les élèves ou nous) télécharger thonny pour chez nous ?
- comment peut-on demander à ajouter une fonction dans les librairies ?

7) un ou deux autres exemples d’activités à faire avec les élèves.
traceur de courbes?
discriminant ?

8) un peu plus de python : listes, boucles
Les listes sont-elles nécessaires?
