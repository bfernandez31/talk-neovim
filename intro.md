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



<!-- reset_layout -->




<!-- end_slide -->


Mon parcours
===



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


<!-- speaker_note: |
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

# Les modes : 

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
# Langage d'édition:

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


![image:width:100%](vim-productive.png)

<!-- end_slide -->

![image:width:100%](hide_pain_harold.png)

<!-- end_slide -->

<!-- end_slide -->

![image:width:100%](pulp.gif)

<!-- end_slide -->


<!-- end_slide -->

Mon environnement de développement
---



# Le confort de l'IDE


<!-- end_slide -->

# Le quotidien avec IntelliJ
## Le quotidien avec IntelliJ

### Le quotidien avec IntelliJ

<!-- end_slide -->
# Le déclencheur


<!-- end_slide -->
 Les premiers pas vers le changement
---

# IdeaVim : la passerelle


<!-- end_slide -->
# Les premières frustrations

<!-- end_slide -->
# L'importance d'une transition progressive


<!-- end_slide -->
L'acceptation et l'apprentissage
---

# Le moment "déclic"

<!-- end_slide -->

Fonctionnalités Modernes
---

# 󰛔 Support des langages et Débogage



<!-- end_slide -->

# Les ressources essentielles


<!-- end_slide -->
# Ma configuration actuelle

*Démonstration en direct*


<!-- end_slide -->
# Les bénéfices 


<!-- end_slide -->
Conseils pratiques
---

# Par où commencer ?


<!-- end_slide -->
# Les pièges à éviter


<!-- end_slide -->
# Resources et communauté

<!-- end_slide -->
Merci !
---

Questions ?

*Vous pouvez retrouver ma config sur GitHub*


<!-- end_slide -->
Questions ?
===

<!-- jump_to_middle -->
 

Config disponible sur GitHub

<!-- end_slide -->
