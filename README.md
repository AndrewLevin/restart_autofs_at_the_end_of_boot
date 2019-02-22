# For resolving the issue of "Permission Denied" errors occurings when "ls /eos/" is issued after reboot of a virtual machine in CERN's Openstack cloud

1) echo "service autofs restart" | sudo tee -a /etc/rc.d/rc.local > /dev/null
