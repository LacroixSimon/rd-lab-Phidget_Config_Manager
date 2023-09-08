# /tests

***Aucun test unitaire, voir le [README.md](/README.md) à la racine pour les méthodes de validation.***

## But du dossier

Ce dossier devrait contenir tout ce qui est relié aux tests et à la vérification du code. Il est destiné aux utilisateurs qui désirent valider le code et pourrait même être l'objet d'une exécution automatique dans un processus de vérifcation. 

À titre d'exemple, lorsqu'un nouveau membre finit d'écrire du code source, celui-ci devrait pouvoir y retrouver les tests du projet et pourra y ajouter ses propres méthodes pour valider ses modifications.

On pourra y retrouver, sans y être exclusivement restraint, des documents tel que : 
- Des fichiers excutables tests
- Un script pour lancé l'ensemble des tests
- Les résultats des tests si applicable
- Etc.

À l'inverse, ce dossier ne devrait pas contenir des fichiers tel que : 
- Des fichiers essentiels à l'exécution du code
- Des fichiers documentaires génériques 
- Des fichiers executables à titre d'exemples

## Que faire si aucun document trouve sa place dans ce dossier

Le dossier `/tests` devrait avoir un minimum de documents pour permettre de valider certains aspects du code et faciliter la maintenabilité du projet. 

Toutefois, il est possible que les tests s'effectuent dans un autre contexte que celui du répertoire actuel et que le dossier reste vide. Dans ce cas, simplement laissé ce fichier dans le dossier inchangé.

**Lorsque des fichiers pertinents sont présents dans le dossier, ce README peut être supprimer en toute quiétude.**
