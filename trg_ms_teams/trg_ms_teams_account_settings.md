# Configure your MS Teams account settings

For **Teams Dynamic OAuth2 Accounts**, configure your account with the following details:

* **Label:** Enter a unique name to help identify your MS Teams account in Flows. For example, _MS\_prod\_account_, if you are part of the production team.
* **Access Token**: Specify the access token for the application.
* **Access Token Type:** Select your access token type.
  * On behalf of user (authorization\_code grant type)&#x20;
  * On behalf of application (client\_credentials grant type)
* Click any one of the following:&#x20;
  * **Apply** to save your account information in Flows.
  * **Cancel** to return to the previous screen.

For **Teams OAuth2 User Accounts**, configure your account with the following details:

* **Label:** Enter a unique label for the account.
* **Client ID**: Enter the client ID associated with your Azure application. You can create the client ID as advised by your application provider.
* **Client Secret:** Enter the client secret associated with your account. You can create the client secret as advised by your application provider.
* **Access token**: _Auto-generated after authorization._ The access token associated with the Azure portal application is used to make API requests on behalf of the user associated with the client ID.
* **Refresh token**: _Auto-generated after authorization_. The token used to refresh the access token.
* **Access token expiration**: The access token expiration value.
* **OAuth2 Endpoint,** enter the tenant ID in the designated position in the URL.
* **OAuth2 Token**, enter the tenant ID in the designated position in the URL.
* **Token endpoint config**: Enable this if the endpoint uses bearer header authentication. Click ![https://docs-snaplogic.atlassian.net/wiki/download/attachments/896369522/Plus.png?version=1\&modificationDate=1579553898874\&cacheVersion=1\&api=v2](<../.gitbook/assets/0 (1)>) on the right of the field to add a row. This field set comprises the following fields:
  * Token endpoint parameter
  * Token endpoint parameter value
* **Auth endpoint config**: Use this field set to assign scopes for the OAuth2 authentication endpoint for the account. It is recommended to define at least one scope entry in this fieldset. Click ![https://docs-snaplogic.atlassian.net/wiki/download/attachments/896369522/Plus.png?version=1\&modificationDate=1579553898874\&cacheVersion=1\&api=v2](../.gitbook/assets/1) on the right of the field to add a row. This field set comprises the following fields:
  * Authentication parameter
  * Authentication parameter value
* **Auto-refresh token**: Select this to refresh the access token automatically.
* Click **Authorize.** You will be directed to the login page of your MS Teams account.
* Click any one of the following:
  * **Apply** to save your account information in Flows.
  * **Cancel** to return to the previous screen.
