sonic-nas-platform-s6000
==================

This repo contains platform-specific files and implementation for the network abstraction service (NAS). The configuration files define port mapping, initial quality of service (QoS) policies, physical media types, and so on.

Build
---------
See [sonic-nas-manifest](https://github.com/Azure/sonic-nas-manifest) for more information on common build tools.

### Build requirements
* `sonic-common`
* `sonic-object-library`
* `sonic-logging`
* `sonic-nas-ndi-api`

### Dependent packages
* `libsonic-logging1` 
* `libsonic-logging-dev`
* `libsonic-common1` 
* `libsonic-common-dev` 
* `libsonic-object-library1` 
* `libsonic-object-library-dev` 
* `libsonic-model1` 
* `libsonic-model-dev` 
* `sonic-ndi-api-dev`

BUILD CMD: sonic_build --dpkg libsonic-logging1 libsonic-logging-dev libsonic-common1 libsonic-common-dev libsonic-object-library1 libsonic-object-library-dev libsonic-model1 libsonic-model-dev sonic-ndi-api-dev -- clean binary

(c) Dell 2016
