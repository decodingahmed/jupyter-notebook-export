# Export Jupyter notebooks for publishing

This repository is to demonstrate how we can publish Jupyter notebooks in a GitHub- or web-friendly formats.

## Command line

Export as markdown:
```bash
$ ~/Anaconda3/python.exe -m jupyter nbconvert --to markdown notebook/Notebook.ipynb --output-dir markdown_output
```

Export as HTML:
```bash
$ ~/Anaconda3/python.exe -m jupyter nbconvert --to html notebook/Notebook.ipynb --output-dir html_output
```

## What's in this repository?

- A sample Jupyter notebook containing: see [notebook](/notebook) folder
  - Console, DataFrame and Series outputs
  - Graphs
  - Formulas
- Outputs for sample notebook:
  - Markdown: [markdown_output](/markdown_output)
  - HTML: [markdown_output](/html_output)

## Why?

Jupyter notebooks are essentially JSON documents which makes them difficult to display in user-friendly way.
