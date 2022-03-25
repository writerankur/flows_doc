# Configure your REST OAuth2 account

Enter the following details for your REST OAuth2 account:&#x20;

* **Label:** Enter a unique name to help identify your REST OAuth2 account in Flows. For example, _rest\_sales\_account_, if you are part of the sales team.
* **Client ID:** The client ID associated with your account. You can create the client ID as advised by your application provider.
* **Client Secret**: The client secret associated with your account. You can create the client secret as advised by your application provider.
* **Access token**: _Auto-generated after authorization._ The token that SnapLogic uses to make API requests on behalf of the user associated with the client ID.
* **Refresh token**: _Auto-generated after authorization_. The refresh token associated with your account. If the refresh token is stored, then the access token can be refreshed automatically before it expires.
* **Access token expiration**: _Auto-generated after authorization_. The access token expiration value, in seconds.
* **Header authenticated**: Select this checkbox to indicate that the endpoint uses bearer header authentication.
* **OAuth2 Endpoint**: Enter the URL of the endpoint that authorizes the application. For example, [_https://login.microsoftonline.com/common/oauth2/v2.0/authorize_](https://login.microsoftonline.com/common/oauth2/v2.0/authorize)\_\_
* **OAuth2 Token**: Enter the URL of the endpoint that retrieves the token for an authenticated account. For example, [_https://login.microsoftonline.com/common/oauth2/token_](https://login.microsoftonline.com/common/oauth2/token)\_\_
* **Grant Type**: Select the method of authorization.
  * **authorization\_code**: The user is authenticated using credentials (username and password), which return to the client through a redirect URL. The application then receives the authorization code from the URL and uses it to request an access token.
  * **client\_credentials**: Obtains an access token to the client ID and client secret through the token endpoint URL.
  * **password**: Obtains access token using your login credentials (username and password).
* **Token endpoint config**: Use this fieldset to provide custom properties for the OAuth2 token endpoint. Click the + or - icons to respectively add or remove configuration rows. This fieldset comprises the following fields:
  * **Token endpoint parameter**: Defines an optional token endpoint parameter.
  * **Token endpoint parameter value**: The value associated with the optional endpoint parameter defined above.
* **Auth endpoint config**: Use this fieldset to provide custom properties for the OAuth2 auth endpoint. Click the + or - icons to respectively add or remove configuration rows. This fieldset comprises the following fields:
  * **Authentication parameter**: Defines an optional authorization endpoint parameter.
  * **Authentication parameter value**: The value associated with the optional authorization endpoint parameter defined above.
* **Auto-refresh token**: Select this checkbox to refresh the token automatically using the refresh token, if the property is enabled. If this property is deselected, the token expires and is not refreshed automatically.
* Click **Authorize** to authorize the REST OAuth2 account using the credentials provided.
* **Send Client Data as Basic Auth header**: Select this checkbox to send the client information as a header to the OAuth endpoint.
* Click any one of the following:
  * **Apply** to save your account information in Flows.
  * **Cancel** to return to the previous screen.
