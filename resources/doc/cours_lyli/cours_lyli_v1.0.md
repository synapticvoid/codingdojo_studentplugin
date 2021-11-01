---
marp: true
footer: Robin Penea
theme: gaia
class:
  - lead
  - invert

---
# Lyli
## **Cours**

---
# Planning des 3 jours
* Prise en main de Java
    * Variables
    * Conditions
    * Boucles
    * Fonctions
* Course des vaisseaux

---
# Démarrade la course aujourd'hui
## **Milieu d'après-midi**

---
# Nous ferons 2 courses par jour
## **Une en fin de matinée (11h30)**
## **Une en fin de journée (16h30)**

---
# Fondamentaux Java

---
# Définition d'un algorithme ?

---
## Succession d'opérations **déterministes**
* Prend des données **en entrée**
* Produit un résultat **en sortie**

---
# Quelques exemples d'algorithmes
* **Une recette de cuisine**
  * Prend des ingrédients en entrée
  * Produit un plat en sortie
* **Une partition de musique**
  * Prend des notes de musique en entrée
  * Produit une chanson en sortie

---
# Découpage d'un algorithme
1. **Déclaration et initialisation** des données d'entrée
1. **Traitement** qui va appliquer la séquence d'opérations
1. **Résultat** qui est produit


---
# Variables

---
## Une variable sert à **mémoriser une information** pour la réutiliser / modifier plus tard

---
# Variables
* On **réserve** une "case" mémoire
* On précise le **type du contenu** (nombre entier, chaine de caractères, etc)
* On **affecte** une valeur d'initialisation

---
# Variable
```java
// Déclaration d'une variable de type int (integer)
// nommée age
// Initialisé avec la valeur 14
int age = 14;

System.out.println(age); // Affiche 14
```

---
# Caractéristiques variables
* Le signe égal signifie **affecter à gauche**
```java
int age = 14:

// On affecte la valeur 23 à la variable age
// Vous pouvez voir le signe = comme ceci <-
// age <- 23
age = 23;
```

---
# Caractéristiques variables
* On ne peut déclarer une variable qu'une seule fois
```java
int age = 14;
int age = 10; // NOPE ! la variable age existe déjà
```

---
# Caractéristiques variables
* Le type est définitif
```java
int age = 14;
age = "Hello"; // NOPE ! On ne peut mettre que des nombre entiers dans age
```

---
# Liste des types de variables
 | Type      | Définition                   | Exemple                  |
| --------- | ---------------------------- | ------------------------ |
| `boolean` | Valeur booléen (Vrai / Faux) | `boolean aPerdu = true;` |
| `int`     | Nombre entier                | `int score = 345;`       |
| `float`   | Nombre à virgule             | `float taille = 1.80f;`  |
| `String`  | Chaine de caractère / Text   | `String name = "Bob";`   |


---
# Opération sur les variables
* Additioner `+`
* Soustraire `-`
* Multiplier `*`
* Diviser `/`
* Les mêmes règles de priorités (multiplication avant addition)
* Vous pouvez utiliser des parenthèses

---
# Opération sur les variables
```java
float note1 = 10.5f;
float note2 = 14.5f:
float somme = note1 + note2;
float moyenne = somme / 2;

// Ou alors tout en une ligne
float moyenne2 = (note1 + note2) / 3;
```

---
# TP
<!-- _class: lead -->
* Déclarer une variable de chaque type (boolean, int, float, String)
* Initialiser chaque variable avec une valeur arbitraire
* Afficher chaque variable avec `System.out.println()`
* Modifier chaque variable numérique avec des opérateurs arithmétiques (+ - * /) et afficher le résultat


---
# Conditions

---
# Boucles

---
# Fonctions