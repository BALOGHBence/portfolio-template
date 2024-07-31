# A Template Repository for a Portfolio Website using Sphinx and GitHub Pages

Hi stranger! I've created this repository for my article on Medium, click [here](https://medium.com/@bencebalogh_33809/how-to-create-a-killer-portfolio-using-sphinx-and-github-pages-18a5c4f5702e) to read it.

You can also check out the repository I use to build my own portfolio site [here](https://github.com/BALOGHBence/portfolio). Use it to get ideas or as a kitchen sink.

## Contents

* All the boilerplate code to create your own portfolio page,
  including a YAML file that sets up a workflow using GitHub Actions. All you have to care about is to fill up the repo with the contents of your portfolio.
* A blueprint RST file for your projects.

## Usage

The first step is to use this repository as a template to create your own.

### Installation

I'm using Poetry in this project to manage dependencies, so first you need to install it globally.

```console
pip install poetry
```

Now, in the root of your cloned repo, issue the following command

```console
poetry env use python3
```

This will create a dedicated virtual enviroment for the project. Next is to install all the dependencies.

```console
poetry install
```

### Building the documentation

You can build the documentation with the following command

```console
poetry run make html
```

## License

The source files are distributed under the MIT license.
