# Bernardaud SI - Apercu frontend, version 2

Copie du premier apercu (`bernardaudsi-preview`, commit a9327aa) avec les retours de la
relecture de novembre 2026. Le premier apercu reste inchange : les deux versions se
comparent cote a cote.

Apercu statique francais / anglais, 26 pages internes (contre 33), navigation, images
et preferences locales. Aucun serveur, backoffice, identifiant ou document de relecture
interne n'est publie.

## Ce qui change par rapport a la version 1

- Presentation : trois pages (presentation generale, histoire, outil industriel) au lieu de cinq.
- Offre : trois offres (ceramiques techniques, imprimerie serigraphique, traitements de surface et decoration) ;
  mise en forme, deliantage et frittage sont integres aux ceramiques techniques.
- Marches : defense, horlogerie, industrie ; la page defense suit la plaquette balistique.
- Materiaux : les deux alumines sont fusionnees en une page.
- Actualites : une seule page (salons et publication).
- Accueil : expertises et marches, titres et visuels seulement.
- Textes : ton affirmatif et factuel, sans renvois entre pages ni bandeau de contact repete.

Les anciennes adresses (historique, production, contenants...) redirigent vers la page qui les remplace
(`routes.js`).

## Publication

GitHub Pages : branche main, dossier racine, avec .nojekyll.
La balise `<base href>` de `index.html` et de `404.html` doit porter le nom du depot
(`/bernardaudsi-preview-v2/`).
Ce site de demonstration est public et demande a ne pas etre indexe.

Les photographies et le logo restent la propriete de leurs ayants droit.
Polices Manrope sous OFL et icones Lucide sous ISC : licences conservees dans assets.
