# Configure your REST OAuth1 account

Enter the following details for your REST OAuth1 account:&#x20;

* **Label:** Enter a unique name to help identify your REST OAuth1 account in Flows.
* **Client ID:** The client ID associated with your account. You can create the client ID as advised by your application provider.
* **Client Secret**: The client secret associated with your account. You can create the client secret as advised by your application provider.
* **OAuth Token**: _Auto-generated after authorization_. The token that SnapLogic uses to make API requests on behalf of the user associated with the client ID.
* **OAuth Token Secret**: _Auto-generated after authorization_. The refresh token is associated with your account. If the refresh token is stored, then the access token can be refreshed automatically before it expires.
* **Request Token Endpoint**: The endpoint from where the application can retrieve the request token required for the account. For example, [https://api.xero.com/oauth/RequestToken](https://api.xero.com/oauth/RequestToken)
* **Access Token Endpoint**: The URL of the endpoint from where the application can retrieve the access tokens required for the account. For example, [https://api.xero.com/oauth/AccessToken](https://api.xero.com/oauth/AccessToken)
* **Authorize Endpoint**: The endpoint that authorizes the application to access the target database. For example, [_https://api.xero.com/oauth/Authorize_](https://api.xero.com/oauth/Authorize)
* Click **Authorize** to authorize the REST OAuth1 account using the credentials provided.
* Click any one of the following:
  * **Apply** to save your account information in Flows.
  * **Cancel** to return to the previous screen.
