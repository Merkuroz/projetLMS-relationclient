# Parcours nouvel arrivant Enedis — Socle Marché de Masse

Mise en page dynamique, ludique et pédagogique (couleurs Enedis, accessibilité WCAG AA) destinée aux apprenants et aux managers.

## Contenu

- `index.html` : **page HTML autonome** (document complet, ouvrable directement dans un navigateur). C'est le livrable principal.
- `../archive/bloc-lms-experience-bealink.html` : archive — fragment HTML à coller dans un bloc HTML du LMS « Expérience » (Bealink), si ce mode d'intégration est un jour requis.

## Fonctionnalités

- Suivi de progression par apprenant (anneau global, barres par étape, statuts « À venir / En cours / Terminée »), sauvegarde locale (localStorage).
- 4 étapes : accueil et acculturation, bases techniques de l'électricité, relation clients Marché de Masse, spécifique métier.
- Étape 4 : deux parcours métier optionnels (CRC ACH C5/AD et CRC Gestion et Raccordement Petits Producteurs), sélection en accord avec le manager.
- Liens vers les formations Syfadis (« Expérience »).
- Mode manager avec export CSV du suivi.
- Accessibilité : structure sémantique ARIA, navigation clavier, focus visible, respect de « prefers-reduced-motion ».

## Utilisation

Ouvrir `index.html` dans un navigateur, ou l'héberger et partager le lien aux apprenants et managers.
