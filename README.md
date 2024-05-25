# Processing-for-DoorDash-Delivery-Data

This assignment involves creating an automated AWS-based solution for processing daily delivery data from DoorDash. JSON files containing delivery records will be uploaded to an Amazon S3 bucket. An AWS Lambda function, triggered by the file upload, will filter the records based on delivery status and save the filtered data to another S3 bucket. Notifications regarding the processing outcome will be sent via Amazon SNS.

## Steps
1. Create A sample JSON file named 2024-03-09-raw_input.json with 10 delivery records, including different statuses like cancelled, delivered, and order placed.
   ![image](https://github.com/RITS98/Processing-for-DoorDash-Delivery-Data/assets/51791113/fd646c26-ae75-47e9-bc59-d92b741f1563)

2. Create two S3 buckets: doordash-landing-zn for incoming raw files and doordash-target-zn for processed files.
   ![image](https://github.com/RITS98/Processing-for-DoorDash-Delivery-Data/assets/51791113/647f83df-e303-4676-a56d-caf7b3d4e979)

   ![image](https://github.com/RITS98/Processing-for-DoorDash-Delivery-Data/assets/51791113/60aa8456-3013-4e43-ba2b-422209a93894)

3. Create an SNS topic for sending processing notifications.
   ![image](https://github.com/RITS98/Processing-for-DoorDash-Delivery-Data/assets/51791113/71281c7b-bafe-4085-9abc-80b3967e6f05)

4. Create a Lambda
   ![image](https://github.com/RITS98/Processing-for-DoorDash-Delivery-Data/assets/51791113/95afef64-fe9b-4ad7-b90d-48f8eb187dc2)

5. Create IAM Role for Lambda
   ![image](https://github.com/RITS98/Processing-for-DoorDash-Delivery-Data/assets/51791113/9eae40f6-d1b3-46f8-8c3e-28af50efe325)

6. 


