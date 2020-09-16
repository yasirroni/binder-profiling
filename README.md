# binder-profiling

Profiling your data using Pandas Profiling

## Requirements

```python
numpy # tested on 1.19.2
pandas # tested on 1.1.2
pandas-profiling[notebook] #tested on 2.9.0
voila<=0.1.23 # tested on 0.1.23
```

## Usage

### jupyter on mybinder

1. Open jupyter on mybinder: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/yasirroni/binder-profiling/master?filepath=%2Fbinder-profiling.ipynb)

2. On navigation: `Kernel -> Restart & Run All -> Restart and Run All Cells`

3. Click on `Upload` below the last cell and upload your file

<!---
Voila profiling ended up not showing
-->
<!---
### voila on mybinder
1. Open voila on mybinder: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/yasirroni/binder-profiling/master?urlpath=%2Fvoila%2Frender%2Fbinder-profiling.ipynb)
-->

<!---
Profiling using colab stopped at middle
-->
<!---
### jupyter on colab
1. Open jupyter on colab*: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yasirroni/binder-profiling/blob/master/binder-profiling.ipynb)

2. Add the following code before the first cell:
```bash
!pip install -U pandas-profiling[notebook]
```

3. `Runtime -> Run all`