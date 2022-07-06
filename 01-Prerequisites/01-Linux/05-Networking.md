# Networking

Devices attached to a network must have at least one unique network address identifier known as the IP (Internet Protocol) address. The address is essential for routing packets of information through the network. There are two different types of IP addresses available: IPv4 (version 4) and IPv6 (version 6). IPv4 is older and by far the more widely used, while IPv6 is newer and is designed to get past limitations inherent in the older standard and furnish many more possible addresses.

`IPv4` uses 32-bits for addresses; there are only 4.3 billion unique addresses available.

`IPv6` uses 128-bits for addresses; this allows for $3.8*10^{38}$ unique addresses.

## Decoding IPv4 addresses

```
IP address →        172  .    16  .    31  .   46
Bit format →     10101100.00010000.00011111.00101110
```
`$ /sbin/ip addr show`: To view the IP address

`$ /sbin/ip route show`: To view the routing information
