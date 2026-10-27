# Panel de direction — aperçu GitHub Pages

Le panel est une application statique en HTML, CSS et JavaScript, sans compilation. L’interface permet de naviguer entre les rubriques, rechercher et filtrer les tâches, en créer et modifier leur statut. Les modifications de tâches sont enregistrées dans le stockage local du navigateur utilisé.

## Limites de GitHub Pages

GitHub Pages publie les fichiers à toute personne disposant de l’adresse du site. Il ne fournit pas de serveur, base de données, authentification privée, permissions serveur, sessions sécurisées, journal d’audit fiable ni stockage partagé. Le bandeau « Aperçu statique » le signale dans l’interface. Les données affichées sont des exemples et ne doivent pas être considérées comme des données de serveur réelles. Ne saisis aucune information confidentielle.

Pour répondre au cahier des charges de sécurité et de collaboration, il faudra déplacer le panel vers un hébergeur d’application avec backend, authentification et PostgreSQL. Une API peut ensuite remplacer le stockage navigateur. Un site GitHub Pages seul ne peut pas fournir ces garanties.

## Personnalisation et publication

1. Remplace le nom NOCTURNE RP et les données d’exemple dans `index.html` et `script.js`.
2. Envoie `index.html`, `style.css`, `script.js` et `recrutement.html` à la racine du dépôt GitHub.
3. Dans **Settings → Pages**, sélectionne **Deploy from a branch**, la branche `main` et le dossier `/(root)`.
4. GitHub affichera l’URL publiée dans les réglages Pages.

La page publique de recrutement est conservée dans `recrutement.html`.
