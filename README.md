[<-- BACK](https://github.com/bkieselEducational/OAuth-1.0a-from-Scratch/)

# OAuth 1.0 Parameters

### oauth_callback:
- A callback URL to which the OAuth provider redirects the resource owner after successful authorization.
### oauth_callback_confirmed:
- A flag indicating whether the callback URL provided by the client has been confirmed by the server. This is typically set to "true" in OAuth 1.0a.
### oauth_consumer_key:
- The consumer key provided by the OAuth provider to identify the consumer (client application).
### oauth_nonce:
-  A unique nonce (number used once) value to prevent replay attacks. It should be unique for each request.
### oauth_problem:
- An optional parameter used in error responses to convey additional information about the error.
### oauth_signature:
- The signature generated for the request using the specified signature method. (Probably SHA1-HMAC)
### oauth_signature_method:
- The signature method used to sign the request, such as HMAC-SHA1.
### oauth_token:
- The access token obtained from the OAuth provider after successful authentication by the resource owner (user).
### oauth_token_secret:
- The secret token associated with the access token. This is used in generating the signature.
### oauth_verifier:
- A verifier token obtained from the OAuth provider after the resource owner grants authorization.
### oauth_version:
- The version of the OAuth protocol being used. For OAuth 1.0a, this is usually "1.0".
