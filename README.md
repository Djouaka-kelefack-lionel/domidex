# Photosens - Site Web Photographe

Un site web moderne et interactif pour un photographe professionnel, mettant en valeur un design élégant avec des effets visuels sophistiqués.

## 🎨 Design & Style

### Palette de Couleurs
- Vert néon (`#CCFF00`) pour les accents et effets de lueur
- Fond sombre (`#0A0A0A`) pour un contraste optimal
- Texte blanc (`#FFFFFF`) pour la lisibilité

### Typographie
- Police principale : 'Inter', sans-serif
- Hiérarchie de taille de texte claire
- Effets de soulignement animés sur les liens

## 🎭 Effets Visuels Principaux

### Effets de Fond
1. **Gradient Dynamique**
   - Fond dégradé du noir au gris foncé
   - Effet de lueur radiale pulsante en arrière-plan
   - Particules animées en arrière-plan

### Header
1. **Barre de Navigation**
   - Fond semi-transparent avec effet de flou (backdrop-filter)
   - Bordure inférieure subtilement lumineuse
   - Liens avec animation de soulignement au survol

### Portfolio Grid
1. **Disposition des Images**
   - Grille avec décalage alterné (zigzag)
   - Gap de 20px entre les éléments
   - Images responsives avec object-fit: cover

2. **Effets sur les Images**
   - Transformation 3D avec preserve-3d
   - Effet de survol avec translation et mise à l'échelle
   - Bordure lumineuse apparaissant au survol
   - Overlay avec dégradé au survol
   - Animation de distorsion subtile
   - Effet de lueur pulsante

### Animations
1. **Effets Parallax**
   - Animation de flottement sur les éléments du hero
   - Délais d'animation différents pour créer de la profondeur

2. **Animations au Survol**
   - Transitions fluides avec cubic-bezier
   - Rotations 3D sur les cartes
   - Effets de lueur et d'ombre
   - Changements de luminosité et de contraste

### Footer
1. **Design**
   - Fond semi-transparent avec effet de flou
   - Disposition en trois colonnes
   - Liens sociaux avec animations au survol
   - Bordure supérieure subtilement lumineuse

## 📱 Responsive Design

### Points de Rupture
- Desktop : > 1200px
- Tablette : 768px - 1200px
- Mobile : < 768px

### Adaptations
1. **Navigation**
   - Menu masqué sur mobile
   - Ajustement des paddings et marges
   - Réorganisation du footer en colonnes

2. **Portfolio**
   - Grille flexible sur les petits écrans
   - Taille des images adaptative
   - Espacement optimisé

## ⚡ Effets 3D et Perspective

1. **Transformations 3D**
   - Utilisation de perspective (1000px-2000px)
   - transform-style: preserve-3d
   - Rotations et translations sur l'axe Z

2. **Effets de Profondeur**
   - Ombres dynamiques
   - Superposition de couches
   - Effets de parallaxe

## 🛠 Technologies Utilisées

- HTML5 sémantique
- CSS3 avancé
  - Variables CSS
  - Flexbox
  - Animations et transitions
  - Transformations 3D
  - Filtres et effets visuels

## 🎯 Performance

- Optimisation des animations avec transform
- Utilisation de will-change pour les performances
- Transitions optimisées avec cubic-bezier
- Effets de flou appliqués avec parcimonie

## 📦 Structure des Fichiers

```
├── index.html
├── style.css
└── img/
├── project1.jpg
├── project2.jpg
├── project3.jpg
├── project4.jpg
└── project5.jpg
```

## 🚀 Installation

1. Cloner le repository
2. Placer les images dans le dossier `/img`
3. Ouvrir index.html dans un navigateur moderne

## 💻 Compatibilité

- Chrome (dernières versions)
- Firefox (dernières versions)
- Safari (dernières versions)
- Edge (dernières versions)

## ⚠️ Notes Importantes

- Nécessite un navigateur moderne supportant les effets CSS avancés
- Les effets 3D peuvent être désactivés sur les appareils à faible puissance
- Les images doivent être optimisées pour le web
