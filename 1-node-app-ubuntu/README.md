1  apt-get update
2  apt install curl -y
3  curl -sL https://deb.nodesource.com/setup_10.x | bash
4  apt install nodejs -y
6 cd opt
9 mkdir node-app
10 cd node-app/
11 echo 'console.log("nodejsapp from ubuntu..");' > index.js
14 node imdex.js
