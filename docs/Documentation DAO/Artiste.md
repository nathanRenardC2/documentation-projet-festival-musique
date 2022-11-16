---
sidebar_position: 1
---

------------------------------------------
## getArtistesAvecConcert()
------------------------------------------
retourne tous les artistes ayant un concert

**param(s) :** *void*

**return :** *array*

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

------------------------------------------
## getDateConcertArtiste()
------------------------------------------
retourne la date du concert pour un artiste

**param(s) :** *int* $id_artiste

**return :** *String*

```php 

    string '2022-07-02'

```

------------------------------------------
## getArtisteById()
------------------------------------------
retourne un artiste en fonction de son id

**param(s) :** *int* $id_artiste

**return :** *Artiste*

```php 

    object(Artiste)[4]
        private int 'id_artiste' => int 7
        private string 'nom_artiste' => string 'ARABELLA' (length=8)
        private string 'lien_page' => string 'https://www.vercorsmusicfestival.com/artiste/arabella/' (length=54)
        private string 'lien_illustration' => string    'https://www.vercorsmusicfestival.com/media/cache/program_artist_large/uploads/artist_image/large/7c50b32e3b1e42208fdc6df1ad26106c7cbd88d0.jpeg' (length=142)

```





