# IITM VPN Documentation
IIT Madras provides VPN access to its netowrk via Fortigate SSL VPN. 
In order to enable VPN, student/faculty/staff should make a request to Computer Center.
VPN can be accessed through FortiClient by using LDAP username and password.

## Installation

### Windows, MacOS, iOS & Android

- Download and install `Forticlient` from 
  [FortiNet Website](https://www.fortinet.com/support-and-training/support/product-downloads.html)

### Ubuntu & Debian

- Download and install `OpenFortiGUI` from
  [Bits and Bytes](https://hadler.me/linux/openfortigui/)

### Linux

- Build `OpenFortiGUI` from source: [Instructions](https://hadler.me/linux/openfortigui/)
- Use `OpenFortiVPN` from command line: [Instructions](https://github.com/adrienverge/openfortivpn)

## Usage

### Windows, MacOS, iOS & Android

- Launch FortiClient
- Create a new VPN profile with following parameters:
  - Name: `IITM`
  - Type: `SSL VPN`
  - Server: `vpn.iitm.ac.in`
  - Port: `10443`
  - Username: `<your-ldap-username>`
  - Password: `<your-ldap-password>`
- Save the profile and connect
- You can now use any browser to get IITM interal websites
