# Mark-tex

A very lightweight python app for converting Markdown with basic LaTeX (`$x = 5$` for inline or `$$x = 5$$` for block equations) into HTML designed for mathematical/technical blogging and meant to mimic TeX handling in GitHub and Jupyter.

## Installation

```$ git clone https://github.com/neurotaxis/mark-tex.git
$ cd mark-tex
$ pip install markdown
```

## Usage

```$ python mark-tex.py my_blog_post.md```

See `test_post.md` and `test_post.html` for example.

For your own website you will want to replace the relevant sections of `template.html` with your own site's html.
