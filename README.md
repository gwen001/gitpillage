# gitpillage

![python badge](https://img.shields.io/badge/python-v3-blue)  ![python badge](https://img.shields.io/badge/python-v3-blue)  
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

---

I don't believe in license.  
You can do whatever you want with this program.


