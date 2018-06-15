# UsingGluonCV
Trying GluonCV examples



Gluon CV
https://zh.mxnet.io/blog/gluon-cv
https://gluon-cv.mxnet.io/

pip3.6 install --pre mxnet
pip3.6 install gluoncv

https://gluon-cv.mxnet.io/build/examples_detection/index.html

https://gluon-cv.mxnet.io/build/examples_detection/demo_ssd.html#sphx-glr-build-examples-detection-demo-ssd-py

➜  incubator-mxnet git:(master) ✗ python3.6 demo_ssd.py
/usr/local/lib/python3.6/site-packages/h5py/__init__.py:36: FutureWarning: Conversion of the second argument of issubdtype from `float` to `np.floating` is deprecated. In future, it will be treated as `np.float64 == np.dtype(float).type`.
  from ._conv import register_converters as _register_converters
Downloading street_small.jpg from https://github.com/dmlc/web-data/blob/master/gluoncv/detection/street_small.jpg?raw=true...
117KB [00:00, 507.84KB/s]
Shape of pre-processed image: (1, 3, 512, 512)

It worked well.

fork and mod
nifi_gluoncv_sd.py
