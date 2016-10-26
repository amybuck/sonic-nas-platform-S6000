SONiC NAS platform
==================

Platform specific utilities for the SONiC project

Description
-----------

This repo contains platform specific files and implementation for the Network abstraction service. There are configuration files in this repo that define port mapping, initial QoS policies, PHY media types, etc.

Building
---------
Please see the instructions in the sonic-nas-manifest repo for more details on the common build tools.  [Sonic-nas-manifest](https://github.com/Azure/sonic-nas-manifest)

Build Requirements:
 - sonic-common
 - sonic-object-library
 - sonic-logging
 - sonic-nas-ndi-api

Dependent Packages:
  libsonic-logging1 libsonic-logging-dev libsonic-common1 libsonic-common-dev libsonic-object-library1 libsonic-object-library-dev libsonic-model1 libsonic-model-dev sonic-ndi-api-dev

BUILD CMD: sonic_build --dpkg libsonic-logging1 libsonic-logging-dev libsonic-common1 libsonic-common-dev libsonic-object-library1 libsonic-object-library-dev libsonic-model1 libsonic-model-dev sonic-ndi-api-dev -- clean binary

(c) Dell 2016
