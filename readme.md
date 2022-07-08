# GOSSIP
## A Microservice Based End-To-End Encrypted Chat Application.

A chat system that provide high awailability and scalibility. It garantees that the msg will be delivered to the target atleast once. It achieve the garantee of delivering of message by persisting the message in the database and once the data is reached to the target, the target will send the achnowledgement and the message will be removed from the database. Every chat message that is send from user to another is being encrypted by AES symmetric
encryption algorithm. A unique key is being shared between users using RSA asymmetric encryption algorithm before they starts chatting.

It uses websockets for real-time communication between user and servers. It also uses RestAPI for some request-response kind of stuffs. It uses rabbitMQ for communication between microservices. We achieve it in way that every service that is running hase it own channel/queue in rabbitMQ through which it communicate with other.

## Technologies that is being used:
  * <code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/go/go.png"></code> Golang
  * <code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/flutter/flutter.png"></code> Flutter/Dart
  * <code><img height="20" src="https://seeklogo.com/images/R/rabbitmq-logo-25641A76DE-seeklogo.com.png"></code> RabbitMQ
  * <code><img height="20" src="https://toppng.com/uploads/preview/9kib-354x415-unnamed-mongodb-logo-sv-11562860723mgempnmrq3.png"></code> MongoDB
  * <code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/redis/redis.png"></code> Redis
  * <code><img height="20" src="https://seeklogo.com/images/W/websocket-logo-91B815D333-seeklogo.com.png"></code> Websocket
  * <code><img height="20" src="https://uxwing.com/wp-content/themes/uxwing/download/07-web-app-development/rest-api.png"></code> RestAPI
  * <code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/nodejs/nodejs.png"></code> NodeJS
  * <code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/docker/docker.png"></code> Docker
  
  ## Microservice in the architecture:

<p align="left">
  <a href="https://github.com/DenverCoder1/github-readme-streak-stats"><img width="282" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=ShikharY10&repo=gossip-engines&theme=react&bg_color=1F222E&title_color=F85D7F&icon_color=F8D866&hide_border=true&show_icons=false" alt="shiSock"></a>
  <a href="https://github.com/DenverCoder1/readme-typing-svg"><img width="282" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=ShikharY10&repo=gossip-api&hide_border=true&bg_color=1F222E&title_color=F85D7F&icon_color=F8D866&theme=react&show_icons=false" alt="go_shiSock"></a>
  <a href="https://github.com/DenverCoder1/custom-icon-badges"><img width="282" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin?username=ShikharY10&repo=gossip-gateway&theme=react&bg_color=1F222E&title_color=F85D7F&icon_color=F8D866&hide_border=true&show_icons=false" alt="flutter_shiSock"></a>
</p>
