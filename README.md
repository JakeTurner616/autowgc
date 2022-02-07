# autowgc (Auto Wireguard Client)
Allows for easy managment of a wireguard connection. Requires a root or sudo user.


------------
Download and Chmod:

`sudo curl -o ~/autowgc.sh https://raw.githubusercontent.com/JakeTurner616/autowgc/main/autowgc.sh && sudo chmod a+x ~/autowgc.sh`

Execute:

`sudo ~/autowg.sh`

------------

Syntax: 	 sudo ~/autowgc	  [ 	-h  	| -a `<file>` |  -s  	 ]

 flags:
 
 -a  `<file>`  Add a wireguard client config file or ommit the `<file>` to start an already added connection.
               `<file>` Should be the location of a valid wireguard config. > EXAMPLE: sudo ~/autowgc -a ~/Wireguard.conf
 
 -s           	Stop the wireguard VPN easily.
 
 -h           	Shows command syntax and other info.
