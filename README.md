# internship-assignment

In cryptography, a cipher (or cypher) is an algorithm for performing encryption or decryption—a series of well-defined steps that can be followed as a procedure. An alternative, less common term is encipherment. To encipher or encode is to convert information into cipher or code. In common parlance, "cipher" is synonymous with "code", as they are both a set of steps that encrypt a message; however, the concepts are distinct in cryptography, especially classical cryptography.

Codes generally substitute different length strings of character in the output, while ciphers generally substitute the same number of characters as are input. There are exceptions and some cipher systems may use slightly more, or fewer, characters when output versus the number that were input.


Look at this encoded message	:	L ORYH BRX
When decoded, it looks this way	:	I LOVE YOU

Wondering how?
In the previous encoding we used an alphabet right shift of 3.
It means every alphabet will be considered with third corresponding alphabet when encoded. Finally we will have,

Shift value: 3
Actual	   : A  B  C  D  E  F  G ...... U  V  W  X  Y  Z
Encoded    : C  D  E  F  G  H  I ......	X  Y  Z  A  B  C
