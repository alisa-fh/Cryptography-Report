# Cryptography Report

This cryptography report forms part of a summative assignment in my final year of my university. Read the report [here](./Cryptography.pdf).

The objective of this assignment was to decrypt a 16 byte long ciphertext that was encoded using data encryption standard (DES) encoding with the electronic code book (ECB) mode of operation. More precisely, the original plaintext consisted of three words separated by a dot, representing a 3m x 3m square area on Earth \textit{e.g. heavy.bravo.goals}. Further information included the 16 byte ciphertext in hexadecimal and the fact that the key was 8 bytes long. We are provided an \textit{.exe} file, acting as a black box oracle which takes in as input a hexadecimal string and returns an encrypted hexadecimal string. Unfortunately a Windows OS is inaccessible, and consequently it is not possible to implement the attack plan on the given oracle. Rather, the approach has been tested using self-made test cases, by means of the \textit{des} python library. This report details an analysis of the problem, a proposed solution and finally an analysis of the approach.
	
