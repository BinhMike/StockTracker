README

PA1 - 

This directory contains sample code for the producer and consumer of Kafka topic.
We use the Linux "top" command in the producer process and send its output to a
Kafka broker. A consumer then pulls the incoming message and prints it.

Producer and consumer processes have hardcoded IP addresses as of now to my
setup but this will need to be modified. It will be better to get these as an argument
on the command line when you invoke the code.

To run the code, in one VM do

           python3 producer.py

In another VM do

           python3 consumer.py

Note that both these VMs must be able to communicate with the Kafka ecosystem.

It is also assumed that Kafka brokers are up and running.