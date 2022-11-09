novacomd
========

This build of novacomd compiles on macOS, which allows it to run on Macs that no longer support 32-bit binaries. Tested on Big Sur 11.0.1, GNU Make 3.81

Before building, you need the libusb-compat library. The easiest way to install it is via Homebrew:

> brew install libusb-compat

To build:

> make host

To install, copy `build-novacomd-host/novacomd` to the `/bin` directory of your Palm SDK install (usually `/opt/nova/bin`).

For more detailed, step-by-step instructions for installation on both Intel and Apple Silicon machines, please see the webOS Archive Docs:
[https://docs.webosarchive.org/macos-install/](https://docs.webosarchive.org/macos-install/)

Thanks to [NotAlexNoyle](https://github.com/NotAlexNoyle/novacomd) for doing the USB compatibility legwork.

# Copyright and License Information

Unless otherwise specified, all content, including all source code files 
and documentation files in this repository are:
 Copyright (c) 2008-2012 Hewlett-Packard Development Company, L.P.

Unless otherwise specified, all content, including all source code files
and documentation files in this repository are:
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this content except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.


