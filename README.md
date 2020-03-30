# The Complete Web Developer in 2020: Zero to Mastery

## Section 1: Introduction

### Basics

My Discord buddies:

- @kramdane
- @Lissy

 #js - For all questions javascript
 #dev-resources - Myself and others share interesting articles and tools we find. Great way to stay up to date in the industry
 #alumni - Ask graduates of this course questions
 #womenintech - For the female coders out there
 #job-hunting - Anything related to finding a job as a developer
 #code100 - To join a community of students dedicated to code every day for 100 days. You can join anytime.

## Section 2: How The Internet Works

### List of undersea cables map

<https://www.submarinecablemap.com/>

### Tracerouting pages

Windows: ```tracert -4 google.com```
Mac/Linux: ```traceroute -4 google.com```

>4 Means force IPv4 addresses.

### How to read it

```console
1     7 ms     2 ms     3 ms  csp1.zte.com.cn [192.168.1.1]
2     *        *        *     Request timed out.
3     *        *        *     Request timed out.
4    44 ms    39 ms    40 ms  74.125.50.156
5    32 ms    35 ms    33 ms  108.170.245.49
6    38 ms    54 ms    39 ms  108.170.236.229
7    48 ms    62 ms    31 ms  prg03s01-in-f14.1e100.net [216.58.201.78]
```

- 1st column means hop (you can set maximum hops by ```-h``` switch
- 2nd to 4th column is response in milliseconds (3 columns because packed is sending in smaller pieces). You can set maximum timeout by ```-w``` option
- 5th column is reached server (or IP address) in that hop (step). By switch ```-d``` you can skip resolving hostname (you will see just IP addresses)

### How we can speed loading web site from far server

- General is minimize the code (like ```.min.css``` versions)
- Hosting the separate scripts on nearer server (like css, javascript or some parts of web pages)
- Custom mirroring (expensive)
- Using service like cloudflare
- Using modern HTML elements like ```<picture>``` for smaller images on smaller devices (usually more than 80% daily internet users using a smartphone for browsing)

### Epilogue

The author of ZTM Web Development (Andrei Neagoie) was inspired by this article: <https://zerotomastery.io/blog/learn-to-code-in-2020-get-hired-and-have-fun-along-the-way/>
Web developer monthly blog: <https://zerotomastery.io/blog/?tag=WDM>

## Section 3: History Of The Web

### WWW vs Internet

Author of World Wide Web: **Sir Tim Berners-Lee** in 1989

The good history lesson is on <https://www.vox.com/a/internet-maps>

In the past every internet page (every computer) has own IP address and you must known the IP address.
Sir **Tim Berners-Lee** arrives with World Wide Web (www) which means that whole page works under www roof.
He created the first web page also (server and www page)

>The first website was in 1991 and the copy of that is on <info.cern.ch/hypertext/WWW/TheProject.html>

### HTML, CSS, Javascript

- HTML: Structure and data of web page (text)
- CSS: How web page will look
- Javascript: Advanced and interactive functionality of web page

### Developer Fundamentals

We have many web browsers and devices (like notebooks, tablets or mobile phones) today and each of one must process HTML, CSS and Javascript files
to desired result. That's the reason why are some basics fundamentals are very important of web development.
The absolute elementary basic is the testing your website on each device. Web browsers can helps with it too because they are offers simulating of
mobile devices, different screen resolutions, etc...

### Developer History

In the past usually exists just front-end developer and full-stack backend developer called LAMP developer too. LAMP is shortcut for Linux, Apache, MySQL, PHP
which was most used backend technologies in past. That means the backend developer must have knowledge of Database and backend website logic too.
The programmer which had knowledge of LAMP, Javascript, CSS and HTML was Full-Stack developer.
But today web sites is too complicated for one-man show.
For example in fronted we usually mixing Javascript + React
or on backend we have Java with many frameworks or Node.js
which like Javascript on server side and many
databases like PostgreSQL, Oracle, Microsoft SQL, MySQL, etc...
