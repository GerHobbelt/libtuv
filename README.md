You can find project details in [wiki](https://github.com/pando-project/libtuv/wiki)

---

### Overview

**libtuv** is multi-platform **tiny event library** refactored from [libuv](https://github.com/libuv/libuv) source for IoT.js and embedded system.

[Lightweight points](https://github.com/Samsung/libtuv/wiki/Lightweight-points) page is list of ideas how to make memory saving.

### Features

* loop (working: linux, nuttx, mbed)
* idle (working: linux, nuttx, mbed)
* timer (working: linux, nuttx, mbed)
* poll (working: linux, nuttx)
* tcp (working: linux, nuttx)
   * Enabling tcp
* udp
* fs (working: linux, nuttx)
   * [Enabling file system](https://github.com/Samsung/libtuv/wiki/Enabling-file-system)
* thread (working: linux, nuttx, mbed:emulation)
* worker (working: linux, nuttx)
* ...

### APIs

Supported APIs are listed at [libtuv APIs](https://github.com/Samsung/libtuv/wiki/libtuv-APIs) page.


### Building

Read [How to Build](https://github.com/Samsung/libtuv/wiki/How-to-Build) for building libtuv

##### Supported target platforms

* i686-linux (Ubuntu Linux 14.04 on Intel core) (working)
* arm-linux (Raspbian on Raspberry Pi 2) (working)
* arm-nuttx (NuttX on STM32F4-discovery) (working)
* arm-mbed (mbed on FRDM-K64F) (in development)

### License

Read [License](https://github.com/Samsung/libtuv/wiki/License) for license of libtuv

### Getting involved

To contribute to the libuv Project (such as reporting bugs and submitting patches):

* Follow the [IoT.js Development Process](https://github.com/Samsung/iotjs/wiki/Development-Process) and [GitHub contributor guidelines](https://guides.github.com/activities/contributing-to-open-source/).
* Add the [libtuv DCO signoff](https://github.com/Samsung/libtuv/wiki/libtuv-Developer's-Certificate-of-Origin-1.0) to each commit message during development.

