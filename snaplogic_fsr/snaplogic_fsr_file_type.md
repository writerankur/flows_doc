# SnapLogic File System Reader overview

The SnapLogic File System Reader (SFSR) enables you to read any type of data from various source file types such as SLDB, HTTP, S3, SFTP, and HDFS. This endpoint produces a binary data stream at the output.

Select the **Data Collection Type** from where your data will be sourced to configure this Flow.



## Add Account

You can select a preconfigured account from the dropdown or click **Add Account** to configure your existing account. This is not required to configure this Flow.



## Select your data collection type

Select the **Data Collection Type** from where your data will be sourced to configure this Flow.&#x20;

You can also choose any one of the available data collection types to start your Flow and provide the following information:

**Read CSV File**

* **File**: Enter URL for a regular file. It should start with a file protocol.
* **Delimiter**: Enter the delimiter character to be used as a delimiter in parsing the CSV data.
* **Skip Lines**: Enter the number of lines in the input data to be skipped before the Snap starts parsing.

**Read Excel File**

* **File**: Enter URL for a regular file. It should start with a file protocol.

**Read JSON File**

* **File**: Enter URL for a regular file. It should start with a file protocol.

**Read XML File**

* **File**: Enter URL for a regular file. It should start with a file protocol.

Use the **Filter Data** option to filter the incoming data uploaded by the source endpoint. Once a filter is applied, you can view it in the **Data Wrangler** and further edit the filter condition.
