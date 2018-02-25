# DNScheckBashScript
Simple Bash script to check the a list of hosts from the domain name system to retrieve the IP address for a chosen domain name.

To run first change the permissions on the script file by:

  $ chmod +rwx dns-check.sh

After this you can execute the script for a domain of your choice:

  $ ./dns-check.sh dns-names.txt google.com
  
Sample output from this is:

dns.google.com has address 216.58.198.78

www.google.com has address 209.85.203.104

www.google.com has address 209.85.203.99

www.google.com has address 209.85.203.105

www.google.com has address 209.85.203.147

www.google.com has address 209.85.203.103

www.google.com has address 209.85.203.106
