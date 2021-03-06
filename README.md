# Dronesmith Download Hub

The purpose of this repository is to provide a hub for all of our downloads.

If you're wondering where to start, consult our [documentation](http://readme.dronesmith.io/).

## API Documentation
Our Dronesmith API documentation is available on [readme.dronesmith.io](http://readme.dronesmith.io/reference).

## Dronesmith Engine
Dronesmith Engine lives on a drone's onboard Linux processor and establishes connection with Dronesmith Cloud if available, along with creating a general status page. It also provides local access to the API, so you don't always have to be connected to the cloud. See the `dronesmith-engine` folder for downloads. Generally, unless otherwise specified, you will want to download the latest version of your system architecture.

See our [install guide](http://readme.dronesmith.io/docs/install-dsengine) for more information about how to install and use.

## Luci Firmware
You can get the latest Luci flight control PX4 Firmware from the `Luci` folder. Please download the latest firmware from your hardware revision letter, indicated on your Luci board. See our [firmware guide](http://readme.dronesmith.io/docs/firmware) for more info.

Our firmware is open source. If you'd like to contribute, see our [github page](https://github.com/Dronesmith-tech/Firmware).

### Preset Params
We also provide preset params (settings for Luci), which you can obtain from the `luci/params` directory. Simply move this file into the root directory of your Micro SD Card and insert it into the `FMU SD` slot of your Luci. Next time your Luci starts, it will load with these params. See [PX4 params](http://dev.px4.io/advanced-configurations.html) and [system startup](http://dev.px4.io/advanced-system-startup.html) for more information.
