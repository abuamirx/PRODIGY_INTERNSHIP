Encrypt the message "Hello, World!" with a key of 5:

python
Copy code
python caesar_cipher.py --encrypt "Hello, World!" --key 5
Output: "Mjqqt, Btwqi!"

Decrypt the encrypted message "Mjqqt, Btwqi!" with the same key (5):

python
Copy code
python caesar_cipher.py --decrypt "Mjqqt, Btwqi!" --key 5
Output: "Hello, World!"

How It Works
The script takes input from the command line and processes the plaintext or ciphertext based on the specified operation (--encrypt or --decrypt).
Each letter in the input string is shifted by the key value in the alphabet.
Non-alphabet characters are unchanged in both encryption and decryption.
Requirements
Python 3.x
No additional libraries or modules are required beyond the Python standard library.
