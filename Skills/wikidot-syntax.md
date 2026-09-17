# Skills & Syntax Guidelines: Wikidot & SCP CSS

## 1. Structure de base & Blocs Wikidot
- **Divs personnalisées** : Utiliser la syntaxe native Wikidot pour les blocs, par exemple :
  [[div class="my-box"]]
  Contenu ici
  [[/div]]
- **Blocs repliables (Collapsible)** : 
  [[collapsible show="Afficher" hide="Masquer"]]
  Contenu caché...
  [[/collapsible]]
- **Tabviews (Onglets)** :
  [[tabview]]
  [[tab Onglet 1]]
  Contenu 1
  [[/tab]]
  [[tab Onglet 2]]
  Contenu 2
  [[/tab]]
  [[/tabview]]

## 2. Intégration CSS (Thèmes SCP)
- Ne jamais utiliser de balises <style> mal fermées. Toujours encapsuler le CSS proprement.
- Utiliser les variables natives de Wikidot ou du thème Sigma/BHL si applicables.
- Classes spécifiques SCP : Assurez-vous de respecter le style "dark/industrial" ou "classified" typique des thèmes de la Fondation.

## 3. Contraintes de génération
- Ne pas inventer de balises HTML/JS non supportées par le moteur Wikidot.
- Écrire le code de manière modulaire (CSS d'un côté, structure Wikidot de l'autre).