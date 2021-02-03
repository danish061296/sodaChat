# sodaChat
SodaChat is a full-stack app using ReactJS, NodeJS, and Express for frontend and JavaMaven, Maven Spark, WebSocket and MongoDB for backend.
It features a full login and auth system to sign in or create accounts, live messaging, and a like button. It's deployed on an AWS EC2 instance, hosted on a domain from Google Domains, and SSL certified with LetsEncrypt.

# domain link
https://sodachat.net/

**best viewed on laptops/desktops.**

--- 

# Contributors
Danish Siddiqui, Rinay Kumar, Ronald Lee, Michael Morales, Girish Rawat, and Jose.

---

# Backend Structure (Uses DTO and DAO design pattern)

![](/frontend/src/videos/SodaChatImage.png)

# App live demo

![](/frontend/src/videos/ui-demo.gif)

# local installation

open backend folder in an ide such as intellij idea and build/run server main

start local mongodb service

cd into frontend folder in terminal and install node modules
npm i

run frontend servers with pm2

pm2 start server.js wsServer.js

now running on localhost
