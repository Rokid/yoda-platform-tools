# yoda-platform-tools

[![Build Status](https://travis-ci.com/Rokid/yoda-platform-tools.svg?branch=master)](https://travis-ci.com/Rokid/yoda-platform-tools)

Tools to interact with YodaOS devices.

## Usage

### yoda-am

Tool to interact with applications.

##### yoda-am open-url <url>

Open a url on device. The url would be dispatched to an app registered for the hostname.

##### yoda-am launch <package-name>

Launch an app on device.

##### yoda-am force-stop <package-name>

Force stop an app on device.


### yoda-pm

##### yoda-pm list

Get info of all packages on device.

##### yoda-pm path <package-name>

Get package directory on device.

##### yoda-pm install <package-local-path>

Install an app from local package path.
