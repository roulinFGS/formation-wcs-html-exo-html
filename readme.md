
# Testing using :
https://www.npmjs.com/package/http-server

# to install
```
 npm install --global http-server
```

# To generate new cert
```
openssl req -newkey rsa:2048 -new -nodes -x509 -days 3650 -keyout key.pem -out cert.pem
```

# To launch
```
http-server -S -C cert.pem
```

# Remark
Example only. No certificate should be stored in git :)
