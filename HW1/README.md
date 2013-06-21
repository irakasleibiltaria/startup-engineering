### Homework 1 - Web Services and Basic SSJS

####HW1 Quiz: Github, Heroku, and AWS

``` bash
Execute these commands on your EC2 instance.
Note that -qO- is not -q0-. O is the English letter, 0 is the number zero.

1) Install heroku and git
$ sudo apt-get install -y git-core
$ wget -qO- https://toolbelt.heroku.com/install-ubuntu.sh | sh
$ which git
$ which heroku

2) Login and set up your SSH keys
$ heroku login
Note: the next two steps are not necessary
$ ssh-keygen -t rsa
$ heroku keys:add

3) Clone a sample repo and push to heroku
$ git clone https://github.com/heroku/node-js-sample.git
$ cd node-js-sample
$ heroku create
$ git push heroku master

```

Heroku example:

http://thawing-headland-3276.herokuapp.com

####HW1 Programming: Basic Server-Side Javascript with node.js

Install node.js
```bash
sudo apt-get update
sudo apt-get install python-software-properties python g++ make
sudo add-apt-repository ppa:chris-lea/node.js
sudo apt-get update
sudo apt-get install nodejs
```

