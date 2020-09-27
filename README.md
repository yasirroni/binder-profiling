# binder-profiling

Website implementation of [Pandas Profiling](https://github.com/pandas-profiling/pandas-profiling) to help you understand your data using [MyBinder](https://mybinder.org/) cloud services. Also available on [Google Colab](https://colab.research.google.com/).

## Requirements

```python
numpy # tested on 1.19.2
pandas # tested on 1.1.2
pandas-profiling[notebook] #tested on 2.9.0
voila<=0.1.23 # tested on 0.1.23 (buggy)
```

## Usage

### jupyter on mybinder

1. Open jupyter on mybinder: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/yasirroni/binder-profiling/master?filepath=%2Fbinder-profiling.ipynb)

2. On navigation: `Kernel -> Restart & Run All -> Restart and Run All Cells`

3. Click on `Upload` below the last cell and upload your file

4. Repeat poin (3) to process new file

<!---
Voila profiling ended up not showing
-->
<!---
### voila on mybinder
1. Open voila on mybinder: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/yasirroni/binder-profiling/master?urlpath=%2Fvoila%2Frender%2Fbinder-profiling.ipynb)
-->

### jupyter on colab

1. Open jupyter on colab*: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yasirroni/binder-profiling/blob/master/colab-profiling.ipynb)

2. `Runtime -> Run all`

3. Click on `Upload` below the `display(wrapper)` cell and upload your file

4. type `c` in the `text-box` below the  `Pdb().set_trace()` cell

5. Repeat poin (3) and `shift + enter` all cell below `Pdb().set_trace()` cell

## Note

Only accept `.csv` format with `,` as delimiter and `.` as decimal separator. To make sure, open your `.csv` file in notepad. If your `.csv` file use `;` as delimiter and `,` as decimal separator, you can use google spreadsheet to convert it or change your windows language settings.
