# ✔️ France ioi Correction Python
Corrected exercise from france ioi python.

<div align="center">
  <picture>
    <img src="https://www.france-ioi.org/dataSite/img/logo.png" alt="france_ioi_logo">
  </picture>
</div>

<br/>

## 📋 Table of Contents

- [✧ LEVEL 1 ✧](#Level_1)
  - [Level 1-1 – Text display, sequence of instructions](#1-1)
  - [Level 1-2 – Repetitions of instructions](#1-2)
  - [Level 1-3 – Calculations and discovery of variables](#1-3)
  - [Level 1-4 – Reading the entry](#1-4)
  - [Level 1-5 – Tests and requirements](#1-5)
  - [Level 1-6 – Advanced structures](#1-6)
  - [Level 1-7 – Advanced conditions, Boolean operators](#1-7)
  - [Level 1-8 – Conditioned repetitions](#1-8)

<a id="Level_1"></a>

# [LEVEL 1](#Level_1)

<a id="1-1"></a>

## [1 – Text display, sequence of instructions](1-1)
<ul>
  <li> <b> 1) Hello world! </b> </li>
  
```
print("Hello world!")
```
  <li> <b> 2) Presentation </b> </li>
  
```
print("Coucou !")
print("Je m'appelle Camthalion")
print("Ma devise est 'Parler peu mais parler bien'.")
```
  
  <li> <b> 3) Map of the mountain </b> </li>
  
```
print("Tout droit tu grimperas,")
print("La clé tu trouveras,")
print("Habile tu seras,")
print("Quand tu les porteras,")
print("Et avec le chef tu reviendras !")
```
  <li> <b> 4) In the thicket </b> </li>
  
```
from robot import *
haut()
haut()
haut()
droite()
droite()
bas()
bas()
droite()
```
  <li> <b> 5) Stack of cylinders </b> </li>
  
```
deplacer(1, 3)
deplacer(1, 2)
deplacer(3, 2)
deplacer(1, 3)
deplacer(2, 3)
deplacer(2, 1)
deplacer(3, 2)
deplacer(1, 3)
deplacer(2, 3)
deplacer(1, 2)
deplacer(3, 1)
deplacer(3, 2)
deplacer(1, 3)
deplacer(2, 1)
deplacer(3, 1)
deplacer(3, 2)
deplacer(1, 2)
deplacer(1, 3)
deplacer(2, 3)
deplacer(2, 1)
deplacer(3, 2)
deplacer(3, 1)
deplacer(2, 1)
deplacer(2, 3)
deplacer(1, 2)
deplacer(1, 3)
deplacer(2, 3)
deplacer(1, 2)
deplacer(3, 2)
deplacer(3, 1)
deplacer(2, 1)
deplacer(2, 3)
deplacer(1, 2)
deplacer(1, 3)
deplacer(2, 3)
```
  <li> <b> 6) Secret recipe </b> </li>
  
```
from robot import *

remplir(5)
transferer(5, 3)
vider(3)
transferer(5, 3)
remplir(5)
transferer(5, 3)
```
</ul>

<a id="1-2"></a>

## [2 – Repetitions of instructions](#1-2)
<ul>
  <li> <b> 1) Punishment </b> </li>
  
```
for i in range(135):
   print("Je dois respecter le Grand Sorcier.")
```
  <li> <b> 2) Basic math </b> </li>

```
for loop in range(13):
   print("9 * 8 = 72")
```
  <li> <b> 3) Water transportation </b> </li>
  
```
from robot import *

gauche()
gauche()
print("Bonjour, laissez-moi vous aider")
ramasser()
for loop in range(32):
   droite()
deposer()
```
  <li> <b> 4) The secret of Goma </b> </li>

```
from robot import *

for loop in range(15):
   droite()
   ramasser()
droite()
deposer()
```
  <li> <b> 5) Sisyphus </b> </li>
  
```
from robot import *

for loop in range(21):
   haut()
   droite()
for loop in range(21):
   gauche()
   bas()
```
  <li> <b> 6) Writing page </b> </li>
  
```
for i in range(30):
   print("a_", end = "")
print()
for i in range(30):
   print("b_", end = "")
print()
for i in range(30):
   print("c_", end = "")
```
  <li> <b> 7) Checkers game </b> </li>
  
```
for loop in range(20):
   for loop in range(20):
      print("OX", end = "")
   print()
   for loop in range(20):
      print("XO", end="")
   print()
```
  <li> <b> 8) Mount Kailash </b> </li>
  
```
for loop in range(20):
   for loop in range(20):
      print("OX", end = "")
   print()
   for loop in range(20):
      print("XO", end="")
   print()
```
  <li> <b> 9) Harvest </b> </li>
    
```
from robot import *

for loop in range(20):
   for rammaser in range(1):
      ramasser()
   for pas_droite in range(15):
      droite()
   for deposer_raisain in range(1):
      deposer()
   for pas_gauche in range(15):
      gauche()
   
```
  <li> <b> 10) The Big Event </b> </li>
  
```
from robot import *

for loop in range(9):
   haut()
droite()

for howcompt in range(4):
   for b in range(8):
      bas()
   for d in range(1):
      droite()
   for h in range(8):
      haut()
   for d in range(1):
      droite()
for b in range(9):
   bas()
for finish in range(9):
   gauche()
```
</ul>

<a id="1-3"></a>

## [3 – Calculations and discovery of variables](#1-3)

<ul>
  <li> <b> 1) Answer! </b> </li>
  
```
print(42)
```
  <li> <b> 2) The eclipse </b> </li>
  
```
print(12581 - 11937)
```
  <li> <b> 3) Candy for everyone! </b> </li>
  
```
print((25 + 30 + 27 + 22 - 8) * 3) 
```
  <li> <b> 4) Algoreathlon </b> </li>
  
```
a = 2
b = 34
c = 6

print((a + b + c), end =" ")
print((a + b + c) * 2, end =" ")
print((a + b + c) * 3, end =" ")
```
  <li> <b> 5) Playground </b> </li>
  
```
c = 108

print(c * 108)
print(c * 4)
```
  <li> <b> 6) A game of hide and seek </b> </li>
  
```
for loop in range(100):
   print(loop + 1)
print("J'arrive !")
```
  <li> <b> 7) Progress by error </b> </li>
  
```
print("V")
print("V")
print("I")
print("I")
print("V")
print("I")
print("I")
```
  <li> <b> 8) Rocket take off </b> </li>
  
```
for comptage in range(100,-1,-1):
   print(comptage)
print("Décollage !")
```
  <li> <b> 9) Invasion of batrachians </b> </li>
  
```
crapauds = 1337

for loop in range(12):
   crapauds = crapauds * 2
print(crapauds)
```
  <li> <b> 10) Fair </b> </li>
  
```
tir = 1
bonbon = 0

for loop in range(50):
   bonbon = bonbon + tir
   print(bonbon)
   tir = tir + 1

```
  <li> <b> 11) Race with the kids </b> </li>
  
```
from robot import *

i = 1               # compteur.
n = 1    
           # nombre de fois gauche/droite.
while i < 11:         # boucle (while) tourne 10 fois.
   for y in range(n):
      droite()
   for e in range(1):
      ramasser()
   for y in range(n):
      gauche()
   for e in range(1):
      deposer()

   n += 1
   i += 1
```
  <li> <b> 12) Construction of a pyramid </b> </li>
  
```
c = 0

for i in range(1):
   c = 17**3
   c = c + 15**3
   c = c + 13**3 
   c = c + 11**3
   c = c + 9**3
   c = c + 7**3
   c = c + 5**3
   c = c + 3**3
   c = c + 1**3
print(c)
```
  <li> <b> 13) Multiplication table </b> </li>
  
```
for j in range(1, 21):
   for c in range(1, 21):
      print(j * c, end= ' ')
   print()
```
</ul>

<a id="1-4"></a>

## [4 – Reading the entry](#1-4)

<ul> 

  <li> <b> 1) Harvests </b> </li>
  
```
lg = int(input(""))

mc = 23 * lg * lg
print(mc)     
```
  <li> <b> 2) Spiritual retreat </b> </li>
  
```
jours = int(input())
nombreH = jours * 16
nombreM = nombreH * 60
nombreS = nombreM * 60
print (nombreS)
```
  <li> <b> 3) Age of grandchildren </b> </li>
  
```
ageCadet = int(input())

ageAine = int(input())

difference = ageAine - ageCadet

print(difference)
```
  <li> <b> 4) More punishments </b> </li>
  
```
x = int(input())
for i in range(x):
    print("Je dois suivre en cours")
```
  <li> <b> 5) Graduation of thermometers </b> </li>
  
```
tempMin = int(input())
tempMax = int(input())
for i in range(tempMin, tempMax+1):
    print(i)
```
  <li> <b> 6) Mental math game </b> </li>
  
```
tempMin = int(input())
tempMax = int(input())
for i in range(tempMin, tempMax+1):
    print(i)
```
  <li> <b> 7) The Great Sale </b> </li>
  
```
positionDepart = int(input())
largeurEmplacement = int(input())
nbVendeurs = int(input())

for i in range(nbVendeurs + 1):
    print(positionDepart + largeurEmplacement * i)
```
  <li> <b> 8) Livestock </b> </li>

```
nbkarvas = 0
for i in range(20):
    nbkarvas = nbkarvas + int(input())
print(nbkarvas)
```
  <li> <b> 9) Pedestals for statues </b> </li>
  
```
socle = 0
largeursol = int(input())
largeurface = int(input())

for i in range(largeurface, largeursol + 1):
    etage = i * i
    socle += etage

print(socle)
```
  <li> <b> 10) The most beautiful Karva </b> </li>
  
```
nbkarvascomp = int(input()) # nombres de karvas

for i in range(nbkarvascomp): # 
   poinds = int(input())
   age = int(input())
   long_des_cornes = int(input())
   hauteur_au_garot = int(input())
   print(long_des_cornes * hauteur_au_garot + poinds)
```
</ul>

<a id="1-5"></a>

## [5 – Tests and requirements](#1-5)

<ul>
  <li> <b> 1) Baggage transportation </b> </li>
  
```
nbpaquets = int(input())
poids_paquets = int(input())
poids_total = nbpaquets * poids_paquets

if  poids_total > 105:
   print("Surcharge ! ")
```
  <li> <b> 2) Kilometer markers </b> </li>
  
```
debutnombre = int(input())
finnombre = int(input())

if finnombre - debutnombre >= 0:
   print(finnombre - debutnombre)
elif debutnombre - finnombre >= 0:
   print(debutnombre - finnombre)
```
  <li> <b> 3) Decreasing prices </b> </li>
  
```
heure_arrivé = int(input())

list_prix = [10, 15, 20, 25, 30, 35, 40, 45, 50, 53, 53, 53, 53]

if heure_arrivé == heure_arrivé:
   print(list_prix[heure_arrivé])
```
  <li> <b> 4) All-out brawl </b> </li>
  
```
supArignon = int(input())
supEvaran = int(input())

if supArignon - supEvaran > 10:
   print("La famille Arignon a un champ trop grand")
elif supEvaran - supArignon > 10:
   print("La famille Evaran a un champ trop grand")
```
  <li> <b> 5) Boat price </b> </li>
  
```
age_personne = int(input())

if age_personne >= 21:
   print("Tarif plein") 
elif age_personne < 21:
   print("Tarif réduit")
```
  <li> <b> 6) Crossing the bridge </b> </li>
  
```
de_1 = int(input())
de_2 = int(input())

somme_de = de_1 + de_2

if somme_de >= 10:
   print("Taxe spéciale !")
   print(36)
else:
   print("Taxe régulière")
   print(de_1 * 2 + de_2 * 2)
```
  <li> <b> 7) Tug of war contest </b> </li>
  
```
nbMembres = int(input())

equipe_1 = 0
equipe_2 = 0

for i in range(nbMembres):
    equipe_1 += int(input())
    equipe_2 += int(input())

if equipe_1 > equipe_2:
    print("L'équipe 1 a un avantage")
else:
    print("L'équipe 2 a un avantage")
print("Poids total pour l'équipe 1 :", equipe_1)
print("Poids total pour l'équipe 2 :", equipe_2)
```
  <li> <b> 8) Village password </b> </li>
  
```
secre_code = int(input())

if secre_code == 64741:
    print("Bon festin !")

if secre_code != 64741:
    print("Allez-vous en !")
```

</ul>

<a id="1-6"></a>

## [6 – Advanced structures](#1-6)

<ul>
  
  <li> <b> 1) Towns and villages </b> </li>
  
```
nblieux = int(input())
villes = 0

for i in range(nblieux):
    nbpopulation = int(input())
    if nbpopulation > 10000:
        villes += 1
print(villes)
```
  <li> <b> 2) Schedule for the day </b> </li>
  
```
posactuelle = int(input())
nbvillages = int(input())
villagesproche = 0

for i in range(nbvillages):
    posvillages = int(input())
    distance = posactuelle - posvillages
    if  abs(distance) <= 50:
        villagesproche += 1
print(villagesproche)
```
  <li> <b> 3) Longest stage </b> </li>
  
```
nbjourdemarche = (int(input()))
maxdistance = 0

for i in range(nbjourdemarche):
    distanceparcouru = int(input())
    if maxdistance < distanceparcouru:
        maxdistance = distanceparcouru
        
print(maxdistance)
```
  <li> <b> 4) Calculation of height differences </b> </li>
  
```
nbmonte_descend = int(input())
variation_altitude_descente = 0
variation_altitude_descente_pos = 0
variation_altitude_montante = 0

for i in range(nbmonte_descend):
    variation_altitude = int(input())
    if variation_altitude > 0:
        variation_altitude_montante += variation_altitude
    elif variation_altitude < 0:
        variation_altitude_descente += variation_altitude
        variation_altitude_descente_pos = abs(variation_altitude_descente)

print(variation_altitude_montante)
print(variation_altitude_descente_pos)
```
  <li> <b> 5) Type of trees </b> </li>
  
```
hauteur = int(input())
nbfolioles = int(input())

if hauteur <= 5 and nbfolioles >= 8:
    print("Tinuviel")
elif hauteur >= 10 and nbfolioles >= 10:
    print("Calaelen")
elif hauteur <= 8 and nbfolioles <= 5:
    print("Falarion")
elif  hauteur >= 12 and nbfolioles <= 7:
    print("Dorthonion")
```
  <li> <b> 6) Hostel prices </b> </li>
  
```
age = int(input())
poid = int(input())

if age == 60:
    print(0)
elif age < 10:
    print(5)
else:
    if poid >= 20:
        print(30 + 10)
    else: 
        print(30)
```
  <li> <b> 7) Protection of the village </b> </li>
  
```
nbmaisons = int(input())
pos_x_min = 1000000
pos_y_min = 1000000
pos_x_max = 0
pos_y_max = 0

for i in range(nbmaisons):
    pos_x = int(input())
    pos_y = int(input())
    if pos_x < pos_x_min:
        pos_x_min = pos_x
    if pos_x > pos_x_max:
        pos_x_max = pos_x

    if pos_y < pos_y_min:
        pos_y_min = pos_y
    if pos_y > pos_y_max:
        pos_y_max = pos_y

print(2 * (pos_x_max - pos_x_min + pos_y_max - pos_y_min))
```
  <li> <b> 8) The right price </b> </li>
  
```
nbMarchands = int(input())
minPrix = 1000 * 1000
posMinPrix = -1
pos = 1
for loop in range(nbMarchands):
   prix = int(input())
   if prix <= minPrix:
      minPrix = prix
      posMinPrix = pos
   pos = pos + 1
print(posMinPrix)
```

</ul>

<a id="1-7"></a>

## [7 – Advanced conditions, Boolean operators](#1-6)

<ul>

  <li> <b> 1) Alien Spy </b> </li>
  
```

```
  <li> <b> 2) Spy House </b> </li>
  
```

```
  <li> <b> 3) Number of days in the month </b> </li>
  
```

```
  <li> <b> 4) Friendship between guards </b> </li>
  
```

```
  <li> <b> 5) Number of people at the party </b> </li>
  
```

```
  <li> <b> 6) Fire stations </b> </li>
  
```

```
  <li> <b> 7) Missing person </b> </li>
  
```

```
  <li> <b> 8) The Big Party </b> </li>
  
```

```
  <li> <b> 9) The spy is unmasked! </b> </li>
  
```

```
  <li> <b> 10) Color areas </b> </li>
  
```

```

</ul>

<a id="1-8"></a>

## [8 – Conditioned repetitions](#1-8)

<ul>
  <li> <b> 1) Department of Medicine: control of an epidemic </b> </li>
  
```

```
  <li> <b> 2) Administration: annual accounts </b> </li>
  
```

```
  <li> <b> 3) Department of Pedagogy: "it's more, it's less" </b> </li>
  
```

```
  <li> <b> 4) Department of Architecture: construction of a pyramid </b> </li>
  
```

```
  <li> <b> 5) Department of chemistry: explosive mixture </b> </li>
  
```

```
  
</ul>

## BY SEBASTIEN XIA

