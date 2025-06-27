# `px4_msgs`

This repo is defined to work as a place holder for the [EOLab Drone catalog](https://drones.eolab.de/#drones). It is "automagically" synchronized with for firmware [releases](https://github.com/EOLab-HSRW/drones-fw/releases) to match the "physical" firmware and the SITL (Software In The Loop) simulation.

Related workflows:

| [![Generate Firmwares](https://github.com/EOLab-HSRW/drones-fw/actions/workflows/build-firmwares.yml/badge.svg)](https://github.com/EOLab-HSRW/drones-fw/actions/workflows/build-firmwares.yml) |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| (TODO: add .deb package for SITL)                                                                                                                                                               |
| (TODO: auto-sync workflow)                                                                                                                                                                      |
Copied from `CONTRIBUTING.md`:

*Do not* commit changes directly to this repository that change the message definitions. All the message definitions are directly generated from the [uORB msg definitions](https://github.com/PX4/Firmware/tree/master/msg) on the [PX4 Firmware repository](https://github.com/PX4/Firmware).
