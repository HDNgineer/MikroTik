/
/ip dhcp-client add interface=ether1
/ip dhcp-client print
/ip dhcp-client enable numbers=0
/ip firewall nat add chain=srcnat action=masquerade
/ip firewall nat print
/
