## In-Touch Programming Challenge #3 - Cryptography

Write a PHP program to decode the given ciphertext, provide the output cleartext and the hexadecimal representation of the key that was used to encrypt.

The details you'll need are as follows:

* Cipher is `AES-256-CBC`
* Only the first 3 bytes of the key are used - the rest are 0's
	* i.e. `[?,?,?,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0]`
* The first byte of the key is `0xBA`
* The decrypted text is a plain ASCII string in English

### Initialization Vector

	wfQWvRpD/bjkdLBQVCFyGg==

### Ciphertext

	U45PXdltSdze1oC9OhxWtYybClZeNLd/MZ1LsC+CRTc=
