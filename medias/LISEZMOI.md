# Sons et vidéos de la régie

La régie trouve toute seule les fichiers de ce dossier, une fois poussés sur GitHub.

| Dossier | Ce qu'on y met | Dans la régie |
|---|---|---|
| `ambiance/` | musiques d'ambiance | jouées en boucle, une seule à la fois, avec un fondu |
| `sons/` | bruitages | joués par-dessus l'ambiance, qui baisse un peu pendant ce temps |
| `videos/` | extraits vidéo | en plein écran ; coupent l'ambiance et les bruitages, l'ambiance reprend à la fin |

**Le nom du fichier est le nom du bouton** : `porte-qui-grince.mp3` donne le bouton « Porte qui grince ».
Les tirets et les soulignés deviennent des espaces ; majuscules et accents ne comptent pas pour retrouver un fichier.

**Formats conseillés** : `.mp3` pour les sons et musiques, `.mp4` (H.264) pour les vidéos.
GitHub refuse les fichiers de plus de 100 Mo : compresser les vidéos (moins de 50 Mo, c'est plus sûr).

**Dans le livret (Google Sheets)**, une ligne de type `Son`, `Ambiance` (ou `Musique`) ou `Vidéo`,
avec le nom du fichier dans la colonne Texte, affiche un bouton ▶ au bon endroit du script.
Exemple : `N2-2 | | Son | carillon` joue `medias/sons/carillon.mp3`.

Le dépôt est public : tout ce qui est déposé ici est visible par tous.
