## Infoga - Email Information Gathering

Infoga is a tool gathering email accounts informations (ip,hostname,country,...) from different public source (search engines, pgp key servers and shodan) and check if emails was leaked using haveibeenpwned.com API. Is a really simple tool, but very effective for the early stages of a penetration test or just to know the visibility of your company in the Internet.

 ![screen](https://raw.githubusercontent.com/m4ll0k/Infoga/master/screen/main.png)

## Installation

```
$ git clone https://github.com/m4ll0k/Infoga.git infoga
$ cd infoga
$ python setup.py install
$ python infoga.py
```

## Usage

```
$ python infoga.py --domain nsa.gov --source all --breach -v 2
```

![run_!](https://raw.githubusercontent.com/m4ll0k/Infoga/master/screen/run_2.png)
