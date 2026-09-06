\# Wireshark Configuration commands



\## Setup

&#x09;- First installing the ssh server package to connect to the laptop (which is acting as a server) and enabling it to run even after boot (third command runs a check on its status to verify it is running)

&#x09;	- sudo apt install openssh-server -y \&\& sudo systemctl enable ssh --now \&\& sudo systemctl status ssh

&#x09;- Then actually install Wiregaurd with command to start configuration

&#x09;	- sudo apt install wireguard -y





\## Configuration

