# examdeveloper

1. They ask you the ***Authentication Types***

>Only one answer is related to Trusted Application.

2. ***Okta error codes and descriptions:*** Why an API returns Error [404, 429](https://developer.okta.com/docs/reference/error-codes/) ?

>400 Bad Request
>
>429 Too Many Requests

3. What API Return information about a token?

>/introspect

4. How is the language of the ***sign in widget*** configured?

>

5. In which situation to use ***SPA using PKCE?*** *They give you an example of a real case*

>

6. They ask you to mention an example of ***Identity Providers***

>OpenID
>
>SAML

7. They ask you to list the users of a specific group, you just have to choose the correct API but of the 4 proposals, 3 have {userId} in the path so these are not because they ask to list all.

> {{url}}/api/v1/groups/{{groupId}}/users

8. What are the possible values of the ***Content-Type header***?

>Application/json

9. What does the /api/v1/sessions API return?

>[Sessions API](https://developer.okta.com/docs/reference/api/sessions/)

10. They give you the following case: They are going to update a user's profile but the method is sent by ***PUT*** and a field is not specified, so they ask: *What value the field will have?*

>NULL, because as the PUT command you must send the value of all the fields

11. What is the default ID of an ***Authorization server***?

>default

12. They ask something about the API: ***https://${yourOktaDomain}/oauth2/${authorizationServerId}/.well-known/openid-configuration*** :

>Return OpenID Connect metadata related to the specified authorization server.

13. They give you several [APIS](https://developer.okta.com/docs/reference/api/oidc/#:~:text=opens%20new%20window) so that you can choose the existing ones:

>/authorize
>
>/instrospect

14. How can you verify the ***token signature***?

>JWT Json web token

15. There are several questions about the ***interaction Code flow***, it would be good to remember the following. image:

>[image](https://developer.okta.com/docs/concepts/oauth-openid/#interaction-code-flow)

16. Pagination:

>[pagination](https://developer.okta.com/docs/reference/core-okta-api/#pagination)

17. About the ***Rame limits***, they ask about *End-User rate limits*:

>[End-User rate limits](https://developer.okta.com/docs/reference/rl-additional-limits/#end-user-rate-limits)

18. They ask you to choose an API, you must list the *groups assigned to a specific application*:

>/api/v1/apps/${applicationId}/groups

19. What are the ***Schemas APIs*** used for?

>[Schemas API](https://developer.okta.com/docs/reference/api/schemas/)

20. What web browsers support ***CORS*** or how to know if they support them?

>[caniuse.com](https://caniuse.com/cors)

21. ***Token inline hook reference***:

>[Inline Hook](https://developer.okta.com/docs/reference/token-hook/)

22. How enable the ***token inline hook***? 

>[Activate and enable the token inline hook](https://developer.okta.com/docs/guides/token-inline-hook/nodejs/main/#send-a-response-to-okta)










