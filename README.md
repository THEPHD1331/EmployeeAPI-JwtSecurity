# EmployeeAPI with JWT Security 

JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object.
This information can be verified and trusted because it is digitally signed. JWTs can be signed using a secret (with the HMAC algorithm) or a public/private key pair using RSA or ECDSA.

Although JWTs can be encrypted to also provide secrecy between parties, we will focus on signed tokens. Signed tokens can verify the integrity of the claims contained within it, while encrypted tokens hide those claims from other parties. When tokens are signed using public/private key pairs, the signature also certifies that only the party holding the private key is the one that signed it.


# Unauthorized Prompt

![jwt1](https://github.com/THEPHD1331/EmployeeAPI-JwtSecurity/assets/126282296/db898f5a-d914-43c2-b451-cefabbdf25a5)


# Incorrect Username and Password

![jwt3](https://github.com/THEPHD1331/EmployeeAPI-JwtSecurity/assets/126282296/9bedb454-adca-4607-9ced-911e451bd4b1)


# Generated JSON Web Token for Authorized User

![jwt2](https://github.com/THEPHD1331/EmployeeAPI-JwtSecurity/assets/126282296/798bafe9-a230-466d-bc3b-cf38c5ee63b4)


# Access to resource by successful authentication

![jwt4](https://github.com/THEPHD1331/EmployeeAPI-JwtSecurity/assets/126282296/b8abaffd-4c22-44fc-96b5-6026e275236f)
