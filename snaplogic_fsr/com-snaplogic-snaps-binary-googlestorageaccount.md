# Configure Google Storage account

Enter the following details according to the account selected: 

*   **Label:** User-provided name for the account instance.

    in Flows. For example, _Filereader_sales_account_, if you are part of the sales team.
* **Access token**: Enter the access token for the application. The access token is retrieved when setting up the account for the endpoint.
* **Refresh token**: Enter the refresh token for the application. The refresh token is refreshed when setting up the account for the endpoint.
* **Access token expiration**: Enter the expiration value of the access token. 
* **OAuth2 Endpoint**: Enter the authorization endpoint to authorize the application. Default value: https://accounts.google.com/o/oauth2/auth
* **OAuth2 Token**: Enter the token endpoint to get the access token.  **Default value**:  https://accounts.google.com/o/oauth2/token
* **Access Type**:  Select if you want the Flow to access a Google API when the user is not present in the browser. If the property value is **offline**, then the refresh token receives the first-time authorization. Default value:  offline
* **Approval Prompt**: Select if you want the user to receive the offline consent for a new refresh token.
* **Application Scope:** Enter the scope of the application execution. 
* **Auto-refresh token**: Select if you want to refresh the refresh token automatically. 
* Click **Authorize**.
* Click any one of the following:
  * **Apply** to save your account information in Flows.
  * **Validate** to verify if your account information is valid by connecting Flows with your Salesforce.com account.
  * **Cancel** to return to the previous screen.
