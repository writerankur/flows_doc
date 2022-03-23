# Configure your AWS S3 Account

Enter the following details for your AWS S3 account:&#x20;

* **Label:** Enter a unique name to help identify your SnapLogic File system Writer (SFSR) AWS S3 account in Flows. For example, _sfsr\_sales\_account_, if you are part of the sales team.
* **Access-key ID:** Unique access key ID part of AWS authentication.
* **Secret Key:** Secret key part of AWS authentication. See [https://docs.aws.amazon.com/powershell/latest/userguide/pstools-appendix-sign-up.html](https://docs.aws.amazon.com/powershell/latest/userguide/pstools-appendix-sign-up.html) to know more about Access Key and Secret Key and the process to retrieve them.
* **Server-side encryption**: Select this checkbox if you want the S3 file to write and encrypt using the 256-bit Advanced Encryption Standard AAES256.
* **KMS Encryption type**: Select the AWS Key Management Service key used to encrypt S3 objects. It can be the key ID or ARN.

The available options are:

* _None_: The files do not get encrypted using KMS encryption.
* _Server-Side KMS Encryption:_ If selected, the output files on Amazon S3 are encrypted using this encryption with Amazon S3 generated KMS key.
* _Client-Side KMS Encryption:_ If selected, the output files on Amazon S3 are encrypted using this encryption with a client-generated KMS key.
* **KMS Key**: Specifies _the_ AWS Key Management Service (KMS) key ID or ARN to be used for the S3 encryption. This is only required if the KMS Encryption type property is configured to use the encryption with KMS.
* **KMS Region**: Name of the region to which the KMS key belongs.
* **IAM role**: Select this checkbox to use the IAM role stored in the EC2 instance, instead of the normal AWS authentication, to access the S3 bucket.
* **Role ARN**: The Amazon Resource Name (ARN) of the role to assume.
* **External ID**: An optional external ID that might be required by the role to assume.
