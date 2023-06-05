# Pip Package Template

Contains the following python modules:
- Super Helper Scripts (superscripts)
- Cluster Helper Scripts (clusterscripts)

Any module can be installed by entering the following command:
```bash
pip install git+https://TOKEN@github.ibm.com/decimelli/HelperScripts.git
```
where `TOKEN` is an [access token](https://github.ibm.com/settings/tokens).
The modules can then be used like this in your python script like this:
```python
from superscripts import example

example.main()
```
Or, you may run any of the shell scripts from the  [scripts directory](scripts). 
These are placed in the bin folder when you pip install this package.
```bash
./bin/example.sh)
```
Which bin directory depends on your python installation. To find it you can run:
`
dirname $(which pip)
`
