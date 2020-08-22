*DISCLAIMER: This page contains the wheel packages of [Apache MXNet (incubating)](https://github.com/apache/incubator-mxnet)
build on version 1.7.0.
This is mainly for the purpose of the KDD2020 Tutorial
**"Practical Automated Machine Learning with Tabular, Text, and Image Data"**: 

- [mxnet-1.7.0b20200722-cp37-cp37m-macosx_10_7_x86_64.whl](https://autogluon-kdd-mxnet-wheels.s3-accelerate.amazonaws.com/mxnet-1.7.0b20200722-cp37-cp37m-macosx_10_7_x86_64.whl)
- [mxnet-1.7.0b20200722.py3-none-manylinux2014_x86_64.whl](https://autogluon-kdd-mxnet-wheels.s3-accelerate.amazonaws.com/mxnet-1.7.0b20200722-py2.py3-none-manylinux2014_x86_64.whl)
- [mxnet_cu100-1.7.0b20200730-py2.py3-none-manylinux2014_x86_64.whl](https://autogluon-kdd-mxnet-wheels.s3-accelerate.amazonaws.com/mxnet_cu100-1.7.0b20200730-py2.py3-none-manylinux2014_x86_64.whl)
- [mxnet_cu101-1.7.0b20200729-py2.py3-none-manylinux2014_x86_64.whl](https://autogluon-kdd-mxnet-wheels.s3-accelerate.amazonaws.com/mxnet_cu101-1.7.0b20200729-py2.py3-none-manylinux2014_x86_64.whl)
- [mxnet_cu102-1.7.0b20200730-py2.py3-none-manylinux2014_x86_64.whl](https://autogluon-kdd-mxnet-wheels.s3-accelerate.amazonaws.com/mxnet_cu102-1.7.0b20200730-py2.py3-none-manylinux2014_x86_64.whl)

You may install MXNet via:

```bash
# For CPU users
python3 -m pip install -U --pre "mxnet>=1.7.0b20200713, <2.0.0" -f https://sxjscience.github.io/KDD2020/

# For GPU users, CUDA v10.0
python3 -m pip install -U --pre "mxnet_cu100>=1.7.0b20200713, <2.0.0" -f https://sxjscience.github.io/KDD2020/

# For GPU users, CUDA v10.1
python3 -m pip install -U --pre "mxnet_cu101>=1.7.0b20200713, <2.0.0" -f https://sxjscience.github.io/KDD2020/

# For GPU users, CUDA v10.2
python3 -m pip install -U --pre "mxnet_cu102>=1.7.0b20200713, <2.0.0" -f https://sxjscience.github.io/KDD2020/
```
To determine which CUDA version you have, execute the following in the command line: `nvcc --version`

# Common Issues

- I cannot install the package and it reports the error 
`XXX is not a supported wheel on this platform.`

    One possibility is that you are using an older version of pip. Try to upgrade your pip to a version later than `19.0.0`, 
e.g., use the following command:

    ```bash
    python3 -m pip install --upgrade pip --user
    ```

- I cannot find the cu102 with version `>=1.7.0b20200713, <2.0.0`.

    May be the pip version is too old. Try to upgrad the pip via:
    
    ```bash
    python3 -m pip install --upgrade pip --user
    ```
