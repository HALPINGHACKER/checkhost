# checkhost
This Tool will ping each IP address in the specified range and report back which ones are up. Please note that not all hosts may respond to ICMP echo requests (ping), so the results might not be definitive for all cases.
Save this script to a file, such as check_hosts.sh, and make it executable with chmod +x check_hosts.sh.

To use the script, provide the starting and ending IP addresses as arguments. For example:./check_hosts.sh 192.168.1.1 192.168.1.10

