# Parcours nouvel arrivant Enedis — Socle Marché de Masse

Mise en page dynamique, ludique et pédagogique (couleurs Enedis, accessibilité WCAG AA) destinée aux apprenants et aux managers.

## Contenu

- `bloc-lms.html` : fragment HTML autonome à coller dans un **bloc HTML** d'une page du LMS « Expérience » (Bealink). CSS et JavaScript intégrés, sélecteurs préfixés `#pna` pour éviter tout conflit avec la charte du LMS.

## Fonctionnalités

- Suivi de progression par apprenant (anneau global, barres par étape, statuts « À venir / En cours / Terminée »), sauvegarde locale (localStorage).
- 4 étapes : accueil et acculturation, bases techniques de l'électricité, relation clients Marché de Masse, spécifique métier.
- Étape 4 : deux parcours métier optionnels (CRC ACH C5/AD et CRC Gestion et Raccordement Petits Producteurs), sélection en accord avec le manager.
- Liens vers les formations Syfadis (« Expérience »).
- Mode manager avec export CSV du suivi.
- Accessibilité : structure sémantique ARIA, navigation clavier, focus visible, respect de « prefers-reduced-motion ».

## Intégration

1. Ouvrir une page du LMS Expérience (Bealink) en édition.
2. Ajouter un bloc HTML et coller le contenu de `bloc-lms.html` en mode source / HTML brut.
3. Publier et vérifier le rendu (styles et scripts non filtrés par l'éditeur).

> Remarque : si le LMS bloque le JavaScript dans les blocs, demander la variante statique (suivi désactivé, même mise en page).
