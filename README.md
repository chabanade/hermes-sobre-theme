# Sobre

A clean, low distraction dark theme for the [Hermes Agent](https://github.com/NousResearch/hermes-agent) web dashboard. Solid dark background, system fonts, high contrast, no textures. One file, no fork, no rebuild.

I wanted a calm and readable dashboard to actually work in, so I built this in response to the request in [issue #36865](https://github.com/NousResearch/hermes-agent/issues/36865). It uses only the theme fields documented in the official guide, so nothing in the dashboard code changes.

🇫🇷 Un thème sombre, sobre et lisible pour le tableau de bord web de Hermes Agent. Fond gris anthracite uni, polices système, fort contraste, zéro texture. Un seul fichier à déposer, pas de fork, pas de recompilation.

## Ce que ça change / What it changes

* Surfaces gris anthracite unies, sans dégradé. *(Solid dark grey surfaces, no gradients.)*
* Polices système, aucune police web chargée. *(System fonts, no web font loaded.)*
* Grain de fond et vignette désactivés. *(Background grain and vignette turned off.)*
* Texte à fort contraste, lisible. *(High contrast, readable text.)*
* Un seul accent bleu acier, discret. *(One discreet steel blue accent.)*

## Installation

```bash
cp sobre.yaml ~/.hermes/dashboard-themes/sobre.yaml
```

Rafraîchissez le dashboard, ouvrez le sélecteur de thèmes (icône palette en haut), choisissez **Sobre**. Pour le mettre par défaut, ajoutez `dashboard.theme: sobre` dans votre `~/.hermes/config.yaml`.

*Refresh the dashboard, open the theme picker (palette icon), pick **Sobre**. To make it the default, set `dashboard.theme: sobre` in your `~/.hermes/config.yaml`.*

## Notes

* N'utilise que des champs documentés (`palette`, `typography`, `layout`, `componentStyles`, `colorOverrides`, `customCSS`). Voir la [doc officielle des thèmes](https://github.com/NousResearch/hermes-agent/blob/main/website/docs/user-guide/features/extending-the-dashboard.md).
* Le terminal de chat intégré reste sombre, ce qui est attendu sur un thème sombre (voir l'issue #38238).
* *Uses documented theme fields only. The embedded chat terminal stays dark, which is expected on a dark theme.*

## Crédits / Credits

Le tableau de bord Hermes Agent est développé par [Nous Research](https://github.com/NousResearch/hermes-agent) (MIT). Ce thème est une contribution indépendante, sous licence MIT (voir [LICENSE](LICENSE)).

*The Hermes Agent dashboard is built by Nous Research (MIT). This theme is an independent contribution, MIT licensed.*

---

Par **HEXAGONE ÉNERGIE** ([github.com/chabanade](https://github.com/chabanade)). *By HEXAGONE ÉNERGIE.*
