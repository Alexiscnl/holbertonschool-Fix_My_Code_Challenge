# Fix My Code Challenge

## By: Guillaume

### Description

**Fix my code** est un projet où tu dois plonger dans une base de code existante et la corriger !

Parfois tu connaîtras le langage, parfois non. Le but n'est pas de tout réécrire, mais de corriger ce qui ne fonctionne pas.

- Ce projet est 100% optionnel et n'affectera pas négativement ta moyenne.
- Si tu le fais, tu peux obtenir une note supérieure à 100%.
- Amuse-toi bien !

### Requirements

- Éditeurs autorisés : vi, vim, emacs
- Compilation sur Ubuntu 20.04 LTS
- Tous les fichiers doivent se terminer par un saut de ligne
- Un fichier `README.md` à la racine du projet est obligatoire

---

## Tasks

### 0. FizzBuzz

Corrige l'implémentation de FizzBuzz en Python : [`0-fizzbuzz.py`](challenge/0-fizzbuzz.py)

**Problème :**

```
$ ./0-fizzbuzz.py 50
1 2 Fizz 4 Buzz Fizz 7 8 Fizz Buzz 11 Fizz 13 14 Fizz 16 17 Fizz 19 Buzz Fizz 22 23 Fizz Buzz 26 Fizz 28 29 Fizz 31 32 Fizz 34 Buzz Fizz 37 38 Fizz Buzz 41 Fizz 43 44 Fizz 46 47 Fizz 49 Buzz
```

Le nombre 15 devrait afficher FizzBuzz, pas Fizz.

---

### 1. Print square

Corrige l'implémentation d'un affichage de carré en JavaScript : [`1-print_square.js`](challenge/1-print_square.js)

**Problème :**

```
$ ./1-print_square.js 4
####
####
####
####
$ ./1-print_square.js 10
################
...
```

Le carré de taille 10 n'est pas correct.

---

### 2. Sort

Corrige le tri des arguments en Ruby : [`2-sort.rb`](challenge/2-sort.rb)

**Problème :**

```
$ ruby 2-sort.rb 12 41 2 C 9 -9 31 fun -1 32
31
32
12
41
2
9
-9
-1
```

Le tri ne fonctionne pas comme attendu.

---

### 3. User password

Corrige la classe User en Python : [`3-user.py`](challenge/3-user.py)

**Problème :**

```
$ ./3-user.py
Test User
is_valid_password devrait retourner True si le mot de passe est correct.
```

Les tests ne doivent afficher aucune erreur.

---

### 4. Double linked list

Corrige la double linked list en C : [`4-delete_dnodeint/`](challenge/4-delete_dnodeint/)

**Problème :**

```
$ gcc ...
$ ./delete_dnodeint
0
1
2
...
```

Le comportement n'est pas correct.

---

## Repository

- GitHub repository : **holbertonschool-Fix_My_Code_Challenge**
- Dossier : `challenge`

---

## Score

Ton score sera mis à jour au fur et à mesure de ta progression.

---

## Liste des tâches

- [x] 0. FizzBuzz
- [ ] 1. Print square
- [ ] 2. Sort
- [ ] 3. User password
- [ ] 4. Double linked list
