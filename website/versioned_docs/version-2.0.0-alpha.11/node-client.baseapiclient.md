---
id: version-2.0.0-alpha.11-node-client.baseapiclient
title: BaseAPIClient class
hide_title: true
original_id: node-client.baseapiclient
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->


## BaseAPIClient class


<b>Signature:</b>

```typescript
export declare abstract class BaseAPIClient 
```

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)(options)](./node-client.baseapiclient._constructor_.md) |  | Constructs a new instance of the <code>BaseAPIClient</code> class |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [apiKey](./node-client.baseapiclient.apikey.md) |  | <code>string</code> |  |
|  [endpoint](./node-client.baseapiclient.endpoint.md) |  | <code>string</code> |  |
|  [fetchFunction](./node-client.baseapiclient.fetchfunction.md) |  | <code>typeof fetch</code> |  |
|  [getExtraSessionInfo](./node-client.baseapiclient.getextrasessioninfo.md) |  | <code>() =&gt; Promise&lt;JSONObject &#124; null&gt;</code> |  |
|  [refreshTokenFunction](./node-client.baseapiclient.refreshtokenfunction.md) |  | <code>() =&gt; Promise&lt;boolean&gt;</code> |  |
|  [requestClass](./node-client.baseapiclient.requestclass.md) |  | <code>typeof Request</code> |  |
|  [userAgent](./node-client.baseapiclient.useragent.md) |  | <code>string</code> |  |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [changePassword(newPassword, oldPassword)](./node-client.baseapiclient.changepassword.md) |  |  |
|  [del(path, options)](./node-client.baseapiclient.del.md) |  |  |
|  [deleteOAuthProvider(providerID)](./node-client.baseapiclient.deleteoauthprovider.md) |  |  |
|  [fetch(input, init, options)](./node-client.baseapiclient.fetch.md) |  |  |
|  [get(path, options)](./node-client.baseapiclient.get.md) |  |  |
|  [getSession(id)](./node-client.baseapiclient.getsession.md) |  |  |
|  [linkOAuthProviderWithAccessToken(providerID, accessToken)](./node-client.baseapiclient.linkoauthproviderwithaccesstoken.md) |  |  |
|  [listSessions()](./node-client.baseapiclient.listsessions.md) |  |  |
|  [login(loginID, password, options)](./node-client.baseapiclient.login.md) |  |  |
|  [loginOAuthProviderWithAccessToken(providerID, accessToken, options)](./node-client.baseapiclient.loginoauthproviderwithaccesstoken.md) |  |  |
|  [loginWithCustomToken(token, options)](./node-client.baseapiclient.loginwithcustomtoken.md) |  |  |
|  [logout()](./node-client.baseapiclient.logout.md) |  |  |
|  [me()](./node-client.baseapiclient.me.md) |  |  |
|  [oauthAuthorizationURL(providerID, options)](./node-client.baseapiclient.oauthauthorizationurl.md) |  |  |
|  [post(path, options)](./node-client.baseapiclient.post.md) |  |  |
|  [postAndReturnAuthResponse(path, options)](./node-client.baseapiclient.postandreturnauthresponse.md) |  |  |
|  [prepareHeaders()](./node-client.baseapiclient.prepareheaders.md) |  |  |
|  [refresh(refreshToken)](./node-client.baseapiclient.refresh.md) |  |  |
|  [request(method, path, options)](./node-client.baseapiclient.request.md) |  |  |
|  [requestEmailVerification(email)](./node-client.baseapiclient.requestemailverification.md) |  |  |
|  [requestForgotPasswordEmail(email)](./node-client.baseapiclient.requestforgotpasswordemail.md) |  |  |
|  [resetPassword(form)](./node-client.baseapiclient.resetpassword.md) |  |  |
|  [revokeOtherSessions()](./node-client.baseapiclient.revokeothersessions.md) |  |  |
|  [revokeSession(id)](./node-client.baseapiclient.revokesession.md) |  |  |
|  [signup(loginIDs, password, options)](./node-client.baseapiclient.signup.md) |  |  |
|  [updateMetadata(metadata)](./node-client.baseapiclient.updatemetadata.md) |  |  |
|  [updateSession(id, patch)](./node-client.baseapiclient.updatesession.md) |  |  |
|  [verifyWithCode(code)](./node-client.baseapiclient.verifywithcode.md) |  |  |
