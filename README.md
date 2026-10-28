<div align="center">
  <img src="icon-512.png" alt="Logo Canapé" width="96">

# Canapé · Site

**Le site de présentation de Canapé, l'accueil console pour la ROG Ally.**<br>
**The showcase for Canapé, a console-style home for the ROG Ally.**

[Français](#français) · [English](#english) · [Visiter le site](https://pierregouedar.github.io/canape-site/) · [Canapé](https://github.com/pierregouedar/canape)

<img src="og.jpg" alt="Illustration du site Canapé sur une ROG Ally" width="800">
</div>

## Français

Ce dépôt contient le site de présentation de [Canapé](https://github.com/pierregouedar/canape), un accueil Windows conçu pour la ROG Ally. Il présente la bibliothèque de jeux, les réglages de performance et l'état du projet.

[Visiter le site](https://pierregouedar.github.io/canape-site/) · [Documentation de Canapé](https://github.com/pierregouedar/canape/blob/main/docs/README.md) · [Rapports d'essai](https://github.com/pierregouedar/canape/blob/main/docs/m5-report-2.md)

### Découvrir le site

- **Visite interactive** : parcourez les cinq étapes au défilement ou avec les boutons accessibles au clavier. Les vues de l'Ally sont des maquettes animées.
- **Auto TDP et banc d'essai** : une simulation et des mesures issues d'essais documentés expliquent le réglage de puissance. La limite TDP n'est pas la consommation totale de la console.
- **Avancement et compatibilité** : le site distingue les fonctions essayées sur l'Ally, celles qui restent à valider et celles qui sont prévues.

> [!IMPORTANT]
> Canapé est en développement. Les essais sur l'Ally concernent les versions indiquées dans les rapports ; les modifications ultérieures ne sont pas nécessairement validées. La mise à l'échelle et la génération d'images ne sont pas encore appliquées.

### Développement

Le site est statique : HTML, CSS et JavaScript dans `index.html`, sans étape de compilation. Pour le consulter localement :

```sh
python3 -m http.server 8000
```

Ouvrez [http://localhost:8000](http://localhost:8000). Les visuels et icônes sont à la racine du dépôt.

### Déploiement

Le workflow [GitHub Actions](.github/workflows/static.yml) publie le dépôt sur GitHub Pages lors d'un push sur `main`. Il peut aussi être lancé manuellement depuis l'onglet Actions.

## English

This repository contains the showcase for [Canapé](https://github.com/pierregouedar/canape), a Windows home designed for the ROG Ally. It introduces the game library, performance controls and project status. The site itself is in French.

[Visit the site](https://pierregouedar.github.io/canape-site/) · [Canapé documentation](https://github.com/pierregouedar/canape/blob/main/docs/README.md) · [Hardware test report](https://github.com/pierregouedar/canape/blob/main/docs/m5-report-2.md)

### Explore

- **Interactive tour**: scroll through five sections or use the keyboard-accessible step buttons. The Ally views are animated mockups.
- **Auto TDP and benchmark**: a simulation and documented measurements explain power settings. The TDP limit is not the console's total power consumption.
- **Status and compatibility**: features tried on the Ally, those still awaiting validation and planned work are listed separately.

> [!IMPORTANT]
> Canapé is in development. Ally tests apply to the versions named in the reports; later changes are not necessarily validated. Upscaling and frame generation settings are not yet applied.

### Development

The site is static: `index.html` contains the HTML, CSS and JavaScript, with no build step. To preview it locally:

```sh
python3 -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000). Images and icons are at the repository root.

### Deployment

The [GitHub Actions workflow](.github/workflows/static.yml) deploys the repository to GitHub Pages on pushes to `main`. It can also be started manually from the Actions tab.
