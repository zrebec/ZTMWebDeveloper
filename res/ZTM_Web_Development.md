# The Complete Web Developer in 2020: Zero to Mastery

## Section 1

### Basics

My Discrod buddies:

- @kramdane
- @Lissy

 #js - For all questions javascript
 #dev-resources - Myself and others share interesting articles and tools we find. Great way to stay up to date in the industry
 #alumni - Ask graduates of this course questions
 #womenintech - For the female coders out there
 #job-hunting - Anything related to finding a job as a developer
 #code100 - To join a community of students dedicated to code every day for 100 days. You can join anytime.

## Section 2

### List of undesea cables map

<https://www.submarinecablemap.com/>

### Tracerouting pages

Windows: ```tracert -4 google.com```
Mac/Linux: ```traceroute -4 google.com```

>4 Means force IPv4 addreeses.

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
- 2nd to 4th column is response in miliseconds (3 columns because packed is sending in smaller pieces). You can set maximum timeout by ```-w``` option
- 5th column is reached server (or IP adress) in that hop (step). By switch ```-d``` you can skip resolving hostnames (you will see just IP addresses)

### How we can speed loading web site from far server

- General is minizing the code (like ```.min.css``` versions)
- Hosting the separate scripts on nearer server (like css, javascripts or some parts of web pages)
- Custom mirroing (expensive)
- Using service like clouflare
- Using modern HTML elements like ```<picture>``` for smaller images on smaller devices (usually more than 80% daily internet users using a smartphone for browsing)

### Epilogue

The author of ZTM Web Develomnet (Andrei Neagoie) was inspired by this article: <https://zerotomastery.io/blog/learn-to-code-in-2020-get-hired-and-have-fun-along-the-way/>
Web developer monthly blog: <https://zerotomastery.io/blog/?tag=WDM>

## Section 3
