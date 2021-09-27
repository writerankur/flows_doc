# Configure S3 Dynamic account

Enter the following details according to the account selected: 

* **Label:** Enter a unique name to help identify your REST basic auth account

  in Flows. For example, _rest\_sales\_account_, if you are part of the sales team.

* **Access-key ID:** Unique access key ID part of S3 authentication.
* **Secret Key:** Secret key part of AWS authentication
* **Security token**: Enter the security token part of S3 Security Token Service \(STS\) credentials
* **Server-side encryption**: Select this checkbox if you want the S3 file to write and encrypt using the 256-bit Advanced Encryption Standard AAES256.
* **KMS Encryption type**: Select the S3 Key Management Service key used to encrypt S3 objects. It can be the key ID or ARN. The available options are:
  * _None_: The files do not get encrypted using KMS encryption.
  * _Server-Side KMS Encryption:_ If selected, the output files on Amazon S3 are encrypted using this encryption with Amazon S3 generated KMS key.
  * _Client-Side KMS Encryption:_ If selected, the output files on Amazon S3 are encrypted using this encryption with a client-generated KMS key.
* **KMS Key**:  Specifies _the_ AWS Key Management Service \(KMS\) key ID or ARN to be used for the S3 encryption. This is only required if the KMS Encryption type property is configured to use the encryption with KMS.
* **KMS Region**: Name of the region to which the KMS key belongs.
* **Role ARN**: The Amazon Resource Name of the role to assume.
* **External ID**: An optional external ID that might be required by the role to assume.
* Click any one of the following:
  * **Apply** to save your account information in Flows.
  * **Cancel** to return to the previous screen.

