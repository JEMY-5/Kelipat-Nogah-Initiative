# Skills & Design Rules: SCP Foundation CSS Themes

## 1. Identité Visuelle & Codes Couleurs SCP
- **Style Industriel / Dossier Classifié** : Privilégier les tons sombres, gris acier, ou les contrastes marqués typiques des dossiers de la Fondation.
- **Blocs d'avertissement (Warning/Notice)** : 
  - Utiliser des bordures nettes et des fonds colorés distincts (ex: rouge/orange pour les alertes de sécurité, jaune pour les notes d'information).
- **Typographie** : Assurer la lisibilité avec des polices standard de type monospace ou sans-serif propres aux thèmes Wikidot.

## 2. Classes CSS Communes & Bonnes Pratiques
- **Compatibilité Wikidot** : Ne pas casser les éléments natifs (comme les sidebars, le top-bar ou les notes de bas de page).
- **Structure propre** : Utiliser des classes explicites (ex: `.scp-box`, `.classified-header`, `.warning-block`).
- **Flexbox/Grid léger** : Préférer les structures simples et robustes pour éviter les bugs d'affichage sur les vieux navigateurs ou mobiles.

## 3. Contraintes de Génération CSS
- Toujours fournir du code CSS pur, bien indenté, sans balises HTML superflues à l'intérieur du style.
- Ne pas utiliser de préfixes propriétaires lourds non supportés par le rendu Wikidot.

## 4. Variables CSS Standards (Palette SCP)
Pour maintenir une cohérence visuelle sur tes pages, l'IA doit utiliser ou s'inspirer de ces variables personnalisées :

- **Fonds & Surfaces** :
  - `--scp-bg: #141414;` (Fond sombre principal - Style dossier classifié)
  - `--scp-panel-bg: #1a1a1a;` (Fond des blocs / tabviews)
- **Textes** :
  - `--scp-text: #b2b2b2;` (Texte standard lisible sur fond sombre)
  - `--scp-header-text: #ddd;` (Titres)
- **Accents & Alertes** :
  - `--scp-accent: #990000;` (Le rouge classique de la Fondation SCP)
  - `--scp-warning: #b38f00;` (Jaune/Orange pour les notes de sécurité)
- **Bordures** :
  - `--scp-border: #333333;` (Bordures de cadres et séparateurs)