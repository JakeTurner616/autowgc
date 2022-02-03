# autowgc (Auto Wireguard Client)
Allows for easy managment of a wireguard connection.


------------



Syntax: 	 ./autowgc	  [ 	-h  	| -a `<file>` |  -s  	 ] Where ``<file>` is the location of a valid wireguard config.

 flags:
 
 -a  `<file>`  Add a wireguard client config file or ommit the `<file>` to start an already added connection.
 
 > EXAMPLE:   ./autowgc -a ~/Wireguard.conf
 
 -s           	Stop the wireguard VPN easily.
 
 -h           	Shows command syntax and other info.
