# psychic-spork
# VPN CONNECTING ISSUE WITH FEDORA (Open-VPN)

If you ever face an issue while connecting an open-vpn on fedora, then disable the SElinux and try again.
#The error you probably get is "Activation of network connection failed"

Open the terminal on Fedora and disable the SElinux and try again.

You can disable the SElinux by running the following command.
# #sudo setenforce 0

And connect to the VPN network.

Cheers...
