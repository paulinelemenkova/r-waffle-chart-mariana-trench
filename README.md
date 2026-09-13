# R Waffle Charts — Mariana Trench Aspect and Steepness

R scripts drawing waffle (square-pie) charts of the proportional distribution of slope aspect and steepness classes across the Mariana Trench profiles, using the waffle package and a ggplot2 tile equivalent.

## Related publication

Companion to the author's R statistical-graphics analysis of the Mariana Trench (uses the same Morphology.csv data):

Lemenkova, P. Statistical Analysis of the Mariana Trench Geomorphology Using R Programming Language. Geodesy and Cartography 2019, 45(2), 57-84.

- DOI: https://doi.org/10.3846/gac.2019.3785
- figshare: https://doi.org/10.6084/m9.figshare.9762860
- HAL: https://hal.science/hal-02277500
- Zenodo: https://zenodo.org/record/3385005
- SSRN: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3447481
- ISSN: 2029-6991 (Scopus)

## Scripts

- Waffle-Chart_lib-waffle.R: waffle charts of aspect / steepness class proportions with the waffle package (each square = a fixed share of observations).

- Waffle-Chart_lib-ggplot2.R: the same square-pie idea built from ggplot2 geom_tile.

## Methods

- Waffle / square-pie part-to-whole visualisation of categorical proportions.

## Data

- Morphology.csv: per-profile aspect and slope-steepness values of the Mariana Trench.

## Requirements

- R (>= 3.5); packages: waffle, ggplot2, RColorBrewer

## Author and citation

Polina Lemenkova — ORCID https://orcid.org/0000-0002-5759-1089

Cite: Lemenkova, P. Statistical Analysis of the Mariana Trench Geomorphology Using R Programming Language. Geodesy and Cartography 2019, 45(2), 57-84. https://doi.org/10.3846/gac.2019.3785

## License

MIT — see LICENSE (Copyright Polina Lemenkova).
