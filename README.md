## Information-Security-Practicals

### 1. Implement the error correcting code.
### 2. Implement the error detecting code.
### 3. Implement caeser cipher substitution operation.
### 4. Implement monoalphabetic and polyalphabetic cipher substitution operation.
### 5. Implement playfair cipher substitution operation.
### 6. Implement hill cipher substitution operation.
### 7. Implement rail fence cipher transposition operation.
### 8. Implement row transposition cipher transposition operation.
### 9. Implement product cipher transposition operation.
### 10. Illustrate the Ciphertext only and Known Plaintext attacks.
### 11. Implement a stream cipher technique


#### ANSWER-10 
####

Ciphertext-only and known-plaintext attacks are two types of attacks that can be used to break cryptographic systems. 

1. Ciphertext-only attack: In a ciphertext-only attack, the attacker has access only to the encrypted ciphertext but not to the corresponding plaintext or the encryption key. The goal of the attacker is to determine the plaintext or the encryption key. 

For example, if an attacker intercepts an encrypted message that was sent over the internet, they will have access to the ciphertext but not the plaintext. The attacker's goal in this scenario is to determine the plaintext of the message or the encryption key used to encrypt it. 

Ciphertext-only attacks are often difficult to execute because the attacker has no knowledge of the underlying plaintext or the encryption key. One way to execute a ciphertext-only attack is through a brute force method, where the attacker tries every possible encryption key until the correct one is found.

2. Known-plaintext attack: In a known-plaintext attack, the attacker has access to both the plaintext and its corresponding ciphertext. The goal of the attacker is to determine the encryption key used to encrypt the plaintext. 

For example, if an attacker intercepts an encrypted message along with its original plaintext, they can use this knowledge to determine the encryption key used to encrypt the plaintext. 

Known-plaintext attacks are often easier to execute than ciphertext-only attacks because the attacker has knowledge of both the plaintext and the corresponding ciphertext. One common technique for executing a known-plaintext attack is through frequency analysis, where the attacker analyzes the frequency of characters or patterns in the plaintext and uses this information to determine the encryption key. 

Both ciphertext-only and known-plaintext attacks are important to consider when designing and implementing cryptographic systems, as they can both be used to break the security of a system.
