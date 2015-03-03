# saltstack-grains
Grains used in my saltstack formulas

Simply drop into the _grains folder in your file_roots base (By default, /srv/salt)

### externalip.py
Detects the external ipv4 address of salt minion and adds it as external_ip4.
Used in firewall configurations as the 'default' IP to allow access to.
