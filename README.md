# Iptables profiles and templates

This is a repo of iptables rules files
Iptables-new blocks all in comming including local ports 
iptables-lo has local ports opened 
# How to import
you can use the script to import or do it yourself with the following command  
* <code> sudo Iptables-restore iptables-new </code> & <code> ip6tables-restore /path/to/the/profile/ </code>
* past them to <code>/etc/ </code>diractory and run smip script
