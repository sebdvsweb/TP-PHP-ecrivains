
# 🧪 TP PHP — Les écrivains français

## 🎯 Objectif

Manipuler des **tableaux associatifs** en PHP et créer une **fonction d’affichage** personnalisée pour présenter des données sous forme structurée.

---

## ✍️ Consignes

1. Créer un **tableau PHP associatif** contenant des informations sur plusieurs écrivains célèbres.   

2. Pour chaque écrivain, stocker les informations suivantes :
   - `firstname` (Prénom)
   - `name` (Nom)
   - `portrait` (URL de l’image)
   - `birth` (Année de naissance)
   - `death` (Année de mort)
   - `main_work` (Œuvre principale)   

3. Créer une fonction `afficherPortrait()` qui :
   - Affiche le nom complet de l’écrivain
   - Affiche son portrait via une balise `<img>`
   - Affiche ses années de naissance et de mort
   - Affiche son œuvre principale   

4. Parcourir le tableau principal avec une **boucle** et appeler `afficherPortrait()` pour chaque écrivain.

---

## 📚 Données à utiliser

| Prénom  | Nom               | Naissance | Mort | Œuvre principale        | Lien du portrait |
|---------|-------------------|-----------|------|--------------------------|------------------|
| Victor  | Hugo              | 1802      | 1885 | *Les Misérables*         | [Portrait](https://upload.wikimedia.org/wikipedia/commons/5/5a/Bonnat_Hugo001z.jpg) |
| Jean    | de La Fontaine    | 1621      | 1695 | *Fables*                 | [Portrait](https://upload.wikimedia.org/wikipedia/commons/e/e1/La_Fontaine_par_Rigaud.jpg) |
| Pierre  | Corneille         | 1606      | 1684 | *Le Cid*                 | [Portrait](https://upload.wikimedia.org/wikipedia/commons/2/2a/Pierre_Corneille_2.jpg) |
| Jean    | Racine            | 1639      | 1699 | *Phèdre*                 | [Portrait](https://upload.wikimedia.org/wikipedia/commons/d/d5/Jean_racine.jpg) |

---

## 💡 Exemple générique : tableau PHP avec des objets/associatifs

```php
$films = array(
    array(
        'title' => 'Inception',
        'director' => 'Christopher Nolan',
        'year' => 2010,
        'genre' => 'Science-fiction'
    ),
    array(
        'title' => 'Le Fabuleux Destin d\'Amélie Poulain',
        'director' => 'Jean-Pierre Jeunet',
        'year' => 2001,
        'genre' => 'Comédie romantique'
    )
);

```

## ➕ Bonus

- Ajouter un lien vers la page Wikipédia de chaque écrivain.
- Créer une fonction pour trier les écrivains par année de naissance avec `usort()`.

## 📷 Exemple attendu

![Exemple](https://sebastien-devos.fr/img/codegt/exemple-ecrivains.png "TP Ecrivains")
