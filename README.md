Jegarn
======

A high performance chat system, based on swoole, redis and msgpack.
Integrated authorization, chat, groupchat, chatroom and offline storage.

And Client-SDKs for iOS, Android, JS, and PHP are provided.

Website: [https://jegarn.com](https://jegarn.com)




Requirements
------

* PHP 5.3.10 or newer
* Swoole 1.7.20 or newer
* Msgpack 0.5.7
* Redis 2.8.22 or newer




Installation
------


	wget http://pecl.php.net/get/swoole-1.7.20.tgz
	tar -zvxf swoole-1.7.20.tgz 
	cd swoole-1.7.20
	phpize
	./configure --enable-openssl
	make && make install
	echo "extension=swoole.so" > /etc/php.d/swoole.ini
	
	pecl install msgpack
	yum -y install redis




Tutorial
------

start a tcp server

	$ php server.php 192.168.1.2 9501

start a websocket server
	
	$ php webserver.php 192.168.1.2 9503




Contribution
------

Thank you very much because of your contribution, and I believe we can make jegarn better.
Some ways available:

* contribute your code via Pull Request
* write down your issues
* make the Wiki complete




License
------

[Apache License Version 2.0](./LICENSE)



