\# Wireshark Configuration commands



\## Setup

&#x09;- First installing the ssh server package to connect to the laptop (which is acting as a server) and enabling it to run even after boot (third command runs a check on its status to verify it is running)

&#x09;	- sudo apt install openssh-server -y \&\& sudo systemctl enable ssh --now \&\& sudo systemctl status ssh

&#x09;- Then actually install Wiregaurd with command to start configuration

&#x09;	- sudo apt install wireguard -y





\## Configuration

&#x09;- Setting up wg0 as a new network interface so wireguard can work its magic and send packets to devices on the virtual IP range

&#x09;	- sudo ip link add dev wg0 type wireguard



\### Notes

&#x09;- Wireguard dose not use MAC address or ARP to communicate to other devices because there is no physical layer connecting these devices together

&#x09;

