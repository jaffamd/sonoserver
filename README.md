# sonoserver
 A simple, user-friendly software platform to facilitate livestreaming ultrasound images for realtime feedback and guidance.

## Installation
This version (2.1.0) has been configured to run on Ubuntu with Nginx as the webserver and UFW for a firewall. This is a very basic configuration. Log into your server, and run the following commands from the command line:
```
wget https://raw.githubusercontent.com/jaffamd/sonoserver/master/configure-server
sudo chmod +x configure-server
sudo ./configure-server
```
A few of the prompts require user input (all self-explanatory; basically just hit the `Enter` key to get through these). Make note of the IP address, and use that as the target of your [Sonostreamer](https://github.com/jaffamd/sonostreamer) to start livestreaming.
