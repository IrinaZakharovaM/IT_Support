## Using tcpdump
## fill terminal with a constant stream of text as new packets are read.

```shell
sudo tcpdump -i eth0
```

## the -v flag to enable more verbose output
## the -n avoid generating additional traffic from the DNS lookups, and to speed up the analysis

```shell
sudo tcpdump -i eth0 -vn
```

## tcpdump's filter
## we only want packets where the source or destination IP address matches what we specify (in this case 8.8.8.8)

```shell
sudo tcpdump -i eth0 -vn host 8.8.8.8 and port 53
```

## in second terminal

```shell
dig @8.8.8.8 A example.com
```

## Saving captured packets
## capture on our eth0 interface that filters for only HTTP traffic by specifying port 80. 
## the -w flag indicates that we want to write the captured packets to a file named http.pcap.

```shell
sudo tcpdump -i eth0 port 80 -w http.pcap
```

## in second terminal

```shell
curl example.com # generate some traffic
```

## read from this file using tcpdump 

```shell
tcpdump -r http.pcap -nv
```

## list all running jobs

```shell
jobs -l
```

## This uses the dig utility to query a specific DNS server (in this case 8.8.8.8), asking it for the A record for the specified domain (in this case "example.com").

```shell
dig @8.8.8.8 A example.com
```

