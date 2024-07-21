# Network Topology Diagram ( LAN, WAN, Switch, Firewall)

![Network Topology Diagram drawio](https://github.com/user-attachments/assets/3c5115b2-b07c-4abd-988d-31fb8c973ed9)

## Web/Internet
- <b>Function: The internet ultimately is a global network that allows users to communicate, share information, and access web pages.
  
- Importance:  In this specific example, we focus on the web due to 95% of security breaches being human error. Users are typically browsing/researching via the web which can lead to potential threats.</b>

## Primary Modem
- <b>Function: In its simplest form, a modem is intended to allow communication between one or more devices and the internet.
  
- Popular ISP's: Spectrum, Verizon, AT&T</b>

## Firewall
- <b>Function: Firewalls allow for policies to be configured to determine whether traffic is allowed to enter the host network.
  
- Popular Manufacturers: Fortinet, Palo Alto, Cisco</b>

## Backup Internet
- <b>Function: To allow for network resiliency, I have included the backup internet modem. This device allows for a seamless transition, if the primary modem were to fail, and can prove invaluable to users who need constant reliable connections.
  
- Popular Manufacturers: Cisco, NETGEAR, Cradlepoint</b>

## Network Switch
- <b>Function: Connects all devices within a LAN/WAN, allowing multiple devices to communicate simultaneously.

- Duplex: Switches are typically Full Duplex, unlike a Network Hub which only allows 1 instance of communication: Half Duplex.

- Popular Manufacturers: HP/Aruba, Cisco, NETGEAR</b>

## Wireless Router
- <b>Function: Allows mobile devices such as laptops, tablets, and cellphones to connect to the network. Also, routes data packets to appropriate devices and assigns IP addresses using DHCP.

- Popular Manufacturers: Spectrum, NETGEAR, Cisco</b>

## Server
- <b>Function: Stores data, resources, and provides services to devices within the network.
  
- AWS: Ideally we would utilize a cloud service provider such as AWS to leverage ELB (Elastic Load Balancing) to automatically distribute any incoming traffic to be prepard in case of any possible DDos attacks.
  
- Popular Manufacturers: HP, DELL, Lenovo</b>

## Patch Panel
- <b>Function: Connects network switches to wall ports throughout a building, typically using CAT5 RJ45 cables. Helps in organizing and tracing network connections.
  
- Best Practice: Label wall ports to easily trace connections back to the patch panel and switch, ensuring cables are correctly patched into the switch according to the configured VLAN.

- Toner & Probe Kit: Alternatively, you can also utilize a Toner & Probe kit to trace a patch cable via its electrical signal.</b>

## User Devices
- <b>Examples: Printers, POS systems, desktops, etc.

- LAN Connection: These devices are patched into the wall ports, which lead to the patch panel, and ultimately go into the intended port on the switch based on the configured VLAN.

- Wireless Connection: Devices connected wirlessly to a network, communicate via radio waves/frequencies and transmit data to the wireless router which then allows for internet access.
  
- Configuration: These devices typically have statically set IP Addresses, Subnet masks, Default gateways, & DNS according to the network IP scheme.</b>



Authored by: Brian Hernandez
