# ![logo](/examples/assets/LINE-sm.png) LINE Python

*LINE Messaging's private API*

----

## Requirement

The linepy module only requires Python 3. You can download from [here](https://www.python.org/downloads/). 

## Installation

Installation is simple. It can be installed from pip using the following command:
```sh
$ python -m pip install -r requirements.txt
```
Or from the code:
```sh
$ python setup.py install
```

## Usage

```python
>>> from linepy import *
>>> line = LINE("")
>>> line.log("Auth Token : " + str(line.authToken))
```
