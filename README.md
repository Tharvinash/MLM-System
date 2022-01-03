# MLM-System

Design and develope a program to implement a multi-level marketing system.

Encryption & Decryption

1.Every user will need to have an encrypted_name to protect their identity.

2. Only the company has the KEY to decrypt the encrypted_name to real_name.

   a. encrypt(NAME, KEY) → ENCRYPTED_NAME

   b. decrypt(ENCRYPTED_NAME, KEY) → NAME

3. When signing up the new user, you must only save the encrypted name.

4.Every time you want to see the user original NAME, you should type in the KEY.
