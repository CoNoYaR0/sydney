# Architecture WordPress Professionnelle

Ce dépôt contient l'architecture d'un projet WordPress professionnel basé sur le thème "Sydney".

## Structure

- **Thème Parent :** Le thème original "Sydney" est situé dans `wp-content/themes/sydney`. **NE JAMAIS MODIFIER CE DOSSIER.** Il est géré comme une dépendance et doit pouvoir être mis à jour sans conflit.

- **Thème Enfant :** Toutes les personnalisations (CSS, PHP, templates) doivent être effectuées dans le thème enfant, situé dans `wp-content/themes/sydney-child`. C'est le cœur de notre développement.

- **`.gitignore` :** Le fichier `.gitignore` est configuré pour ne suivre que le thème enfant. Le cœur de WordPress, les plugins et autres thèmes sont exclus du versioning.

## Workflow de Développement

1.  **Installation :** Mettre en place une installation WordPress standard.
2.  **Thèmes :** Cloner ce dépôt. Le thème "Sydney" est inclus pour la commodité, et le thème "Sydney Child" est prêt à l'emploi.
3.  **Activation :** Depuis l'administration WordPress, activez le thème "Sydney Child".
4.  **Développement :** Effectuez toutes les modifications dans le dossier `wp-content/themes/sydney-child`.

Cette structure garantit la maintenabilité, la sécurité et la scalabilité du projet, conformément aux meilleures pratiques de développement WordPress.
