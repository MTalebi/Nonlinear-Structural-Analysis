# Nonlinear Structural Analysis

[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-nd/4.0/)

An interactive book on matrix methods for nonlinear structural analysis, with OpenSeesPy as the computational platform.

**Read the book:** <https://mtalebi.github.io/Nonlinear-Analysis-Book/>

## About the book

Each method in the book is developed in three layers: the governing mechanics derived from first principles, a language-independent algorithm stated in pseudocode, and a runnable OpenSeesPy implementation that builds the model, runs the analysis, and plots or tabulates the result. The fourteen chapters start with the matrix framework, virtual work, shape functions, transformations, and numerical integration. They continue through linear elastic elements, nonlinear material models, fiber section discretization, nonlinear solution strategies, nonlinear beam-column elements, geometric nonlinearity, and nonlinear dynamics. The book closes with a mini analysis program and worked case studies. All examples use SI units, and the code cells can be run directly in the browser.

## About this repository

This repository is the public archive record of the book. It holds the citation metadata that Zenodo uses to assign the book a DOI, and the Python environment that mybinder.org builds for the live code cells on the website. The manuscript of the book is not part of this repository.

| File | Purpose |
| --- | --- |
| `CITATION.cff` | Citation metadata (the "Cite this repository" button on GitHub) |
| `.zenodo.json` | Metadata for the Zenodo archive |
| `requirements.txt`, `runtime.txt` | Python 3.12 environment of the live kernel |
| `LICENSE` | Full text of the CC BY-NC-ND 4.0 license |

## How to cite

```bibtex
@book{TalebiKalaleh_NonlinearStructuralAnalysis,
  author    = {Talebi-Kalaleh, Mohammad},
  title     = {Nonlinear Structural Analysis},
  year      = {2026},
  publisher = {Zenodo},
  url       = {https://mtalebi.github.io/Nonlinear-Analysis-Book/}
}
```

## License

This work is licensed under the [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License](https://creativecommons.org/licenses/by-nc-nd/4.0/). See [LICENSE](LICENSE) for the full text.
