x-qrcode
================

Custom Polymer element to create QR Code.

## Getting started

```
$ cd /your-project-root/
$ git clone https://github.com/vittominacori/x-qrcode.git
$ cd x-qrcode/
$ bower install
```

or install it via bower

```
$ bower install x-qrcode --save
```

## Try it

```
$ cd .. # You'll want to run the web server from the parent directory.
$ python -m SimpleHTTPServer
```

Go to [http://localhost:8000/x-qrcode/demo.html](http://localhost:8000/x-qrcode/demo.html) to see it in action.

## Usage

```
<x-qrcode data="Hello, I'm a custom Polymer element to create QR Code." w="200" h="200"></x-qrcode>
```

## Note

QR Code are generated using [Google Chart](https://developers.google.com/chart/infographics/docs/qr_codes).
