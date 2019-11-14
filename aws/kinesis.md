# Amazon Kinesis


### Data schemas 

* Amazon Kinesis Analytics can now discover data schemas from sample S3 objects, Posted On: Oct 4, 2017
https://aws.amazon.com/about-aws/whats-new/2017/10/amazon-kinesis-analytics-can-now-discover-data-schemas-from-sample-s3-objects/


*How does Kinesis support Avro?*

Separately, writing lots of little Avro files, each with their own schema, for "gluing records together" in Kinesis is certainly not a very good use of storage space, so I think the Kinesis model combined with Avro isn't the right choice here.
https://stackoverflow.com/questions/50263992/how-does-kinesis-support-avro