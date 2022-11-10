# AWS
Repository to AWS Resources ,learning materials and code snippets



Resources :

1.[Stephane Maarek Udemy Course](https://www.udemy.com/course/aws-certified-developer-associate-dva-c01/learn/lecture/11851550#overview)</li>

2.[Pythoholic Youtube](https://www.youtube.com/c/Pythoholic/videos)</li>



### Simple Storage Service (s3)

Amazon S3 is a web service that lets you store and retrieve data in an object store via API reachable over HTTPS. 

- Object storage service.
- Each object has the below information stored in S3
    - key
    - version id
    - value
    - metadata
    - subresources
    - access control information
- simple key-value store.
- max size of each object is 5 TB.
- No folder/Nested folder structure.
- No limit on the number of objects that can be stored in the bucket.
- Each object has metadata and data stored in the object.
- can store any kind of data
- By default 100 buckets in each account and 1000 by submitting the request
- Once the bucket is created in a specific region that region cannot be changed.

<b>Important Concepts</b>
- Bucket Naming convention
  - Names must be unique across all accounts
  - 3 -63 characters long
  - No IP address
  - Name should not contain upper case or _
  - Name should start with lower case alphabets and number
  - Must follow DNS naming convenstions
- Lifecycle Management
  - Transmission rules
  - Expiration rules
- Bucket Policy
- Data Encryption
- Versioning
- Different storage tiers of S3
- CRR/SRR
- Event Notifications / Event Bridge
- Transfer Acceleration
- Performance
- S3 Select & Glacier Select
- MFA
- CORS
- Access Points

### **Hands-on  Exercises using User Interface**

- [ ]  Create a Bucket
- [ ]  Enable Versioning in the bucket
- [ ]  Transmission policies and Expiration policies
- [ ]  Enable transfer acceleration
- [ ]  Set event notification rules
- [ ]  Data Encryption using all the methods - Server side client encryption
- [ ]  Set a bucket policy
- [ ]  Enable MFA
- [ ]  create a simple quiz to validate s3 bucket names.
- [ ]  Replication of CRR and SRR
- [ ]  Pre-Signed URLs - Create a simple app to download the file and provide a download link to the user.
