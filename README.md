## Basic Backbone project with Vagrant setup

### Setup develompment environment

~~~
~$ vagrant up
~~~

~~~
~$ vagrant ssh
~~~

* This is required(will be automatically installed on provision soon)

~~~
~$ sudo apt-get install libfontconfig1
~~~

~~~
~$ sudo npm install yo generator-backbone generator-mocha grunt-cli bower -g
~~~

~~~
~$ cd /vagrant && npm install && bower install
~~~

~~~
~$ cd /vagrant/test && bower install
~~~
