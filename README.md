# WIRINGPI-IOTJS #

[![GitHub forks](
https://img.shields.io/github/forks/rzr/wiringpi-iotjs.svg?style=social&label=Fork&maxAge=2592000
)](
https://GitHub.com/rzr/wiringpi-iotjs/network/
)
[![License](
https://img.shields.io/badge/licence-BSD-3.svg?style=flat
)](LICENSE)
[![NPM](
https://img.shields.io/npm/v/wiringpi-iotjs.svg
)](
https://www.npmjs.com/package/wiringpi-iotjs
)
[![IRC Channel](
https://img.shields.io/badge/chat-on%20freenode-brightgreen.svg
)](
https://kiwiirc.com/client/irc.freenode.net/#tizen
)

Lightweight reimplentation of wiring-node for IoT.js,

WARNING: it's not isofunctionnal, many features are dropped, but API should align
to help porting Node.js modules to IoT.js

* URL: <https://github.com/rzr/wiringpi-iotjs>

[![NPM](
https://nodei.co/npm/wiringpi-iotjs.png
)](
https://npmjs.org/package/wiringpi-iotjs
)

## USAGE ##

### USING IOTJS ###

Running from sources tree is straightforward, but each step will be detailed.

```sh
git clone --depth 1 https://github.com/rzr/wiringpi-iotjs ; cd wiringpi-iotjs
iotjs example
#| GPIO: Setup: pin=5: direction=1
#| GPIO: write: high: pin=5
#| GPIO: write: low: pin=5
```

### DEMO ###

```sh
iotjs example
```

Or using more advanced device:

[![wiringpi-iotjs](
https://pbs.twimg.com/ext_tw_video_thumb/1019945702791766017/pu/img/bbbNf-HJR2FkUb5l.jpg
)](
https://twitter.com/TizenHelper/status/1019945989388546048#
"blinkt-node")

### USING NODEJS ###

Node is not yet supported but for debugging purpose, gpio calls can be stubbed.

## EXTRA ##

An extra I2C API has been added to ensure compatibility between IoT.js and Node.js.

## RESOURCES ##

* <https://github.com/rzr/wiringpi-iotjs>
* <https://www.npmjs.com/package/wiringpi>
* <https://libraries.io/npm/wiringpi-iotjs>
* <https://github.com/Soarez/node-wiring-pi>
* <https://www.npmjs.com/package/wiringpi-node>
* <https://github.com/fengjiannan2010/wiringpi-node>
* <http://iotjs.net>
* <https://github.com/~rzr>
* <https://github.com/Irrelon/node-blinkt>
* <https://github.com/Irrelon/node-blinkt/pull/15>
