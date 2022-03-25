# Snaplogic File System Writer Overview

The SnapLogic File System Writer enables you to write any type of data from various source file types such as SLDB, HTTP, S3, SFTP, HDFS, etc, and produces a binary data stream at the output.

Select the **Data Collection Type** from where your data will be sourced to configure this Flow.

## Add Account

You can select a preconfigured account from the dropdown or click **Add Account** to configure your existing account. This is not required to configure this Flow.

## Select your data collection type

You can also choose any one of the available data collection types to start your Flow and provide the following information:

**Write CSV File**

* **File**: Enter URL for a regular file. It should start with a file protocol.
* **File action**: Specify the action to perform if the file already exists. The available options are:
  * _Overwrite_ - If _Overwrite_ is selected, the Flow attempts to write the file without checking for the file's existence for better performance.
  * _Append_ - _Append_ is supported for file, FTP, FTPS and SFTP protocols only.
  * _Ignore_ - If _Ignore_ is selected, it writes the status and file name to its output view.
  * _Error_ - If _Error_ is selected, the error is displayed in the Run Log.
* **Delimiter**: Enter the delimiter character to be used as a delimiter in parsing the CSV data.

**Write Excel File**

* **File**: Enter URL for a regular file. It should start with a file protocol.
* **File action**: Specify the action to perform if the file already exists. The available options are:
  * _Overwrite_ - If _Overwrite_ is selected, the Flow attempts to write the file without checking for the file's existence for better performance.
  * _Append_ - _Append_ is supported for file, FTP, FTPS and SFTP protocols only.
  * _Ignore_ - If _Ignore_ is selected, it writes the status and file name to its output view.
  * _Error_ - If _Error_ is selected, the error is displayed in the Run Log.

**Write JSON File**

* **File**: Enter URL for a regular file. It should start with a file protocol.
* **File action**: Specify the action to perform if the file already exists. The available options are:
  * _Overwrite_ - If _Overwrite_ is selected, the Flow attempts to write the file without checking for the file's existence for better performance.
  * _Append_ - _Append_ is supported for file, FTP, FTPS, and SFTP protocols only.
  * _Ignore_ - If _Ignore_ is selected, it writes the status and file name to its output view.
  * _Error_ - If _Error_ is selected, the error is displayed in the Run Log.

**Write XML File**

* **File**: Enter URL for a regular file. It should start with a file protocol.
* **File action**: Specify the action to perform if the file already exists. The available options are:
  * _Overwrite_ - If _Overwrite_ is selected, the Flow attempts to write the file without checking for the file's existence for better performance.
  * _Append_ - _Append_ is supported for file, FTP, FTPS, and SFTP protocols only.
  * _Ignore_ - If _Ignore_ is selected, it writes the status and file name to its output view.
  * _Error_ - If _Error_ is selected, the error is displayed in the Run Log.
