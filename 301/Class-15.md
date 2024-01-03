# Read: Class 15

These concepts are vital for securing access, protecting user identities, and enabling safe interactions between applications. Understanding these flows is key to building secure systems and ensuring data protection in the digital environment.

[What is OAuth](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)

1. What is OAuth?

OAuth is an open standard for secure authorization, allowing users to grant third-party applications limited access to their resources without sharing their credentials. It uses tokens instead of passwords, and OAuth 2.0 is the widely adopted version. It's commonly used in API access scenarios on the web.

2. Give an example of what using OAuth would look like.
Chatgpt

Alice wants AppXYZ to access her Google Drive. Instead of sharing her Google credentials, she uses OAuth. Google grants AppXYZ a limited access token. AppXYZ uses the token to access Alice's Google Drive on her behalf, ensuring security without revealing her password.

3. How does OAuth work? What are the steps that it takes to authenticate the user?

* Client Registration:
The client registers with the authorization server.
* User Authorization:
The user grants permission to the client.
* Authorization Grant:
The authorization server issues a grant to the client.
* Access Token Request:
The client requests an access token.
* Access Token Issuance:
The authorization server validates and issues the access token.
* Resource Access:
The client uses the access token to access the user's resources on the resource server.

4. What is OpenID?

OpenID is an authentication protocol that lets users use a single digital identity (OpenID) to log in to multiple websites. It involves a user, an OpenID Provider (OP) that manages user identity, and a Relying Party (RP) that wants to authenticate the user. The process allows for single sign-on across various services without needing separate credentials for each site. OpenID Connect (OIDC) is a modern extension of OpenID, often used with OAuth 2.0 for authentication and authorization.


[Authorization and Authentication flows](https://auth0.com/docs/flows)


1. What is the difference between authorization and authentication?

Authentication is the process of confirming an entity's identity, often through passwords or biometrics. Authorization, on the other hand, determines the actions or resources an authenticated entity is allowed to access. Authentication verifies "who you are," while authorization specifies "what you can do" based on that identity.

2. What is Authorization Code Flow?

Authorization Code Flow is an OAuth 2.0 mechanism where a client redirects a user to the authorization server. After user consent, the server returns an authorization code to the client. The client exchanges this code for an access token, allowing secure access to resources on behalf of the user. It's suitable for server-side applications.

3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

The Authorization Code Flow with Proof Key for Code Exchange (PKCE) is an OAuth 2.0 extension, enhancing security for public clients like mobile apps. It introduces a code verifier and challenge, ensuring even if the authorization code is intercepted, it can't be misused. PKCE is used to securely obtain access tokens in scenarios where storing a client secret is challenging.

4. What is Implicit Flow with Form Post?

The Implicit Flow with Form Post is an OAuth 2.0 flow for browser-based applications. It retrieves tokens directly, especially for Single Page Applications. Unlike the traditional Implicit Flow, it uses a form post to enhance security and reduce exposure of tokens in the browser history.

5. What is Client Credentials Flow?


The Client Credentials Flow is an OAuth 2.0 flow where a client application directly authenticates with the authorization server using its credentials (client ID and secret). It obtains an access token to access protected resources on its own behalf, commonly used in server-to-server communication scenarios.

6. What is Device Authorization Flow?

The Device Authorization Flow is an OAuth 2.0 flow for devices with limited input capabilities. The device obtains a user code and instructs the user to authorize on a secondary device. After user authorization, the device exchanges the code for an access token to access resources.

7. What is Resource Owner Password Flow?

The Resource Owner Password Credentials (ROPC) or Resource Owner Password Flow is an OAuth 2.0 flow where a user provides their username and password directly to the client application. The client uses these credentials to obtain an access token from the authorization server, but it's considered less secure and not recommended in modern OAuth implementations.

[Auth0 for single page apps](https://auth0.com/docs/libraries/auth0-react)