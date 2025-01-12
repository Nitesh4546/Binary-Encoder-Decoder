# Binary Encoder & Binary Decoder
In this repository I have created two functions:- 
1. Encoder:- The encoder function takes a string as input and converts each character in the string to its corresponding 8-bit binary representation. It constructs a custom dictionary where each printable character (letters, digits, punctuation, and spaces) is mapped to a unique 8-bit binary code. For each character in the input string, the function appends the binary equivalent to the output, effectively transforming the entire string into a long sequence of binary digits. If no text is provided, the function returns a prompt to enter the text. The function ensures that the output consists only of binary codes, which can be used for encryption or further data processing.
2. Decoder:- The decoder function reverses the process performed by the encoder. It takes a binary string as input and converts it back into the original human-readable text. The binary string is divided into chunks of 8 bits, and each chunk is matched to its corresponding character using a reverse dictionary. This dictionary maps 8-bit binary codes back to the characters they represent. If the input binary string is missing or empty, the function prompts the user to enter the text. The decoding process restores the original string, enabling the transmission or storage of the information in an encrypted binary form and decoding it back to its readable form.

# Used Libaray 
* String
