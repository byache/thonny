# Formation technique.

*Ce document est utilisé pour former les collègues du lycée à l'utilisation de l'environnement Thonny / Python / modules "maison"*

## 1. Où se trouve le raccourci vers thonny

Démarrer > Programmes > \_Maths > Raccourcis maths > Thonny python

## 2. Prise en main : 
Quand on lance Thonny, il y a deux zones : 
![](https://thonny.org/img/get_started.png)
 - la zone du haut où on travaille dans un fichier, qui peut être exécuté quand on le demande, et qui peut être enregistré (sur cette image, le fichier s'appelle "Hell.py") 
 - la zone du bas qui est un **shell** : comme un écran de calculatrice, mais qui exécute des commandes Python (on ne peut pas l'enregistrer)(c'est dans cette zone qu'apparaissent les résultats des commandes exécutées depuis un fichier de la zone du haut)
 
### Quelques instructions à essayer dans le shell :
```python
3+4
print("hello world")
"hello"+"world"
```
### Quelques exemples à enregistrer dans un fichier :
```python
3+4
print("hello world")
"hello"+"world"
```
Pour exécuter le fichier, il faut cliquer sur le bouton **run** (un triangle blanc dans un disque vert).
Il faut donner un nom au fichier. Le fichier sera sauvegardé par défaut dans : `USER/python`

## 3. Quelques trucs sur python :
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
