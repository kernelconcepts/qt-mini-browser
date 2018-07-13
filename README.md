# qt-mini-browser
Simple Qt/QML based webkit browser

## Installation

The qt mini browser can be installed using `dpkg` as follows:
``` bash
  dpkg -i qt-mini-browser_1.0.0_armhf.deb
  apt install -f
```

## Usage

The browser can be started showing an initial page given by the first command line argument:
``` bash
  qt-mini-browser https://kernelconcepts.de
```
To visit another page a physical keyboard has to be connected. `ALT+BACKSPACE` shows the url text field, which can be edited and confirmed by pressing `ENTER`.
