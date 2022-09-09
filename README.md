# AWS S3 Walkthrough

•	What is it? 

Object storage is offered by Amazon S3 (Simple Storage Service), which was created for the purpose of storing and retrieving any quantity of data or information from anywhere online. It offers this storage capability through a convenient web services interface. It is useful because it has been known to deliver 99.999999999 percent durability and 99.99 percent availability of items while being built for developers to make web-scale computing easier. Additionally, it can hold data large files of up to 5 terabytes in size in the storage buckets. It offers “pay as you go” payment schemas so the user only pays for the S3 services used on the cloud.

•	What does it do? 

AWS S3 is known to provide features like easy scalability, enhanced security and performance, and high availability of data on the cloud from anywhere in the word. These features can be utilized by organizations of any size in any geographic location without worrying about physical on premises servers. Users can store data in a variety of "storage classes" using S3. These categories are based on how frequently and quickly users need to access the data files on S3 buckets. Businesses only pay AWS for the resources they use on S3(pay as you go); there are no overage or hidden fees involved. In order effortlessly meet the shifting needs of a business, users can easily scale their storage resources just by the click of a few buttons. S3 has a reputation to deliver 99.99 percent availability of data items stored in the S3 buckets. This means that there are no downtimes, and a business can work efficiently while depending completely on the cloud service for data storage.

•	How does it work? 

Every single object/folder in S3 is stored in a container called as an S3 bucket. Each object stored in this bucket consists of 3 parts: Data	, Key (the name associated with the data), and metadata. Every time data is added to the S3 bucket, a unique version ID is created internally by AWS S3 and is allocated to the object. Firstly, a bucket is created by a user. The user will define the zone in which this bucket will be deployed when it is built. The user will then choose the type of S3 storage class to be utilized for those specific objects later, when files are uploaded to the bucket. Users may then specify bucket features like bucket policy, lifecycle policies, version control, etc. The data on an S3 bucket is highly secured. This data is protected by methods like data encryption, versioning, cross-region acceleration, and transfer acceleration. All the objects in the bucket can be managed with the AWS management console.

•	Why do we need it? 

There are many reasons why an organization needs/should consider using AWS S3 instead on an on-premises storage system. 
Data durability: S3 supports data durability of 99.999999999% (11 9s). Similarly, if you maintained 10,000,000 data objects in Amazon S3, you would lose just one object once every 10,000 years. 
Data availability: Every object that is uploaded to S3 will be automatically duplicated and stored on several servers. This ensures comprehensive data availability when you need it while safeguarding your data from mistakes, failures, and attacks.
Security: S3 provides excellent security thanks to its outstanding array of access management tools and encryption technologies.
Flexibility: S3 is excellent for a variety of tasks, including data backup, disaster recovery, software distribution, data archiving, website hosting, mobile applications, Internet of Things devices, and much more.
Simplified Data transfer: Data transmission is straightforward on S3, so you don't need to be an IT pro to utilize it. The focus of the service is on use and simplicity.

•	Use case? 

AWS S3 has many use cases. Below are a few real world use cases:
Cost optimization: Due to the infinitely expandable and accessible resources that cloud computing offers, more firms are choosing to host their data there. It's important to maximize the cloud utilization since the costs associated with data access and storage mount up quickly. By segregating frequently used data from data that is viewed less frequently, S3 enables businesses to save expenses. Less expensive yet always accessible data levels are available for the data. Without sacrificing speed, users may lower your cloud storage expenses by keeping cold data in the Infrequent access section. 
Workload management and data availability: Intelligent Tiering performs task of segregation automatically rather than requiring users to choose which data belongs on the Infrequent Access and Archive Tiers as you would do with strict Lifecycle Policies. For example, one will receive different requests for exam data when you are constructing a school database. For a sizable chunk of the academic year, this data will be kept in the Infrequent access tier. There will be a huge number of requests to access the test database when the exam season gets underway. When no access requests are received for a month, this data is then transferred from the Frequently access tier to the Infrequent access tire, where it will remain available.
Attached is a link of a few example organizations that chose S3 for their data management:
https://aws.amazon.com/s3/customers/ 

