---
title: "D'IntelliJ à Neovim : Chronique d'une transition inattendue"
author: Benoit Fernandez
---

Qui suis-je ?
===
<!-- column_layout: [1, 3, 2, 1] -->

<!-- column: 1 -->

<!-- new_lines: 2 -->

Benoit Fernandez

Tech Lead

Onepoint

<!-- column: 2 -->

<!-- new_lines: 2 -->
![image:width:100%](moi.jpg)

<!-- reset_layout -->

<!-- end_slide -->

Mon parcours
===
<!-- pause -->
<!-- column_layout: [1, 1] -->

<!-- column: 0 -->
# Expérience
<!-- pause -->
<span style="color: palette:red">Java/Angular</span> depuis plusieurs années
<!-- pause -->
Spécialisé 95% frontend depuis 4-5 ans
<!-- pause -->
Utilisation d'IntelliJ IDEA
<!-- pause -->

<!-- column: 1 -->
# Ce qui me motive
<!-- pause -->
<span style="color: palette:red">Passion d'apprendre</span> et d'expérimenter
<!-- pause -->
Recherche de <span style="color: palette:red">l'état de flux</span> optimal
<!-- pause -->
<!-- reset_layout -->

TODO Image illustrant mon evelotion de setup

<!-- end_slide -->

Vim, c'est quoi ?
===

<!-- new_lines: 2 -->

<!-- pause -->

Vim (Vi IMproved) : éditeur de texte créé par Bram Moolenaar en 1991
<!-- pause -->

Clone de vi (1976)
<!-- pause -->

Philosophie : efficacité et minimalisme
<!-- pause -->

Ajoute des fonctionnalités essentielles

<!-- 
speaker_note: |
  Vi a été créé par Bill Joy en 1976, intégré dans tous les systèmes UNIX.
  Vim (Vi IMproved) ajoute de nombreuses fonctionnalités essentielles :
  - Édition multi-fichiers et multi-fenêtres
  - Annulation multi-niveaux (undo/redo)
  - Coloration syntaxique avancée
  - Complétion intelligente
  - Recherche avec expressions régulières
  - Macros et automatisation
  - Configuration via vimrc
  - Extensible via plugins (VimL/VimScript)
  - Initialement développé pour AmigaOs, d'où son support multi-plateformes amélioré
  - Prise en charge de nombreux encodages
-->

<!-- end_slide -->

Le coeur de Vim
===

<!-- new_lines: 2 -->
<!-- pause -->
<!-- column_layout: [1, 1] -->

<!-- column: 0 -->

# Les modes

<!-- pause -->
**Normal**: navigation et manipulation
<!-- pause -->
**Insertion**: saisie de texte

<!-- pause -->
**Visuel**: sélection de texte

<!-- pause -->
**Commande**: actions spéciales

<!-- column: 1 -->
<!-- pause -->
# Langage d'édition

<!-- pause -->
**Verbes** : actions (d = delete, c = change, y = yank/copy)

<!-- pause -->

**Modificateurs** : quantité, direction (2, i, a)

<!-- pause -->
**Objets**: sur quoi agir (w = word, { = block)

<!-- end_slide -->

![image:width:90%](vim_cheat_sheet.png)
<!-- end_slide -->

Neovim : L'évolution moderne
===

<!-- new_lines: 2 -->
<!-- pause -->
Fork de Vim créé en 2014
<!-- pause -->
100% compatible avec Vim
<!-- pause -->
Extensible en Lua (plus simple que VimScript)
<!-- pause -->
Support natif des protocoles modernes
<!-- pause -->
Écosystème actif et communautaire

<!-- speaker_note: |
Neovim apporte des améliorations majeures à Vim :
- Architecture moderne avec API asynchrone
- Support natif des Language Server Protocols (LSP) pour l'auto-complétion, la navigation, etc.
- Support du Debug Adapter Protocol (DAP) pour le débogage
- Terminal intégré
- Interface graphique détachable (GUI)
- Meilleure gestion des événements et des tâches en arrière-plan
- Communauté très active et innovante
- Configuration plus simple et plus puissante en Lua
- Architecture asynchrone native (plus complète que celle ajoutée à Vim 8)
- Meilleure intégration avec les outils modernes de développement
-->

<!-- end_slide -->
Le Changement Inattendu
===

<!-- new_lines: 2 -->
<!-- column_layout: [1, 1] -->

<!-- column: 0 -->

<!-- pause -->
Reprise après un congé parental
<!-- pause -->
Changement de projet
<!-- pause -->
Environnement dans une VDI sous windows
<!-- pause -->

<!-- column: 1 -->

![image:width:60%](among_panik.png)

<!-- end_slide -->

La passerelle : IdeaVim
===

<!-- column_layout: [1, 2] -->

<!-- column: 0 -->

<!-- new_lines: 2 -->
<!-- pause -->
Plugin pour IntelliJ IDEA
<!-- pause -->
Émulation de Vim
<!-- pause -->

<!-- column: 1 -->
![image:width:90%](extract-ideavimrc.png)
<!-- end_slide -->

![image:width:100%](vim-productive.png)

<!-- end_slide -->

Le déclic
===

<!-- new_lines: 4 -->
<!-- pause -->
Projet perso en Zig
<!-- pause -->
Mauvais support dans IntelliJ
<!-- pause -->
Communauté Zig essentiellement sur Neovim

<!-- end_slide -->

![image:width:100%](hide_pain_harold.png)

<!-- end_slide -->
Démonstration
===

<!-- jump_to_middle -->
🏠 Tour du propriétaire

<!-- end_slide -->

Par où commencer ?
===
<!-- column_layout: [1, 1] -->

<!-- column: 0 -->
# Stratégie progressive
<!-- pause -->
Commencer avec <span style="color: palette:red">IdeaVim</span> ou VSCodeVim
<!-- pause -->
Partir de Kickstart ou d'une distribution
<!-- pause -->
Garder des "filets de sécurité"
<!-- pause -->
<!-- column: 1 -->
# Mindset gagnant
<!-- pause -->
Accepter la courbe d'apprentissage
<!-- pause -->
Célébrer les petites victoires
<!-- pause -->
<!-- reset_layout -->
# Le secret ultime : **LA MOTIVATION !**

Les possibilités sont infinies, mais tout repose sur votre envie de créer VOTRE environnement.

<!-- end_slide -->
Ressources
===

<!-- column_layout: [1, 1] -->

<!-- column: 0 -->
# Apprendre

<span style="color: palette:red">vimtutor</span> (commande intégrée)
[ThePrimeagen](https://www.youtube.com/@ThePrimeagen) sur YouTube
[Neovim from Scratch](https://github.com/LunarVim/Neovim-from-scratch)

# Configurations

[LazyVim](https://www.lazyvim.org/)

<!-- column: 1 -->
# Communauté

[r/neovim](https://www.reddit.com/r/neovim/)
[Discord Neovim](https://discord.com/invite/Xb9B4Ny)

<!-- end_slide -->
Merci
===
<!-- column_layout: [1, 1] -->

<!-- column: 0 -->
**GitHub**

![image:width:60%](feedback.png)
<!-- column: 1 -->
**feedback**

![image:width:60%](feedback.png)
