# JWT

To help prepare for API authentication tomorrow, research [JSON Web Tokens](https://jwt.io) (known as JWTs). This should take about 30 minutes. Answer the following questions and submit this README as your homework:

1. What are the 3 parts of a JWT?
    Header, Payload, Signature.

2. What information does each part contain?

        Header conisists fo the type of token and hashing algorithm being used. 

        Payload contains the claims : statements about an entity and additional metadata. claim types: reserved, public, private

        Signature uses encoded header, encoded payload, secret, algorithm specified in header and sign it.


3. Why do people use JWTs for authentication? A great resource to read would be https://jwt.io/introduction/.
    
        It allows the user to access routes, services and resources that are permitted with that token.
