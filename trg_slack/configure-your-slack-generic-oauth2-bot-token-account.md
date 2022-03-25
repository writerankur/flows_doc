# Configure your Slack Generic OAuth2 Bot Token account

Enter the following information for your Slack Generic OAuth2 Bot Token account:

* **Label**: Specify a unique label for the account.
* **Client ID**: Enter the client ID associated with your Slack application.
* **Client secret**: Enter the client secret associated with your account.
* **Access token**: The access token associated with the Slack application is used to make API requests on behalf of the user associated with the client ID.
* **Refresh token**: The refresh token retrieval for the application is specified when setting up the account for the endpoint.
* **Access token expiration**: The access token expiration value in Epoch time.
* **Header authenticated**: Enable this if the endpoint uses bearer header authentication.
* **OAuth2 Endpoint**: Enter the OAuth2 endpoint authorization URL to authorize the application.
* **OAuth2 Token**: Enter the Token endpoint to get the access token.
* **Token endpoint config**: Use this field set to configure token endpoint parameters as necessary for the account.
  * **Token endpoint parameter**: Provide the name for the token endpoint parameter.
  * **Token endpoint parameter value**: Provide the value for the parameter.
* Auth endpoint config:
  * **Authentication parameter**: Provide the name for an authentication parameter.
  * **Authentication parameter value**: Provide the value for the parameter, typically one of the Bot scopes.
* **Auto-refresh token**: You need not select this checkbox as the bot token never expires.
* Click **Authorize.** You will be directed to the login page of your Slack Account.
* Click any one of the following:
  * **Apply** to save your account information in Flows.
  * **Cancel** to return to the previous screen.
