# Installing Cechmate

At the time of writing this, the typical install procedure
```
pip install cechmate
```
errors due to a missing dependency `phat`.
To fix this, do the following:

1. Install wheel and setuptools
```
pip install wheel setuptools
```

2. Download and extract the source code for phat:
```
wget https://files.pythonhosted.org/packages/43/82/c14de81dc2953a71a060f72f2bc34c41996307956b162751f2a47e2c78f7/phat-1.5.0a.tar.gz
```

3. Extract the tarball and install phat-1.5.0
```
tar -xvf phat-1.5.0a.tar.gz && pip install ./phat-1.5.0
```

4. Install cechmate
```
pip install cechmate
```

