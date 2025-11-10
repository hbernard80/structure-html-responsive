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
- Fichiers CSS et JS optimisés : un global, _app.min.css_ + un spécifique par page, minifiés avec cssnano.
- Feuille de style pour l'impression avec couleur et police "eco-fiendly".
- Menu responsive repliable avec prise en compte des attributs ARIA.
- Structure/arborescence optimisée (répertoire public).
- Fichier Apache _\_\_.htaccess_ : 
  - sécurité
  - compression/mise en cache.
  - enlever le '\_\_' du nom de fichier pour l'utiliser
  - en local (Wamp etc.) : commenter les directives de mise en cache et de sécurité sinon ne fonctionne pas.
- Fichier _sitemap.xml_ pour le SEO (note : les pages ne sont pas référençables en l'état, balise méta "robots" avec la valeur "none").