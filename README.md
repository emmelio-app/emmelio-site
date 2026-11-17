# emmelio-site

Site vitrine du studio Emmelio, publié sur https://emmelio.fr via GitHub Pages.
HTML + CSS uniquement : aucun framework, aucun cookie, aucun traceur.

## Structure

| Fichier / dossier            | URL publique                         |
|------------------------------|--------------------------------------|
| `index.html`                 | emmelio.fr/                          |
| `applications/<appli>.html`  | emmelio.fr/applications/<appli>.html |
| `contact.html`               | emmelio.fr/contact.html              |
| `mentions-legales.html`      | emmelio.fr/mentions-legales.html     |
| `kidavie/`                   | emmelio.fr/kidavie/…                 |
| `recruito/`                  | emmelio.fr/recruito/…                |
| `flexibilite-mentale/`       | emmelio.fr/flexibilite-mentale/…     |

## À compléter

Chercher les crochets `[` dans les fichiers : phrases de présentation,
descriptions et fonctionnalités de Recruito et Flexibilité Mentale.

## Textes légaux des applications

Copier le contenu du dossier `site-legal/` de chaque projet dans le dossier
correspondant (les fichiers copiés remplacent la page d'attente `index.html`) :

- Kidavie (à la sortie, une fois les crochets complétés) : contenu de `Kidavie/site-legal/kidavie/` → `kidavie/`
- Flexibilité Mentale : contenu de `flexibilite-mentale/site-legal/` → `flexibilite-mentale/` (fait le 17/11/2026)
- Recruito : contenu de `site-legal/` du projet → `recruito/`

Puis : `git add -A && git commit -m "Textes légaux" && git push`.

## Passer une application en « Disponible »

Dans `index.html` et `applications/<appli>.html`, remplacer
`<span class="statut bientot">Bientôt disponible</span>` par
`<span class="statut dispo">Disponible sur Google Play</span>` et ajouter le lien
: `<a href="https://play.google.com/store/apps/details?id=...">Voir sur Google Play</a>`.
