![](http://res.cloudinary.com/jollen/image/upload/h_110/v1455862763/devify-logo_rh63vl.png)

ESP8266 over the Web: Getting started with IoT System Architecture

# Project Goal

![](https://cloud.githubusercontent.com/assets/1126021/13699804/b9498212-e7b7-11e5-99e3-734ac6bf91da.png)

The use scenario of this project.

* Save hardware data to Dropbox files
* The name of each file is according to the current timestamp

This project shows how to extend devify-server biolerplate to save data to Dropbox files. Please read [Devify](https://github.com/DevifyPlatform/devify-server/blob/master/README.md) to understand Devify in a bit before continue to this project.

## Prerequisites

The guidelines are the same with the previous lessons. Therefore, this lesson will be explained in a short. Please read the previous 3 lessons before starting the project of this lesson. 

* [101-air-quality-sensor-console-print](../101-air-quality-sensor-console-print)
* [101-air-quality-sensor-text-messaging-twilio](../101-air-quality-sensor-text-messaging-twilio)
* [102-air-quality-sensor-email](../102-air-quality-sensor-email)

## Quickstart

1. This project uses Dropbox APIs. Please signup and get your own application key at [Dropbox](https://dropbox.com/).

2. Please copy ```config.app.json.example``` to ```config.app.json```.

3. Please copy ```config.access_token.json.example``` to ```config.access_token.json```.

4. Please modify ```config.app.json``` and ```config.access_token.json``` to fill with your Dropbox token and secret key.

## Next

* [201: Building Real-Time Dahsboard](../201-web-of-things-dashboard/)
