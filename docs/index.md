# Lmo

{%
   include-markdown "../README.md"
   start="<!--badges-start-->"
   end="<!--badges-end-->"
%}


Lmo is a lightweight library with pythonic syntax. Some features include:

 - Lightweight; it only requires [numpy](https://numpy.org/doc/stable/index.html)
 - Clean code style: linted with [ruff](https://github.com/charliermarsh/ruff)
 - Fully type-annotated, valid in [pyright](https://github.com/microsoft/pyright)'s strict mode.
 - [Hypothesis](https://hypothesis.readthedocs.io/en/latest/)-tested
 - Flat functions, no classes (scipy > scikit) 
 - Red and fluffy

## Installation

```shell
pip install lmo
```

## Why (T)L-moments?

!!! note info "Coming soon. For now, see [Wikipedia](https://wikipedia.org/wiki/L-moment)"


## Roadmap

- [x] Sample L-, and TL-moment estimators
- [x] Sample L- and TL- co-moments (multivariate) estimators
- [ ] Variance structure of sample (T)L moments [#4](https://github.com/jorenham/lmo/issues/4)
- [ ] Fitting of distributions with known TL- or L-moments [#5](https://github.com/jorenham/lmo/issues/5)
- [ ] Population (T)L-moment estimation from quantile functions [#6](https://github.com/jorenham/lmo/issues/6)