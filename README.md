# Stream Logs from cloud watch to Datadog using AWS Kinesis Firehouse

This module has ability to create following resources:
- AWS Kinesis Firehouse
- AWS IAM Role
- AWS S3 Bucket [ To store failure messages ]
- AWS CloudWatch Log Group
- Subscription of Cloud Watch Log Group to Kinesis Firehouse


You will need an API Key from Datadog to send Logs:


Example:
```
module "datadog_log_stream" {
    source = "git@github.com:devops-made-easy/terraform-aws-datadog-kinesis-firehouse.git"
    version = 0.0.1
}
```





----
## Share the Love

Like this project? Please give it a ★ on  [our GitHub!](https://github.com/devops-made-easy/terraform-aws-datadog-kinesis-firehouse)(it helps us a lot)