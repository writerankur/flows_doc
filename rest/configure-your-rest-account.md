# Enter your REST account information

Enter the following details according to the account selected: 

**REST Basic Auth Account**

* **Label:** Enter a unique name to help identify your REST basic auth account

  in Flows. For example, _rest\_sales\_account_, if you are part of the sales team.

* **Username:** Enter a valid username as given in your REST basic auth account.
* **Password:** Enter the password for the above account as used in your REST basic auth account.
* Click **Apply**.

**REST Dynamic OAuth2 Account**

* **Label:** Enter a unique name to help identify your Salesforce.com account in Flows. For example, _Salesforce\_sales\_account_, if you are part of the sales team.
* **Access Token**: The access token for the application. The retrieval of the access token is done when setting up the account for the endpoint.
* **Header authenticated**: Select to indicate that the endpoint uses bearer header authentication.
* Click **Apply**.

**REST NTLM Account**

* **Label:** Enter a unique name to help identify your REST basic auth account

  in Flows. For example, _rest\_sales\_account_, if you are part of the sales team.

* **Username:** Enter a valid username as given in your REST basic auth account.
* **Password:** Enter the password for the above account as used in your REST basic auth account.
* **Domain**: The name of the NETBIOS domain in which the account is configured.
* Click **Apply**.

**REST OAuth1 Account**

* **Label:** Enter a unique name to help identify your REST basic auth account

  in Flows. For example, _rest\_sales\_account_, if you are part of the sales team.

* **Client ID:** The client ID associated with your account. You can create the client ID as advised by your application provider.
* **Client Secret**: The client secret associated with your account. You can create the client secret as advised by your application provider.
* **OAuth Token**: _Auto-generated after authorization_. The token that SnapLogic uses to make API requests on behalf of the user associated with the client ID. 
* **OAuth Token Secret**: _Auto-generated after authorization_. The refresh token associated with your account. If the refresh token is stored, then the access token can be refreshed automatically before it expires.
* **Request Token Endpoint**: The endpoint from where the application can retrieve the request token required for the account. For example, 

  [https://api.xero.com/oauth/RequestToken](https://api.xero.com/oauth/RequestToken) 

* **Access Token Endpoint**: The URL of the endpoint from where the application can retrieve the access tokens required for the account. For example, [https://api.xero.com/oauth/AccessToken](https://api.xero.com/oauth/AccessToken) 
* **Authorize Endpoint**: The endpoint that authorizes the application to access the target database.
* Click **Authorize** to authorize the REST OAuth1 account using the credentials provided.
* Click **Apply**.

**REST OAuth2 Account**

* **Label:** Enter a unique name to help identify your REST basic auth account

  in Flows. For example, _rest\_sales\_account_, if you are part of the sales team.

* **Client ID:** The client ID associated with your account. You can create the client ID as advised by your application provider.
* **Client Secret**: The client secret associated with your account. You can create the client secret as advised by your application provider.
* **Access token**:  _Auto-generated after authorization._ The token that SnapLogic uses to make API requests on behalf of the user associated with the client ID.
*  **Refresh token**:  _Auto-generated after authorization_. The refresh token associated with your account. If the refresh token is stored, then the access token can be refreshed automatically before it expires.
* **Access token expiration**: _Auto-generated after authorization_. The access token expiration value, in seconds.
* **Header authenticated**: Select this check box to indicate that the endpoint uses bearer header authentication.
* **OAuth2 Endpoint**: Enter the URL of the endpoint that authorizes the application. 
* **OAuth2 Token**: Enter the URL of the endpoint that retrieves the token for an authenticated account.
* **Grant Type**:

**REST OAuth2 SSL Account**

**REST SSL Account**  


