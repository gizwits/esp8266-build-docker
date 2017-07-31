# ESP32, ESP8266 and ESP8285 build environment
[![Docker Pulls](https://img.shields.io/docker/pulls/gizwits/esp8266-build-docker.svg)](https://hub.docker.com/r/gizwits/esp8266-build-docker/) [![Docker Stars](https://img.shields.io/docker/stars/gizwits/esp8266-build-docker.svg)](https://hub.docker.com/r/gizwits/esp8266-build-docker/) [![License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat)](https://github.com/github/esp8266-build-docker/blob/master/LICENSE)

It is a build environment of espressif's Wi-Fi(or bluetooth) Soc.

## Overview

This project is mainly inspired by [this](https://github.com/vowstar/esp8266.git) and [this](https://github.com/igrr/esptool-ck) projects. The only difference is it is built on top of a Jenkins Slave base, so it can be used as a Jenkins agent.

Credits go to [vowstar](https://github.com/vowstar) and [Christian Klippel](https://github.com/igrr).