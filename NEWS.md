# lancer output 0.0.8.9000 (development version)

## TODO

# lancer output 0.0.8

Version first send to teams on 28 Jan 2023.

* Update README with details on how to reproduce the figures in the manuscript, simulation results and other examples.

### Manuscript

* Add figshare links for this repository and the `lancer` package itself.

# lancer output 0.0.7

### Manuscript

* Swap statistical summary issue and plotting of many curves issue.
* Remove the word "high throughput".
* Changed "Microsoft Excel" to "spreadsheet software".
* Indicate that R can be used to quickly plot curves and report curve statistics but hard to implement from scratch for a novice analyst and hence an R package is created.
* Split Figure 1A and 1B to Figure 1 and Supplementary Figure 3.
* Add reference of papers that give other metrics for linearity evaluation.
* Add reference of papers creating response curves in metabolomic/lipidomic studies.
* Add reference of one paper that describe curves that plateau at high and low concentration as saturation and noise regime.

# lancer output 0.0.6

Version first send to teams on 5 Jan 2023.

### Manuscript

Change the name of the tables in the *lancer* workflow.

* Change characterisation of LOD curves from LOD to Noise Regime.
* Change characterisation of Saturation curves from Saturation to Saturation Regime.

### Quarto_Example

Replace dilution with curve in `index.qmd`.

### Quarto_Simulation

Replace dilution with curve in `index.qmd`.

# lancer output 0.0.5

Version first send to teams on 17 Nov 2022.

* Change *DCVteskit* to *lancer*.

# lancer output 0.0.4

Version first send to teams on 9 Nov 2022.

### Manuscript

* Change title to *lancer*: a R package for linearity assessment and visualisation of multiple curves"
* Make manuscript content more generalised. Talking more about linearity assessment rather than dilution curves from metabolomic/lipidomic experiment. The dilution curves from metabolomic/lipidomic experiment will be used as a running example instead.
* Found a way to change figure title from Figure to Supplementary Figure in `supplementary.qmd`.
* Found a way to add page break `{{< pagebreak >}}` in the `manscript.qmd`.
* Change figure in `manscript.qmd` to a merged figure of the curve grouping workflow diagram and the interactive plot diagram.
* Transfer *lancer* workflow diagram from `manscript.qmd` to `supplementary.qmd`.
* Add relevant equations for Mandel's Fitting Test and Percent Residual Accuracy. Thank you [njbart](https://github.com/quarto-dev/quarto-cli/discussions/3236) for the help.

# lancer output 0.0.3

Version first send to teams on 1 Nov 2022.

### Manuscript

* Reduce the number of words in the manuscript to less than a thousand words and one figure.
* Add a Word file for supplementary figures.

# lancer output 0.0.2

Version first send to teams on 18 Oct 2022.

### Manuscript

* Correct some sentence structure issue.
* Change `lancer` to *lancer*.
* Make section Statistical Summary for Dilution Curves more clear.
* Add figure labels in the image caption.
* Add Simulation Results to test proposed workflow.
* Add the importance of linearity assessment in the introduction.

### Quarto_Simulation

* Add interactive tables to view the simulated data and results.
* Found a way to fill up the trellis plot.
* Add R session info and R package citations

### Quarto_Example

* Found a way to fill up the trellis plot.
* Add R session info and R package citations

# lancer output 0.0.1

Version first send to via email on 8 Oct 2022.

* Added a `NEWS.md` file to track changes to the package.
* Create a folder `Quarto_Example` that contains some output from [`lancer`](https://github.com/SLINGhub/lancer) and scripts that generate the results.
* Create a folder `Manuscript` that contains the manuscript for [`lancer`](https://github.com/SLINGhub/lancer).
* Create a folder `Quarto_Simulation` that contains scripts to see how [`lancer`](https://github.com/SLINGhub/lancer) does on simulated dilution data.
