# CONTEXTE GLOBAL DU PROJET : KELIPAT NOGAH INITIATIVE (KNI)
> *Ce fichier sert de mémoire et de contexte de base pour l'assistant IA (Jan.ai). Il doit être lu avant toute nouvelle génération de code ou de texte.*

## 1. PROFIL DE L'UTILISATEUR & ENVIRONNEMENT
- **Workflow** : L'utilisateur travaille en local avec Jan.ai. Les historiques de chat sont jetables. La mémoire du projet réside exclusivement dans les fichiers du dépôt local, synchronisés via GitHub Desktop. L'utilisateur privilégie des solutions rapides, directes et sans friction (pas de configurations complexes ou de cloud superflu).
- **Matériel (Double PC)** : 
  - **PC Principal** : Machine puissante avec GPU NVIDIA dédié (gère des modèles complexes).
  - **PC Secondaire (Mobilité)** : Laptop AMD Ryzen 5 PRO 4650U, 16Go RAM, GPU intégré (fait tourner Qwen2.5-Coder-1.5B sur CPU).
- **Conséquence pour l'IA** : L'IA doit fournir du code prêt à être copié-collé (CSS, Wikidot) pour faciliter l'intégration rapide via GitHub Desktop.

## 2. UNIVERS & LORE DU PROJET (SCP WIKIDOT)
- **Fondation SCP** : Organisation d'origine, axée sur le confinement strict (Secure, Contain, Protect). Esthétique institutionnelle, clinique, froide.
- **Kelipat Nogah Initiative (KNI)** : Faction scissionniste. Contrairement à la Fondation qui enferme les anomalies à l'aveugle, la KNI étudie l'écorce lumineuse (*Nogah*) cachée sous la matière brute (*Kelipah*). 
- **Tonalité de la KNI** : Ésotérique, sombre, mystique, industrielle. Ils cherchent à comprendre la structure sous-jacente de l'anomalie plutôt que de simplement la cacher.

## 3. ARCHITECTURE DU PROJET
Le projet est organisé dans le dépôt local ainsi :
- `/skills/` : Contient les règles de génération.
  - `wikidot-syntax.md` (règles des Divs, Tabviews, Collapsibles propres à Wikidot).
  - `css-rules.md` (règles de design, variables de couleurs SCP/KNI).
- `/css/` : Feuilles de style.
  - `sigma-9-base.css` (thème classique Fondation).
  - `kni-theme.css` (thème sombre et ésotérique KNI).
- `/pages/` : Brouillons de contenu.
  - `conte-scission-kni.txt` (l'histoire de la rupture avec la Fondation).

## 4. OBJECTIFS DE L'IA POUR CE PROJET
1. **Design CSS** : Développer et affiner le thème *Sigma-9* classique, et concevoir de A à Z le thème *KNI* avec ses propres codes couleurs, blocs d'avertissement et en-têtes classifiés.
2. **Intégration Wikidot** : Convertir tout le design en syntaxe purement compatible avec la plateforme Wikidot (pas de HTML complexe non supporté).
3. **Rédaction de Lore** : Étendre l'univers de la KNI en rédigeant de nouvelles pages, rapports d'anomalies, ou journaux de chercheurs basés sur l'incident de scission.
4. **Assistance au vol** : Répondre aux requêtes de l'utilisateur de manière concise. Ne pas générer de blabla inutile, fournir directement le bloc de code ou le texte demandé.