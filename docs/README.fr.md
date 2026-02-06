# 🎨 Emoji2Pixel

Transformez des emojis et des images en magnifiques œuvres pixel art avec ce puissant convertisseur web. Créez des animations époustouflantes, personnalisez chaque détail et exportez vos créations en images ou GIF.

![Emoji2Pixel Badge](https://img.shields.io/badge/Emoji2Pixel-v1.0-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue) ![Languages](https://img.shields.io/badge/languages-8-orange)

## ✨ Fonctionnalités

### 🖼️ **Sources d'Entrée Multiples**
- **Support Emoji**: Saisissez des emojis directement ou parcourez une bibliothèque complète
- **Import d'Images**: Téléchargez n'importe quel fichier image pour la pixellisation
- **Mode Auto-Ajustement**: Ajuste automatiquement l'échelle de l'emoji pour s'adapter parfaitement au canevas
- **Recherche et Filtre**: Recherche rapide d'emoji avec navigation par catégories

### 🎬 **Système d'Animation**
- **Animation par Images Clés**: Créez des animations fluides avec plusieurs images clés
- **Interpolation de Transition**: Génération automatique d'images de transition entre les images clés
- **Contrôles de Lecture**: Lecture, pause et ajustement de la vitesse d'animation en temps réel
- **Export GIF**: Exportez les animations en fichiers GIF animés

### 🎛️ **Contrôles de Transformation Avancés**
- **Échelle**: Redimensionnez votre œuvre de 0% à 200%
- **Position**: Ajustez finement le décalage X/Y pour un alignement parfait
- **Rotation**: Tournez dans n'importe quelle direction (0-360°)
- **Canevas Interactif**: Manipulation directe par glisser-déposer + Maintenez Shift pour pivoter

### 🎨 **Moteur de Rendu Puissant**
- **Deux Modes de Rendu**:
  - **Mode Idéal**: Pixel art professionnel avec espaces et bordures personnalisables
  - **Mode Brut**: Rendu de pixels pur pour un style rétro authentique
- **Canevas Flexible**: Taille de grille ajustable (8x8 à 128x128 pixels)
- **Styles de Pixels**: Choisissez parmi pixels carrés, arrondis ou circulaires
- **Quantification des Couleurs**: Réduisez la palette de couleurs à 2-256 couleurs pour une esthétique rétro
- **Filtres d'Accentuation**: Améliorez la définition des bords avec une intensité ajustable

### 🖌️ **Outils d'Édition**
- **Suppression d'Arrière-plan**: Suppression intelligente avec contrôle de tolérance
- **Outils de Sélection**: Sélection rectangulaire avec remplissage, effacement, copier-coller
- **Système de Calques**: Flux de travail d'édition non destructif
- **Support d'Annulation**: Annulez les opérations de sélection de couleur et de suppression d'arrière-plan

### 📏 **Options d'Export Professionnelles**
- **Unités Multiples**: Travaillez en millimètres, pouces ou unités de grille
- **Préréglages de Taille**: Préréglages rapides pour les tailles d'affichage courantes
- **Formats d'Export**:
  - PNG (avec transparence)
  - GIF (animé ou statique)
  - Données de pixels brutes
- **Rendu de Cadre**: Visualisez la disposition physique des pixels avec des dimensions réelles

### 🌍 **Support International**
Traductions intégrées en 8 langues:
- 🇨🇳 简体中文 (Chinois simplifié)
- 🇺🇸 English (Anglais)
- 🇫🇷 Français
- 🇩🇪 Deutsch (Allemand)
- 🇮🇹 Italiano (Italien)
- 🇯🇵 日本語 (Japonais)
- 🇰🇷 한국어 (Coréen)
- 🇪🇸 Español (Espagnol)

## 🚀 Démarrage Rapide

### Démo en Ligne
Visitez la démo en ligne : [https://thomas-hiddenpeak.github.io/emoji2pixel](https://thomas-hiddenpeak.github.io/emoji2pixel)

### Développement Local

1. **Clonez le dépôt**
   ```bash
   git clone https://github.com/thomas-hiddenpeak/emoji2pixel.git
   cd emoji2pixel
   ```

2. **Servir localement**
   
   Avec Python :
   ```bash
   python -m http.server 8000
   ```
   
   Ou avec Node.js :
   ```bash
   npx http-server -p 8000
   ```

3. **Ouvrir dans le navigateur**
   ```
   http://localhost:8000
   ```

Aucun processus de build requis ! C'est une application web statique pure.

## 📖 Guide d'Utilisation

### Flux de Travail de Base

1. **Entrée**: Saisissez un emoji ou téléchargez une image
2. **Transformation**: Ajustez l'échelle, la position et la rotation à votre goût
3. **Ajouter un Cadre**: Cliquez sur le bouton `+` pour ajouter à votre animation
4. **Personnaliser**: Ajustez les paramètres de rendu, le style des pixels et les couleurs
5. **Exporter**: Téléchargez en PNG ou GIF

### Raccourcis Clavier

| Raccourci | Action |
|-----------|--------|
| `Espace` | Basculer la lecture de l'animation |
| `Entrée` | Ajouter la vue actuelle comme image clé |
| `Suppr` / `Retour arrière` | Supprimer l'image sélectionnée |
| `←` / `→` | Naviguer entre les images |
| `Échap` | Annuler la sélection/sélection de couleur |
| `Ctrl/Cmd + C` | Copier la sélection |
| `Ctrl/Cmd + V` | Coller la sélection |

### Astuces Pro

- 🎯 **Maintenez Shift** tout en faisant glisser sur le canevas pour pivoter au lieu de déplacer
- 🔍 Utilisez la **Quantification des Couleurs** (8-64 couleurs) pour un pixel art rétro authentique
- ⚡ Activez l'**Accentuation** (30-50% d'intensité) pour améliorer la clarté des bords
- 🎬 Réglez les **Images de Transition** sur 5-10 pour des animations fluides
- 📐 Utilisez le **Mode de Rendu de Cadre** pour visualiser les dispositions de matrices LED physiques

## 🛠️ Stack Technique

- **Frontend Pur**: HTML5, CSS3, JavaScript Vanilla
- **Aucune Dépendance**: Zéro bibliothèque ou framework externe
- **API Canvas**: Manipulation de pixels haute performance
- **GIF.js**: Encodage GIF côté client
- **Design Responsive**: Fonctionne sur ordinateur et tablette

## 📁 Structure du Projet

```
emoji2pixel/
├── index.html          # Structure HTML principale
├── app.js              # Logique d'application principale
├── styles.css          # Style et mise en page
├── locales/            # Internationalisation
│   ├── index.json      # Manifeste des langues
│   ├── fr-FR.json      # Traductions françaises
│   ├── en-US.json      # Traductions anglaises
│   └── ...             # Autres langues
├── docs/               # Documentation multilingue
│   ├── README.fr.md    # Documentation française
│   ├── README.en.md    # Documentation anglaise
│   └── ...             # Autres langues
└── scripts/            # Utilitaires de build
    └── generate_locales_index.py
```

## 🌐 Ajouter de Nouvelles Langues

1. Créez un nouveau fichier de langue dans `locales/` (par ex., `pt-BR.json`)
2. Copiez la structure d'un fichier de langue existant
3. Traduisez toutes les clés dans votre langue cible
4. Ajoutez un champ `selfName` avec un emoji de drapeau
5. Exécutez le générateur d'index de langues :
   ```bash
   python scripts/generate_locales_index.py
   ```

La nouvelle langue apparaîtra automatiquement dans le sélecteur de langue !

## 🤝 Contribuer

Les contributions sont les bienvenues ! Voici comment vous pouvez aider :

- 🐛 Signaler des bugs et problèmes
- 💡 Suggérer de nouvelles fonctionnalités
- 🌍 Ajouter ou améliorer les traductions
- 📝 Améliorer la documentation
- 🎨 Soumettre des vitrines de pixel art

### Lignes Directrices de Développement

1. Forkez le dépôt
2. Créez une branche de fonctionnalité (`git checkout -b feature/amazing-feature`)
3. Commitez vos changements (`git commit -m 'Add amazing feature'`)
4. Poussez vers la branche (`git push origin feature/amazing-feature`)
5. Ouvrez une Pull Request

## 📄 Licence

Ce projet est sous licence MIT - voir le fichier [LICENSE](../LICENSE) pour plus de détails.

## 🙏 Remerciements

- Données emoji provenant des standards Unicode
- Inspiré par les outils de pixel art classiques et les affichages de matrices LED
- Construit avec ❤️ pour la communauté pixel art

## 📮 Contact et Support

- **Problèmes**: [GitHub Issues](https://github.com/thomas-hiddenpeak/emoji2pixel/issues)
- **Discussions**: [GitHub Discussions](https://github.com/thomas-hiddenpeak/emoji2pixel/discussions)

---

<div align="center">

**Fait avec 🎨 et ⌨️**

Si vous trouvez ce projet utile, pensez à lui donner une ⭐ !

[English](README.en.md) | [简体中文](README.zh-CN.md) | [Deutsch](README.de.md) | [Italiano](README.it.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Español](README.es.md)

</div>
