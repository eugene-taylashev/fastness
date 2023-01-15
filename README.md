# fastness
A distributed network of services for remote location with limited Internet coverage and typical hydro. Designed as Infrastructure as a Service (IaaS), Infrastructure as a Code (IaaC)

*[fastness](https://www.merriam-webster.com/dictionary/fastness) - a remote and secluded place*

Initial requirements:
- Debian x86/x64 based to run on any old/outdated hardware
- Low power consumtion. Available voltage is 5v and 12V, get 110/220 with an invertor. Like Jackery Exploler 240
- Scalability: solution will run on one system, or could be distributed to few
- Minimum services:
  - Internet gateway to connect a cell phone or Starlink for RV
  - Wi-Fi Access Point (hostapd)
  - DHCP
  - Internal DNS
  - LDAP for authentication
  - Web service for an entertainment content
  - File sharing using CIFS/Samba
  - VOIP using [uMurmur](https://umurmur.net/) and [Plumble](https://play.google.com/store/apps/details?id=com.morlunk.mumbleclient.free&hl=en_CA&gl=US)
  - SSH for administration


![Jackery Explorer](https://www.jackeryportablepowerstation.com/wp-content/uploads/2021/05/49-1.jpg)
![Starlink RV](https://www.hitched4fun.com/wp-content/uploads/2022/10/Starlink-RV-Pole-Kit.jpeg)
