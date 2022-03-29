# Rabbitmq
In this little project I have experimented with the basics of rabbitmq:
1) Created a publisher/sender file where I establish a connection with the rabbitmq server, create a channel, assert a queue and send message to the queue.
2) Created a receiver file where I establish a connection (different tcp connection than the publisher file) with the server, create a channel, assert the queue and consume the message with acknowledgment (when certain conditions are met) so that once the message has been consumed it is removed from the queue.
