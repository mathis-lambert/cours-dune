[//]: <> (https://stackedit.io/app#)
# Versionning GIT


## Bonnes pratiques en programmation.
- Lisibilité du code
> Écrivez votre code de manière à ce qu'il soit lisible par d'autres.
- Commentaires pertinents
> Commentez le pourquoi, pas le comment.
- Nommer judicieusement
> Utilisez des noms de variables, de fonctions et de classes qui décrivent leur utilité ou leur fonction. il faut pouvoir comprendre une fonction ou une variable uniquement grâçe à son nom !
- Diviser le code en fonctions et classes 
>Évitez les fonctions monolithiques. Divisez votre code en fonctions ou méthodes plus petites, chacune effectuant une tâche spécifique. Utilisez des classes pour regrouper des fonctionnalités liées.
- Nommage des variables
> Utilisez des noms de variables qui décrivent leur utilité ou leur fonction. il faut pouvoir comprendre une variable uniquement grâçe à son nom !
- Syntaxe et indentation
>variables (let)	**camelCase** 	premier lettre en minuscule et tous les autres mots ont leur premiere lettre en maj parExempleCommeCa

>constantes (const)	**camelCase** 	exeption pour les VRAIES constante par exemple un délai d'attente en secondes qu'on notera tout en majuscule : const TIMER = 2

>classes, id (pour le HTML)	**kebab-case**	exemple : ma-super-div sans majuscule

>propriétés (clés dans les objet js ou JSON)	**snake_case**	exemple : ma_propriete

>Nom des composants (nom du fichier .jsx)	**PascalCase**	par exemple le composant boutton envoyer : SendButton.jsx.     PAS: le nom de la fonction interne au composant doit aussi etre en PC
- Éviter la duplication de code
> Ne pas répéter le même code. Si vous avez besoin d'une logique similaire à plusieurs endroits, créez une fonction réutilisable.
- Gérer les erreurs
> Utilisez la gestion des exceptions pour gérer les erreurs plutôt que de renvoyer des codes d'erreur. Cela rend le code plus robuste et plus facile à maintenir.
- Utiliser le même outil de mise en forme
> Prettier, code formatter, etc.
