###HW3 Programming: Your First Crowdfunding Site: Instructions
https://class.coursera.org/startup-001/assignment/view?assignment_id=8

https://docs.google.com/file/d/0B3GawKz4dDR7bU1mTlhGaHZ0Qlk/edit?usp=sharing

```bash
$ git clone https://github.com/heroku/node-js-sample.git
$ mv node-js-sample bitstarter
$ cd bitstarter
$ git config --global user.name "irakasleibiltaria"
$ git config --global user.email "irakasleibiltaria@gmail.com"

# add a new repository in github named bitstarter and then:
$ git remote rm origin
$ git remote add origin https://github.com/irakasleibiltaria/bitstarter.git
$ git push -u origin master

# edit the web.js file
$ vim web.js
$ git add web.js
$ git commit -m "update"
# to github
$ git push origin master
# install heroku
$ wget -qO- https://toolbelt.heroku.com/install-ubuntu.sh | sh
# to heroku
$ heroku create #this must be done only once
$ git push heroku master

# create index.html ...
$ vim index.html
$ git add index.html
...
```
bitstarter repository:
https://github.com/irakasleibiltaria/bitstarter

Solution:

https://github.com/irakasleibiltaria/bitstarter/tree/b4ba5139ace83e67ef6590d4f4c37fefea90d1d4
