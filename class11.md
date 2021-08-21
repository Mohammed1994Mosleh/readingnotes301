# Readings for Class10 : What is OAuth

## What is OAuth

![OAUTH](https://d33wubrfki0l68.cloudfront.net/99bea281c4d8758b97fe07ded0136019b0ed75f6/3da15/assets-jekyll/blog/oauth/oauth-actors-cd8b4861e839037400d8521e97c5d8cf0cb029add65d1036488991c7e85dcb72.png)
1. OAuth allows websites and services to share assets among users. It is widely accepted, but be aware of its vulnerabilities.
2. The simplest example of OAuth is when you go to log onto a website and it offers one or more opportunities to log on using another website’s/service’s logon. You then click on the button linked to the other website, the other website authenticates you, and the website you were originally connecting to logs you on itself afterward using permission gained from the second website.

3. * The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.

* The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.
* he first site gives this token and secret to the initiating user’s client software.
* The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).
* he client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).
* f not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.
* The user approves (or their software silently approves) a particular transaction type at the first website

* The user is given an approved access token (notice it’s no longer a request token).
    
* he user gives the approved access token to the first website.

* he first website gives the access token to the second website as proof of authentication on behalf of the user.

    *The second website lets the first website access their site on behalf of the user.

* OAuth is not the first authentication/authorization system to work this way on behalf of the end-user. In fact, many authentication systems, notably Kerberos, work similarly. What is special about OAuth is its ability to work across the web and its wide adoption. It succeeded with adoption rates where previous attempts failed (for various reasons).

## Authorization and Authentication flows

![Authorization and Authentication flows](https://miro.medium.com/max/1080/1*quwFs1fFCvTvLT80e_QHVA.png)

1. Auth0 uses the OpenID Connect (OIDC) Protocol and OAuth 2.0 Authorization Framework to authenticate users and get their authorization to access protected resources. 

2. Authorization code flow is used to obtain an access token to authorize API requests.

3. To mitigate these, OAuth 2.0 provides a version of the Authorization Code Flow which makes use of a Proof Key for Code Exchange (PKCE).

4. offer a streamlined workflow if the application needs only an ID token to perform user authentication.

5. With machine-to-machine (M2M) applications, such as CLIs, daemons, or services running on your back-end, the system authenticates and authorizes the app rather than a user

6. device asks the user to go to a link on their computer or smartphone and authorize the device

7.  requests that users provide credentials (username and password), typically using an interactive form