# [TEAM_ALANBR](t.me/TEAM_ALANBR)
# BEST SOURCE ON TELEGRAM


# install:

---------------------------------------------------------

 لتنصيب :-
 
cd $home

sudo apt-get install libreadline6 -y

sudo apt-get update

sudo apt-get dist-upgrade -y

sudo apt-get upgrade -y

sudo apt-get install git -y

sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev make unzip git redis-server autoconf g++ libjansson-dev libpython-dev expat libexpat1-dev -y

sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev make unzip git redis-server autoconf g++ libjansson-dev libpython-dev expat libexpat1-dev ppa-purge python3-pip python3-dev -y

--------------------------------------------------------------------

cd $home

git clone https://github.com/storevpsnet/TEAM_ALANBR.git

----------------------------------------------------------------

cd TEAM_ALANBR

sudo apt-get install axel

axel http://luarocks.org/releases/luarocks-2.2.2.tar.gz

tar zxpf luarocks-2.2.2.tar.gz

cd luarocks-2.2.2

	./configure

	make build
	
	make install

	sudo make bootstrap

	sudo luarocks install luasec

	sudo luarocks install luasocket

	sudo luarocks install redis-lua

	sudo luarocks install lua-term

	sudo luarocks install serpent

	sudo luarocks install dkjson

	sudo luarocks install Lua-cURL

	sudo apt-get install libnotify-dev -y


--------------------------------------------------------------------


cd $home

cd TEAM_ALANBR

chmod 777 launch.sh

chmod 777 cli.lua

chmod 777 tg

./launch.sh install


---------------------------------------------------------------------


killall screen

cd TEAM_ALANBR

screen ./launch.sh
