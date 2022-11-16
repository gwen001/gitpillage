# gitpillage

<p align="left">
    <img src="https://img.shields.io/badge/python-v3-blue" alt="python badge">
    <img src="https://img.shields.io/badge/license-MIT-green" alt="MIT license badge">
    <a href="https://twitter.com/intent/tweet?text=https%3a%2f%2fgithub.com%2fgwen001%2fgitpillage%2f" target="_blank"><img src="https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Fgithub.com%2Fgwen001%2Fgitpillage" alt="twitter badge"></a>
</p>

Extract data from a `.git` directory.

## Install

```
git clone https://github.com/gwen001/gitpillage
cd gitpillage
pip3 install -r requirements.txt
```

## Usage

```
$ python3 gitpillage.py -u https://www.example.com/.git/ -t 10
```

```
usage: gitpillage.py [-h] [-u URL] [-t THREADS] [-e EXTENSION] [-x EXCLUDE] [-v]

options:
  -h, --help            show this help message and exit
  -u URL, --url URL     url of the .git, example https://www.target.com/.git
  -t THREADS, --threads THREADS
                        threads, default: 5
  -e EXTENSION, --extension EXTENSION
                        extensions to download separated by comma, overwrite --exclude, default: all but default exclude
  -x EXCLUDE, --exclude EXCLUDE
                        extensions to exclude separated by comma, default: png,gif,jpg,jpeg,ico,svg,eot,otf,ttf,woff,woff2,css,sass,less,po,mo,mp3,mp4,mpeg,avi
  -v, --verbose         verbose mode, default: off
```

<img src="https://raw.githubusercontent.com/gwen001/gitpillage/main/preview.png" />
