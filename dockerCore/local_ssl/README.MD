run the following comand to generate keys 

```
openssl req -x509 -nodes -days 1024 -newkey rsa:2048 -keyout dev.local.key -out dev.local.crt -config open_ssl.conf -extensions 'v3_req'
```