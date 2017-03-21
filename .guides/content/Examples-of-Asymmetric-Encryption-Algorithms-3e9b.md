## RSA Encryption
- Developed by Rivest, Shamir, Adleman (scientists at Berkley) in 1976
- Included in the cipher suite for key agreement/exchangein TLS/SSL (Transport Layer Security/Secure Socket Layer)
## Elliptic Curve Encryption
- Suggested independently by N. Koblitz and V. Miller in 1985
- Included in the cipher suite for key agreement / exchange in TLS/SSL (https://en.wikipedia.org/wiki/Cipher_suite)
	- Also included in Bluetooth Low Energy (LE) protocols

|||guidance
These algorithms are used to encrypt the values (possibly keys) that need to be shared between two users who want to communicate privately over a public channel. The parties do not encrypt/decrypt all messages using these algorithms (that would be too expensive time-wise), but just some secret values that are used to set up keys or are themselves secret keys.
|||