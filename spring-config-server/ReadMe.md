####Tutorial Document 
https://tech.asimio.net/2017/02/02/Refreshable-Configuration-using-Spring-Cloud-Config-Server-Spring-Cloud-Bus-RabbitMQ-and-Git.html

#Install Rabbit Mq 
# To start the service:
/sbin/service rabbitmq-server start

# To stop the service:
/sbin/service rabbitmq-server stop

# To restart the service:
/sbin/service rabbitmq-server restart

# To check the status:
/sbin/service rabbitmq-server status

#ngrok gives the flexibility to expose any local / private server port as Public Domain
#Installation and guide lines are avilable in below link
https://dashboard.ngrok.com/get-started

#to start ngrok and expose port 8888 as publi domain
./ngrok http 8888

#To monitor all the events on the exposed ports
http://localhost:4040/inspect/