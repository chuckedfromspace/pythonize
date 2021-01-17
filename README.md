# Pythonize

Practical data crunching and visualization in Python with `pandas`, `matplotlib`, `plotly` and much more. Please check out the [GitHub page](https://chuckedfromspace.github.io/pythonize/intro.html) for more!

## Usage

### Building the book

If you'd like to develop on and build the pythonize book, you should:

- Clone this repository and run
- Run `pip install -r requirements.txt` (it is recommended you do this within a virtual environment)
- (Recommended) Remove the existing `pythonize/_build/` directory
- Run `jupyter-book build pythonize/`

A fully-rendered HTML version of the book will be built in `pythonize/_build/html/`.

### Hosting the book

The html version of the book is hosted on the `gh-pages` branch of this repo. You may build the book manually by:

- Navigating to your local build; and running,
- `ghp-import -n -p -f pythonize/_build/html`

This will automatically push your build to the `gh-pages` branch. More information on this hosting process can be found [here](https://jupyterbook.org/publish/gh-pages.html#manually-host-your-book-with-github-pages).

## Credits

This project is created using the excellent open source [Jupyter Book project](https://jupyterbook.org/) and the [executablebooks/cookiecutter-jupyter-book template](https://github.com/executablebooks/cookiecutter-jupyter-book).
