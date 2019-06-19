https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/index.html

http://tensorflow-object-detection-api-tutorial.readthedocs.io

这是一个非常不错的api，囊括tensorflow中目标检测方面的大多数models，网上搜出来的文章大多片面。 逐步翻译出来，以后能用得上。

其中用到的：

面向的os：以windows 10、linux为主，在这连个平台下已经过完备的测试。

Python：3.6

TensorFlow ：1.9

CUDA Toolkit：v9.0

CuDNN：v7.0.5

Anaconda ：Python 3.7 (非必要)

.. TensorFlow setup documentation master file, created by
   sphinx-quickstart on Wed Mar 21 19:03:08 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

TensorFlow Object Detection API tutorial
============================================

This is a step-by-step tutorial/guide to setting up and using TensorFlow's Object Detection API to perform, namely, object detection in images/video.

The software tools which we shall use throughout this tutorial are listed in the table below:

+---------------------------------------------+
| Target Software versions                    |
+==============+==============================+
| OS           | Windows, Linux [*]_          |
+--------------+------------------------------+
| Python       | 3.6                          |
+--------------+------------------------------+
| TensorFlow   | 1.9                          |
+--------------+------------------------------+
| CUDA Toolkit | v9.0                         |
+--------------+------------------------------+
| CuDNN        | v7.0.5                       |
+--------------+------------------------------+ 
| Anaconda     | Python 3.7 (Optional)        |
+--------------+------------------------------+

.. [*] Even though this tutorial is mostly based (and properly tested) on Windows 10, information is also provided for Linux systems.

.. toctree::
   :maxdepth: 4
   :caption: Contents:

   install
   camera
   training
   issues



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
