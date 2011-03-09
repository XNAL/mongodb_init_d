# MongoDB init.d script

A basic mongodb init.d script. Provides start|stop|restart
functionality.

### Quick start script
  
  curl https://github.com/nerdyworm/mongodb_init_d/raw/master/mongodb > mongodb
  chmod +x mongodb
  sudo mv mongodb /etc/init.d/mongodb
  sudo update-rc.d mongodb defaults
  sudo /etc/init.d/mongodb start
