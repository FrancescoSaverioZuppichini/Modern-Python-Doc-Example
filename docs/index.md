# A Modern Doc Template for your Python Project 💅

This website was build with:

 - [mkdocs.org](https://www.mkdocs.org)
 - [mkdocs-material](https://squidfunk.github.io/mkdocs-material/)
 - [pymdown](https://facelessuser.github.io/pymdown-extensions/)

## Features

- out of the box amazing good looking website thanks to [mkdocs.org](https://www.mkdocs.org) and [mkdocs-material](https://squidfunk.github.io/mkdocs-material/)
- a wide array of cool features, such as code highlight, admonition, latex rendering and more thanks to [pymdown](https://facelessuser.github.io/pymdown-extensions/)
- [FastApi](https://fastapi.tiangolo.com/) cool [terminal rendering](/terminal/)
- auto documentation for code thanks to [mkdocstrings](https://github.com/mkdocstrings/mkdocstrings)
- automatic build thanks to github action, see the [CI/CD page](/ci_cd/)


## Getting Started

Head over the [getting started](getting_started) guide

## Cool stuff

### Code Highlights

See [here](https://squidfunk.github.io/mkdocs-material/reference/code-blocks/) for doc

```python

print("Hello World!")
```

### Admonition

See [here](https://squidfunk.github.io/mkdocs-material/reference/admonitions/) for doc

!!! note "Hello There"
    General Kenobi!

??? note "Hello There"
    General Kenobi!

!!! error
    Boom!


### Latex

See [here](https://squidfunk.github.io/mkdocs-material/reference/mathjax/) for doc

Inline

$p(x|y) = \frac{p(y|x)p(x)}{p(y)}$, \(p(x|y) = \frac{p(y|x)p(x)}{p(y)}\).

Block

$$
E(\mathbf{v}, \mathbf{h}) = -\sum_{i,j}w_{ij}v_i h_j - \sum_i b_i v_i - \sum_j c_j h_j
$$

\begin{align}
    p(v_i=1|\mathbf{h}) & = \sigma\left(\sum_j w_{ij}h_j + b_i\right) \\
    p(h_j=1|\mathbf{v}) & = \sigma\left(\sum_i w_{ij}v_i + c_j\right)
\end{align}