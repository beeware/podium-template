# Podium Presentation Cookiecutter Template

This is a [Cookiecutter](https://cookiecutter.readthedocs.io) template for [Podium](https://github.com/pybee/podium)

## Creating a project from this template

Assuming you have a Python environment with `pip` installed:

```shell
$ pip install cookiecutter
$ cookiecutter https://github.com/pybee/podium-template
```

You'll then be asked for some input

```shell
presentation_name [My Presentation]:
```

## Customistaion Notes

You can customise the theme in `theme.css`, but you cannot rename this file. `@import()` other files from there. 

Your slides are in `slides.md`.

Your images are in `images`

Your fonts are in `fonts`


## Podium usage notes

See [Podium Usage Notes](https://github.com/pybee/podium#quickstart) for how to drive this presentation from the Podium view

## Web usage notes

This template allows for web-based presentations. 

```python
python -m SimpleHTTPServer   # Python 2.7
python -m http.server        # Python 3
```

This will create a presentation at `localhost:8000`

Saving this repo in a [GitHub Pages](https://pages.github.com/)-enabled repo means you can host your slides

See [Remark Usage Notes](https://github.com/gnab/remark/wiki/Keyboard-shortcuts) for how to drive this presentation from the web view
