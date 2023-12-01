# GPU development with Python 101 Tutorial

**Welcome to the GPU Development in Python 101 tutorial.**

Over the last two years I’ve gotten to grips with the fundamentals of writing accelerated code in Python. I was amazed to discover that I didn’t need to learn C++ and I didn’t need new development tools. Writing GPU code in Python is easier today than ever, and in this tutorial, I will share what I’ve learned and how you can get started with accelerating your code.

In this tutorial we will cover:
- What is a GPU and why is it different to a CPU?
- An overview of the CUDA development model.
- Numba: A high performance compiler for Python.
- Writing your first GPU code in Python.
- Managing memory.
- Understanding what your GPU is doing with pyNVML (memory usage, utilization, etc).
- RAPIDS: A suite of GPU accelerated data science libraries.
- Working with Numpy style arrays on the GPU.
- Working with Pandas style dataframes on the GPU.
- Performing some scikit-learn style machine learning on the GPU.

Attendees will be expected to have a general knowledge of Python and programming concepts, but no GPU experience will be necessary. The key takeaway for attendees will be the knowledge that they don’t have to do much differently to get their code running on a GPU.

## Notebooks

| Notebook      | Link |
| ----------- | ----------- |
| 0.0 Welcome | [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jacobtomlinson/gpu-python-tutorial/blob/colab/0.0%20Welcome.ipynb)|
| 1.0 CPU GPU Comparison | [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jacobtomlinson/gpu-python-tutorial/blob/colab/1.0%20CPU%20GPU%20Comparison.ipynb)|
| 2.0 Numba | [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jacobtomlinson/gpu-python-tutorial/blob/colab/2.0%20Numba.ipynb)|
| 2.1 Numba Lab | [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jacobtomlinson/gpu-python-tutorial/blob/colab/2.1%20Numba%20lab.ipynb)|
| 2.2 Numba Lab (solution) | [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jacobtomlinson/gpu-python-tutorial/blob/colab/2.2%20Numba%20lab%20(solution).ipynb)|
| 3.0 Numba Gauss | [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jacobtomlinson/gpu-python-tutorial/blob/colab/3.0%20Numba%20gauss.ipynb)|
| 3.1 Numba Lab 2 | [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jacobtomlinson/gpu-python-tutorial/blob/colab/3.1%20Numba%20lab%202.ipynb)|
| 3.2 Numba Lab 2 (solution) | [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jacobtomlinson/gpu-python-tutorial/blob/colab/3.2%20Numba%20lab%202%20(solution).ipynb)|
| 4.0 pyNVML | [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jacobtomlinson/gpu-python-tutorial/blob/colab/4.0%20pyNVML.ipynb)|
| 4.1 CUDA Array Interface | [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jacobtomlinson/gpu-python-tutorial/blob/colab/4.1%20CUDA%20Array%20Interface.ipynb)|
| 5.0 Cupy | [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jacobtomlinson/gpu-python-tutorial/blob/colab/5.0%20Cupy.ipynb)|
| 5.1 Cupy Lab | [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jacobtomlinson/gpu-python-tutorial/blob/colab/5.1%20Cupy%20Lab.ipynb)|
| 5.2 Cupy Lab (solution) | [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jacobtomlinson/gpu-python-tutorial/blob/colab/5.2%20Cupy%20Lab%20(solution).ipynb)|
| 6.0 cuDF | [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jacobtomlinson/gpu-python-tutorial/blob/colab/6.0%20cuDF.ipynb)|
| 7.0 cuML | [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jacobtomlinson/gpu-python-tutorial/blob/colab/7.0%20cuML.ipynb)|
| 8.0 Multi-GPU with Dask | [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jacobtomlinson/gpu-python-tutorial/blob/colab/8.0%20Multi-GPU%20with%20Dask.ipynb)|
