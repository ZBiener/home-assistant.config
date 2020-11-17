This repository contains configuration files for a Home Assistant installation on a RaspberryPi 3B, running Hassio operating system. 

The config depends on:
+ A basic installation of Hassio
+ The following add-ons:
  + Duck DNS, 
  + MQTT Mosquitto Broker, 
  + RTL\_433 to MQTT Bridge, repository by James Fry
  + Samba Share, 
  + SSH Addons. 
  Note that RTL\_433 uses an alternate script found in the RTL_433 folder and setting found in vacuum.yaml,  Duck DNS, SSH, and MQTT Broker use the keys found in the SSL directory that is not backed up here.
+ The following integrations, installed through the GUI:
  + HACS
  + Tile
  + MQTT 
+ The HACS installation further requires the following repositories to be installed:
  + fold-entity-row
  + vertical stack in card
  + card-tools
  + secondaryinfo entity row
  + loveland home feed card