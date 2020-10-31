
# Access Control (ACL)

1. When is Basic Authorization used vs. Bearer Authorization?
- Basic auth confirms the users identity and Bearer confirms the Token granted to the user 

2. What does the JSON Web Token package do?
- It is the packaging that contains the information passed from the client to the API. this consists of the payload, secret, header etc.  

3. What considerations should we make when creating and storing a SECRET?
- That it needs to be stored in our .env and not open to the public

## Vocabulary Terms

1. encryption:  is the process of encoding information. This process converts the original representation of the information, known as plaintext, into an alternative form known as ciphertext. Ideally, only authorized parties can decipher a ciphertext back to plaintext and access the original information. Wikipedia

2. token:  is a piece of a two-factor authentication security device that may be used to authorize the use of computer services.

3. bearer: is a developer tool that helps engineering and DevOps teams monitor API consumption, track performances, detect anomalies, and fix issues for their critical API usage

4. secret: refers to the tools and methods for managing digital authentication credentials 

5. Json Web TokeN. is an Internet standard for creating data with optional signature and/or optional encryption whose payload holds JSON that asserts some number of claims.