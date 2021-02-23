安装 conda

创建环境
conda create -n ak_test python=3.8.5

安装 backtrader
pip install backtrader[plotting]

修复 big sur bug
        ImportError: cannot import name 'warnings' from 'matplotlib.dates'
```python
pip uninstall matplotlib
pip install matplotlib==3.2.2
```