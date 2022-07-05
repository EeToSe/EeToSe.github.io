# Steve's Learning Notes

This repository holds the Jupyter Book source for my learning notes throughout the Phd
journey.

## Usage

### From scratch
Jupyter Book also provides a [Jupyter Book cookiecutter](https://github.com/executablebooks/cookiecutter-jupyter-book) that can be used to interactively create a book directory structure. 

### Build and preview the book locally

If you'd like to develop and/or build my notes, you should:

1. Clone this repository
2. Run `pip install -r requirements.txt` (it is recommended you do this within a virtual environment)
3. (Optional) Edit the books source files located in the `chapters/` directory
4. Run `jupyter-book clean .` to remove any existing builds
5. Run `jupyter-book build .`

A fully-rendered HTML version of the book will be built in `./_build/html/`.

Follow the build instructions on the [Jupyter Book guide](https://jupyterbook.org/en/stable/start/your-first-book.html)

### Hosting the book

Please see the [Jupyter Book documentation](https://jupyterbook.org/publish/web.html) to discover options for deploying a book online using services such as GitHub, GitLab, or Netlify.

For GitHub and GitLab deployment specifically, the [cookiecutter-jupyter-book](https://github.com/executablebooks/cookiecutter-jupyter-book) includes templates for, and information about, optional continuous integration (CI) workflow files to help easily and automatically deploy books online with GitHub or GitLab. For example, if you chose `github` cookiecutter option, your book template was created with a **GitHub actions** workflow file that, once pushed to GitHub, automatically renders and pushes your book to the `gh-pages` branch of your repo and hosts it on GitHub Pages when a push or pull request is made to the main branch.

## Credits

This project is created using the excellent open source [Jupyter Book project](https://jupyterbook.org/) and the [executablebooks/cookiecutter-jupyter-book template](https://github.com/executablebooks/cookiecutter-jupyter-book).

## Get up with Jupyter   
[UBC JupyterDays](https://ubc-dsci.github.io/jupyterdays/index.html)