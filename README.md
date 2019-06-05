# storiesig
Instagram story/highlight(s) downloader using storiesig.com as a pseudo-API.

```
usage: storiesig.py [-h] -u [USER] [-s]

optional arguments:
  -h, --help            show this help message and exit
  -u [USER], --user [USER]
                        Instagram username (required)
  -s, --stories         Only download last 24h stories
```

## Installation
```
$ git clone https://github.com/artikrh/storiesig
$ cd storiesig
$ sudo pip3 install -r requirements.txt
$ chmod +x storiesig.py
```

## Usage

There are two ways you can use this script:

1. If you want to download stored highlights for a user:  
`$ ./storiesig.py -u <username>`  
This will create a new directory based on username with its relevant subdirectories based on highlight names.

2. If you want to only download last 24h stories:  
`$ ./storiesig.py -u <username> --stories`  
This will create a new directory based on username and date/time when the script is executed.
