:material-aws:

## Logs


=== "CloudTrail"
API Calls.

* JSON format
* Stored for 90 days (management events by default)
* S3 bucket configuration available

Trails.

* Read/write events
* Management/data/insight events
* Saved to a specified bucket every 5 minutes
* Optional prefix for all stored logs
* Not real time - within 15 minutes
* 5 trail limit per account per region

Management Events - default events, describe api calls to AWS services such as create, describe, update, list, and delete.

Data Events - Data Plane operations. API actions on S3 objects, can also track Lambda functions. Really noisy

Insight Events - collect Write Management Events


=== "VPC Flow Logs"
    
## CloudWatch
### CloudWatch Logs
    
### Fields

=== "Important Fields for investigation"

    1. TBD



## Resources
* https://traildiscover.cloud/
* 