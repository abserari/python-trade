# Refer
https://www.akshare.xyz/zh_CN/latest/anaconda.html#id1
# Usage
## 环境
推荐使用 vscode, 其中的 python 扩展也兼容 conda
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