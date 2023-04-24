# ✔️ France ioi Correction Python
Corrected exercise from france ioi python.

<div align="center">
  <picture>
    <img src="https://www.france-ioi.org/dataSite/img/logo.png" alt="france_ioi_logo">
  </picture>
</div>

<br/>

<a id= table_contents></a>
## 📋 Table of Contents

- [✧ LEVEL 2 ✧](#Level_2)
  - [Level 2-1 – Decimal numbers and other tools](#2-1)
    - [A – Make roundings (lower and upper)](#A-2-1)
    - [B – Make roundings (to nearest)](#B-2-1)
    - [C – Basic Arithmetic](#C-2-1)
  - [Level 2-2 – Discovery of the paintings](#2-2)
  - [Level 2-3 – Character strings](#2-3)
  - [Level 2-4 – Functions](#2-4)
  - [Level 2-5 – Programming on your computer](#2-5)

<a id="Level_2"></a>

# [LEVEL 2](#Level_2)

<a id="2-1"></a>

## [1 – Decimal numbers and other tools](2-1)

- <b> 1) Origami </b>

```
epaisseurpapier = 0.110
epaisseurpapier_en_centimètre = 0.011

for plis in range(15):
    epaisseurpapier_en_centimètre = epaisseurpapier_en_centimètre * 2
    epaisseur_final = epaisseurpapier_en_centimètre
    plis += 1

print(epaisseur_final)
```
- <b> 2) Distance conversions </b>

```
nblieux = float(input())

print(nblieux / 0.707)
```
- <b> 3) Price comparison </b>

```
nb_legumes_vente = int(input())

for legumes in range(nb_legumes_vente):
    poids = float(input())
    age = float(input())
    prix = float(input())
    prix_kg = prix / poids
    print(prix_kg)
```
- <b> 4) Average marks </b>

```
nb_notes = int(input())
total = 0
for i in range(nb_notes):
    note = int(input())
    total += note
moyenne = total / nb_notes
print(moyenne)
```
<a id = "A-2-1"></a>
## [A – Make roundings (lower and upper)](#A-2-1)
- <b> A - 1) Population increase </b>

```
population_actuelle_ville = int(input())
croissance_population = float(input())

nouvelle_population = int(population_actuelle_ville * (1 + croissance_population / 100))

print(nouvelle_population)
```
- <b> A - 2) Construction of houses </b>

```
from math import *

quantite_ciment_kg = float(input())
nb_sacs_ciment = int(ceil(quantite_ciment_kg / 60))
cout_tt = nb_sacs_ciment * 45
print(cout_tt)
```
<a id = "B-2-1"></a>
## [B – Make roundings (to nearest)](#B-2-1)
- <b> B - 1) Stormy evening </b>

```
temps = float(input())

distance = temps * 340.29

distance_km = round(distance / 1000)
print(distance_km)
```
- <b> B - 2) Tax increase </b>

```

```
<a id ="C-2-1"></a>
## [C – Basic Arithmetic](#C-2-1)
- <b> C - 1) Purchase of books </b>

```

```
- <b> C - 2) A good harvest </b>

```

```
- <b> C - 3) The wheel of fortune </b>

```

```

<div align="right">
    <a href= "#table_contents"> <img src="https://images.emojiterra.com/google/android-nougat/512px/2b06.png" width="32" alt="UP"> </a>
</div>

<a id="2-2"></a>

## [2 – Discovery of the paintings](2-2)

<ul>
  
</ul>

<div align="right">
    <a href= "#table_contents"> <img src="https://images.emojiterra.com/google/android-nougat/512px/2b06.png" width="32" alt="UP"> </a>
</div>

<a id="2-3"></a>

## [3 – Character strings](2-3)

<ul>
  
</ul>

<div align="right">
    <a href= "#table_contents"> <img src="https://images.emojiterra.com/google/android-nougat/512px/2b06.png" width="32" alt="UP"> </a>
</div>

<a id="2-4"></a>

## [4 – Functions](2-4)

<ul>
  
</ul>

<div align="right">
    <a href= "#table_contents"> <img src="https://images.emojiterra.com/google/android-nougat/512px/2b06.png" width="32" alt="UP"> </a>
</div>

<a id="2-5"></a>

## [5 – Programming on your computer](2-5)

