# Authentication

## What Is OAuth? How The Open Authorization Framework Works
OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential.

Another common example OAuth scenario could be a user sending cloud-stored files to another user via email, when the cloud storage and email systems are otherwise unrelated other than supporting the OAuth framework.

For OAuth to work, the end-user's client software, the services involved and authentication provider must support the right version of OAuth.

Many people think that OAuth stands for open authentication, but it's more helpful to understand it by thinking about it as open AUTHorization.

OAuth essentially allows the user, via an authentication provider that they have previously successfully authenticated with, to give another website/service a limited access authentication token for authorization to additional resources.

OAuth vs. SAML. The Security Assertion Markup Language, or SAML, is another technology you'll hear talked about in the same breath as OAuth.

SAML describes a framework that allows one computer to perform both authentication and authorization on behalf of one or more other computers, unlike OAuth, which requires an additional layer like OpenID Connect to perform authentication.