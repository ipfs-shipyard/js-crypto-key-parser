> An encrypted PKCS8-DER key using PBES2+PKDF2+desCBC (2048 bits)

```sh
openssl genrsa 2048 | openssl pkcs8 -topk8 -outform DER -out key -v2 des -passout pass:password
```
