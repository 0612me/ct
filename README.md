<img src="https://cloud.githubusercontent.com/assets/633843/9855504/f30a715c-5b51-11e5-83f3-f4fab03e5459.png" alt="screenshot"/>

### Features

* Single binary
* Cross platform
* Embedded search
* Serve download directory
* [*More features coming soon*](https://github.com/jpillora/cloud-torrent/labels/core-feature)

### Install

**Binaries**

See [the latest release](https://github.com/jpillora/cloud-torrent/releases/latest) or download it now with `curl i.jpillora.com/cloud-torrent | bash`

**Source**

``` sh
$ go get -v github.com/jpillora/cloud-torrent
```

**Heroku**

Click this button to...

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

### Usage

```
$ cloud-torrent --help

  Usage: cloud-torrent [options]

  Options:
  --port, -p        Listening port (default 3000, env PORT)
  --host, -h        Listening interface (default all)
  --auth, -a        Optional basic auth (in form user:password) (env AUTH)
  --configpath, -c  Configuration file path (default cloud-torrent.json)
  --log, -l         Enable request logging
  --help
  --version, -v

  Version:
    0.8.1

  Read more:
    https://github.com/jpillora/cloud-torrent

```

### Overview

Cloud torrent is a hosted torrent client written in Go (golang). This project is the version 2 rewrite of the original [Node version](https://github.com/jpillora/node-torrent-cloud).

![overview](https://docs.google.com/drawings/d/1ekyeGiehwQRyi6YfFA4_tQaaEpUaS8qihwJ-s3FT_VU/pub?w=606&h=305)

#### MIT License

Copyright © 2015 Jaime Pillora &lt;dev@jpillora.com&gt;

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
