## This serverless file would do these steps:
Creates an SQS queue with the name based on the parameter supplied
Assigns a queue policy allowing messages to be sent to the queue
Creates an IAM Role with permissions to allow API Gateway to send messages to SQS
Creates a REST API endpoint with POST method, configured with the SQS integration

Use Postman test example for the call. 

#### Note that in Postman test, Content-Type in Headers should be "application/json".