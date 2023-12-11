# Atelier Git et GitHub Avancé
Durée : 2 heures

Objectifs :

Maîtriser les fonctionnalités avancées de Git et GitHub.
Améliorer la collaboration et la gestion de projets sur GitHub.

# 1. Branching et Merging Avancés
Exercice : Gestion de Branches et Résolution de Conflits

Tâche 1: Créez un nouveau repository sur GitHub. Clonez-le localement.

Tâche 2: Créez trois branches séparées (feature-1, feature-2, bug-fix) à partir de main.

Tâche 3: Dans chaque branche, modifiez un fichier commun (par exemple, README.md) de manière différente.

Tâche 4: Fusionnez feature-1 dans main, puis essayez de fusionner feature-2. Résolvez les conflits qui apparaissent.

Tâche 5: Fusionnez bug-fix dans main en utilisant une stratégie de merge différente (par exemple, rebase).


# 2. Gestion des Pull Requests et Code Reviews
Exercice : Collaboration avec Pull Requests

Tâche 1: Sur le même repository, invitez un autre participant comme collaborateur.

Tâche 2: Créez une nouvelle branche (enhancement) et apportez des modifications significatives.

Tâche 3: Poussez cette branche sur GitHub et créez une Pull Request.

Tâche 4: Le collaborateur doit effectuer une revue de code, commenter et suggérer des modifications.

Tâche 5: Apportez les modifications suggérées et fusionnez la Pull Request.


# 3. Automatisation avec GitHub Actions
Exercice : Mise en Place d'un Workflow d'Intégration Continue

Tâche 1: Créez un fichier .github/workflows/main.yml dans votre repository.

Tâche 2: Rédigez un workflow simple pour exécuter des tests automatiques (utilisez un framework de test de votre choix).

Tâche 3: Faites un commit et poussez les changements. Vérifiez que le workflow se déclenche et s'exécute correctement.

Tâche 4: Introduisez volontairement une erreur dans votre code et observez l'échec du workflow.

# 4. Gestion avancée des Issues et Project Boards
Exercice : Organisation d'un Projet avec Issues et Project Board

Tâche 1: Créez un Project Board pour votre repository avec des colonnes telles que To Do, In Progress, Done.

Tâche 2: Créez différentes issues représentant des tâches ou des bugs.

Tâche 3: Liez ces issues à des Pull Requests spécifiques.

Tâche 4: Déplacez les issues dans le Project Board au fur et à mesure de leur progression.


# 5: Exploration des Historiques de Commits
Objectif: Comprendre comment naviguer dans l'historique des commits.

Tâche 1: Clonez un repository Git existant avec un historique de commits substantiel.

Tâche 2: Utilisez git log pour visualiser l'historique des commits.

Tâche 3: Identifiez un commit spécifique et utilisez git checkout [commit-hash] pour voir l'état du projet à ce moment-là.

Tâche 4: Explorez les commandes git diff pour comparer les modifications entre deux commits.


# 6: Gestion des Stash et Cherry-Pick
Objectif: Maîtriser les commandes git stash et git cherry-pick.

Tâche 1: Commencez à travailler sur une nouvelle fonctionnalité dans une branche, mais ne terminez pas.

Tâche 2: Utilisez git stash pour mettre de côté vos modifications en cours.

Tâche 3: Changez de branche, faites d'autres modifications et committez-les.

Tâche 4: Revenez à votre branche initiale et utilisez git stash pop pour récupérer vos modifications.

Tâche 5: Identifiez un commit dans une autre branche et utilisez git cherry-pick [commit-hash] pour appliquer ces modifications à la branche actuelle.


# 7: Gestion des Branches et Rebasing
Objectif: Comprendre le rebasing et la gestion avancée des branches.

Tâche 1: Créez une nouvelle branche (feature-x) et ajoutez quelques commits.

Tâche 2: Revenez à la branche principale (main) et ajoutez d'autres commits.

Tâche 3: Utilisez git rebase main sur la branche feature-x pour repositionner ses commits sur le dessus de la branche main.

Tâche 4: Résolvez les conflits potentiels qui peuvent survenir pendant le rebase.


# 8: Utilisation des Tags et Releases
Objectif: Comprendre comment utiliser les tags pour marquer des versions spécifiques.

Tâche 1: Sur le repository principal, identifiez un commit qui représente une version stable du projet.

Tâche 2: Utilisez git tag -a v1.0 [commit-hash] -m "Version 1.0" pour marquer ce commit comme une version.

Tâche 3: Poussez ce tag sur le repository distant avec git push origin v1.0.

Tâche 4: Listez tous les tags existants et explorez les commandes pour supprimer ou déplacer un tag.


# 9: Collaboration et Résolution de Conflits

Objectif: Pratiquer la collaboration et la résolution de conflits dans Git.

Tâche 1: Travaillez en groupe sur un même repository. Chaque membre doit créer sa propre branche et y apporter des modifications.

Tâche 2: Tous les membres doivent ensuite essayer de fusionner leurs branches avec main.

Tâche 3: Si des conflits surviennent, utilisez les outils de résolution de conflits de Git pour les résoudre.

Tâche 4: Discutez des stratégies pour éviter les conflits à l'avenir et la meilleure façon de les gérer lorsqu'ils se produisent.


