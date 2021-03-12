## Adding-https-support

```bash
openssl req -newKey rsa:2048 -new -nodes -x509 -days 3650 -keyout key.pem -out cert.pem

openssl req -newkey rsa:2048 -nodes -keyout key.pem -x509 -days 365 -out certificate.pem
```
