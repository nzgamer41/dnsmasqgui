# dnsmasq GUI
dnsmasq GUI is a simple Web GUI for editing the /etc/hosts file on a computer, with the intention of using it for easily setting up results for dnsmasq use.

## Installation
All you need is a webserver capable of running PHP, and a browser compatible with HTML5 and JavaScript.

I tested using Apache2 on Windows using Google Chrome 103, but I can't see why it wouldn't work on any other browser or webserver given that it's all native PHP/HTML/JS.

The only external resource used is a font from Google Fonts for the header.

## Features
- Display all results in the /etc/hosts file
- Add new results
- Remove resultts

## TODO:
- Allow editing dnsmasq configuration file, potentially via parsing it into HTML elements but alternatively just a in-browser text editor.
- Check to make sure the domain doesn't already exist when adding a record

## LICENSE
Please refer to the LICENSE file in the repository.

## Contributing
Contributions are welcome, please try to stick with how I've got things formatted (so CRLF, 4 spaces, etc) but if there's a tidier way or you want to fix some broken formatting that's okay with me!