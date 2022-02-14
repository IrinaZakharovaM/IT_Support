# Cryptography Applications

## Question 1

*What information does a digital certificate contain? Check all that apply.*

* Private key data
* **Public key data**
* **Identifying information of the certificate owner**
* **Digital signature**

> A digital certificate contains the public key information, along with a digital signature from a CA. It also includes information about the certificate, like the entity that the certificate was issued to.

## Question 2

*Which type of encryption does SSL/TLS use?*

* Asymmetric encryption
* **Both**
* Symmetric encryption
* Neither

> SSL/TLS use asymmetric algorithms to securely exchange information used to derive a symmetric encryption key.

## Question 3

*What are some of the functions that a Trusted Platform Module can perform? Check all that apply.*

* Secure user authentication
* **Data binding and sealing**
* **Remote attestation**
* Malware detection

> A TPM can be used for remote attestation, ensuring that a host is a known good state and hasn't been modified or tampered (from a hardware and a software perspective). TPMs can also seal and bind data to them, encrypting data against the TPM. This also allows it to be decrypted by the TPM, only if the machine is in a good and trusted state.