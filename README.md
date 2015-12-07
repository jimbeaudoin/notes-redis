# notes-redis

### Installation
```sh
sudo apt-get install build-essential
sudo apt-get install tcl8.5
wget http://download.redis.io/releases/redis-stable.tar.gz
tar -xzf redis-stable.tar.gz
cd redis-stable
make
make test
sudo make install
cd utils
sudo ./install_server.sh
```

### Start/Stop/Access Server
```sh
sudo service redis_6379 start
sudo service redis_6379 stop
redis-cli
```

--
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/80x15.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">notes-redis</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://jimmy-beaudoin.com" property="cc:attributionName" rel="cc:attributionURL">Jimmy Beaudoin</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
