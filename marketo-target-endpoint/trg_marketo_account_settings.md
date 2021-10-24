# Configure your Marketo account settings

1. Configure your account with the following details:
   * **Label:** Specify a unique user-provided label for the account.
   * **Munchkin ID**: Enter the Munchkin ID associated with your Marketo application.
   * **Client ID**: Enter the client ID associated with your Marketo application.
   * **Client Secret:** Enter the client secret associated with your account.
   * **Access token**: The access token associated with the Marketo portal application is used to make API requests on behalf of the user associated with the client ID.
   * **Access token expiration**: The access token expiration value.
   * Select the **Header Authenticated** checkbox if the endpoint uses bearer header authentication.
   * In **OAuth2 Endpoint,** enter the authorization endpoint to authorize the application.
   * **OAuth2 Token**, enter the token endpoint to get the access token.
   * **Token endpoint config**: Enable this if the endpoint uses bearer header authentication. This field set comprises the following fields:
     * Token endpoint parameter
     * Token endpoint parameter value
   * **Auth endpoint config**: Use this field set to assign scopes for the OAuth2 authentication endpoint for the account. It is recommended to define at least one scope entry in this field set. This field set comprises the following fields:
     * Authentication parameter
     * Authentication parameter value
2. Select the **Auto-refresh token** checkbox to refresh the token automatically using your Marketo account's refresh token
3. Click **Authorize.** You will be directed to the login page of your Marketo Account.
4. Click any one of the following:

* **Apply** to save your account information in Flows.
* **Cancel** to return to the previous screen.
