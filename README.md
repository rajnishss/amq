## Version

Current Version: **5.9.0**

#To build docker activemq image

sudo docker build -t activemq:5.9.0 -f .docker/amq.dockerfile .

#To run activemq in interactive mode

sudo docker run -p 8161:8161 -p 61616:61616 -t activemq:5.9.0

#To run activemq in backgroup

sudo docker run -p 8161:8161 -p 61616:61616 -t -d activemq:5.9.0
