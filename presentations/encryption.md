# History of Crypthography & Encryption Nowadays

## 1. Zkb? (Why?)

- people have secrets
- to keep the secret for long enough
- war

## 2. Brief History of Crypthography

### 2.1. Ancient Era
- 600 BC - Scytale: proper size rod + leather strip
- 60 BC - Caesar substitution cypher: shift characters by 3 places

![Scytale](https://upload.wikimedia.org/wikipedia/commons/5/51/Skytale.png)

### 2.2. Medieval Era
- 1553 - Giovan Battista Bellaso: first cipher to use a proper encryption key
- 1854 - Playfair cipher: encrypts pairs of letters instead of single ones

### 2.3. World War I
- 1917 - Hebern rotor machine: electro-mechanical machine using key on a rotating disc
- 1918 - Arthur Scherbius - Enigma: Rather than the one rotor, it uses several.

### 2.4. World War II
- 1932 - Marian Rejewski: discovers how Enigma works.
- It's shared with French and British intelligence services
- Allowing crypthographers like Alan Turing to figure out how to crack and create Bombe Machine

![Bombe Machine](https://upload.wikimedia.org/wikipedia/commons/7/7a/Wartime_picture_of_a_Bletchley_Park_Bombe.jpg)

### 2.5. Modern Crypthography
- 1945 - Claude E. Shannon: published "A mathematical theory of cryptography"
- 1970s: IBM's crypto group designs a block cipher - DES (Data Encryption Standard). First publicly accessible cipher
- 1976 - Whitfield Diffie and Martin Hellman: defines Diffie-Hellman key exchange - definition of public and private keys
- 1977 - RSA - asymmetric cipher
- 1990s - DSA (Digital Signature Algorithm): RSA alternative
- 1991 - PGP (Pretty Good Privacy): hashing, data-compression, symmetric cipher, public key cryptography
- 1997 - DES is cracked
- 2000 - AES (Advanced Encryption Standard) replaces DES. It was the winner of a public cipher competition.

## 3. Encryption

### 3.1. Concepts
- symmetric: using the same key on both sides
- asymmetric: using public key for encryption and private for decryption
- block cipher: fixed lenghth group (128-bit, etc.) encryption. symmetric key is required
- stream cipher: input + pseudorandom cipher digit keystream
- asymmetric cipher is slow, symmetric cipher is fast
- hashing: one way functions

### 3.2. Usage

#### 3.2.1. SSH/SFTP/SCP
- asymmetric encryption is used to authenticate and share each public keys
- server and client use their own private key, public key and the shared public key to generate symmetric key
- symmetric encryption is used to communicate with the newly generated symmetric key
- hashing is used to provide data integrity

#### 3.2.2. SSL/TLS
- asymmetric encryption is used to establish secure connection
- symmetric encryption is used to exchange data

### 3.3. Attacks
- hardware, software & human capabilities
- success in time (Enigma 1 day rotation)
- cryptanalysis
- brute-force & dictionary attack

## 4. Resources
- [Online crypting tool](https://cryptii.com/)
