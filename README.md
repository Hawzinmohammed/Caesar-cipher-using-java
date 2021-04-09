# Caesar-cipher
Developed application also has some constraints:

1) You should submit source code of your file and also all files should be in github account

2) Input file should have following structure:

[Shift Count]:[Encrypt/De-crypt]:[Alphabet 0-4]:Plain text/Cipher Text

Shift Count: Number of shift should be given here as it described in first step.

Second field: 0->Encrypt,1->De-crypt

Third field: Alphabet Type 0 for English, 1 for French, 2 for Spanish, 3 for Turkish

Forth field: If second field Encrypt(0) forth part should have plain text  if  it is De-crypt(1) it should have cipher-text.
Example encrypt for english input file:

4:0:0:hello world    

Screen Output ->LIPPS ASVPH

Example for de-crypt input file

4:1:0:LIPPS ASVPH

Screen Output -> hello world

Example encrypt for Spanish input:

7:0:2:HOLLA