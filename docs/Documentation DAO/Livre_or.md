---
sidebar_position: 3
---

---

## ajouterMessageLivreOr()

---

Ajoute un commentaire dans la base de donnée

**param(s) :** _String_ $pseudo, _String_ $commentaire, _String_ $date, _String_ $ip

**return :** _void_

---

## getFiveLastMessagesLivreOr()

---

Retourne les 5 derniers messages du livre d'or

**param(s) :** _void_

**return :** _array_

```php

  0 =>
    object(LivreOr)[7]
      private int 'id_post' => int 9
      private string 'date_post' => string '2022-11-12 13:33:08' (length=19)
      private string 'pseudo_post' => string 'jack5' (length=5)
      private string 'message_post' => string 'Merci pour ce festival juste fabuleux ���' (length=42)
      private string 'ip_post' => string '127.0.0.1' (length=9)
  1 =>
    object(LivreOr)[8]
      private int 'id_post' => int 8
      private string 'date_post' => string '2022-11-12 13:17:17' (length=19)
      private string 'pseudo_post' => string 'test redirection' (length=16)
      private string 'message_post' => string 'test redirection' (length=16)
      private string 'ip_post' => string '127.0.0.1' (length=9)
  2 =>
    object(LivreOr)[9]
      private int 'id_post' => int 7
      private string 'date_post' => string '2022-11-12 13:14:31' (length=19)
      private string 'pseudo_post' => string 'test3' (length=5)
      private string 'message_post' => string 'test3' (length=5)
      private string 'ip_post' => string '127.0.0.1' (length=9)
  ...

```
