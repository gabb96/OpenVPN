
Otherwise, use the installer:

1. Pull up a terminal or SSH into the target server.

1. Logon as root

	````
	sudo -i
	````

1. Download the installer script.

	````
	wget https://raw.githubusercontent.com/gabb96/OpenVPN/master/openvpn.sh
	````

1. Make the script executable

	````
	chmod +x openvpn.sh
	````

1. Run the script.

	````
	./openvpn.sh --adminpassword=mypassword
	````
