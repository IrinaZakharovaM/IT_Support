# OpenSSL: You'll explore what generating key pairs looks like using OpenSSL.
# Encrypt and decrypt: You'll use the key pair to encrypt and decrypt some small amount of data.
# Verify: You'll use the key pair to sign and verify data to ensure its accuracy.

## generate a 2048-bit RSA private key and take a look
```bash
openssl genrsa -out private_key.pem 2048
cat private_key.pem
```

## generate public key and take a look
```bash
openssl rsa -in private_key.pem -outform PEM -pubout -out public_key.pem
cat public_key.pem
```

## creating a text file
```bash
echo 'This is a secret message, for authorized parties only' > secret.txt
```

## encrpyt the file using public key
```bash
openssl rsautl -encrypt -pubin -inkey public_key.pem -in secret.txt -out secret.enc
```

## decrpyt the message using private key
```bash
openssl rsautl -decrypt -inkey private_key.pem -in secret.enc
```

## create hash digest
```bash
openssl dgst -sha256 -sign private_key.pem -out secret.txt.sha256 secret.txt
```

## verificate
```bash
openssl dgst -sha256 -verify public_key.pem -signature secret.txt.sha256 secret.txt
```