# INSTALL NODE

apt install curl
curl -sL https://deb.nodesource.com/setup_13.x -o nodesource_setup.sh
nodesource_setup.sh
bash nodesource_setup.sh
apt-get install nodejs
apt-get install build-essential

# INSTALL GIT

apt install git-all

# INSTALL PM2

npm i -g pm2
pm2 start app.js -n APP_NAME -i 3
pm2 startup systemd
pm2 save
