## What is OAuth?
which stands for “Open Authorization,” allows third-party services to exchange your information without you having to give away your password.
## Give an example of what using OAuth would look like.
ne website saying “hey, do you want to log into our website with other website's login?
## How does OAuth work? What are the steps that it takes to authenticate the user?
Step 1 – The User Shows Intent.
Step 2 – The Consumer Gets Permission.
Step 3 – The User Is Redirected to the Service Provider.
Step 4 – The User Gives Permission.
Step 5 – The Consumer Obtains an Access Token.
## What is OpenID?
allows you to use an existing account to sign in to multiple websites, without needing to create new passwords.
## What is the difference between authorization and authentication?
Authentication confirms that users are who they say they are. Authorization gives those users permission to access a resource.
## What is Authorization Code Flow?
 used to obtain an access token to authorize API requests. ... Access tokens while having a limited lifetime, can be renewed with a refresh token. A refresh token is valid indefinitely and provides ability for your application to schedule tasks on behalf of a user without their interaction.
## What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
The Authorization Code Flow + PKCE is an OpenId Connect flow specifically designed to authenticate native or mobile application users. This flow is considered best practice when using Single Page Apps (SPA) or Mobile Apps. PKCE, pronounced “pixy” is an acronym for Proof Key for Code Exchange.
## What is Implicit Flow with Form Post?
Implicit Flow with Form Post flow uses OIDC to implement web sign-in that is very similar to the way SAML and WS-Federation operates. The web app requests and obtains tokens through the front channel, without the need for secrets or extra backend calls.
## What is Client Credentials Flow?
The Client Credentials flow is a server to server flow. There is no user authentication involved in the process. ... This flow is useful for systems that need to perform API operations when no user is present. It can be nightly operations, or other that involve contacting OAuth protected APIs.
## What is Device Authorization Flow?
The authorization flow defined by this specification, sometimes referred to as the "device flow", instructs the user to review the authorization request on a secondary device, such as a smartphone, which does have the requisite input and browser capabilities to complete the user interaction.
## What is Resource Owner Password Flow?
The Resource Owner Password Credentials flow allows exchanging the username and password of a user for an access token and, optionally, a refresh token.