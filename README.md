# CIS Benchmark Configuration for PaloAlto Firewall using Ansible

Note:
CyberArk is implemented for Ansible Vault to make it secure.
If you do not care about security at all, fill free to remove it

Cyberark Codes:
- name: credential retrieval
- name: Set ansible_password to remote node

Update 15/9/2024
- ansible_username and ansible_password is not working, change it to 'username:' and 'password:' instead
- Added Verification script to test if your Palo Alto Firewall is Compliant

The ansible script will execute commands remotely to Palo Alto Firewall Machine.
It is recommended to use Burp Suite to see what kind of changes you are making and refer to what is within the script.
Having a form of understanding can help in modifying the codes according to your needs.

LinkedIn: https://www.linkedin.com/in/chua-shan-jing-61ab28239/
