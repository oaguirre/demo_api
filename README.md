# demo_api
Demo API

# Installation
```
sudo apt update
sudo apt install nodejs
sudo apt install mongo
sudo apt-get install -y mongodb
sudo apt install git
git clone https://github.com/oaguirre/demo_api.git
sudo apt install pm2
npm install -g pm2
sudo npm install -g pm2
cd demo_api/
npm install
pm2 start server.js
pm2 save
sudo service mongodb start
pm2 startup
sudo env PATH=$PATH:/usr/bin /usr/local/lib/node_modules/pm2/bin/pm2 startup systemd -u ubuntu --hp /home/ubuntu
```   

