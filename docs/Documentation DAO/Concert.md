---
sidebar_position: 2
---

------------------------------------------
## getAllConcerts()
------------------------------------------
retourne une liste d'objects de type Concert

**param(s) :** *void*

**return :** *array*

```php 

  0 => 
    array (size=6)
      'id_concert' => int 1
      'id_artiste' => int 1
      'id_scene' => int 1
      'date_concert' => string '2022-07-01' (length=10)
      'heure_debut_concert' => string '18:00:00' (length=8)
      'entree_libre' => boolean false
  1 => 
    array (size=6)
      'id_concert' => int 2
      'id_artiste' => int 2
      'id_scene' => int 2
      'date_concert' => string '2022-07-01' (length=10)
      'heure_debut_concert' => string '19:15:00' (length=8)
      'entree_libre' => boolean false
  2 => 
    array (size=6)
      'id_concert' => int 3
      'id_artiste' => int 3
      'id_scene' => int 1
      'date_concert' => string '2022-07-01' (length=10)
      'heure_debut_concert' => string '20:15:00' (length=8)
      'entree_libre' => boolean false
  ...

```

------------------------------------------
## getNbJoursConcert()
------------------------------------------
retourne le nombre de jours de concert

**param(s) :** *void*

**return :** *int*

```php 

    int 3

```

------------------------------------------
## getNbConcertsParDate()
------------------------------------------
retourne le nombre de concert à une date donnée

**param(s) :** *String* $date

**return :** *int*

```php 

    int 5

```

------------------------------------------
## getHeurePremierConcert()
------------------------------------------
retourne l'heure du premier concert pour une date donnée

**param(s) :** *String* $date

**return :** *String*

```php 

    string '18H00'

```

