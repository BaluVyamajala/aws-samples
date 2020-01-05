# aws-samples
### streaming_data_cf.yaml
##### Create CloudFormation stack in AWS console and run the test Lambda with below sample JSON to publish events to Kinesis 
```
{
  "event": {
    "staffName": "Balu Vyamajala",
    "staffId": 4,
    "emailId": "balu@initechglobal.com",
    "status": "Active"
  },
  "metadata": {
    "appName": "WebApp",
    "eventType": "CREATE_STAFF",
    "sourceTimestamp": "2020-01-05T01:05:00.000Z"
  }
}
```
