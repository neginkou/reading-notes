# Cryptography

Understanding encryption and decryption is crucial for digital security and privacy. They form the foundation of secure communication, data protection, and safeguarding sensitive information in today's interconnected world. Mastery of these concepts is essential to protect data from unauthorized access, ensuring confidentiality and integrity in the digital age.

[Encryption, Decryption & Hacking](https://www.khanacademy.org/computing/computers-and-internet/xcae6f4a7ff015e7d:online-data-security/xcae6f4a7ff015e7d:data-encryption-techniques/a/encryption-decryption-and-code-cracking)

[Ceasar Cipher](https://en.wikipedia.org/wiki/Caesar_cipher)

[Cryptography Crash Course](https://www.youtube.com/watch?v=jhXCTbFnK8o)

[Introduction to Cryptography](https://thebestvpn.com/cryptography/)

[How Computers Generate Random Numbers](https://www.howtogeek.com/183051/htg-explains-how-computers-generate-random-numbers/)


1. What is the basic principle behind the Caesar Cipher, and how was it used historically?

The Caesar Cipher is a simple encryption technique that involves shifting each letter in a message by a fixed amount. Historically, it was used by Julius Caesar to secure his messages. However, it's not very secure, as there are only 25 possible keys, making it vulnerable to decryption. Today, it's mainly used for educational purposes and as a basic example of encryption.

2. What are the key differences between symmetric and asymmetric encryption? How is asymmetric used in secure communication today?

Symmetric encryption uses a single shared key for both encryption and decryption, while asymmetric encryption uses a pair of public and private keys. Asymmetric encryption is primarily used for secure key exchange, digital signatures, and securing communication over untrusted networks, like the internet. It addresses key distribution and security challenges, while symmetric encryption is used for efficient data encryption once secure key exchange is established.

3. How do computers generate random numbers, and what are the differences between true random number generation (TRNG) and pseudo-random number generation (PRNG)? Discuss their use cases in cryptography.

Computers generate random numbers using true random number generation (TRNG) and pseudo-random number generation (PRNG).

* PRNG is deterministic and follows a predictable pattern, suitable for non-critical applications like simulations and games. In cryptography, it's used for non-secret data but not for critical cryptographic secrets.

* TRNG relies on unpredictable physical processes, making it truly random and highly secure. It's essential for generating cryptographic keys and enhancing security in critical cryptographic applications like secure communications.

4. What’s the difference between encryption and decryption? Explain with an analogy. 

Encryption is like locking a letter in a box, turning it into unreadable ciphertext. Decryption is using the key to unlock the box and reveal the original message. Encryption protects data, and decryption restores it.