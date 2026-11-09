## Create firewall rule
Field	Value
Name	allow-http-port-80
Network	default
Priority	1000
Direction	Ingress
Action	Allow
Targets	All instances in the network
Source IPv4 ranges	0.0.0.0/0
Protocols	Specified protocols and ports
Protocol	TCP
Port	80

Allow HTTP traffic
Click Create.
