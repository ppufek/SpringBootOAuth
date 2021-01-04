# OpenID Connect Application

## using Okta to make an even simpler client app with fully functioning SSO and OAuth authentication

> Okta is a _SaaS (software-as-service)_ authentication and authorization provider. 

> They provide free accounts to developers, so they can develop OIDC apps with no fuss. 

### Head over to **developer.okta.com** and sign up for an account. After you’ve verified your email, log in and perform the following steps:
 
-    Go to Application > Add Application.
-    Select application type Web and click Next.
-    Give the app a name. I named mine “Spring Boot OAuth”.
-    Under Login redirect URIs change the value to http://localhost:8080/login/oauth2/code/okta. The rest of the default values will work.
-    Click Done.
 
###   Leave the page open and take note of the Client ID and Client Secret.

[Okta | The Identity Standard](https://developer.okta.com/blog/2019/03/12/oauth2-spring-security-guide)