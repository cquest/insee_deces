# Fichier des personnes décédées

Ce projet a pour but:
- de proposer une version agrégée et remise en forme des fichiers publiés par l'INSEE
- de permettre des corrections collaboratives et ouvertes

## Fichiers originaux

Source: INSEE

Millésime: voir date de modification du fichier

Licence: Licence Ouverte 2.0


## Fichier mensuels

Ces fichiers au format CSV contiennent les décès mois par mois.
L'idée est d'**expérimenter une édition collaborative** à l'aide des mécanismes classiques de GIT.
Vous pouvez donc proposer des PR pour modifier leur contenu.


## Fichier global CSV

Les fichiers d'origine au format fixe sont:
- agrégés
- remis en CSV
- les dates sont remises à la norme ISO

Le résultat est un fichier CSV unique gzippé.

Le code utilisé est disponible dans le fichier repack.sh
