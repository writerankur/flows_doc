# Configure SnapLogic File System Reader account settings

Enter the following details based on the account selected:&#x20;

**AWS S3 account**

* **Label**: Enter a unique name to help identify your SnapLogic File System Reader AWS S3 account in Flows. For example, _rest\_sales\_account_, if you are part of the sales team.
* **Access-key ID**:** **Unique access key ID part of AWS authentication.
* **Secret Key**: Secret key part of AWS authentication
* **Server-side encryption**: Select this checkbox if you want the S3 file to write and encrypt using the 256-bit Advanced Encryption Standard AAES256.
*   **KMS Encryption type**: Select the AWS Key Management Service key used to encrypt S3 objects. It can be the key ID or ARN.

    The available options are:

    * _None:_ The files do not get encrypted using KMS encryption.
    * _Server-Side KMS Encryption:_ If selected, the output files on Amazon S3 are encrypted using this encryption with Amazon S3 generated KMS key.
    * _Client-Side KMS Encryption:_ If selected, the output files on Amazon S3 are encrypted using this encryption with a client-generated KMS key.
* **KMS Key**: Specifies _the _AWS Key Management Service (KMS) key ID or ARN to be used for the S3 encryption. This is only required if the KMS Encryption type property is configured to use the encryption with KMS.
* **KMS Region**: Name of the region to which the KMS key belongs.
* **IAM role**: Select this checkbox to use the IAM role stored in the EC2 instance, instead of the normal AWS authentication, to access the S3 bucket.
* **Role ARN**: The Amazon Resource Name of the role to assume.
* **External ID**: An optional external ID that might be required by the role to assume.

**Azure Data Lake account**

* **Label**: Enter a unique name to help identify your SnapLogic File system Reader Azure Data Lake account in Flows. For example, _rest\_sales\_account_, if you are part of the sales team.
* **Tenant ID**:** **The Directory ID of the Azure Active Directory.
* **Access ID**: The Application ID of the application in the Azure Active Directory.
* **Secret Key**: The authentication key for accessing the Azure Active Directory.

**Azure Storage Account**

*   **Label**: User-provided name for the account instance.

    in Flows. For example, _Filereader\_sales\_account_, if you are part of the sales team.
* **Account name**: Enter the Azure storage account name.
* **Primary access key**: Enter the primary access key for Azure storage account.
* **Blob endpoint**: Enter the Azure storage blob endpoint. If you do not enter any value, then the account uses your default Azure storage blob endpoint.

**Basic Auth account**

*   **Label**: User-provided name for the account instance.

    in Flows. For example, _Filereader\_sales\_account_, if you are part of the sales team.
* **Username**:** **Enter a valid username as given in your Snapogic File System Reader basic auth account.
* **Password**: Enter the password for the above account as used in your Snapogic File System Reader basic auth account.
* Click any one of the following:
  * **Apply** to save your account information in Flows.
  * **Validate **to verify if your account information is valid by connecting Flows with your SnapLogic File System Reader account.
  * **Cancel** to return to the previous screen.

**Google Service Account**

* **Label**: User-provided name for the account instance in Flows. For example, _Filereader\_sales\_account_, if you are part of the sales team.
* **Project ID**:  Enter the project ID with which the service account is associated. For example, testproject1234
* **JSON Key**: Enter the relative path of the JSON key in the SLDB. For example,  ../shared/testproject1234-a0545b98719d\_dummy.json

**Google Storage Account**

* **Label**: User-provided name for the account instance in Flows. For example, _Filereader\_sales\_account_, if you are part of the sales team.
* **Access token**: The access token for the application.
* **Refresh token**: The refresh token for the application.
* **Access token expiration**: The access token expiration value.
* **OAuth2 Endpoint**: Authorization endpoint to authorize the application.
* **OAuth2 Token**: Token endpoint to get the access token.
* **Access type**: Indicates whether the Snap needs to access a Google API when the user is not present at the browser. The property value **offline **results in a refresh token is obtained the first time authorization has been received.
* **Approval prompt**: Indicates whether the user should be re-prompted for offline consent to receive a new refresh token.
* **Application scope**: The scope for the application's execution.
* **Auto-refresh token**: Refreshes the token automatically using the refresh token if the property is enabled.

**S3 Dynamic Account**

* **Label**:** **User-provided label for the account instance
* **Access-key ID**:** **Access key ID part of AWS authentication
* **Secret key**:** **Secret key part of AWS authentication
* **Security Token**:** **Security token part of AWS Security Token Service (STS) credentials\
  **Server-side encryption**: Represents the type of encryption to use for the objects stored in S3.&#x20;
* **KMS Encryption type**:** **Represents the AWS Key Management Service key used to encrypt S3 objects. It can be the key ID or ARN. The available options are:
  * _None_: The files do not get encrypted using KMS encryption.
  * _Server side KMS Encryption:_ If selected, the output files on Amazon S3 are encrypted using this encryption with Amazon S3 generated KMS key.
  * _Client side KMS Encryption:_ If selected, the output files on Amazon S3 are encrypted using this encryption with a client-generated KMS key.
* **KMS key**:** **Represents the AWS Key Management Service key used to encrypt S3 objects. It can be the key ID or ARN.&#x20;
* **Cross Account IAM Role**:** **This field set helps in granting cross-account access, with the following two fields that help you in [setting up Cross Account IAM Role](https://docs-snaplogic.atlassian.net/wiki/spaces/SD/pages/1246956316/Configuring+Cross+Account+IAM+Role+Support).
* **Role ARN**:** **The Amazon Resource Name of the role to assume.
* **External ID**:** **An optional external ID that might be required by the role to assume.

**SMB Account**

* **Label**: User-provided name for the account instance** **in Flows. For example, _Filereader\_sales\_account_, if you are part of the sales team.
* **Domain**: Domain of the SMB account
* **Username**:** **Enter a valid username as given in your SnapLogic File System Reader SMB account.
* **Password**: Enter the password for the above account as used in your SnapLogic File System Reader SMB account.

**SSH Auth Account **and **Two-Factor Auth account**

* **Label**: User-provided name for the account instance** **in Flows. For example, _Filereader\_sales\_account_, if you are part of the sales team.
* **Username**: Account username.
* **Private key**: Private key part of SSH authentication.
* **Key passphrase**: Passphrase is used to decrypt the private key.
