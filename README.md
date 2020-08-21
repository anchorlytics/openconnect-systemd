# openconnect-systemd
systemd service unit for openconnect client for Cisco AnyConnect VPN

## Usage
+ Copy service file to `/etc/systemd/service/openconnect.service`
+ Copy netdev file to `/etc/systemd/network/vpn0.netdev`
+ (Optional) systemd unit config in `/etc/default/openconnect`
+ (Optional) openconnect config in `/etc/openconnect.conf` (see openconnect (8))

## Thanks
+ [Infradead OpenConnect](https://github.com/openconnect/openconnect)
