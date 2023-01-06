This code go to the Shodan and display the hosts that are available on the IP address, the open ports and all the CVEs to the vulnerabilities that are on those ips. 

Non-vulnerable hosts are named with their IP address and saved to a text document in the format <IP>.txt and vulnerable hosts in the format <IP>_vulnerable.txt to make it easier to track vulnerable and non-vulnerable hosts.

# Shodan_CVE 2.0

Create a file called hosts.txt and add IPs to it, each IP on a new line.

python ShodanCVE2.0.py

# Shodan_CVE 3.0

python ShodanCVE3.0.py --hosts/-i hosts.txt
