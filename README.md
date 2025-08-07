<h1>ETL Development: Connecting to Big Data and Cloud Platforms</h1>


<h2>Overview</h2>
Implemented connections to big data and cloud platforms in Talend to enable seamless integration, extraction, and loading across distributed systems, including Kafka, Cassandra, MongoDB, Amazon S3, and FTP.
<br />


<h2>Key Highlights</h2>

- **Apache Kafka:** Used the `tKafkaConnection` component to connect to the Kafka platform and utilized `tInfiniteLoop` with `tFixedFlowInput` and `tMap` (for string to byte conversion) to output data to Kafka via the tKafkaOutput component.  

- **Apache Cassandra:** Used the `tCassandraConnection` component to connect to the Cassandra platform and `tCassandraInput` to read data. Also utilized `tCassandraOutput` to write data, then closed the connection with `tCassandraClose`.  

- **MongoDB:** Used the `tMongoDBConnection` component to connect to the MongoDB database and `tMongoDBOutput` to write data. Also utilized `tMongoDBInput` to query and filter data, then closed the connection with `tMongoDBClose`.  

- **Amazon S3:** Used the `tS3Connection` component to connect to Amazon S3 and `tS3Put` to upload data to the storage. Also utilized `tS3List` to iterate files in the storage folder and output information to the console, then closed the connection with `tS3Close`.  

- **Google BigQuery:** Used the `tBigQueryOutput` component to write data to Google BigQuery and `tBigQueryInput` to read data from the database.  

- **File Transfer Protocol (FTP):** Used the `tFTPConnection` component to connect to a public FTP test site provided by DLP Test. Utilized `tFTPPut` to upload files and `tFTPFileList` to iterate files and output their information to the console, then closed the connection with `tFTPClose`. 

<h2>Skills </h2>

Talend Open Studio, ETL Development, Big Data Integration, Cloud Integration.

<h2>Documentation:</h2>

<p align="center">
Apache Kafka - Job Designer Workflow <br/>
<img src="https://github.com/user-attachments/assets/960ff58e-fa7e-4701-a752-31e0d7a7ddf7" height="80%" width="80%" alt="Schema Handling"/>
<br />
<br />
Apache Cassandra - Job Designer Workflow  <br/>
<img src="https://github.com/user-attachments/assets/998c17b3-3dc2-46d7-8dcc-a8a28d97b7ca" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
MongoDB - Job Designer Workflow <br/>
<img src="https://github.com/user-attachments/assets/105f1968-74ec-4ee8-bc9b-ca4a3e3afa26" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Amazon S3 - Job Designer Workflow  <br/>
<img src="https://github.com/user-attachments/assets/93151ff9-2d41-4136-9f9b-48d4134ab897" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Google BigQuery - Job Designer Workflow  <br/>
<img src="https://github.com/user-attachments/assets/33335f25-9533-49fc-bd65-8f0917539cf3" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
FTP - Job Designer Workflow  <br/>
<img src="https://github.com/user-attachments/assets/2ed7cb63-44ee-4536-8839-b194eaae56a9" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
