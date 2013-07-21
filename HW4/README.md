###Homework 4

https://class.coursera.org/startup-001/assignment/view?assignment_id=10

https://docs.google.com/file/d/0B3GawKz4dDR7d1VKRkN1ZVVGX1U/edit?usp=sharing

####Set up an EC2 Instance which allows instant previews:

* Open 8080 port in AWS EC2 Instance.
* Once your EC2 instances is once again provisioned and available, edit your web.js file to configure it to port 8080 and then run node web.js.
```
var port = process.env.PORT || 8080;
```
* To preview how your website will look with a mobile client is by installing Chrome's User [Agent Switcher](https://chrome.google.com/webstore/detail/user-agent-switcher-for-c/djflhoibgkdhkhhcedjiklpkjnoahfmg?hl=en-US) and its [Resolution Test](https://chrome.google.com/webstore/detail/resolution-test/idhfcdbheobinplaamokffboaccidbal?hl=en) tools. 

####Part 1: Add CSS styles and enable responsive design via Twitter Bootstrap

https://spark-public.s3.amazonaws.com/startup/images/part1-instructions.pdf

https://docs.google.com/file/d/0B3GawKz4dDR7WXpLMi1OblhHeVU/edit?usp=sharing

bootstrap. font-awesome. social-buttons:
* http://twitter.github.io/bootstrap/scaffolding.html#responsive
* http://blogs.endjin.com/2013/04/tips-forimplementing-responsive-designs-usingbootstrap
* http://stackoverflow.com/a/12270322
* http://noizwaves.github.io/bootstrap-social-buttons/
```$ wget https://raw.github.com/noizwaves/bootstrap-social-buttons/master/social-buttons.css```
* http://fortawesome.github.io/Font-Awesome/get-started/

```
<link href="//netdna.bootstrapcdn.com/twitter-bootstrap/2.3.2/css/bootstrap-combined.no-icons.min.css" rel="stylesheet">
<link href="//netdna.bootstrapcdn.com/font-awesome/3.2.1/css/font-awesome.css" rel="stylesheet">
```
* http://www.bootstrapcdn.com/

fonts:
* http://www.google.com/fonts
* http://www.google.com/fonts/specimen/Ubuntu
* http://www.google.com/fonts#QuickUsePlace:quickUse/Family:
* http://www.google.com/fonts#QuickUsePlace:quickUse/Family:

```
<link href='http://fonts.googleapis.com/css?family=Ubuntu:300,400,500,700,300italic,400italic,500italic,700italic' rel='stylesheet' type='text/css'>
<link href='http://fonts.googleapis.com/css?family=Open+Sans:300italic,400italic,600italic,700italic,800italic,400,300,600,700,800' rel='stylesheet' type='text/css'>
```

