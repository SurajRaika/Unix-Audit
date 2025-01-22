# Unix-Audit

### **Firewall and Networking**

-   **Disabled Firewall**: A disabled firewall means no network filtering.\
    *Command*: `ufw status` or `iptables -L`\
    **Example**:

    makefile

    CopyEdit

    `Status: inactive`

    -   No active firewall = high risk of unauthorized access.



sudo grep "authentication failure" /var/log/auth.log
for getting any failed aattempt 
and 
 sudo tail -f /var/log/auth.log
 to get any real time info  
 
sudo zgrep "authentication failure" /var/log/auth.log.*.gz
 for to get older 
