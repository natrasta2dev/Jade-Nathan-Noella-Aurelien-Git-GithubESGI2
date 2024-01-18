# Jade-Nathan-Noella-Aurelien-Git-GithubESGI2


Création de branches dans Git

Introduction
Dans Git, les branches sont utilisées pour développer des fonctionnalités isolées les unes des autres. La branche principale est généralement appelée master. Lorsque vous créez une branche, vous créez une nouvelle ligne de développement qui est indépendante de la branche principale.

Commandes de base
git branch
Syntaxe: git branch [nom_de_la_branche]
Description: Crée une nouvelle branche.

Exemple:
git branch ma-nouvelle-branche
git checkout
Syntaxe: git checkout [nom_de_la_branche]

Description: Permet de basculer sur la branche spécifiée.

Exemple:
git checkout ma-nouvelle-branche
Syntaxe alternative: git checkout -b [nom_de_la_branche]

Description: Crée une nouvelle branche et bascule dessus simultanément.

Exemple:
git checkout -b ma-nouvelle-branche


Utilisation courante

Vérifier la branche actuelle:
git branch

Créer une nouvelle branche:
git branch ma-nouvelle-branche

Basculer sur la nouvelle branche:
git checkout ma-nouvelle-branche
Faire des modifications:

Modifier des fichiers.
Utiliser git add pour préparer les changements.
Utiliser git commit pour enregistrer les changements.


Fusionner la branche:

Retourner à la branche principale:
git checkout master

Fusionner la nouvelle branche:
git merge ma-nouvelle-branche


Conclusion
La gestion des branches dans Git est un aspect crucial de la gestion de versions. Elle permet à plusieurs développeurs de travailler sur différentes fonctionnalités en parallèle, sans interférer les uns avec les autres.

