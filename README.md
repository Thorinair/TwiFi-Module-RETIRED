**NOTE: This repository is now retired and should no longer be used. I am currently working on a new proper library for this.**

# TwiFi Module (RETIRED)
TwiFi is a simple software module which allows you to easily manage the WiFi connections on your ESP8266. The module works like a template. It is designed to be placed directly into your project as the code should be modified to your needs, along with the configuration file. Please check the contents of the files and look for comments starting with `/****** [ADD CODE]`.

# Usage
Before using, copy the source code files to your project. No need to copy the README or the licence. Once copied, include the `TwiFi.h` header to get started. Rename the `ConfigurationWiFi_EXAMPLE.h` file to `ConfigurationWiFi.h` and edit it to define all the different networks you wish to connect to and set other parameters. Up to 8 WiFi networks can be defined. Please refer to the configuration file for more details. To start a connection, call the `connectWiFi` funcion. You may also specify whether the cycle of attempts should repeat. The function will return a result once it finishes executing.