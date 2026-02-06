# JSON Web Token (JWT)
Open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object.

Digital signed with:
- secret (HMAC); **OR**
- public/private key pair (RSA or ECDSA)

## When to use?
**Authorization**:
- User log in -> backend return a JWT -> user access information permitted by the JWT.

**Information Exchange:**
- Signed JWT -> ensure sender/content is correct

## Structure
JSON Web Token consist of three parts separated by dots (.):
- Header
- Payload
- Signature

### Header
- consist of two parts:
  - Type of token
  - Signing algorithm

  ```
  {
  "alg": "HS256",
  "typ": "JWT"
  }
  ```

### Payload
- contains the claims (Statement about an entity & additional data)
- Three types of claims:
  - Registered
  - Public
  - Private 

### Signature
- encoded header + encoded payload + secret + algorithm specified in the header

## Reference
1. [Introduction to JSON Web Tokens](https://www.jwt.io/introduction#what-is-json-web-token) 
2. [What Are JSON Web Tokens (JWT)?](https://www.freecodecamp.org/news/what-are-json-web-tokens-jwt/)