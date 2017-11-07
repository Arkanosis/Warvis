# Warvis [![License](http://img.shields.io/badge/license-ISC-blue.svg)](/LICENSE)

**Warvis** is your personal steward, answering your questions using Wikidata.

## Installation

### On ArchLinux

```console
sudo pacman -S cython
python -m venv nlp
source nlp/bin/activate
pip install -r requirements.txt
python -m spacy download fr
```

### On Debian / Ubuntu

```console
sudo apt install cython
python3 -m venv nlp
source nlp/bin/activate
pip install -r requirements.txt
python -m spacy download fr
```

## Usage

```console
Usage: warvis <question>
       warvis -h | --help
       warvis --version

Arguments:
    question     Your question in natural language.

Options:
    -h, --help           Show this screen.
    --version            Show version.
```

## Recommended setup for hacking

```console
pip install pudb
pip install ptpython
python -m pudb warvis
```

## Contributing and reporting bugs

Contributions are welcome through [GitHub pull requests](https://github.com/Arkanosis/Warvis/pulls).

Please report bugs and feature requests on [GitHub issues](https://github.com/Arkanosis/Warvis/issues).

## License

Warvis is copyright (C) 2017 Jérémie Roquet <jroquet@arkanosis.net> and
licensed under the ISC license.
