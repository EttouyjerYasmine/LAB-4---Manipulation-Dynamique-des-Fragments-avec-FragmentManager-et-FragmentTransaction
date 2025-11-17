#### LAB 4 - Manipulation Dynamique des Fragments avec FragmentManager et FragmentTransaction


# 🎯 Objectif général

## Ce que ce projet permet d’apprendre

- Créer et utiliser des **fragments dynamiques** dans une activité.
- Naviguer entre plusieurs fragments avec le **FragmentManager**.
- Gérer les **événements** et l’état de la vue dans un fragment (bouton, SeekBar…).
- Comprendre et appliquer le **cycle de vie d’un fragment**.

# 👀 Vérification visuelle

## Fragment 1
- Affiche le texte : **"Fragment One"**
- Contient un bouton
- Après un clic, le texte devient : **"Bonjour depuis Fragment 1 !"**

## Fragment 2
- Contient une **SeekBar**
- Lorsque l’utilisateur la déplace, le texte affiche : **"Valeur : n"**

# 📘 Notions essentielles

## Fragment
Un composant réutilisable représentant une partie d’interface, possédant son propre cycle de vie.

## FragmentManager
Permet de gérer l’ajout, la suppression et le remplacement de fragments dans une activité.

## FragmentTransaction
Représente l’ensemble des opérations effectuées sur les fragments (add, replace, remove…).

## addToBackStack()
Enregistre l’opération dans la pile afin de permettre le retour au fragment précédent via le bouton *Back*.

## onSaveInstanceState()
Permet de sauvegarder l’état du fragment avant une destruction temporaire (rotation de l’écran, minimisation…).

## onViewCreated()
Méthode utilisée pour initialiser les composants graphiques après la création de la vue.

# 🎥 DEMO

