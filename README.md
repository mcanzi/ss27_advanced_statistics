# Advanced Statistics

Slides for *Advanced Statistics* (Dr Massimiliano Canzi, Department of Linguistics, University of Konstanz), summer semester 2027.

## Rendering the slides

Knit `source/render_all.Rmd` to render every session into `docs`, which GitHub Pages serves. Knitting a single session also writes its HTML into `docs`. All sessions use the buttercup theme (`source/theme-buttercup.css`): slate blue and ice, salmon accents, and glacier buttercups in the background. `source/slides_setup.R` sets the plot colours to match it. The fonts are in `source/fonts` and are embedded in each HTML file.

Requires `tidyverse`, `revealjs`, `broom`, `lme4`, `lmerTest`, `patchwork`, `ggeffects`, `ggrepel` and `ggridges`; optional: `qrcode` (QR codes), `ragg` and `systemfonts` (Atkinson Hyperlegible in the figures).

## License

Course materials © Massimiliano Canzi, licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) (see `LICENSE`). Code is licensed under the MIT License (see `LICENSE-CODE`). The fonts used in the slide theme (Atkinson Hyperlegible, Bricolage Grotesque, JetBrains Mono) are licensed under the SIL Open Font License 1.1.
