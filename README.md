# Reference
Creates ssh and sudo HBACs in a FreeIPA environment for a set of servers/users.

# Variables
Lists are space separated
```
auth_realm # e.g. CHADG.NET
ldap_server # e.g. ldap.chadg.net
kinit_user # e.g. someuser
kinit_password # e.g. somecomplexpassword
client_servers # e.g. 'client1.chadg.net client2.chadg.net'
ssh_users # e.g. 'chad foo bar'
sudo_users # e.g. 'chad foo'
target # an inventoried host able to reach the ldap server
```
