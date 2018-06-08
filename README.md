# log4j-kinesis-endpoint-demo
Simple POC to test the Kinesis Log4j appender with an endpoint other than the default Kinesis endpoint (in my case a Kinesis endpoint within a VPC not open to the public).

Update log4j.properties with the stream and and endpoint you want to post to.

<code>
log4j.appender.KINESIS.streamName=testStream
  
log4j.appender.KINESIS.endpoint=test.kinesis.us-east-1.vpce.amazonaws.com
 </code>
