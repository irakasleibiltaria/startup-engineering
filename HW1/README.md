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

----------------


#####Part 1
In part 1, write a node.js script that writes the output "A startup is a business built to grow rapidly.\n" to a file. Run this script on an EC2 t1.micro instance as described in Lecture 2. To make this incredibly easy for you, here is some sample code that you can modify.

#####Part 2
In part 2, write a node.js script that writes the first 100 prime numbers to a file, with each prime separated by a comma. Remember that the first prime number is 2, and use a function that tests for primality. Here is what the file would look like for the first four prime numbers:
2,3,5,7
There are many ways to do this problem. You may want to look at the methods in the Javascript Math object, especially ceil, floor, and sqrt. You will also probably want to look at the Array object's length and push methods. 
