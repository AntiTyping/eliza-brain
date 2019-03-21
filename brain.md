# iOS
### Convert p12 certificate to pem

     openssl pkcs12 -nodes -clcerts -in certificate.p12 -out certificate.pem
