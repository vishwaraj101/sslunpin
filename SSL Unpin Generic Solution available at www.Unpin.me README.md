# sslunpin
Frida script to bypass ssl Pinning

### Dependencies
Frida,Python 2.7.10

### Note:

1.)Make sure to rename burp ca-certificate.cer to cert-der.crt 
Then hit ```adb push ca-certificate.cer /data/local/tmp/cert-der.crt``` to push it in /data/local/tmp from there this script will load the certificate .

### To execute:

```
python unpin.py
pkg_to_hook>>>com.exploit
```
### References :
https://techblog.mediaservice.net/2017/07/universal-android-ssl-pinning-bypass-with-frida/

