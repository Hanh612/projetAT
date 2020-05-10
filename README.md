# projetAT
# écrivez les fonctions capablesbde calculer
# les variantes d'un TF-IDF
forum os import TF-IDF
from sklearn.feature_extraction.text import Calculerlesvariantes
import numpy as np
import pandas as pd
sentences = Calculerlesvariantes()
with open("!") as file:
    for line in file:
        if lesvariants = 0,5 + 0,5 x f(t,d)/max(t'€d) f(t'd)


#créer un classe index_inverse en python
class index_inverse
    def_init_(self)
    print("constructeur de la classe index_inverse")
    def __init__(self, data)
#Iterator for looping over a sequence backwards.
        self.data = data
        self.index = len(data)

#Créer un serveur web en python
import cherrypy

class MonSiteWeb():           #classe maitresse de l'application
      def index(self):        #méthode invoquée comme URL racine (/)
         index.exposed = True    #la méthode doit être publiée

import bottle
import datetime

@bottle.route("/time")
@bottle.view("page.tpl")
def index() :
    heure = datetime.datetime.now().strftime("<p>Nous sommes le %d/%m/%Y, il est %H:%M:%S</p>")
    return {"title":"Horloge", "body" : heure}

@bottle.route("/menu")
@bottle.view("page.tpl")
def menu() :
    stri = """<ul>
    <li><a href='/action/temp'>Température</a></li>
    <li><a href='/action/pluie'>Pluie</a></li>
    </ul>
    """
    return {"title":"Site Météo", "body" : stri}


#Écrire une fonction recherche les 10 premières pages qui maximisent le score pour ces mots clés
#On import le module time en tant que t
import time as t

t.ctime()
time.ctime()

compteur = 0
#On commence par une boucle infinie
while True:
    compteur += 1
    print(compteur, end = '')

#Quand le compteur vaut 10, on sort de la boucle
    if compteur >= 10:
        break
 avancer(x, y)
    lancerPouvoirMagique(enemieProche)

#	Charger les documents dans l'index
import xlrd
import matplotlib.pyplot as plt

document = xlrd.open_workbook("document_excel.xlsx")

print("Nombre de feuilles: "+str(document.nsheets))
print("Noms des feuilles: "+str(document.sheet_names()))

feuille_1 = document.sheet_by_index(0)
feuille_1 = document.sheet_by_name("Fonction 1")

print("Format de la feuille 1:")
print("Nom: "+str(feuille_1.name))
print("Nombre de lignes: "+str(feuille_1.nrows))
print("Nombre de colonnes: "+str(feuille_1.ncols))

cols = feuille_1.ncols
rows = feuille_1.nrows

X = []
Y= []

for r in range(1, rows):
    X += [feuille_1.cell_value(rowx=r, colx=0)]
    Y += [feuille_1.cell_value(rowx=r, colx=1)]

plt.plot(X, Y)
plt.show()

#Écrire une fonction qui supprime les pages trop similaires dans l'index pour n'en garder qu'une seule
maListe = range(5)
print maListe
Résultat : [0, 1, 2, 3, 4, 5]
del maListe[2]
print maListe
Résultat : [0, 1, 3, 4, 5]
Le mot-clé del peut également supprimer plusieurs éléments à la suite dans une liste. Il faut pour cela indiquer l'index le plus petit, suivi du caractère :, puis l'index le plus grand (celui-là ne sera pas compté dans la suppression).
del maListe[1:3]
print maListe
Résultat : [0, 4, 5]
Si l'on indique uniquement le caractère :, alors le contenu entier de la liste est supprimé.
del maListe[:]
print maListe
Résultat : []
