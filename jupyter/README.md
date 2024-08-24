# Jupyter Notebook + RISE

## Introduction
Jupyter notebook with the extension RISE allows to present your cells as a slideshow ([official documentation](https://rise.readthedocs.io/en/latest/)).

It's a great, under-used tool. 

## When?
When you need to execute lots of code during your presentation and you want to tightly control the environment. Running "the real python" and no pyscript substitution.

## Install
Requires the libraries `jupyter` and `rise` to be installed (see the requirements file).

## How to?

Just include in a markdown cell the iframe with the src pointing to the Vizzu share link.

```html
<iframe allow="fullscreen" width="1200" height="800" src="https://app.vizzu.io/share/story/66a27508fc673fda605c33da-Sample-2-Music"></iframe>
```

## Example?
Install the libraries and run example.ipynb. There is no substitute to actually run the notebook to get the full interativity.