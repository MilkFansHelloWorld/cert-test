# Cert-test
## important feature: the certPool
Uses: self-signed certificates and JWT. 
It is a very important feature. At the start of the server, are generated a defined number of certificates. When you get a certificate, it won't generate one but give you one that is already generated and stocked in the server (so it won't take much time). 
## How to run
Run the serveur in the root directory, by typing: 
### npm start or node ./bin/www
