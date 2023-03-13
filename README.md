# S Ample Tori

This is an implementation of the algorithms derived in my masters thesis
"Calculation of S-ample Tori in special unitary groups" and exists mainly as reference.

Code was tested on Magma V2.27-5
Feel free to change parameters in random_search_single() to look at specific etale algebras or involutions.

Feel free to report any bugs.

# Known Issues:
- very slow when the fixed fields are of degree 3 and higher
- MAGMA sometimes segfaults; I could not determine the root cause
