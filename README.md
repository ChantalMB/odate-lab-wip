# ODATE JupyterLite Env

Base JupyterLite environment for ODATE textbook using a mix of the [xeus-lite-demo](https://github.com/jupyterlite/xeus-lite-demo) and the [try-jupyter](https://github.com/jupyter/try-jupyter) repositories.

Current instructions for running locally:
- Create new conda environment
- `git clone` repository
- `cd` into repository
- `conda install -c conda-forge jupyterlite-core`
- `python -m pip install jupyterlite-pyodide-kernel`
- `conda install micromamba -c conda-forge  `
- `pip install jupyterlite-xeus`
- `pip install jupyter_server`
- `jupyter lite build --output-dir dist`
- `jupyter lite serve`