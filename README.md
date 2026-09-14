# mon-projet

Centre applicatif — intégration du **Paris Social Planner V3**.

## Structure

- `database/` — documentation et éléments liés aux données du projet.
- `apps/paris-social-planner/` — application web statique Paris Social Planner.
- `.github/workflows/deploy-pages.yml` — déploiement automatique vers GitHub Pages à chaque push sur `main`.

## Paris Social Planner V3

Application web statique sans dépendance ni étape de build.

Fonctionnalités :
- choix de période : week-end, jour précis, semaine ou période personnalisée ;
- génération de 3 scénarios de journée complète ;
- détail du parcours en 7 étapes, du matin à la soirée ;
- nouveau tirage aléatoire ;
- favoris persistants dans le navigateur (`localStorage`) ;
- interface responsive mobile / desktop ;
- rappel de bonnes pratiques : ne pas déduire la disponibilité d'une personne de sa solitude ou de son apparence et respecter tout désintérêt ou refus.

### Lancer localement

Ouvrir `apps/paris-social-planner/index.html` dans un navigateur. Aucun build ni dépendance n'est requis.

### Publication

Le site est destiné à être publié par GitHub Pages depuis le workflow `.github/workflows/deploy-pages.yml`.

URL attendue : `https://patrick-convivium.github.io/mon-projet/`
