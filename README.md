# Static Website Hosting and Cross-Region Replication

Static website contains web pages with fixed content. Each page is coded in HTML and displays the same information to every visitor.Static sites are the most basic type of website and are the easiest one to create. Hosting a static website is possible in AWS using a product called Amazon S3.

Amazon S3 or  Amazon Simple Storage Service is a core AWS service. It is the default storage service in AWS. It provides a near infinity scalable storage platform accessible from anywhere with a public Internet connection.
It tends to be the default storage location for data ingestion and output for many AWS services. accessing S3 is generally done via APIs, but static website hosting is a feature of Amazon S3 which lets you define http endpoint, set index and error documents
and use S3 like a website.

Accessing S3 is generally done via APIs. Static Website Hosting is a feature of Amazon, which lets you define a HTTP endpoint, set index and error documents and use S3 like a website.
First Create 'Static Website' Using 'Amazon S3 then Enable 'Cross-Region' Replication for 'Disaster Recovery' and Create 'Pre-signed URL' using 'Amazon S3'


1: Create 'Source Bucket'

![2024-03-04 15_18_01-Greenshot](https://github.com/Anshul3vishwakarmma6/Project3/assets/159995520/6116b29a-bac5-44b9-bbbf-9b5e16a4b4eb)

![2024-03-04 15_18_49-Greenshot](https://github.com/Anshul3vishwakarmma6/Project3/assets/159995520/a97188ad-eea6-47d1-b310-8c7226b9b858)


2: Create 'Static Website' 
![2024-03-04 15_27_49-Greenshot](https://github.com/Anshul3vishwakarmma6/Project3/assets/159995520/dc727236-a750-4dd4-8d95-55462af9ec22)


3: Create 'Bucket Policy' for 'Source Bucket'

![2024-03-04 15_53_18-Greenshot](https://github.com/Anshul3vishwakarmma6/Project3/assets/159995520/15f49379-b0b7-4b2c-8dd1-da41e8f8771b)

![2024-03-04 15_43_36-Greenshot](https://github.com/Anshul3vishwakarmma6/Project3/assets/159995520/24337519-a51b-40ea-a9db-3d30e4d80215)

4:  Enable 'Versioning' 

![2024-03-04 15_54_14-Greenshot](https://github.com/Anshul3vishwakarmma6/Project3/assets/159995520/473f146a-79a0-434d-8f27-f8bb7a822a82)

5: Create 'Destination Bucket'

![2024-03-04 15_53_18-Greenshot](https://github.com/Anshul3vishwakarmma6/Project3/assets/159995520/21b40cde-908d-4507-8342-720c5a148fe2)


6:  Create 'Replication Rule'

![2024-03-04 15_36_21-Greenshot](https://github.com/Anshul3vishwakarmma6/Project3/assets/159995520/61cae005-029c-4818-b190-fb633fd8ed15)


7:  Create 'Pre-Signed' URL

![2024-03-04 16_22_57-Greenshot](https://github.com/Anshul3vishwakarmma6/Project3/assets/159995520/130f29c4-e0b1-4d9f-afd4-d8aaf0a045f2)

![2024-03-04 16_28_11-Greenshot](https://github.com/Anshul3vishwakarmma6/Project3/assets/159995520/61762c10-7d5d-441b-bbd1-1d3fdb587dd0)

