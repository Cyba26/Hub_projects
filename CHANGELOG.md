# Changelog

Toutes les modifications notables de ce projet sont documentées ici.
Format basé sur [Keep a Changelog](https://keepachangelog.com/fr/1.1.0/).

## [1.0.0] - 2026-02-28

### Added
- Page hub avec header animé (orbites, parallax, grille décorative)
- Grille de projets avec cards au design SF (clip-path, SVG borders)
- Card Pico-8 avec lien vers `/pico8/`
- 5 slots vides "Prochain projet" pour les futurs projets
- Animations scroll reveal avec IntersectionObserver
- Design responsive mobile
- Footer avec copyright et lien portfolio

### Fixed
- Compatibilité Firefox : déplacement du `filter: drop-shadow()` du `.card-inner` vers `.project-card` pour éviter le bug clip-path + filter qui faisait disparaître le contenu des cards au hover
