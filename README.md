# SlashMark_Task1
This repository provides a simple JAVA script to read lines from a text file, encrypt each line using cryptographic algorithms encryption, and write the encrypted lines to a new file.

Explanation:
Generate Key: The generate_key function uses the Scrypt key derivation function to generate a key from the password and salt.
Encrypt: The encrypt function uses AES encryption in CFB mode to encrypt each line.
Encrypt File Lines: The encrypt_file_lines function reads each line from the input file, encrypts it, and writes the encrypted lines to the output file. The salt and IV are written to the beginning of the output file for later decryption.
