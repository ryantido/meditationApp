# Authentication

**Title:** En tant qu’utilisateur, je veux m’inscrire en saisissant mon nom d’utilisateur, mon e-mail et mon mot de passe, afin de pouvoir créer un compte.

**Acceptance Criteria:**

1. Les utilisateurs peuvent entrer des informations valides et cliquer sur “S’inscrire” pour créer un compte.
Un message d’erreur est affiché si une saisie est invalide ou manquante.


**Title:** En tant qu’utilisateur, je veux me connecter en utilisant mon e-mail et mon mot de passe, afin de pouvoir accéder à mon compte.

**Acceptance Criteria:**

1. Les utilisateurs peuvent se connecter avec des identifiants corrects et sont redirigés vers leur tableau de bord.
Un message d’erreur est affiché pour des identifiants incorrects.


**Title:** En tant qu’utilisateur, je veux recevoir des retours lorsque j’essaie de m’inscrire ou de me connecter sans entrer de détails, afin de pouvoir corriger les erreurs.

**Acceptance Criteria:**

1. Des messages d’erreur sont affichés pour les champs manquants lors des tentatives d’inscription ou de connexion.


**Title:** En tant qu’utilisateur, je veux que mes détails soient stockés dans le stockage local, afin que mes données persistent entre les sessions.

**Acceptance Criteria:**

1. Les détails de l’utilisateur sont enregistrés dans le stockage local après l’inscription et utilisés pour l’authentification lors de la connexion.

**Story Points:** 10

# Welcome page

**Title:** En tant qu’utilisateur, je veux un message de bienvenue personnalisé avec mon nom et un titre, afin de me sentir accueilli et encouragé à méditer.

**Critères d’acceptation :**

1. Afficher “Bonjour, [nom d’utilisateur]” suivi du titre “Trouvez votre méditation parfaite.”


**Title:** En tant qu’utilisateur, je veux voir des cartes de méditation populaires, afin de pouvoir explorer des options en fonction de mes préférences.

**Acceptance Criteria:**

1. Afficher des cartes avec des images, des titres, des descriptions, des catégories telles que calme, relaxation, et des durées telles que 10 ou 15 minutes.


**Title:** En tant qu’utilisateur, je veux une méditation quotidienne en vedette, afin de pouvoir accéder rapidement à une session recommandée.

**Acceptance Criteria:**

1. Présenter une méditation avec une image, un titre, une catégorie et une durée dans une section dédiée.


**Title:** En tant qu’utilisateur, je veux des icônes de navigation intuitives, afin de pouvoir me déplacer facilement dans l’application.

**Acceptance Criteria:**

1. Afficher un logo dans le coin supérieur gauche et une icône de paramètres dans le coin supérieur droit pour la navigation.

**Story Points:** 30

# Details Page

**Title:** En tant qu’utilisateur, je veux une section “À propos” pour chaque exercice, afin de comprendre ses avantages et son objectif.

**Acceptance Criteria:**

1. Afficher une brève description de l’exercice, expliquant son objectif et ses bienfaits pour réduire le stress.


**Title:** En tant qu’utilisateur, je veux une section “Instructions” pour chaque exercice, afin de pouvoir le réaliser correctement.

**Acceptance Criteria:**

1. Fournir des instructions étape par étape sur la posture et les techniques de respiration pour l’exercice.


**Title:** En tant qu’utilisateur, je veux un bouton “Ajouter aux Favoris”, afin de pouvoir facilement enregistrer un exercice pour une pratique future.

**Acceptance Criteria:**

1. Inclure un bouton “Ajouter aux Favoris” bien en vue en bas de la page.

**Story Points:** 45
**Title:** En tant qu’utilisateur, je veux des icônes de navigation pour partager et revenir en arrière, afin de pouvoir facilement gérer la page de l’exercice.

**Acceptance Criteria:**

1. Afficher une icône de retour et une icône de partage en haut de la page pour une navigation facile.


# Favorite items

**Title:** En tant qu’utilisateur, je veux ajouter un élément à mes Favoris, afin de pouvoir sauvegarder les activités ou articles que j’aime pour un accès rapide plus tard.

**Acceptance Criteria:**

1. Une icône en forme de cœur avec le texte “Ajouter aux Favoris” est affichée à côté de chaque élément.
2. Le cœur en contour indique que l’élément n’est pas dans les Favoris.
3. Taper sur le bouton ajoute l’élément à la liste des Favoris, met à jour le texte du bouton en “Retirer des Favoris” et change l’icône du cœur en remplie.


**Title:** En tant qu’utilisateur, je veux retirer un élément de mes Favoris, afin de pouvoir gérer mon contenu sauvegardé.

**Acceptance Criteria:**

1. Le bouton “Retirer des Favoris” avec un cœur rempli est affiché pour les éléments déjà dans les Favoris.
2. Taper sur le bouton retire l’élément de la liste des Favoris et rétablit l’icône du cœur en contour.
3. Les utilisateurs peuvent ajouter ou retirer des éléments à tout moment, et le texte du bouton se met à jour en conséquence.


**Title:** En tant qu’utilisateur, je veux un écran “Mes Favoris”, afin de pouvoir voir et gérer tous mes éléments sauvegardés en un seul endroit.

**Acceptance Criteria:**

1. L’écran “Mes Favoris” affiche une liste d’éléments sauvegardés avec leur titre, catégorie et durée.
2. Les utilisateurs peuvent taper sur n’importe quel élément pour voir les détails ou commencer l’activité.
3. La liste des Favoris reste organisée pour une navigation facile et un accès rapide.

**Story Points:** 65
