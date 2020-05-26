[![Build Status](https://travis-ci.org/ladybug-tools/queenbee-luigi.svg?branch=master)](https://travis-ci.org/ladybug-tools/queenbee-luigi)
[![Coverage Status](https://coveralls.io/repos/github/ladybug-tools/queenbee-luigi/badge.svg?branch=master)](https://coveralls.io/github/ladybug-tools/queenbee-luigi)

[![Python 3.6](https://img.shields.io/badge/python-3.6-blue.svg)](https://www.python.org/downloads/release/python-360/) [![Python 3.7](https://img.shields.io/badge/python-3.7-blue.svg)](https://www.python.org/downloads/release/python-370/)

# queenbee-luigi

[Queenbee](https://github.com/ladybug-tools/queenbee) extension for to execute Queenbee workflows using [Luigi](https://github.com/spotify/luigi).

## Installation
```console
pip install queenbee-luigi
```

## QuickStart
```python
import queenbee_luigi

```

## [API Documentation](http://ladybug-tools.github.io/queenbee-luigi/docs)

## Local Development
1. Clone this repo locally
```console
git clone git@github.com:ladybug-tools/queenbee-luigi

# or

git clone https://github.com/ladybug-tools/queenbee-luigi
```
2. Install dependencies:
```console
cd queenbee-luigi
pip install -r dev-requirements.txt
pip install -r requirements.txt
```

3. Run Tests:
```console
python -m pytest tests/
```

4. Generate Documentation:
```console
sphinx-apidoc -f -e -d 4 -o ./docs ./queenbee_luigi
sphinx-build -b html ./docs ./docs/_build/docs
```
