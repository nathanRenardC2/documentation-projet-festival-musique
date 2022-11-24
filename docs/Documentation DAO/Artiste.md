---
sidebar_position: 1
---

---

## getAllArtists()

---

Retourne un tableau de tous les artistes en selectionnant seulement les attributs nécessaires à l'affichage d'une liste de vignettes

**param(s) :** _void_

**return :** _array_

```php

    0 =>
    object(Artiste)[4]
      private int 'id_artiste' => int 15
      private string 'nom_artiste' => string 'Adèle & Robin' (length=14)
      private string 'lien_page' => string 'https://www.vercorsmusicfestival.com/artiste/adele-robin/' (length=57)
      private string 'lien_illustration' => string      'https://www.vercorsmusicfestival.com/media/cache/program_artist_large/uploads/artist_image/large/4afc24a470798044c26e489b85484df6009aa88d.jpeg' (length=142)
      string '2022-07-02'
  1 =>
    object(Artiste)[5]
      private int 'id_artiste' => int 7
      private string 'nom_artiste' => string 'ARABELLA' (length=8)
      private string 'lien_page' => string 'https://www.vercorsmusicfestival.com/artiste/arabella/' (length=54)
      private string 'lien_illustration' => string 'https://www.vercorsmusicfestival.com/media/cache/program_artist_large/uploads/artist_image/large/7c50b32e3b1e42208fdc6df1ad26106c7cbd88d0.jpeg' (length=142)
      string '2022-07-02'

  ...

```

---

## getArtistsByDate()

---

Retourne tous les artistes groupés par date de concert

**param(s) :** _void_

**return :** _array_

```php

    'Vendredi 1 juillet 2022' =>
      array (size=6)
        0 =>
          array (size=6)
            'id_artiste' => int 1
            'nom_artiste' => string 'Cléa Vincent' (length=13)
            'heure_debut_concert' => string '18:00' (length=5)
            'lien_illustration' => string 'https://www.vercorsmusicfestival.com/media/cache/program_artist_large/uploads/artist_image/large/b0144dbf23d597397a0d60bb39ef49ff49f45a69.jpeg' (length=142)
            'date_concert' => string '2022-07-01' (length=10)
            'nom_scene' => string 'La Terrasse' (length=11)
    'Samedi 2 juillet 2022' =>
      array (size=8)
        0 =>
          array (size=6)
            'id_artiste' => int 7
            'nom_artiste' => string 'ARABELLA' (length=8)
            'heure_debut_concert' => string '14:00' (length=5)
            'lien_illustration' => string 'https://www.vercorsmusicfestival.com/media/cache/program_artist_large/uploads/artist_image/large/7c50b32e3b1e42208fdc6df1ad26106c7cbd88d0.jpeg' (length=142)
            'date_concert' => string '2022-07-02' (length=10)
            'nom_scene' => string 'L'Avant Scène' (length=14)
    'Dimanche 3 juillet 2022' =>
      array (size=9)
        0 =>
          array (size=6)
            'id_artiste' => int 15
            'nom_artiste' => string 'Adèle & Robin' (length=14)
            'heure_debut_concert' => string '12:00' (length=5)
            'lien_illustration' => string 'https://www.vercorsmusicfestival.com/media/cache/program_artist_large/uploads/artist_image/large/4afc24a470798044c26e489b85484df6009aa88d.jpeg' (length=142)
            'date_concert' => string '2022-07-03' (length=10)
            'nom_scene' => string 'L'Avant Scène' (length=14)

```

---

## groupArtistsByDate()

---

Groupe une liste d'artistes par date de concert

**param(s) :** _array_ $artists

**return :** _array_

```php

```

---

## getArtistesAvecConcert()

---

retourne tous les artistes ayant un concert

**param(s) :** _void_

**return :** _array_

```php

    0 =>
    object(Artiste)[4]
      private int 'id_artiste' => int 15
      private string 'nom_artiste' => string 'Adèle & Robin' (length=14)
      private string 'lien_page' => string 'https://www.vercorsmusicfestival.com/artiste/adele-robin/' (length=57)
      private string 'lien_illustration' => string      'https://www.vercorsmusicfestival.com/media/cache/program_artist_large/uploads/artist_image/large/4afc24a470798044c26e489b85484df6009aa88d.jpeg' (length=142)
  1 =>
    object(Artiste)[5]
      private int 'id_artiste' => int 7
      private string 'nom_artiste' => string 'ARABELLA' (length=8)
      private string 'lien_page' => string 'https://www.vercorsmusicfestival.com/artiste/arabella/' (length=54)
      private string 'lien_illustration' => string 'https://www.vercorsmusicfestival.com/media/cache/program_artist_large/uploads/artist_image/large/7c50b32e3b1e42208fdc6df1ad26106c7cbd88d0.jpeg' (length=142)

  ...

```

---

## getDateConcertArtiste()

---

retourne la date du concert pour un artiste

**param(s) :** _int_ $id_artiste

**return :** _String_

```php

    string '2022-07-02'

```

---

## getArtisteById()

---

retourne un artiste en fonction de son id

**param(s) :** _int_ $id_artiste

**return :** _Artiste_

```php

    object(Artiste)[4]
        private int 'id_artiste' => int 7
        private string 'nom_artiste' => string 'ARABELLA' (length=8)
        private string 'lien_page' => string 'https://www.vercorsmusicfestival.com/artiste/arabella/' (length=54)
        private string 'lien_illustration' => string    'https://www.vercorsmusicfestival.com/media/cache/program_artist_large/uploads/artist_image/large/7c50b32e3b1e42208fdc6df1ad26106c7cbd88d0.jpeg' (length=142)

```
