# Having a go at Jupyter book

Little test of the executeable books [Jupyter book project](https://github.com/executablebooks/jupyter-book)

## Getting started

First sort out the environment with conda:
```{bash}
conda env create -f environment.yml
```

Then build the book locally!

```{bash}
conda activate exebook

jupyter-book build book/
```
