# Helper Scripts

Contains the following python modules:
- Super Helper Scripts (superscripts)
- Cluster Helper Scripts (clusterscripts)

Any module can be installed by entering the following command:
```bash
pip install git+https://TOKEN@github.ibm.com/decimelli/HelperScripts.gitt#subdirectory=MODULE
```
where `TOKEN` is an [access token](https://github.ibm.com/settings/tokens) and `MODULE` is the module from this repository you would like to install.
The modules can then be used like this in your .py file:
```python
from superscripts import example

example.main()
```

## For Developers

To check this project, run
```bash
pip install wheel twine
python setup.py bdist_wheel sdist
```
This will create the `./dist` and `./build` directories, which may be uploaded to various sources. 
This project relies on github to be the source for pip. 