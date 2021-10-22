# Configure your Slack account settings

Configure your account with the following details:

**Slack Dynamic OAuth2 Account**:

1. Configure your account with the following details:
   * **Label**: Specify a unique label for the account.
   * **Access** **token**: The access token associated with the Slack application is used to make API requests on behalf of the user associated with the client ID.
   * **Header** **authenticated**: Select this check box to specify that Slack uses the bearer header authentication.
2. Click any one of the following:
   * Apply to save your account information in Flows.
   * Save & Validate to verify if your account information is valid by connecting Flows with your Salesforce.com account.
   * Cancel to return to the previous screen.

**Slack Generic OAuth2 Bot Token Account** and **Slack Generic OAuth2 User Token Account**

1. Configure your account with the following details:
   * Label: Specify a unique label for the account.
   * Client ID: Enter the client ID associated with your Slack application.&#x20;
   * Client secret: Enter the client secret associated with your account.
   * Access token: The access token associated with the Slack application is used to make API requests on behalf of the user associated with the client ID.
   * Refresh token: The refresh token retrieval for the application is specified when setting up the account for the endpoint.&#x20;
   * Access token expiration: The access token expiration value in Epoch time.
   * Header authenticated: Enable this if the endpoint uses bearer header authentication.
   * OAuth2 Endpoint: Enter the OAuth2 endpoint authorization URL to authorize the application.
   * OAuth2 Token: Enter the Token endpoint to get the access token.
   * Token endpoint config: Use this field set to configure token endpoint parameters as necessary for the account.
     * Token endpoint parameter: Provide the name for the token endpoint parameter.
     * Token endpoint parameter value: Provide the value for the parameter.
   * Auth endpoint config:
     * Authentication parameter: Provide the name for an authentication parameter.
     * Authentication parameter value: Provide the value for the parameter, typically one of the Bot scopes.
   * Auto-refresh token: You need not select this checkbox as the bot token never expires.
2. Click any one of the following:
   * Apply to save your account information in Flows.
   * Save & Validate to verify if your account information is valid by connecting Flows with your Salesforce.com account.
   * Cancel to return to the previous screen.
