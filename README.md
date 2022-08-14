# autowgc (Auto Wireguard Client)
Allows for easy managment of a wireguard connection. Requires a root or sudo user.


------------
Download:

`sudo wget -qO - api.serverboi.org > ~/autowgc.sh`

Execute:

`sudo bash ~/autowgc.sh`

------------

Syntax: 	 sudo bash ~/autowgc	  [ 	-h  	| -a `<file>` |  -s  	 ]

 flags:
 
 -a  `<file>`  Add a wireguard client config file or ommit the `<file>` to start an already added connection.
               `<file>` Should be the location of a valid wireguard config. > EXAMPLE: sudo ~/autowgc -a ~/Wireguard.conf
 
 -s           	Stop the wireguard VPN.
 
 -h           	Shows command syntax and other info.
