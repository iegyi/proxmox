


 nano /etc/network/interfaces
 //interfaces//
auto vmbr0
iface vmbr0 inet static
        address 38.92.26.232/29
        gateway 38.92.26.233
        bridge-ports enp1s0f0
        bridge-stp off
        bridge-fd 0

        //commands//
         systemctl restart networking.service
