[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

# Linguistic value construction in 18th-century London auction advertisements

This repository holds the code and data which were used for the publication:

> De Mulder, A.; Fonteyn, L. & Kestemont, M. "Linguistic value construction in 18th-century London auction advertisements: a quantitative approach". *Proceedings of the Conference on Computational Humanities Research 2022. Antwerp, Belgium, 12-14 December, 2023.

The contents are structured as follows:
- `requirements.txt`: Python requirements file for use with pip
- `annotations`: all (manually) annotated assets in `.xlsx` format
- `data`: all input texts
- `figures`: high-res version of the generated figures
- `notebooks`: all notebooks (Python and R) that were used for the analyses

The final notebook on historical word embeddings wasn't used in the paper in the end but we include it here for the sake of reference. This notebook uses `procrustes.py` which we adapted from a [gist](https://gist.github.com/quadrismegistus/09a93e219a6ffc4f216fb85235535faf) by [Ryan Heuser](https://github.com/quadrismegistus). 

### Dependencies
- Python +3.6 is required for running the Python notebooks. A `requirements.txt` is included in the top-level directory specifying the necessary Python dependencies.
- The R notebook was run under `R version 4.1.1` and depends on the following packages: `glmer`, `effects` and `qpcR`.

### License

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg