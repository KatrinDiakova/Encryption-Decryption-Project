# Encryption-Decryption-Project

Description

1. The program starts by parsing the command line arguments and storing the values in variables. The variables include the action (encode or decode), the key, the text, the input file, the output file, and the algorithm.
2. If an input file is provided, the program reads the contents of the file and stores it in the text variable.
3. The program then creates an encoder object using the EncoderFactory class, which will be used to encode or decode the text. The encoder object is created based on the value of the algorithm variable.
4. The program then checks the value of the action variable to determine whether to encode or decode the text. If the action is "enc", the program calls the encode method on the encoder object with the text and key as arguments. If the action is "dec", the program calls the decode method on the encoder object with the text and key as arguments. The encode and decode methods are implemented differently in the ShiftEncoder and UnicodeEncoder classes.
5. If an output file is provided, the program writes the result to the file. If no output file is provided, the program prints the result to the console.
