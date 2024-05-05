## aws-c ds-eda-lab
## eda-assignment2  - Distributed Systems.


__Name:__ Maxamed Maxamed  

__YouTube Demo link__ - --------

__GitHub link__: https://github.com/Maxamed/eda-assignment2 


__Description__: This is a distributed systems assignment . The assignment contains 3 phases. The assignment is divided into 3 parts. 


#### One problem that I faced is that the email is not recieved by the user but instead they get a confirmation that the upload is successful is not working . Another problem is that the rejection email is not being sent to the user. and the update and delete emails are not being sent to the user. and the rest of the code is working fine and uploading the image to the s3 bucket and the table is updated and the image is deleted from the table and the image is deleted from the s3 bucket and the confirmation and rejection emails and delete emails  are not sent to the user. i don't know why this is happening. 

### Phase 1.


+ Confirmation Mailer - Fully implemented. will get not  a email confirm  but that the upload is successful. 
 - Lambda Function: mailer.ts 
+ Rejection Mailer - Fully implemented.
  + Lambda Function: rejectionMailer.ts
+ Process Image - Fully implemented.
  + Lambda Function: processImage.ts

### Phase 2.
+ Confirmation Mailer - Fully implemented. will get not  a email confirm  but that the Confirmation is successful. 
+ Rejection Mailer - Fully implemented.
+ Process Image - Fully implemented.
+ Update Table - Fully implemented.
  + Lambda Function: processUpdate.ts
+ Delete Table - Fully implemented.
  + Lambda Function: processDelete.ts

### Phase 3.
+ Confirmation Mailer - Fully implemented. will not get a email confirm but that the Confirmation is successful. 
+ Rejection Mailer - Fully implemented.
+ Process Image - Fully implemented.
+ Update Table - Fully implemented.
+ Delete Table - Fully implemented.
  + Lambda Function: processDelete.ts
