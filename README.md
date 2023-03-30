# CRYPT-DAC
This Project is Describe about CRYPT-DAC .

IMPLEMENTATION


    1.	Data Owner
In this module, the data owner uploads their data with its chunks in the cloud server. For the security purpose the data owner encrypts the data file’s chunks and then store in the cloud. The data owner can change the policy over data files by updating the expiration time. The Data owner can have capable of manipulating the encrypted data file. And the data owner can set the access privilege to the encrypted data file. 
Dynamic Operation 
Upload:  is the operation to encrypt and upload the file
Delete: Is the operation to delete a corresponding data owner file in the cloud.
Verify: Verifying the data whether it is safe or not in the cloud.

     2.	Cloud Server 
The cloud service provider manages a cloud to provide data storage service. Data owners encrypt their data files and store them in the cloud for sharing with data consumers. To access the shared data files, data consumers download encrypted data files of their interest from the cloud and then decrypt them. The end user request will be processes based on the queue.
 

     3. End User
    The Cloud User who has a large amount of data to be stored in multiple clouds   and   have the permissions to access and manipulate stored data. The end user sends the request for corresponding file request and it will be processed in the cloud based on the queue and response to the end user.

