# Network Topology Diagram ( LAN, WAN, Switch, Firewall)

![Network Topology Diagram drawio](https://github.com/user-attachments/assets/3c5115b2-b07c-4abd-988d-31fb8c973ed9)

<b>Above is a network topology diagram created with networking principles such as LAN, WAN, Wireless, and Firewalls. This diagram intends to demonstrate how networks are interconnected in their simplest form.</b>

## Let me walk you through each of the components of this diagram.

- <b>Web/Internet: At the top left of this diagram, we have the internet. The internet ultimately is a global network that allows users to communicate, share information, and access web pages. In this specific example, we focus on the web due to 95% of security breaches being human error. And in a business setting users are typically browsing/researching via the web which can lead to potential threats.</b>

- <b>Primary Modem: In its simplest form, a modem is intended to allow communication between one or more devices and the internet. Popular ISP are (Spectrum, Verizon, AT&T)</b>

- <b>Firewall: Next, we have the Firewall. These devices allow for policies to be configured to determine whether traffic is allowed or not allowed to enter the host network. Popular Brands are (Fortinet, Palo Alto, Cisco)</b>

- <b>Backup Internet: To allow for network resiliency, I have included the backup modems. This device will allow for a seamlessly smooth transition say if the primary modem were to go down and can prove invaluable to users who need constant reliable connections. Popular brands are (Cisco, NETGEAR, Cradlepoint)</b>

- <b>Network Switch: The device that connects all devices within a LAN/WAN is referred to as a Network Switch. Switches allow for multiple devices, users, IT equipment to communicate at the same time. Switches are typically Full Duplex, (unlike a Network Hub which only allows 1 instance of communication, Half Duplex.) Popular brands are (HP/Aruba, Cisco, NETGEAR)</b>

- <b>Wireless Router: Subsequently, we have a wireless router that allows Mobile devices such as Laptops, Tablets, & Cellphones to connect to the set network. Another primary function of a router is to receive and analyze packets and based on IP/MAC Addresses/Headers, the device then routes the data to the appropriate device within the network. Lastly, the router also provides the IP address for device given that the device is set for DHCP.Popular brands are (Spectrum, NETGEAR, Cisco)</b>

- <b>Server: Servers essentialy are a computer system which stores data, resources, and provides services for devices within the network. For more complex networks, ideally we would utilize a cloud service provider such as AWS to launch several EC2 instances acrros multiple different Availablity Zones & Regions to increase the network resiliency in case of any possible DDos attacks. Popular brands are (HP, DELL, Lenovo)</b>

- <b>Patch Panel: Network switches connect to Patch Panels (typically via CAT5 RJ45 Cables) which then connect to wall ports across the building. It is best practice to label the wall ports in the building to easily trace the runs back to the patch panel and ultimately back to the switch to ensure the cable is patched into the correct port based; given that the switch has a configured VLAN. Alternatively, you can also utilize a Toner & Probe kit to trace a patch cable via its electrical signal.</b>

- <b>User Devices: Lastly, we have the user devices which range from but are not limited to printers, POS systems, and desktops which are hooked up via an ethernet cable. These devices are patched into the wall ports, which lead to the patch panel, and ultimately go into the intended port on the switch based on the configured VLAN. These devices typically have statically set IP Addresses, Subnet masks, Default gateways, & DNS according to the network IP scheme.</b>

Authored by: Brian Hernandez
