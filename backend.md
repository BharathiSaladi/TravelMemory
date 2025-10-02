Connect to backend ec2 instance
install git
<img width="602" height="221" alt="image" src="https://github.com/user-attachments/assets/66ddbf60-2850-48fc-bcb1-a31cd80f4721" />
sudo yum install git

cloning repository
# clone git https://github.com/BharathiSaladi/TravelMemory.git
<img width="602" height="112" alt="image" src="https://github.com/user-attachments/assets/c365a588-3cf3-431c-85c7-a05d91c15a0e" />

install nginx
# sudo yum install nginx

install nodejs
# sudo yum install nodejs
install dependencies
# sudo npm install
set up reverse proxy
# server {

    listen 80;

    server_name backend_ip_address;

    location / {

        proxy_pass http://localhost:3000;

    }

}
create a .env file and give MONGO_URI and PORT details


run index.js file to start the backend
navigate to /TravelMemory/backend and create a .env file and give MONGO_URI and PORT details
index.js – backend server file, run this file to start backend server
sudo node index.js
