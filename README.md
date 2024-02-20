# BXTC: BXML Type Checker

_ongoing translation from French_

A type checker for XML files generated in Atelier B.

## Traceability with B language reference manual

## 4 Predicates

### 4.1 Propositions

### 4.2 Quantified predicates

* universal quantifier
* existential quantifier

### 4.3 Equality predicates

* equality [X]
* disequality [X]

### 4.4 Membership predicates

* belongs to [X]
* does not belong to [X]

### 4.5 Set inclusion predicates

* inclusion [X]
* strict inclusion [X]
* non inclusion [X]
* strict non inclusion [X]

### 4.6 Numeric comparison predicates

(i) Both operands are typed and have the same type

* lower than or equal to [X]
* strictly lower than [X]
* greater than or equal to [X]
* strictly greater than [X]

(i) + The first operand is typed INTEGER

* lower than or equal to [X]
* strictly lower than [X]
* greater than or equal to [X]
* strictly greater than [X]

(i) + The first operand is typed REAL

* lower than or equal to [X]
* strictly lower than [X]
* greater than or equal to [X]
* strictly greater than [X]

(i) + The first operand is typed FLOAT.

* lower than or equal to [X]
* strictly lower than [X]
* greater than or equal to [X]
* strictly greater than [X]

## 5 Expressions

All expessions shall be typed.

### 5.1 Primary expressions

### 5.2 Boolean expressions

The type is BOOL

* Literal TRUE [X]
* Literal FALSE [X]
* Conversion of a predicate to a Boolean expression [X]

### 5.3 Arithmetic expressions

* Plus grand entier implémentable
* Plus petit entier implémentable
* Addition entière [X]
* Différence entière [X]
* Moins unaire entier
* Produit entier [X]
* Division entière [X]
* Modulo entier [X]
* Puissance [X]
* Successeur
* Prédécesseur
* Partie entière
* Partie entière par excès
* Conversion de INTEGER dans REAL

* Addition réelle [X]
* Différence réelle [X]
* Produit réel [X]
* Division réelle [X]

### 5.4 Expressions arithmétiques (suite)

### 5.5 Pair expressions

* Correspondance binaire [X]

### 5.6 Predefined sets

Le type est un type ensemble.

* Ensemble vide [X]
* Ensemble des entiers relatifs
* Ensemble des entiers (naturels)
* Ensemble des entiers (naturels) non nuls
* Ensemble des entiers (naturels) concrets
* Ensemble des entiers (naturel) concrets non nuls
* Ensemble des entiers relatifs concrets
* Ensemble des nombres réels
* Ensemble des nombres flottants
* Ensemble des entiers relatifs
* Ensemble des booléens
* Ensemble des chaînes de caractères

### 5.7 Set expressions

Les types des arguments sont des ensembles. (i)

(i) + Le type de l'expression est le produit cartésien du type des arguments

* Produit cartésien [X]

(i) + Le type de l'expression est l'ensemble des parties du type des arguments

* Ensemble des parties [X]
* Ensemble des parties non vides [X]
* Ensemble des parties finies [X]
* Ensemble des parties finies non vides [X]

* Ensemble défini en compréhension
* Ensemble défini en extension [X]
* Intervalle

### 5.8 Set expressions

Les types des arguments sont des ensembles. (i)

(i) + Les arguments ont le même type que le résultat

* Différence [X]
* Union [X]
* Intersection [X]

* Union généralisée
* Intersection généralisée
* Union quantifiée
* Intersection quantifiée

### 5.9 Record expressions

* Ensemble de records
* Record en extension
* Accès à un champ de record

### 5.10 Sets of relations

* Ensemble des relations [X]

### 5.11 Expressions of relations

### 5.12 Expressions of relations (continued)

### 5.13 Expressions of relations (continued)

### 5.14 Expressions of relations (continued)

### 5.15 Sets of functions

### 5.16 Expressions of functions

### 5.17 Sets of sequences

* Séquences
* Séquences non vides seq1
* Séquences injectives
* Séquences injectives non vides
* Permutations
* Séquence vide [X]
* Séquence en extension [X]

### 5.18 Sequence Expressions

### 5.18 Sequence Expressions (continued)

## 6 Substitutions
