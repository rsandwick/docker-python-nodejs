# Python and Node.js Combined

The Dockerfile here is a simple composition of the ones for the official
[Node.js](https://hub.docker.com/_/node/)
and
[Python](https://hub.docker.com/_/python/)
images. Each branch here represents a combination of the relevant two
fully-specified upstream versions plus the source image variant.

At present, only Python 3.6.8 and Node.js 6.17.0 are used, and only atop
Debian Stretch and its "slim" alternate variant.
