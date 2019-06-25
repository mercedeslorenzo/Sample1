# Featured Bluetooth Lower Energy and Multi-mode SoC

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.




### New Features!

- Lorem ipsum dolor sit amet consectetur, adipiscing elit pretium vivamus.
- Parturient at aenean dictum accumsan dapibus, rhoncus aliquam donec.
- Penatibus erat litora luctus sodales, cubilia elementum habitant.
- Potenti laoreet est sapien sodales tellus, curae augue sem.


### Tech

Dillinger uses a number of open source projects to work properly:

* [TLSR8232](http://wiki.telink-semi.cn/doc/ds/DS_TLSR8232-E_Datasheet%20for%20Telink%20BLE%20SoC%20TLSR8232.pdf) - The TLSR8232 is Telink-developed BLE SoC solution, which is Bluetooth 4.2 fully standard compliant to allow easy connectivity with Bluetooth Smart Ready mobile phones, tablets, laptops. The TLSR8232 supports BLE slave and master mode operations. It also supports BLE 5.0 2Mbps mode and long packet length.

* [TLSR8258](http://wiki.telink-semi.cn/doc/ds/PB_TLSR8258-E_Product%20Brief%20for%20Telink%20BLE%20IEEE802.15.4%20Multi-Standard%20Wireless%20SoC%20TLSR8258.pdf) - The TLSR8258 with internal Flash and audio support combines the features and functions needed for all 2.4GHz IoT standards into a single SoC. It supports standards and industrial alliance specifications including Bluetooth Low Energy (up to Bluetooth LE 5.0, with up to 8 antenna indoor positioning support), BLE Mesh, Zigbee, RF4CE, HomeKit, 6LoWPAN, Thread, ANT and 2.4GHz proprietary standard. For some use cases, the TLSR8258 supports concurrent multi-standards.

* [TLSR8269](http://wiki.telink-semi.cn/doc/ds/PB_TLSR8269F512-E_Product%20Brief%20for%20Telink%20BLE%20%2B%20IEEE802.15.4%20Multi-Standard%20Wireless%20SoC%20TLSR8269F512.pdf) - The TLSR8269 is Telink-developed BLE + IEEE802.15.4 multi-standard wireless SoC solution.
The TLSR8269 supports standards and industrial alliance specifications including Bluetooth Smart (BLE4.0 and BLE4.2), BLE Mesh, 6LoWPAN, Thread, Zigbee, RF4CE, HomeKit and 2.4GHz proprietary protocols.
For some use cases, the TLSR8269 supports concurrent multi-standards in which stacks like RF4CE and BLE can run simultaneously.


### Installation

Dillinger requires [Node.js](https://nodejs.org/) v4+ to run.

Install the dependencies and devDependencies and start the server.

```sh
$ cd dillinger
$ npm install -d
$ node app
```

For production environments...

```sh
$ npm install --production
$ NODE_ENV=production node app
```

### Development

Want to contribute? Great!

Dillinger uses Gulp + Webpack for fast developing.
Make a change in your file and instantanously see your updates!

Open your favorite Terminal and run these commands.

First Tab:
```sh
$ node app
```

Second Tab:
```sh
$ gulp watch
```

(optional) Third:
```sh
$ karma test
```
#### Building for source
For production release:
```sh
$ gulp build --prod
```
Generating pre-built zip archives for distribution:
```sh
$ gulp build dist --prod
```
