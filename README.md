# RSA_Encryption
1)Choose two prime numbers p and q.

2)Calculate n = p*q

3)Calculate  ϕ(n) = (p – 1) * (q – 1)

4)Choose e such that gcd(e , ϕ(n) ) = 1

5)Calculate d such that e*d mod ϕ(n) = 1

6)Public Key {e,n} Private Key {d,n}

7)Cipher text C = Pe mod n  where P = plaintext

8)For Decryption D = Dd mod n where D will give back the plaintext.
