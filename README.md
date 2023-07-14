# Data-Cryptography-and-Hash-Functions

A cipher or cryptosystem is used to encrypt plaintext or send secure message to a recipient. When we encrypt, we produce a ciphertext and when we decrypt, we recover the plaintext or original message we intended to send to the recipient. The essence of encrypting is to ensure confidentiality and integrity of the message. There are various ways of encrypting plaintext. We would be considering Hash functions and Symmetric Ciphers which will be used to encrypt and decrypt the word document - Security news report 1 (R11503611_data)


* For this project SHA-256 was used to encrypt - the security news report text

---
---

SHA-256 is a type of SHA2 secure hash algorithm is a family of crypto hash functions published by NIST as US standard. SHA2 is a successor of SHA1 due to collisions found in SHA1 crypto which makes it not suitable for situations where crypto security is required. SHA2 has 2 types 256 and 512 bit which varies in length of output. They are more secure and are good for crypto uses.
A link for the concise documentation is shown below. Also, SHA-2 in this link provides further refence 
https://pycryptodome.readthedocs.io/en/latest/src/hash/sha256.html
Its important to note that SHA-256 is vulnerable to length extension attacks, which is relevant if you are computing the hash of a secret message. 
