Aiguillette
===========

A quick and dirty PR dashboard using Eden UI

Install
-------

- Clone this repo
- Download and unzip Eden UI into www : http://scripteden.com/download/eden-ui-bootstrap-3-skin/
- Install dependencies :
```
apt install -y python3-pip
pip3 install ansi2html
```
- Make your web browser serve www/index.html

Usage
-----

```
./fetch.py
./analyze.py
./publish.py
```

- Edit fetch.py and analyze.py to custom list of repo to fetch (should be moved
to a central conf file)
- Don't know the number of API calls someone is allowed to do, so limit the call
to fetch.py :/
- Everything is pretty dirty so far and should be cleaned
