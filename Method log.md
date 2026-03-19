# The four goals of the course

1. estimate $f(x)$ from some real (possibly multi-dimensional) data set,
2. find a way to describe $f(x)$ and its uncertainty,
3. compare it to models of $h(x)$, and then
4. use the knowledge that we have gained to interpret/predict new measurements.

## Lecture 2

### Functions deployed

- `numpy.random.shuffle()` [API](https://numpy.org/doc/2.4/reference/random/generated/numpy.random.shuffle.html#numpy.random.shuffle)
- `numpy.random.default_rng()`[API](https://numpy.org/doc/2.4/reference/random/generator.html#numpy.random.default_rng)
- `np.random.default_rng().choice` [API](https://numpy.org/doc/2.4/reference/random/generated/numpy.random.Generator.choice.html)
- `numpy.intersect1d()` [API](https://numpy.org/doc/2.4/reference/generated/numpy.intersect1d.html#numpy-intersect1d)
- `numpy.delete()` [API](https://numpy.org/doc/2.4/reference/generated/numpy.delete.html#numpy-delete)

## Lecture 3

- Monte Carlo integration
- Mean, median and outliers

### Functions deployed

- `numpy.repeat()` [API](https://numpy.org/doc/2.4/reference/generated/numpy.repeat.html#numpy-repeat)
- `numpy.bincount()` [API](https://numpy.org/doc/2.4/reference/generated/numpy.bincount.html#numpy-bincount)

## Lecture 4

- Central limit theorem
- Multivariate pdfs
- Correlation coefficients: Pearson's, Spearman's, Kendall's
- Sampling from arbitrary distributions:
    - Rejection sampling
    - Inverse transform sampling

### Functions deployed

- `hist, bin_edges = numpy.histogram(z)` [API](https://numpy.org/doc/stable/reference/generated/numpy.histogram.html)
- `numpy.searchsorted()` [API](https://numpy.org/doc/stable/reference/generated/numpy.searchsorted.html#numpy-searchsorted)
- `numpy.cumsum()` [API](https://numpy.org/doc/stable/reference/generated/numpy.cumsum.html#numpy-cumsum)
