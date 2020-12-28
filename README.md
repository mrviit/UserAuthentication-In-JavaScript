# UserAuthentication-In-JavaScript
https://medium.com/better-programming/build-a-login-system-in-node-js-f1ba2abd19a

wget -qO - https://www.mongodb.org/static/pgp/server-4.4.asc | sudo apt-key add -
echo "deb [ arch=amd64,arm64 ] https://repo.mongodb.org/apt/ubuntu xenial/mongodb-org/4.4 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-4.4.list
sudo apt-get install -y mongodb-org
sudo systemctl start mongod
sudo systemctl status mongod
