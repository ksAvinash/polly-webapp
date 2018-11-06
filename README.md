# polly-webapp
The aws serverless web-app to convert text to audio using amazon polly service
Domain Name: http://app.polly.avinashworks.com 

Technologies used : 
1. route53 to route traffic to static website 
2. static website hosted in ap-south-1 region 
3. 3 aws lambda functions performing various tasks 
4. DynamoDB to maintain the states of audio messages (PROCESSING|COMPLETED)
5. s3 bucket to save the converted audio files 
6. Amazon polly service

