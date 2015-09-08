# jsmq
A reliable standalone message queue for the browser (or Node). This module is built to decouple modules within a single application, but it ca connect to other proper MQ channels and forward messages from inside your application to another server altogether.

Decouple frontend modules, using a reliable pub/sub or push/pull pattern.

This module will use optional and alternative implementations like jQuery if available. 

Features:

 - broadcast or unicast messages
 - channels and subchannels
 - priority messages
 - optional delivery ack
 - socket.io transcoder to publish to and subscribe to messages from the server
 - AMD/commonJS implementation
 - connects to RabbitMQ, MQTT, SQS etc
 - broad browser support
 - works as-is, but can be improved when in conjunction with jQuery, or other
