# Learning_Kafka
I'm learning the Basics of Kafka Step by Step


To start Kafka up on my local machine I must run:
# cd to my kafka folder in my case its in:
cd ~/Downloads/kafka_2.13-3.8.0
# start the Kafka server
bin/kafka-server-start.sh config/kraft/server.properties

# For running it in the background and closing the terminal
bin/kafka-server-start.sh config/kraft/server.properties &

To terminate Kafka up on my local machine I must run:
# in the terminal run
ps aux | grep kafka
# use this to kill the first process ID found in the preivous line example: kill 58668
kill ###
# Alternativly you can close the terminal window it is running on
