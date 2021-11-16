# Configure MySQL account settings

**MySQL Database and MySQL Dynamic Account**

Configure the Email Sender account settings as follows:

* **Label**: The user-provided name for the account. Preferably, update the account name if your project includes more than one account of the same type.
* **JDBC Driver Class**: The class name of the JBDC driver.&#x20;
* **JDBC JARs**: List of JDBC JAR files to be loaded. Click ![https://docs-snaplogic.atlassian.net/wiki/download/attachments/896369522/Plus.png?version=1\&modificationDate=1579553898874\&cacheVersion=1\&api=v2](../.gitbook/assets/0) on the right of the field to add a row.
  * **JDBC Driver**:** **The software component enabling an application to interact with a database.
* **Hostname**: The server address to which the application must connect.
* **Port Number**: The database server's port number to which the application must connect.
* **Database name**: The database name to which the application must connect.
* **Username**: The user name that is allowed to connect to the database.
* **Password**: The password used to connect to the data source.&#x20;
* **Configure SSH Tunnel**: Select this check box if the Snap must create an SSH tunnel dynamically for connecting the JCC node to the MySQL server. Once the operation is completed, the tunnel is closed. If selected, the configuration details of the SSH Tunnel must be provided.
* **SSH Auth Mode**: Select the mode for authenticating the user on the SSH tunnel. The associated properties are displayed. The valid options are:
  * _**Password**_: If selected, the SSH Hostname, SSH Username, and the SSH Password properties must be configured.
  * _**KeyFile**_: If selected, the SSH Hostname, SSH Username, KeyStore, KeyStore Password, Key alias, and Private Key Passphrase properties must be configured. This value is considered only if the Configure SSH Tunnel check box is selected.
* **SSH Hostname**: The IP address or the domain name of the SSH server to which you want to connect. This value is considered only if the Configure SSH Tunnel check box is selected.
* **SSH Username**: The SSH username for connecting to the tunnel. This value is considered only if the Configure SSH Tunnel check box is selected.
* **SSH Password**: The password associated with the SSH username. This field is required if SSH Auth Mode is _Password_. This value is considered only if the Configure SSH Tunnel check box is selected.
