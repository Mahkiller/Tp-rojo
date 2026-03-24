# Portfolio Mrigon Williamson

## Structure du Projet

```
Tp-rojo/
├── index.html              # Page pour rediriger
├── style/
│   ├── css/
│   │   └── index.css      # CSS compilé
│   │   └── chef.css
│   └── js/
│       └── main.js        # JavaScript (animations + responsive)
├── page/
│   ├──index.html       # d'accueil
│   └──chef.html
└── src/
    └── sass/
        ├── index.scss                    # Point d'entrée SASS
        ├──chef.scss
        ├── _variables.scss               # Variables (couleurs, espacements)
        ├── _mixins.scss                  # Mixins réutilisables
        ├── _base.scss                    # Styles de base
        └── components/
            ├── _navbar.scss              # Navigation
            ├── _hero.scss                # Section hero
            └── _animations.scss          # Keyframes
```

## Technologies

- **HTML5** - Structure sémantique
- **SASS** - Préprocesseur CSS avec architecture modulaire
- **CSS Grid** - Mise en page responsive
- **JavaScript Vanilla** - Animations et interactivité

## Fonctionnalités

### Navigation
- Effet de remplissage du bas vers le haut sur hover
- Menu hamburger responsive
- Glassmorphism effect

### Section Hero
- Diaporama automatique (5 secondes)
- 3 images en arrière-plan avec transition fluide
- Animations d'entrée (fadeInUp)
- Bouton CTA avec effet de levée

### Responsive
- Mobile: < 768px
- Tablet: < 1024px
- Desktop: > 1024px

## Compiler le SASS

```bash
sass src/sass/index.scss dict/css/index.css
```

Ou utilisez watch mode:
```bash
sass --watch src/sass:dict/css
```
