# ZenPacks.community.ImprovedEthernetCsmacd

Creates a ethernetCsmacd_64 monitoring template on /network that includes the regular ethernetCsmacd_64 datasources/graphs and adds: 

Datasources/datapoints

-ifHCInMulticastPkts
-ifHCOutMulticastPkts
-ifHCInBroadcastPkts
-ifHCInBroadcastPkts

Graphs

-Broadcast Packets
-Multicast Packets

Thresholds 
- Errors (Raises event on 10 errors or more)
