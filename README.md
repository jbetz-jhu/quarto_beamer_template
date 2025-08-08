
<!-- README.md is generated from README.Rmd. Please edit that file -->

# quarto_beamer_template: A Quarto Template for Beamer Presentations

`beamer_template.qmd` is a [Quarto](https://quarto.org/) template for
making presentations with Beamer. The goal of this template is to
provide a template that works reasonably well, and pointing out places
where the user might make further customization. This solves a few
headaches that come with an out-of-the-box Quarto Beamer presentation:
hopefully it will not add any new ones.

Citations are handled with [BibTex](https://www.bibtex.org/) vis the
`bibliography.bib` file: you can easily convert a DOI to a bibtex entry
with [doi2bib](https://www.doi2bib.org/), and customize how citations
are rendered using [CSL](https://citationstyles.org/).

`config.yml` contains information on:

- The packages from CRAN and GitHub required
- The default [chunk
  options](https://bookdown.org/yihui/rmarkdown-cookbook/chunk-options.html)
- Customizations to a [ggplot2
  theme](https://ggplot2.tidyverse.org/reference/theme.html) named
  `plot_theme`
- Color palettes using the
  [ggsci](https://cran.r-project.org/web/packages/ggsci/index.html)
  package, including those of The Lancet, NEJM, BMJ, and AAAS.
