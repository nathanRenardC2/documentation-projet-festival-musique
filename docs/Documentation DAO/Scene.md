---
sidebar_position: 4
---

------------------------------------------
## getAllScenes()
------------------------------------------
retourne une liste d'objects de type Scene

**param(s) :** *void*

**return :** *array*

exemple de retour : 

```php 

    0 => 
        object(Scene)[4]
            private int 'id' => int 1
            private string 'nom_scene' => string 'La Terrasse' (length=11)
            private string 'adresse' => string 'Maison des Sports, Route de la Foulée blanche' (length=46)
            private string 'code_postal' => string '38880' (length=5)
            private string 'ville' => string 'Autrans' (length=7)
    1 => 
        object(Scene)[5]
            private int 'id' => int 2
            private string 'nom_scene' => string 'Le Foyer' (length=8)
            private string 'adresse' => string 'Maison des Sports, Route de la Foulée blanche' (length=46)
            private string 'code_postal' => string '38880' (length=5)
            private string 'ville' => string 'Autrans' (length=7)
    2 => 
        object(Scene)[6]
            private int 'id' => int 3
            private string 'nom_scene' => string 'L'Avant Scène' (length=14)
            private string 'adresse' => string 'Le Châtelard' (length=13)
            private string 'code_postal' => string '38112' (length=5)
            private string 'ville' => string 'Méaudre' (length=8)


```

------------------------------------------
## getNbScenes()
------------------------------------------
retourne le nombre de scènes

**param(s) :** *void*

**return :** *int*

exemple de retour :

```php 

    int 3

```
