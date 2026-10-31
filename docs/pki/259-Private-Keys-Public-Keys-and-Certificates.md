# Private Keys, Public Keys, and Certificates

*PKI / General Information · January 24, 2024*

When you work with a PKI system, you often encounter three terms: **private key**, **public key**, and **certificate**. They are fundamental to digital signatures. Here is a simple explanation.

In short:

- The **private key** creates a digital signature.
- The **public key** verifies that signature.
- A **certificate** vouches for the identity associated with a public key.

For an introduction to digital signatures and certificates, see [A Story About Digital Signatures and Certificates](../136/136-A-Story-About-Digital-Signatures-and-Certificates.md).

![Illustration comparing a digital signature and a certificate](../images/sign_cert.png)

## What is a private key?

A private key is used to create a digital signature. It must remain under the control of its owner and must not be shared with other people. Protecting the private key is one of the central security requirements of a PKI system.

Private keys are therefore often stored in encrypted form or protected by a more secure device, such as a **Hardware Security Module (HSM)**.

## What is a public key?

A public key is used to verify a digital signature. The person who holds the private key creates the signature; anyone who needs to check the signed content can use the corresponding public key to verify it.

Signature verification normally uses both the signature and the original data. A digital signature by itself does not provide confidentiality. It lets a verifier check that the signed data has not changed and that the signature was made by someone with the corresponding private key.

As its name suggests, a public key is intended to be shared so others can verify signatures. Unlike a private key, it generally does not need to be kept secret.

## What is a certificate?

Anyone can generate a public and private key pair. That means anyone can create signatures and anyone can verify a signature if they have the corresponding public key. The remaining question is: **whose public key is it?**

A certificate helps answer that question. A **Certificate Authority (CA)** issues a certificate that binds a subject’s identity to a public key. The CA signs the certificate data with its private key. A verifier can use the CA’s public key to check that signature and determine whether the certificate was signed by that CA and whether its contents have been altered.

A CA typically issues certificates and makes them available through a public repository or other distribution service. Because a certificate contains the public key, people can obtain the key from the certificate and use it to verify signatures.

## In summary

The basic idea of signature verification in a PKI system is straightforward: the private key signs, and the public key verifies. Validating a certificate involves more steps. A verifier may need to build and validate a certificate path through intermediate CAs up to a trusted root, and check that the certificates are valid for the intended use. This process is called **path validation**.

Understanding these basic terms is a useful first step toward understanding the more complex parts of PKI.

**Tags:** certificates · public keys · private keys
