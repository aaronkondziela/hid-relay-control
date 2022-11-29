# hid-relay-control

A hacky shellscript to control the USB Relays you can find out there that speak HID instead of serial.
Specifically, I developed it for Amazon product ID B07CFQMDJ3, the 2 relay version. Haven't tested with
any of the others but should all work similarly.

## Prerequisites

You will need the [hidapitester command](https://github.com/todbot/hidapitester) installed.

## Usage

It's a shell script. Make sure it's marked as readable and executable, and put it wherever you want it.

	relay <all|1|2> <on|off>

## License

Copyright © 2022 Aaron Kondziela

CC-BY https://creativecommons.org/licenses/by/4.0/

