Azure Virtual Network

Objective

Configure and manage Azure Virtual Networks (VNet) to provide secure and scalable cloud networking.

Environment

* Microsoft Azure
* Azure Virtual Network
* Subnets
* Network Security Groups (NSG)

Configuration

Virtual Network Creation

Created a Virtual Network with a dedicated address space.

Example:

* VNet: Production-VNet
* Address Space: 10.0.0.0/16

Subnet Configuration

Configured multiple subnets:

* Management Subnet
* Server Subnet
* User Subnet

Example:

* Management: 10.0.1.0/24
* Servers: 10.0.2.0/24
* Users: 10.0.3.0/24

Network Security Groups

Applied security policies:

* Allow management access
* Restrict unnecessary inbound traffic
* Control inter-subnet communication

Validation

Verified:

* IP address allocation
* Subnet connectivity
* NSG rule functionality
* Resource communication

Skills Demonstrated

* Azure Networking
* Virtual Networks
* Subnet Design
* Network Security Groups
* Cloud Infrastructure Administration
