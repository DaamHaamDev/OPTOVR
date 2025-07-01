# Conventions pour le projet VR

Ce document décrit les conventions à suivre pour les modifications du projet de réalité virtuelle.

## Structure des Versions

Chaque nouvelle version fonctionnelle est un fichier HTML unique. Le nom du fichier suivra le format `vX_description_de_la_modif.html`, où `X` est le numéro de version et `description_de_la_modif` est un nom court en anglais décrivant le changement.

Exemple de nom de fichier :
`v12_aframe_update_and_smoothing.html`

## Lancement et Test

L'application est contenue dans un seul fichier HTML et peut être testée directement.

Pour lancer et tester une version spécifique :
1.  Trouvez le fichier `.html` de la version que vous souhaitez tester.
2.  Ouvrez ce fichier directement dans un navigateur web (comme Chrome, Firefox, ou Edge).

Il n'est plus nécessaire de lancer un serveur local.

## État Actuel

La dernière version stable et recommandée est `v12_aframe_update_and_smoothing.html`. C'est sur cette base que les futures modifications devront être apportées.

---

## Limitation Connue : Affichage PC en Mode VR

Il a été observé que l'affichage sur l'écran du PC (le "miroir") ne se met pas à jour une fois le mode Réalité Virtuelle (VR) activé dans le casque. Cela signifie que les mouvements de la tête de l'utilisateur dans le casque, ainsi que les rotations programmatiques appliquées au joueur, ne sont pas reflétés sur l'écran du PC. Ce comportement semble être une optimisation d'A-Frame pour dédier toutes les ressources au rendu VR. La mise à jour vers A-Frame 1.5.0 dans la v12 n'a pas résolu ce problème.

## Déploiement sur GitHub Pages

Pour rendre l'application accessible depuis n'importe où via internet, la méthode la plus simple est d'utiliser GitHub Pages. Cela vous permet d'héberger des sites web statiques (comme nos fichiers HTML) directement depuis un dépôt GitHub.

Le processus général est le suivant :
1.  **Créer un dépôt GitHub** : Si ce n'est pas déjà fait, créez un nouveau dépôt sur GitHub.com.
2.  **Pousser les fichiers** : Ajoutez vos fichiers de projet (comme `v12_aframe_update_and_smoothing.html`) dans le dépôt et poussez-les sur GitHub en utilisant les commandes `git`.
3.  **Activer GitHub Pages** : Dans les paramètres de votre dépôt sur GitHub, activez GitHub Pages et choisissez la branche et le dossier à publier (généralement la branche `main` ou `master`).

Je peux vous aider à exécuter les commandes `git` nécessaires pour initialiser le dépôt localement, ajouter les fichiers et les pousser vers GitHub. Il faudra au préalable que vous créiez un dépôt vide sur GitHub.com et que vous configuriez votre authentification (généralement via un token d'accès personnel ou une connexion SSH). Je n'ai pas de connexion directe à votre compte GitHub, mais je peux générer les commandes que vous devrez exécuter.
