### Hello and Welcome to my first project program using C++ 👋

This is an encryption and decryption program, and can use any typeable character on your keyboard, space, and basic puncuation. It uses an encryption formula (((m + k) - 64) % 91) + 32, in which m is the plaintext message and k is the key. The numbers being added or subtracted are just to keep parameters around the allowed characters. The decryption formula is very close to the encryption formula, in which it is (((e - 32) + 91 - (k-32)) % 91 + 32). The reason the 91 is in a weird spot is because for whatever reason C++ was just not computing it correcting when it was placed after the (k - 32). This is an object orented program, or it uses data rather than logical systems. It thrives on array and other data sets, widely considered to be "objects".

The program will take the ascii of each character in the plaintext message, and the ascii of each character in the key. The message and key values of each character are added together to get the new character. This is all that would have to be done but parameters must be set. So mod 91 is used to keep the characters on the keyboard so to speak. As for adding 32, its to account for any spaces used in the program. Decryption is the same formula execpt you subtract 91 and subtract 32 to get to the origional space of the character. Then you take the mod and add 32 again and you have your decrypted message. 

How to use this program:
1. You will be first greeted by the system asking you to type a 1 for encryption, and a 2 for decryption then hit enter. YOU MUST use 1 or 2 otherwise the program will not run
2. To run the encryption sequence, type 1 and press enter
3. Type in the message you wish to be encrypted then press enter
4. Type in your key (or other phrase to use in the encryption) and press enter. The system will display The orgional message, the key used, and the encrypted message. 
5. If you wish to decrypt your message, then rerun the program and type 2 instead of 1, then press enter
6. Type in the encrypted message and hit enter
7. Type in the key used for the encryption and press enter
8. The system will display The encrypted message, the key used, and the decrypted message. 
