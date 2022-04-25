# S3 File Writer overview

The S3 File Writer enables you to read a binary data stream from an input view and write it to an S3 file destination. This endpoint produces a binary data stream at the output.



## Add Account

You can select a preconfigured account from the dropdown or click **Add Account** to configure your existing account. This is not required to configure this Flow.

## Select your data collection type

Select the **Data Collection Type** of your data source for this Flow.

You can also select any one of the available data collection types to start your Flow and provide the following information:

* **Write CSV File**
  * **File name**: Enter the URL for the S3 file. The file name must start with `s3:///`.&#x20;
  * **Delimiter**: Enter the delimiter character to be used as a delimiter in parsing the CSV data.
* **Write Excel File**
  * **File name**: Enter the URL for the S3 file, from where the binary data is to be read. The file name must start with `s3:///`
* **Write JSON File**
  * **File name**: Enter the URL for the S3 file, from where the binary data is to be read. The file name must start with `s3:///`.&#x20;
  * **Derive schema from a sample size of**: Select the size of the number of initial input documents to be used when deriving the schema to be added to the binary output header.
* **Write XML File**
  * **File name**: Enter the URL for the S3 file, from where the binary data is to be read. The file name must start with `s3:///`.&#x20;
  * **Output character-set**: Enter The character set in which the input XML data is encoded.

**File action**: For each of the above data collection types, select any of the following actions if the specified file already exists.&#x20;

* _Overwrite:_  The Flow overwrites the existing file.
* _Append:_ _Append_ is supported for file, FTP, FTPS and SFTP protocols only.
* _Ignore:_ If _Ignore_ is selected, it writes the status and file name to its output view.
* _Error:_ If _Error_ is selected, the error is displayed in the Run Log.

Use the **Map Data** option to apply the mapping between fields uploaded by the source endpoint to the same of the target endpoint.

Click **Save and continue**.
