# fullstack-hgrail-redis

<h3>How to use the HolyGrail-app:</h3>

 - fork the app
 - cd
 - run cmd:- docker run -d --name myredis  -p 127.0.0.1:6379:6379 redis:4.0.1
 - docker ps (to make sure it's running)
 - check the redis connection by running the cmds 
 - docker exec -it redis01 sh ==>  # redis -cli  ==> 127.0.0.1:6379> ping ==> response will be 'pong'
 - npm i redis@3.0.2
 - run: node index.js
 - app will run on localhost:3000
 
 Next time run the app using latest version of Redis :)

 
 



<footer> License by MIT @2022 </footer>



