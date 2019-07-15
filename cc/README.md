# HOPE-Box - Command Center (CC)

The following is information provided in regards to the command center and its function in the network.  


## Outline

Checkout the following to gain an overview of the different sections of the `CC`.

* `client/` - the user interface delivered over WiFi to interact with the `CC`.
* `configs/` - configuration files used to run the different `Osmocom` services.
* `pi/` - files to be copied to the `Pi` after the operating system has been burned to the SD card.
* `scripts/` - bash scripts related to the `BTS`.
* `server/` - the server that accepts data as a TCP server for plotting on the graph and user interface.


## Install

To setup and configure the system on a debian based system please refer to the `scripts/install.sh` file.  

If you are running on Ubuntu 18+ you can execute the script to install the system for you `bash scripts/install.sh`.


## Run

To start the command center please run `bash scripts/start.sh`.  


## Clean

To cleanup or force new builds of the required services please run `bash scripts/clean.sh`.  Once completed you can now do a fresh install.
