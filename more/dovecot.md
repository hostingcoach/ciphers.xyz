# Dovecot
```
ssl = yes
ssl_cert = &lt;/etc/dovecot.cert
ssl_key = &lt;/etc/dovecot.key
ssl_protocols = !SSLv2 !SSLv3
ssl_cipher_list = AES128+EECDH:AES128+EDH
ssl_prefer_server_ciphers = yes # >Dovecot 2.2.6
ssl_dh_parameters_length = 4096 # >Dovecot 2.2
```
