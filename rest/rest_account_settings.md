# Configure your REST account information

Enter the following details based on the account selected:&#x20;

**REST Basic Auth Account**

*   **Label:** Enter a unique name to help identify your REST basic auth account in Flows. For example, _rest\_sales\_account_, if you are part of the sales team.&#x20;

    **Username: **Enter a valid username as given in your REST basic auth account.
* **Password:** Enter the password for the above account as used in your REST basic auth account.
* Click any one of the following:
  * **Apply** to save your account information in Flows.
  * **Cancel** to return to the previous screen.

**REST Dynamic OAuth2 Account**

* **Label:** Enter a unique name to help identify your REST Dynamic OAuth2 account in Flows.&#x20;
* **Access Token**: Specify the access token for the application. The retrieval of the access token is done when setting up the account for the endpoint. For example,&#x20;
* **Header authenticated**: Select to indicate that the endpoint uses bearer header authentication.
* Click any one of the following:
  * **Apply** to save your account information in Flows.
  * **Cancel** to return to the previous screen.

**REST NTLM Account**

*   **Label:** Enter a unique name to help identify your REST NTLM account.

    in Flows. For example, _ntlm\_sales\_account_, if you are part of the sales team.
* **Username: **Enter a valid username as given in your REST NTLM account.
* **Password:** Enter the password for the above account as used in your REST NTLM account.
* **Domain**: The name of the NETBIOS domain in which the account is configured.
* Click any one of the following:
  * **Apply** to save your account information in Flows.
  * **Cancel** to return to the previous screen.

**REST OAuth1 Account**

* **Label:** Enter a unique name to help identify your REST OAuth1 account in Flows.&#x20;
* **Client ID: **The client ID associated with your account. You can create the client ID as advised by your application provider.
* **Client Secret**: The client secret associated with your account. You can create the client secret as advised by your application provider.
* **OAuth Token**: _Auto-generated after authorization_. The token that SnapLogic uses to make API requests on behalf of the user associated with the client ID.&#x20;
* **OAuth Token Secret**: _Auto-generated after authorization_. The refresh token is associated with your account. If the refresh token is stored, then the access token can be refreshed automatically before it expires.&#x20;
* **Request Token Endpoint**: The endpoint from where the application can retrieve the request token required for the account. For example, [https://api.xero.com/oauth/RequestToken](https://api.xero.com/oauth/RequestToken)&#x20;
* **Access Token Endpoint**: The URL of the endpoint from where the application can retrieve the access tokens required for the account. For example, [https://api.xero.com/oauth/AccessToken](https://api.xero.com/oauth/AccessToken)&#x20;
* **Authorize Endpoint**: The endpoint that authorizes the application to access the target database. For example, [_https://api.xero.com/oauth/Authorize_](https://api.xero.com/oauth/Authorize)
* Click **Authorize **to authorize the REST OAuth1 account using the credentials provided.
* Click any one of the following:
  * **Apply** to save your account information in Flows.
  * **Cancel** to return to the previous screen.

**REST OAuth2 Account**

* **Label:** Enter a unique name to help identify your REST OAuth2 account in Flows. For example, _rest\_sales\_account_, if you are part of the sales team.
* **Client ID: **The client ID associated with your account. You can create the client ID as advised by your application provider.
* **Client Secret**: The client secret associated with your account. You can create the client secret as advised by your application provider.
* **Access token**: _Auto-generated after authorization._ The token that SnapLogic uses to make API requests on behalf of the user associated with the client ID.
* &#x20;**Refresh token**:  _Auto-generated after authorization_. The refresh token associated with your account. If the refresh token is stored, then the access token can be refreshed automatically before it expires.
* **Access token expiration**: _Auto-generated after authorization_. The access token expiration value, in seconds.
* **Header authenticated**: Select this checkbox to indicate that the endpoint uses bearer header authentication.
* **OAuth2 Endpoint**: Enter the URL of the endpoint that authorizes the application. For example, [_https://login.microsoftonline.com/common/oauth2/v2.0/authorize_](https://login.microsoftonline.com/common/oauth2/v2.0/authorize)__
* **OAuth2 Token**: Enter the URL of the endpoint that retrieves the token for an authenticated account. For example, [_https://login.microsoftonline.com/common/oauth2/token_](https://login.microsoftonline.com/common/oauth2/token)__
* **Grant Type**: Select the method of authorization.
  * **Authorization\_code**: The user is authenticated using credentials (username and password), which return to the client through a redirect URL. The application then receives the authorization code from the URL and uses it to request an access token.
  * **Client\_credentials**: Obtains an access token to the client ID and client secret through the token endpoint URL.
* **Token endpoint config**: Use this fieldset to provide custom properties for the OAuth2 token endpoint. Click the + or - icons to respectively add or remove configuration rows. This fieldset comprises the following fields:
  * **Token endpoint parameter**:** **Defines an optional token endpoint parameter.
  * **Token endpoint parameter value**: The value associated with the optional endpoint parameter defined above.
* **Auth endpoint config**: Use this fieldset to provide custom properties for the OAuth2 auth endpoint. Click the + or - icons to respectively add or remove configuration rows. This fieldset comprises the following fields:
  * **Auth endpoint parameter**: Defines an optional authorization endpoint parameter.
  * **Auth endpoint value**: The value associated with the optional authorization endpoint parameter defined above.
* **Auto-refresh token**: Select this check box to refresh the token automatically using the refresh token, if the property is enabled. If this property is deselected, the token expires and is not refreshed automatically.
* Click **Authorize **to authorize the REST OAuth2 account using the credentials provided.
* Click any one of the following:
  * **Apply** to save your account information in Flows.
  * **Cancel** to return to the previous screen.

**REST OAuth2 SSL Account**

*   **Label:** Enter a unique name to help identify your REST OAuth2 SSL account.

    in Flows. For example, _rest\_sales\_account_, if you are part of the sales team.
* **Client ID: **The client ID associated with your account. You can create the client ID as advised by your application provider. For example, _88a731111-07k1-4714-xz5a-de111aaa9a5e_
* **Client Secret**: The client secret associated with your account. You can create the client secret as advised by your application provider.
* **Access token**:  _Auto-generated after authorization._ The token that SnapLogic uses to make API requests on behalf of the user associated with the client ID.
* **Refresh token**:  _Auto-generated after authorization_. The refresh token is associated with your account. If the refresh token is stored, then the access token can be refreshed automatically before it expires.
* **Access token expiration**: _Auto-generated after authorization_. The access token expiration value, in seconds.
* **Header authenticated**: Select this checkbox to indicate that the endpoint uses bearer header authentication.
* **OAuth2 Endpoint**: Enter the URL of the endpoint that authorizes the application.&#x20;
* **OAuth2 Token**: Enter the URL of the endpoint that retrieves the token for an authenticated account.
* **Grant Type**: Select the method of authorization.
  * **Authorization\_code**: The user is authenticated using credentials (username and password), which return to the client through a redirect URL. The application then receives the authorization code from the URL and uses it to request an access token.
  * **Client\_credentials**: Obtains an access token to the client ID and client secret through the token endpoint URL.
* **KeyStore**: The location of the key store file. It can be in SLDB or at any other unauthenticated endpoint.
* **TrustStore**: The location of the trust store file. It can be in SLDB or at any other unauthenticated endpoint.
* **Key/Trust store password**: Password for the key/trust store. It is used for both if both are defined.
* **Key alias**: The alias of the key that you want to use with this account.
* **Token endpoint config**: Use this fieldset to provide custom properties for the OAuth2 token endpoint. Click the + or - icons to respectively add or remove configuration rows. This fieldset comprises the following fields:
  * **Token endpoint parameter**:** **Defines an optional token endpoint parameter.
  * **Token endpoint parameter value**: The value associated with the optional endpoint parameter defined above.
* **Auth endpoint config**: Use this fieldset to provide custom properties for the OAuth2 auth endpoint. Click the + or - icons to respectively add or remove configuration rows. This fieldset comprises the following fields:
  * **Auth endpoint parameter**: Defines an optional authorization endpoint parameter.
  * **Auth endpoint value**: The value associated with the optional authorization endpoint parameter defined above.
* **Auto-refresh token**: Select this check box to refresh the token automatically using the refresh token, if the property is enabled. If this property is deselected, the token expires and is not refreshed automatically.
* Click **Authorize **to authorize the REST OAuth2 SSL account using the credentials provided.
* Click any one of the following:
  * **Apply** to save your account information in Flows.
  * **Cancel** to return to the previous screen.

**REST SSL Account**

*   **Label:** Enter a unique name to help identify your REST SSL account.

    in Flows. For example, _SSL\_sales\_account_, if you are part of the sales team.
* **Username: **Enter a valid username as given in your REST basic SSL account.
* **Password:** Enter the password for the above account as used in your REST basic SSL account.
* **KeyStore**: The location of the key store file. It can be in SLDB or at any other unauthenticated endpoint.
* **TrustStore**: The location of the trust store file. It can be in SLDB or at any other unauthenticated endpoint.
* **Key/Trust store password**: Password for the key/trust store. It is used for both if both are defined.
* **Key alias**: The alias of the key that you want to use with this account.
* Click any one of the following:
  * **Apply** to save your account information in Flows.
  * **Cancel** to return to the previous screen.
