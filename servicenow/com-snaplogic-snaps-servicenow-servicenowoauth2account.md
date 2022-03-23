# Configure your ServiceNow OAuth2 Account

1.  For ServiceNow OAuth2 User Accounts, configure your account with the following details:&#x20;

    * **Label:** Enter a unique label for the account.&#x20;
    * **Instance:** Enter the name of your ServiceNow instance. For example, if `https://snaplogic.service-now.com/` is the URL of your ServiceNow instance, then "snaplogic" is the instance name.&#x20;
    * **Client ID**: Enter the client ID that is associated with your ServiceNow application and used for authorization. You can create the client ID as advised by your application provider.&#x20;
    * **Client Secret:** Enter the client secret that associated with your account and used for authorization. You can create the client secret as advised by your application provider.&#x20;
    * **Access Token**: Auto-generated upon account authorization. The access token for the application that is generated when setting up the account for the endpoint.&#x20;
    * **Refresh Token**: Auto-generated after authorization. The token used to refresh the access token.&#x20;
    * **Access token expiration**: The access token expiration value.&#x20;
    * **OAuth2 Endpoint**: Enter the the OAuth2 endpoint in this format to authorize the application: `https://<servicenow instance name>.service-now.com/oauth_auth.do`&#x20;
    * **OAuth2 Token:** Enter **** the value for OAuth2 token in this format to get the access token: `https://<servicenow instance name>.service-now.com/oauth_token.do`&#x20;
    * **Grant Type:** Choose an authentication grant type for your ServiceNow instance. Available options are:&#x20;
      * &#x20;_authorization\_code_: This grant type is used to obtain access tokens and refresh tokens from the authorization server.
      * _password_: Exchanges your credentials for an access token. This grant type involves the traditional username and password login to obtain the user's credentials and makes a POST request to the server to exchange the password for an access token.&#x20;
    * **Auto-refresh Token:** Select this checkbox to enable auto-refresh of the access token before it expires.


2. Click **Authorize** to go to the login page of ServiceNow, accept the permissions and generate The Access token and the Refresh Token. &#x20;
3. Click any one of the following:&#x20;
   * **Apply** to save your account information in Flows.
   * **Cancel** to return to the previous screen.
