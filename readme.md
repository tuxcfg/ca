Certificate Authority
=====================

Place `cert.pem` to `/usr/share/ca-certificates/` and change extension to `.crt`. 
Then install in the system:

```bash
dpkg-reconfigure ca-certificates
```

Useful links:

* [OpenSSL Certificate Authority](https://jamielinux.com/docs/openssl-certificate-authority/)
