
Overseer


A Raspberry Pi Configured as a Central Management Server

It is absolutely critical that this device be well-secured and not have ports
open to the public Internet. A firewall rule should be instated that blocks ALL
inbound traffic coming into the perimiter -- that means you should be placing
the rules on your router or firewall appliance (you do have something like that
in place, don't you?). We don't want the host to block all inbound traffic
because we still want to manage the device from within the network.

USE THIS RASPBERRY PI IMAGE:
https://www.raspberrypi.org/downloads/
Use the NOOBS installer and install Raspbian. This will be the default image
most Raspberry Pi users will install for their projects, so it will be the one
that we will attempt to harden against direct attack.

KEY APPLICATIONS SPECIFIC TO THIS DEVICE:
Wordpress
ModSecurity