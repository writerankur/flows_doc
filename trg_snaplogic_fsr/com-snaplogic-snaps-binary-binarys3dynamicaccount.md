# Configure your S3 Dynamic Account

Enter the following details for your S3 Dynamic Account:&#x20;

* **Label**: User-provided label for the account instance
* **Access-key ID**: Access key ID part of AWS authentication
* **Secret key**: Secret key part of AWS authentication. See [https://docs.aws.amazon.com/powershell/latest/userguide/pstools-appendix-sign-up.html](https://docs.aws.amazon.com/powershell/latest/userguide/pstools-appendix-sign-up.html) to know more about Acess Key and Secret key and the process to retrieve them.
* **Security Token**: Security token part of AWS Security Token Service (STS) credentials **Server-side encryption**: Represents the type of encryption to use for the objects stored in S3.
* **KMS Encryption type**: Represents the AWS Key Management Service key used to encrypt S3 objects. It can be the key ID or ARN. The available options are:
  * _None_: The files do not get encrypted using KMS encryption.
  * _Server side KMS Encryption:_ If selected, the output files on Amazon S3 are encrypted using this encryption with Amazon S3 generated KMS key.
  * _Client side KMS Encryption:_ If selected, the output files on Amazon S3 are encrypted using this encryption with a client-generated KMS key.
* **KMS key**: Represents the AWS Key Management Service key used to encrypt S3 objects. It can be the key ID or ARN.
* **KMS Region**: Name of the region to which the KMS key belongs.
* **Cross Account IAM Role**: This field set helps in granting cross-account access, with the following two fields that help you in [setting up Cross Account IAM Role](https://docs-snaplogic.atlassian.net/wiki/spaces/SD/pages/1246956316/Configuring+Cross+Account+IAM+Role+Support).
* **Role ARN**: The Amazon Resource Name of the role to assume.
* **External ID**: An optional external ID that might be required by the role to assume.
* Click any one of the following:
  * **Apply** to save your account information in Flows.
  * **Cancel** to return to the previous screen.
