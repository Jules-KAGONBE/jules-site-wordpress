echo "# jules-site-wordpress

Ce dépôt contient les fichiers essentiels du site WordPress **julesWeb** développé en local avec LocalWP.

## Contenu

- Le dossier \`wp-content/\` : thèmes, plugins et médias du site.
- Le dossier \`database/\` : sauvegarde de la base de données exportée au format SQL.
- Le fichier \`.gitignore\` pour ignorer les fichiers non nécessaires.

## Mise en place du projet

1. Cloner ce dépôt :

\`\`\`bash
git clone https://github.com/Jules-KAGONBE/jules-site-wordpress.git
\`\`\`

2. Copier les fichiers dans le dossier LocalWP correspondant ou configurer un nouvel environnement LocalWP pointant vers ce dossier.

3. Importer la base de données :

- Ouvrir LocalWP, accéder à la base de données via Adminer ou phpMyAdmin.
- Importer le fichier SQL situé dans \`database/local.sql\`.

## Notes

- Le fichier \`wp-config.php\` n'est pas inclus pour des raisons de sécurité.
- Veille à adapter les configurations de connexion à la base de données dans LocalWP selon ton environnement.

---

## Contact

Pour toute question, merci de me contacter.
" > README.md
