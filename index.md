*DISCLAIMER: This page contains the wheel packages of MXNet build on version 1.7.0. This is mainly for the purpose of the KDD2020 Tutorial: 

- [mxnet-1.7.0b20200715-cp37-cp37m-macosx_10_7_x86_64.whl](https://autogluon-kdd-mxnet-wheels.s3-accelerate.amazonaws.com/mxnet-1.7.0b20200715-cp37-cp37m-macosx_10_7_x86_64.whl)
- [mxnet-1.7.0b20200720.py3-none-manylinux2014_x86_64.whl](https://autogluon-kdd-mxnet-wheels.s3-accelerate.amazonaws.com/mxnet-1.7.0b20200720-py2.py3-none-manylinux2014_x86_64.whl)
- [mxnet_cu100-1.7.0b20200720-py2.py3-none-manylinux2014_x86_64.whl](https://autogluon-kdd-mxnet-wheels.s3-accelerate.amazonaws.com/mxnet_cu100-1.7.0b20200720-py2.py3-none-manylinux2014_x86_64.whl)
- [mxnet_cu101-1.7.0b20200720-py2.py3-none-manylinux2014_x86_64.whl](https://autogluon-kdd-mxnet-wheels.s3-accelerate.amazonaws.com/mxnet_cu101-1.7.0b20200720-py2.py3-none-manylinux2014_x86_64.whl)
- [mxnet_cu102-1.7.0b20200720-py2.py3-none-manylinux2014_x86_64.whl](https://autogluon-kdd-mxnet-wheels.s3-accelerate.amazonaws.com/mxnet_cu102-1.7.0b20200720-py2.py3-none-manylinux2014_x86_64.whl)

You may install MXNet via:

```bash
# For CPU users
pip install -U --pre "mxnet>=1.7.0b20200713, <2.0.0" -f https://sxjscience.github.io/KDD2020/

# For GPU users, CUDA 100
pip install -U --pre "mxnet_cu100>=1.7.0b20200713, <2.0.0" -f https://sxjscience.github.io/KDD2020/

# For GPU users, CUDA 101
pip install -U --pre "mxnet_cu101>=1.7.0b20200713, <2.0.0" -f https://sxjscience.github.io/KDD2020/

# For GPU users, CUDA 102
pip install -U --pre "mxnet_cu102>=1.7.0b20200713, <2.0.0" -f https://sxjscience.github.io/KDD2020/
```
