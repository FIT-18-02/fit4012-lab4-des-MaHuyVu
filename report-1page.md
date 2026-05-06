# FIT4012 Lab 4 Report

## Objective

This lab implements DES and TripleDES encryption algorithms using C++.

## Approach

The program supports:
- DES encryption
- DES decryption
- TripleDES encryption
- TripleDES decryption
- Multi-block processing
- Zero padding

The DES implementation uses:
- Initial Permutation
- 16 Feistel rounds
- Expansion permutation
- S-Boxes
- Final Permutation

TripleDES is implemented using:

E(K3, D(K2, E(K1, P)))

and the reverse process for decryption.

## Result

The program was tested with:
- DES sample encryption
- Encrypt/decrypt round-trip
- Multi-block plaintext
- Wrong key negative test
- Tamper negative test

All major functions executed successfully.

## Conclusion

DES and TripleDES were implemented successfully in C++ for educational purposes.