# Reading: Authorization/Authentication

## What header(s) are used in authentication and authorization

> The WWW-Authenticate and Proxy-Authenticate response headers define the authentication method that should be used to gain access to a resource. They must specify which authentication scheme is used, so that the client that wishes to authorize knows how to provide the credentials

 ![](https://media.geeksforgeeks.org/wp-content/uploads/20200420142114/Authentication-header.png)

 ## What is safe to put into a JWT

 >  symmetric signing is the proof of who actually signed the key. When using asymmetric keys you’re sure that the JWT was signed by whoever is in possession of the private key. In case of symmetric signing, any party that has access to the secret can also sign the tokens.

## How are JWTs validated

> Check signature. The last segment of a JWT is the signature, which is used to verify that the token was signed by the sender and not altered in any way. The Signature is created using the Header and Payload segments, a signing algorithm, and a secret or public key (depending on the chosen signing algorithm).


![](https://solutionsanz.files.wordpress.com/2017/06/jwtsjwks_pubprivatejwt.png?w=640)