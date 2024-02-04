The DNS servers of your ISP can be somewhat unreliable. Because of that, it can be desirable to configure alternative DNS servers.

If you're using KDE, the configuration for DNS can be found here:
`System Settings | Connections | IPv4 | DNS Servers`
or
`System Settings | Connections | IPv6 | DNS Servers`
Depending whether you're using IPv4 or IPv6. These are comma separated lists that contain the IP addresses of the DNS servers you want to use.

Below are some recommendations for DNS servers (IPv4):

- OpenDNS
	- [OpenDNS.com](https://www.opendns.com)
	- Default
		- [OpenDNS dashboard](https://dashboard.opendns.com/)
			- requires free account
		- IPv4 (can be used without account I think)
			- [OpenDNS setupguide](https://www.opendns.com/setupguide/)
			- 208.67.220.220
			- 208.67.222.222
		- IPv6
			- 2620:119:35::35
			- 2620:119:53::53
		- IPv6 Non-filtering
			- 2620:0:ccc::2
			- 2620:0:ccd::2
	- Family friendly (Family Shield, blocks adult content)
		- [OpenDNS familyshield](https://www.opendns.com/setupguide/#familyshield)
		- 208.67.222.123
		- 208.67.220.123
- AdGuard
	- [adguard.com](https://www.adguard.com)
	- [adguard public dns](https://adguard-dns.io/en/public-dns.html)
	- IPv4 Default (blocks ads and trackers)
		- 94.140.14.14
		- 94.140.15.15
	- IPv4 Non-filtering
		- 94.140.14.140
		- 94.140.14.141
	- IPv4 Family protection (blocks ads, trackers, adult content ...)
		- 94.140.14.15
		- 94.140.15.16
	- IPv6 Default (blocks ads and trackers)
		- 2a10:50c0::ad1:ff
		- 2a10:50c0::ad2:ff
	- IPv6 Non-filtering
		- 2a10:50c0::1:ff
		- 2a10:50c0::2:ff
	- IPv6 Family protection (blocks ads, trackers, adult content ...)
		- 2a10:50c0::bad1:ff
		- 2a10:50c0::bad2:ff
	