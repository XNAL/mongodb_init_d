# MongoDB init.d script


## Installing
Copy the mongodb file to your /etc/init.d folder

chmod +x /etc/init.d/mongodb


## Start Mongo at boot

update-rc.d mongodb defaults

### Quick start script
curl https://github.com/nerdyworm/mongodb_init_d/raw/master/mongodb > mongodb
chmod +x mongodb
sudo mv mongodb /etc/init.d/mongodb
sudo update-rc.d mongodb defaults
sudo /etc/init.d/mongodb start
