# /deps

***Aucune dépendance additionnelle, voir le [README.md](/README.md) à la racine.***

## But du dossier

Ce dossier devrait contenir tout ce qui est relié aux dépendances externes du projet. Il est destiné aux routines standard qui assurent une version compatible des dépendances en local et aux scripts d'envrionnement de travail.

À titre d'exemple, lorsqu'un nouveau membre se joint au projet, celui-ci devrait pouvoir simplement démarrer l'écriture et la compilation de code source en important les dépendances qui se trouve dans ce dossier. 

On pourra y retrouver, sans y être exclusivement restraint, des documents tel que : 
- Un fichiant listant les librairies externes 
- Les fichiers d'environnement de développement
- D'autres Git inclus en sous-modules
- Tout type de dépendances avec le projet
- Etc.

À l'inverse, ce dossier ne devrait pas contenir des fichiers tel que : 
- Des images statiques nécéssaire à l'interface graphique du projet
- Un fichier executable essentiel au projet
- Des fichiers executables à titre d'exemples
- De la documentation génériques

## Que faire si aucun document trouve sa place dans ce dossier

Le dossier `/deps` devrait avoir un minimum de documents pour permettre une réception facile et efficace du projet dans des nouveaux environnements de travail. 

Toutefois, il est possible que le dossier soit vide et que aucune dépendance externe soit utilisée et que le projet repose seulement sur les modules de base. Dans ce cas, simplement laissé ce fichier dans le dossier inchangé.

**Lorsque des fichiers pertinents sont présents dans le dossier, ce README peut être supprimer en toute quiétude.**
