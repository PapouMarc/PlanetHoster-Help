# Introduction

Exemples à utiliser pour l'hebergeur planethoster

# protectedOneFile

## Cible

* Demander une authentification spécifique pour un fichier donné avec une basic authentification
* Bloque un fichier donné dans un repertoire
* Empeche de lister les fichiers du repertoire

## Mise en oeuvre
Il vous suffit de mettre le repertoire __protectedOneFile__ à la racine de votre hébergement pour tester.

Dans le fichier __protectedOneFile/dirprotected/.htpasswd__, remplacer _[YOURPUBLICHTML]_ par la racine de votre public_html
```
/[YOURPUBLICHTML]/protectedOneFile/dirprotected/.htpasswd"
```

Pensez à mettre en 644 les fichier .htaccess et .htpasswd

>Il est vivement conseillé de ne pas laisser le htpasswd dans le même repertoire que le fichier htaccess
