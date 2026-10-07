# CryoEM Doeboek

[![License: CC BY 4.0](https://licensebuttons.net/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

CryoEM Doeboek is an Open Educational Resource collection of interactive notebooks that illustrate core concepts in cryo-EM through practical, hands-on examples. It was developed for the *High Resolution Imaging* course at TU Delft.

The practicals run entirely in the browser (via [JupyterLite](https://jupyterlite.readthedocs.io/) and [Pyodide](https://pyodide.org/)), with no installation needed:

**https://cryotud.github.io/cryoem-doeboek**

Notebooks: Fourier analysis (available), Single-particle analysis and Tomography (both under construction).

## License

This repository uses two licenses:

| What | License |
|------|---------|
| **Content**: text, explanations, exercises, figures and the notebooks as teaching material | [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE) |
| **Code**: code cells in the notebooks, `serve.py`, build and workflow files | [BSD 3-Clause License](LICENSE-CODE) |

You are free to share and adapt this material for any purpose as long as you give appropriate credit.

**Suggested attribution:**

> *CryoEM Doeboek* licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Source: https://github.com/cryoTUD/cryoem-doeboek

Not covered by these licenses: the TU Delft name and flame logo (including the flame image used as an example image in the notebooks and the `tud_flame` data files) are the property of TU Delft and are not covered by these licenses. Please remove or replace them if you reuse the material outside TU Delft.

## Building the site locally

```bash
pip install mkdocs-material mkdocs-jupyterlite ipywidgets jupytext jupyterlab-myst
mkdocs serve
```
