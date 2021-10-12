# Configure your account settings



Enter the following details based on the account selected: 

**AWS S3 account**

* **Label:** Enter a unique name to help identify your SnapLogic File system Reader AWS S3 account in Flows. For example, _rest_sales_account_, if you are part of the sales team.
* **Access-key ID: **Unique access key ID part of AWS authentication.
* **Secret Key:** Secret key part of AWS authentication
* **Server-side encryption**: Select this checkbox if you want the S3 file to write and encrypt using the 256-bit Advanced Encryption Standard AAES256.
*   **KMS Encryption type**: Select the AWS Key Management Service key used to encrypt S3 objects. It can be the key ID or ARN.

    The available options are:

    * _None_: The files do not get encrypted using KMS encryption.
    * _Server-Side KMS Encryption:_ If selected, the output files on Amazon S3 are encrypted using this encryption with Amazon S3 generated KMS key.
    * _Client-Side KMS Encryption:_ If selected, the output files on Amazon S3 are encrypted using this encryption with a client-generated KMS key.
* **KMS Key**:  Specifies _the _AWS Key Management Service (KMS) key ID or ARN to be used for the S3 encryption. This is only required if the KMS Encryption type property is configured to use the encryption with KMS.
* **KMS Region**: Name of the region to which the KMS key belongs.
* **IAM role**: Select this checkbox to use the IAM role stored in the EC2 instance, instead of the normal AWS authentication, to access the S3 bucket.
* **Role ARN**: The Amazon Resource Name of the role to assume.
* **External ID**: An optional external ID that might be required by the role to assume.

**Azure Data Lake account**

* **Label:** Enter a unique name to help identify your SnapLogic File system Reader Azure Data Lake account in Flows. For example, _rest_sales_account_, if you are part of the sales team.
* **Tenant ID: **The Directory ID of the Azure Active Directory.
* **Access ID:** The Application ID of the application in the Azure Active Directory.
* **Secret Key**: The authentication key for accessing the Azure Active Directory.

**Azure Storage Account**

*   **Label:** User-provided name for the account instance.

    in Flows. For example, _Filereader_sales_account_, if you are part of the sales team.
* **Account name**: Enter the Azure storage account name.
* **Primary access key**: Enter the primary access key for Azure storage account.
* **Blob endpoint**: Enter the Azure storage blob endpoint. If you do not enter any value, then the account uses your default Azure storage blob endpoint.

Basic Auth account

*   **Label:** User-provided name for the account instance.

    in Flows. For example, _Filereader_sales_account_, if you are part of the sales team.
* **Username: **Enter a valid username as given in your Snapogic File System Reader basic auth account.
* **Password:** Enter the password for the above account as used in your Snapogic File System Reader basic auth account.
* Click any one of the following:
  * **Apply** to save your account information in Flows.
  * **Validate **to verify if your account information is valid by connecting Flows with your SnapLogic File System Reader account.
  * **Cancel** to return to the previous screen.
