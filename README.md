# ansible-custom-nameservers

This role adds a custom DHCP enter hook. 

```
- role: ansible-custom-nameservers
  sudo: yes
  custom_name_servers: "10.181.0.2"
```
