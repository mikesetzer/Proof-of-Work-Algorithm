# Proof-of-Work
A sha-256 brute force tester to find leading zeroes

- Update NONCE with the starting nonce
- Update data with the data string to append nonce to
- Update newHash[:x] == 's': with x as the number of leading bits to check, and 's' with the string to search for in leading bits.

Outputs to console as well as an output.txt file on completion.

Sample output:
>New Hash is: 		00713533279182b081042181999d90873188ecbd83dd9755caeb3a8c4fe1cee5
>
>NONCE is: 		163
>
>Duration: 		0.0007550716400146484
>
>Final Pre-image: 	Michael163
