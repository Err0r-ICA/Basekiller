# Basekiller

**Basekiller** is a tool written in Python that can decode all alphanumeric base encoding schemes. This tool can accept single user input, multiple inputs from a file, input from argument, **multi-encoded bases** and decode them incredibly fast.

Decode Base16, Base32, Base36, Base58, Base62, Base64, Base64Url, Base85, Base91, Base92 and more with the best base encoding scheme decoding tool in town. It's useful for **CTFs**, **Bug Bounty Hunting**, and **Cryptography**.

------------

## Supported Encoding Schemes
- Base16
- Base32
- Base36
- Base58
- Base62
- Base64
- Base64Url
- Base85
- Base91
- Base92

## Main Features
- **Can decode multi-encoded bases of any pattern.**
- Can decode multiple base encodings from a file.
- **Generate a wordlist/output with the decoded bases.**
- Predicts the type of encoding scheme.

## Installation
    $ git clone https://github.com/Err0r-ICA/basekiller
    $ cd basekiller
    $ pip install -r requirements.txt
    $ python basekiller.py -h

## Screenshot
![Screenshot](https://i.postimg.cc/L8pbHYbx/Screenshot-20201104-050209-Termux.jpg) 

## Usage
To decode a single base encoding from user input:

    python basekiller.py

To decode a single base encoding from argument **(-b/--base)**:

    python basekiller.py -b SGVsbG8gV29ybGQh

To decode multiple base encodings from a file **(-f/--file)**:

    python basecrack.py -f file.txt

**Magic Mode:** To decode multi-encoded base of any pattern **(-m/--magic)**:

    python basekiller.py --magic

To generate a wordlist/output with the decoded bases **(-o/--output)**:

    python basekiller.py -f file.txt -o output-wordlist.txt
