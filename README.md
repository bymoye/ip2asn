# ip2asn

a iptoasn tools

download the latest file from https://iptoasn.com/data/ip2asn-v4.tsv.gz and extract it to the same directory as the executable.

## Quickstart

"""python
from nazo_ip2asn import Ip2Asn

ip2asn = Ip2Asn(ipv4file="ip2asn-v4.tsv", ipv6file="ip2asn-v6.tsv")

print(ip2asn.lookup(b"8.8.8.8"))

"""
