mirango_nginx
=============

Nginx configuration file for mirango.io.  Write up here: https://www.mirango.io/configure-nginx-for-HTTPS/

Creates a 301 permanent redirect to https://www.mirango.io (forces users to connect to the encrypted site).  Order is important!

Configuration includes HTTP Strict Transportation Security settings, OCSP Stapling, Public Key Pinning Extension for HTTP (HPKP) and uses secure ciphers as recommended by Mozilla.

![alt-tag](https://cloud.githubusercontent.com/assets/6863681/8169078/2fe6ba38-1375-11e5-886d-3d81c5bd0314.png)
