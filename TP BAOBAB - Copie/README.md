# 🌳 Le Baobab Gourmand

Site vitrine d'un restaurant de cuisine africaine moderne à Dakar, Sénégal.

## Sujet choisi

**Sujet A — Site vitrine de restaurant "Le Baobab Gourmand"**

## Technologies utilisées

- HTML5 (balises sémantiques : header, nav, main, section, article, footer)
- CSS3 (variables CSS, animations, Flexbox, Grid)
- Bootstrap 5.3 (via CDN)
- JavaScript Vanilla (aucun framework)
- Bootstrap Icons 1.13
- Google Fonts (Playfair Display + Lato)
- Git / GitHub

## Pages réalisées

| Page | Fichier | Description |
|------|---------|-------------|
| Accueil | `index.html` | Bannière hero, carousel, plats vedettes, témoignages, CTA |
| Menu | `menu.html` | Grille de plats avec filtre dynamique par catégorie |
| À Propos | `about.html` | Histoire, valeurs, équipe, récompenses |
| Contact | `contact.html` | Formulaire validé en JS, infos pratiques, carte |

## Fonctionnalités JavaScript

- ✅ Validation en temps réel du formulaire de contact (champs requis, email, téléphone)
- ✅ Filtre dynamique du menu par catégorie (Tout / Entrées / Plats / Desserts / Boissons)
- ✅ Carousel Bootstrap présentant 3 plats signature
- ✅ Bouton « retour en haut » apparaissant au scroll (>400px)
- ✅ Navbar qui rétrécit au scroll
- ✅ Animations au scroll (Intersection Observer API)
- ✅ Lien actif automatique dans la navbar selon la page courante

## Composants Bootstrap utilisés

1. **Navbar** — responsive avec menu hamburger mobile
2. **Carousel** — diaporama automatique des plats signature
3. **Cards** — présentation des plats, valeurs, équipe, témoignages
4. **Modal** — popup informations allergènes
5. **Alert** — bandeau menu du jour + message de succès formulaire
6. **Badge** — catégorisation des plats
7. **Form** — formulaire de contact avec validation

## Structure des fichiers

```
baobab-gourmand/
├── index.html          # Accueil
├── menu.html           # Menu avec filtre
├── about.html          # À Propos
├── contact.html        # Contact & Réservation
├── css/
│   └── style.css       # CSS personnalisé (>250 lignes)
├── js/
│   └── script.js       # JavaScript vanilla
└── README.md
```

## Site en ligne

> À déployer sur GitHub Pages : `https://[votre-pseudo].github.io/baobab-gourmand/`

## Palette de couleurs

| Nom | Hex | Usage |
|-----|-----|-------|
| Terre de Sienne | `#8B4513` | Liens, accents |
| Safran | `#E8A020` | Couleur principale, CTA |
| Vert forêt | `#2D5A27` | Sections foncées |
| Ivoire | `#FAF3E0` | Fond clair |
| Brun nuit | `#3E1F06` | Navbar, headers sombres |

## Typographie

- **Titres** : Playfair Display (serif élégant)
- **Corps** : Lato (sans-serif lisible)

## Équipe

- **[Votre Prénom Nom]** — Étudiant(e) L1, module Développement Web Front-end

## Remerciements

Projet réalisé dans le cadre du module Développement Web Front-end.
Images : [Unsplash](https://unsplash.com) · Icônes : [Bootstrap Icons](https://icons.getbootstrap.com)