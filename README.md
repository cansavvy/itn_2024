# Acute Myeloid Leukemia Heatmap

This repository contains an analysis of an acute myeloid leukemia sample dataset from [Shih et al., 2017](https://pubmed.ncbi.nlm.nih.gov/28193779/), pre-processed by [refinebio](https://www.refine.bio/). The dataset includes RNA-sequencing results for 19 acute myeloid leukemia (AML) model mice under controlled treatment conditions.

## How to re-run the analysis 

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need to have R installed on your local machine. You can download R [here](https://cran.r-project.org/). The script also uses the `pheatmap` and `magrittr` libraries. You can install them using the following commands:

```R
install.packages("pheatmap", update = FALSE)
install.packages("magrittr", update = FALSE)
```

### Installing

Clone the repository to your local machine:

```bash
git clone https://github.com/<your-github-username>/aml-heatmap.git
```

Navigate to the cloned repository

```bash
cd aml-heatmap
```

Run the R script:

```bash
Rscript script.R
```

## Running the tests

Explain how to run the automated tests for this system.

## Built With

* [R](https://www.r-project.org/) - The programming language used.
* [pheatmap](https://www.rdocumentation.org/packages/pheatmap/versions/1.0.12/topics/pheatmap) - The R package used for clustering and creating a heatmap.

## Authors

* **CCDL for ALSF** - *Initial work* - [CCDL for ALSF](https://github.com/AlexsLemonade)
* **Candace Savonen** - *Adaptation for this repository* - [Candace Savonen](https://github.com/cansavvy)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* This analysis has been adapted from this [refine.bio-examples notebook](https://alexslemonade.github.io/refinebio-examples/03-rnaseq/clustering_rnaseq_01_heatmap.html)
