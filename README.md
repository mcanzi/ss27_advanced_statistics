# Advanced Statistics

Slides for *Advanced Statistics* (Dr Massimiliano Canzi, Department of Linguistics, University of Konstanz), summer semester 2027: a refresher of the Statistics course, figures for publication, generalised additive (mixed) models, random forests, power analysis by simulation, and multivariate methods.

| | Session |
|---|---|
| 1 | Statistics refresher |
| 2 | Figures for publication |
| 3 | Generalised additive models |
| 4 | Generalised additive mixed models |
| 5 | GAMMs in practice |
| 6 | Random forests |
| 7 | Random forests in practice |
| 8 | Power analysis |
| 9 | Factor analysis (in preparation) |
| 10 | Cluster analysis (in preparation) |

The slides are online at [mcanzi.de/ss27_advanced_statistics](https://mcanzi.de/ss27_advanced_statistics/01_refresher.html).

## Rendering the slides

Knit `source/render_all.Rmd` to render every session into `docs`, which GitHub Pages serves. Knitting a single session also writes its HTML into `docs`. All sessions use the glacier theme of mcanzi.de (`source/theme-buttercup.css`): slate blue and ice, salmon accents, and glacier buttercups drawn in ink in the background. `source/slides_setup.R` sets the plot colours to match it. The fonts are in `source/fonts` and are embedded in each HTML file.

Requires `tidyverse`, `revealjs`, `broom`, `lme4`, `lmerTest`, `patchwork`, `ggeffects`, `ggrepel`, `ggridges`, `mgcv`, `tidygam`, `itsadug`, `rpart`, `ranger` and `simr`; optional: `qrcode` (QR codes), `ragg` and `systemfonts` (Atkinson Hyperlegible in the figures).

## License

Course materials © Massimiliano Canzi, licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) (see `LICENSE.md`). Code is licensed under the MIT License (see `LICENSE-CODE.md`). The fonts used in the slide theme (Atkinson Hyperlegible, Bricolage Grotesque, JetBrains Mono) are licensed under the SIL Open Font License 1.1 (see `source/fonts/OFL-*.txt`).
