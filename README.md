Step by step manual for Ubuntu 18.04:

- clone repository
```
git clone https://github.com/vareger/l2tp-client.git
```

- change directory
```
cd l2tp-client
```

- running bash
```
sudo ./connect_vpn.sh \
'your_vpn_server_ip_or_domain_name' \
'your_ipsec_pre_shared_key' \
'your_vpn_username' \
'your_vpn_password'
```