## Objectif général

Apprendre à :

Créer et utiliser des fragments dynamiques dans une activité.

Naviguer entre plusieurs fragments avec FragmentManager.

Gérer les événements et états dans les fragments (clics, SeekBar, etc.).

Comprendre le cycle de vie d’un fragment.

## Vérification visuelle
### Écrans et descriptions

| Écran      | Description                                                                              |
| ---------- | ---------------------------------------------------------------------------------------- |
| Fragment 1 | Texte "Fragment One" + bouton. Après clic -> texte devient "Bonjour depuis Fragment 1 !" |
| Fragment 2 | SeekBar. En la déplaçant -> texte mis à jour : "Valeur : n"                              |

## Résumé des notions apprises

| Concept               | Explication                                                        |
| --------------------- | ------------------------------------------------------------------ |
| Fragment              | Partie réutilisable d’une interface, avec son propre cycle de vie. |
| FragmentManager       | Contrôle l'ajout, le remplacement ou la suppression de fragments.  |
| FragmentTransaction   | Représente une action sur les fragments (add, replace, remove).    |
| addToBackStack()      | Permet de revenir au fragment précédent via le bouton Back.        |
| onSaveInstanceState() | Sauvegarde l'état avant destruction temporaire (rotation).         |
| onViewCreated()       | Idéal pour initialiser les composants de la vue.                   |

## DEMO 