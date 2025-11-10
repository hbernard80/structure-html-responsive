# structure-html-responsive

Page HTML responsive avec menu repliable

- Responsive avec flexbox.
- Mobile first.
- Exemple de galerie flexbox.
- Exemple de tableau responsive (scrollbar horizontale).
- Images responsive :
  - utilisation de la balise HTML picture/source
  - plusieurs dimensions de la même image en fonction du viewport
  - formats WebP et jpeg (si WebP non pris en charge par le navigateur)
  - compression avec TinyPng.
- Fichiers CSS et JS minifiés (avec cssnano).
- Feuille de style pour l'impression avec couleur et police "eco-fiendly".
- Menu responsive repliable avec prise en compte des attributs ARIA.
- Structure/arborescence optimisée (répertoire public).
- Fichier Apache _.htaccess_ : sécurité, compression/mise en cache (enlever le double undescore du nom du fichier pour pouvoir l'utiliser; ne focntionnera pas en local; pour cela il faudra commenter les directives pour les systèmes de mise en cache sont activés).
- Fichier _sitemap.xml_ pour le SEO (note : les pages ne sont pas référençables en l'état, balise méta "robots" avec la valeur "none").