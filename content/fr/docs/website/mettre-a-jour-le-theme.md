---
title: Mettre à jour le thème
weight: 5
description: >
  Le thème évolue fréquemment, et il est préférable de le maintenir à jour
---

## Mettre à jour le thème
Pour récupérer la dernière version du thème :
```bash
yarn update-theme
```

## Mettre à jour le template
Pour faire la mise à jour du template :
```bash
git remote add template git@github.com:noesya/osuny-hugo-template-aaa.git
git fetch --all
git merge template/main --allow-unrelated-histories
```

Malheureusement, cette méthode génère des conflits, qu'il faut traiter à la main.
