The Reverse Hash Application
============================

This web app uses a very simple brute force attack to 
"reverse" an MD5 hash.  But it is really not reversing the hash
at all as that would be impossible.  Instead it knows that 
the original pre hash text was a numerical character string with 
exactly four characters.

So the application uses four nested loops and tests all combinations of four numerical inputs, and computes the
hashes of those values and checks to see if the computed hash
matches.
