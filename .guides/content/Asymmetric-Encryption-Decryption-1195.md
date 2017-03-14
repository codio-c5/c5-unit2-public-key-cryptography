- If Alice wants to send Bob a confidential message, she gets **Bob’s** public key.
- She encrypts her message to Bob using **Bob’s** public key and sends it to Bob (possibly over the Internet).
- Bob, upon receipt of the encrypted message from Alice, uses **his** private key to decrypt the message.
- Because only Bob knows his private key, only he can decrypt the message and read it!

![](.guides/img/asymmetric.png)
Note that no communication is necessary beforehand to agree on a shared secret key.

|||guidance
- Sender = Alice
- Recipient = Bob
Contrast this with the Symmetric Key diagram.
|||