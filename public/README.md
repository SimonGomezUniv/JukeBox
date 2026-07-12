# SonicGlass - Premium Floating Lyric Speaker

Une application web premium inspirée du MorningBlues SonicGlass A1, créée en un seul fichier HTML autonome.

## 🎯 Utilisation

### Démarrage rapide
1. **Double-cliquez** sur `index.html` pour l'ouvrir dans votre navigateur
2. Ou utilisez un serveur web : `python -m http.server` puis ouvrez http://localhost:8000

### Charger un fichier audio
- **Glisser-déposer** un fichier audio (MP3, WAV, MP4, etc.) sur l'interface
- Ou cliquez sur les contrôles pour sélectionner un fichier

### Charger les paroles
- **Glisser-déposer** un fichier LRC avec le fichier audio
- Ou **coller** les paroles synchronisées (format LRC) ou du texte brut
- Les paroles brutes seront distribuées uniformément sur la durée de la piste

## ✨ Fonctionnalités

### 🎨 5 Modes d'affichage spectaculaires
1. **Floating** - Paroles flottantes en 3D avec profondeur et effets cinématiques
2. **Karaoke** - Remplissage ultra-fluide avec bloom dynamique
3. **Neon** - Effet enseigne néon avec glow réaliste et flickering subtil
4. **Wave** - Animation de vague où chaque caractère vit indépendamment
5. **Minimal** - Ultra épuré avec animations extrêmement élégantes

### 🎵 Visualiseur Audio Premium
- Réaction organique aux basses
- Haut-parleur en verre flottant multi-couches
- Effets de respiration synchronisés à la musique
- Rotation lente avec inertie
- Parallaxe suivant la souris

### 🌌 Fond Vivant
- Nébuleuses animées
- Rayons volumétriques (god rays)
- Halos lumineux concentriques
- Particules flottantes avec profondeur
- Gradients animés
- Mouvement très lent et organique

### 🎛️ Contrôles
- Auto-masquage pendant la lecture
- Réapparaissent au survol/toucher
- Design discret inspiré d'Apple Music
- Volume, lecture, pause, timeline interactive
- Sélection des modes d'affichage

### 📱 Responsive Design
- Optimisé pour iPhone (avec support des encoches)
- Android
- iPad
- Desktop
- Safe area insets pour tous les appareils modernes

## 🔧 Architecture Technique

### Classes JavaScript
- `AnimationSystem` - Système d'animations premium avec easing personnalisé
- `AudioEngine` - Web Audio API, analyse de fréquence
- `ParticleSystem` - Système de particules flottantes
- `BackgroundRenderer` - Rendu Canvas (nébuleuses, god rays, halos)
- `SpeakerVisualizer` - Haut-parleur en verre 3D avec breathing
- `LyricsRenderer` - Moteur de rendu des 5 modes de paroles
- `ControlsManager` - Gestion de l'interface utilisateur

### Technologies Utilisées
- **HTML5** - Structure sémantique avec ARIA labels
- **CSS3** - Glassmorphism, backdrop-filter, mix-blend-mode, mask-image
- **JavaScript ES6+** - Classes natives, async/await
- **Canvas 2D** - Effets visuels, particules, arrière-plan
- **Web Audio API** - Analyse audio en temps réel avec AnalyserNode
- **Google Fonts** - Inter, Manrope, Space Grotesk

### Performances
- **60 FPS** maintenu via requestAnimationFrame
- DPR capé à 2 pour les écrans haute densité
- Optimisation Canvas avec dirty regions
- Optimisation DOM avec transforms 3D (GPU)
- Throttling intelligent des calculs coûteux

## 🎨 Direction Artistique

### Inspirations
- MorningBlues SonicGlass A1
- Apple (Vision Pro, Dynamic Island, Apple Music)
- Nothing
- Teenage Engineering
- Interfaces Awwwards
- Science-fiction minimaliste (Blade Runner 2049)

### Principes de Design
- **Minimalisme** - Beaucoup d'espace vide, une seule phrase attire l'œil
- **Respiration** - L'interface respire au rythme de la musique
- **Profondeur** - Effets de profondeur et parallaxe
- **Fluidité** - Animations premium avec inertie et anticipation
- **Premium** - Sentiment de produit haut de gamme

## 📝 Format LRC

Les paroles peuvent être chargées au format LRC standard :

```
[00:12.50]Première ligne de paroles
[00:17.20]Deuxième ligne de paroles
[00:21.80]Troisième ligne de paroles
```

Ou en texte brut (distribué automatiquement sur la durée de la piste).

## 🌐 Compatibilité Navigateur

- ✅ Chrome 90+ (recommandé)
- ✅ Edge 90+
- ✅ Safari 14+
- ✅ Firefox 88+
- ✅ iOS Safari 14+
- ✅ Chrome Mobile

**Requis:**
- Support de `backdrop-filter`
- Support de `mix-blend-mode`
- Web Audio API
- Canvas 2D

## 📦 Contenu du Fichier

**Tout est contenu dans `index.html` :**
- HTML sémantique
- CSS inline (>700 lignes)
- JavaScript inline (~1800 lignes)
- Aucune dépendance externe (sauf Google Fonts)
- Fonctionne 100% offline

## 🎯 Raccourcis Clavier

- **Espace** - Lecture/Pause
- **←/→** - Reculer/Avancer de 5 secondes
- **↑/↓** - Volume +/-
- **M** - Mute
- **1-5** - Changer de mode d'affichage

## 🐛 Dépannage

### Aucun son
- Vérifiez que le fichier audio est supporté par votre navigateur
- Essayez de cliquer sur play (certains navigateurs bloquent l'autoplay)

### Pas de paroles
- Vérifiez le format LRC (timestamps en [mm:ss.ms])
- Essayez de coller du texte brut dans l'interface

### Performance
- Réduisez la taille de la fenêtre sur les appareils faibles
- Fermez les autres onglets gourmands
- Essayez un navigateur basé sur Chromium

### Effets visuels manquants
- Vérifiez que backdrop-filter est supporté (Safari peut nécessiter le préfixe -webkit-)
- Vérifiez que l'accélération matérielle est activée

## 📄 Licence

Projet personnel - Code source ouvert

## 🙏 Crédits

Inspiré par l'expérience MorningBlues SonicGlass A1 et la philosophie de design d'Apple, Nothing, et Teenage Engineering.

---

**Profitez de l'expérience SonicGlass ! 🎵✨**
