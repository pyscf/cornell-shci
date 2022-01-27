Cornell SHCI module for PySCF
=============================

2021-02-27

* Version 0.1

Install
-------
* Install to python site-packages folder
```
pip install git+https://github.com/pyscf/cornell-shci
```

* Install in a custom folder for development
```
git clone https://github.com/pyscf/cornell-shci /home/abc/local/path

# Set pyscf extended module path
echo 'export PYSCF_EXT_PATH=/home/abc/local/path:$PYSCF_EXT_PATH' >> ~/.bashrc
```

You can find more details of extended modules in the document
[extension modules](https://pyscf.org/install.html#extension-modules)
