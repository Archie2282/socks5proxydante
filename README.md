## Main Info

Script for `Ubuntu`, `Debian` and `CentOS` releases

Dante socks proxy server version - `1.4.2`

Official Dante proxy server page - https://www.inet.no/dante/

______
## Install and configuration section
Clone & run & follow the instructions during installation process
```
git clone https://github.com/Archie2282/socks5proxydante.git && bash socks5proxydante/install.sh
```

### Additional options after install
You can run this script again to:
 1. Add new user for proxy
 2. Remove an existing user
 3. Remove Dante socks proxy server

```shell
bash install.sh
```


______
## Useful tips and tricks


Manual sockd options for Ubuntu and Debian `start`,  `stop`, `restart`, `status`
```shell
/etc/init.d/{PARAM_HERE}
```

Manual sockd options for CentOS `start`,  `stop`, `restart`, `status`
```shell
service sockd {PARAM_HERE}
```


Port, interface, auth metod, ipv4\ipv6 support and other cool options here
```shell
/etc/sockd.conf
```
