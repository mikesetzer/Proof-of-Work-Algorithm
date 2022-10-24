# Proof-of-Work
A sha-256 brute force tester to find leading zeroes

- Update NONCE with the starting nonce
- Update data with the data string to append nonce to
- Update newHash[:x] == '': with x as the number of leading bits to check, and '' with the string to search for in leading bits.
