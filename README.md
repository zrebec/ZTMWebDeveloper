# The Complete Web Developer in 2020: Zero to Mastery

## Section 1: Introduction

### Basics

My Discord buddies:

- @kramdane
- @Lissy

Common channels:

- #js - For all questions javascript
- #dev-resources - Myself and others share interesting articles and tools we find. Great way to stay up to date in the
industry
- #alumni - Ask graduates of this course questions
- #womenintech - For the female coders out there
- #job-hunting - Anything related to finding a job as a developer
- #code100 - To join a community of students dedicated to code every day for 100 days. You can join anytime.

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
- 2nd to 4th column is response in milliseconds (3 columns because packed is sending in smaller pieces). You can set
maximum timeout by ```-w``` option
- 5th column is reached server (or IP address) in that hop (step). By switch ```-d``` you can skip resolving hostname
(you will see just IP addresses)

### How we can speed loading web site from far server

- General is minimize the code (like ```.min.css``` versions)
- Hosting the separate scripts on nearer server (like css, javascript or some
parts of web pages)
- Custom mirroring (expensive)
- Using service like cloudflare
- Using modern HTML elements like ```<picture>``` for smaller images on smaller
devices (usually more than 80% daily internet users using a smartphone for
browsing)

### Epilogue

The author of ZTM Web Development (Andrei Neagoie) was inspired by this article:
<https://zerotomastery.io/blog/learn-to-code-in-2020-get-hired-and-have-fun-along-the-way/>
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

We have many web browsers and devices (like notebooks, tablets or mobile phones) today and each of one must process
HTML, CSS and Javascript files to desired result. That's the reason why are some basics fundamentals are very important
of web development. The absolute elementary basic is the testing your website on each device. Web browsers can helps
with it too because they are offers simulating of mobile devices, different screen resolutions, etc...

### More resources

Link 1: <https://www.youtube.com/watch?v=guvsH5OFizE>

Link 2: <https://www.youtube.com/watch?v=AEaKrq3SpW8>

Link 3: <https://www.youtube.com/watch?v=3QhU9jd03a0>

### Developer History

In the past usually exists just front-end developer and full-stack backend developer called LAMP developer too. LAMP is
shortcut for Linux, Apache, MySQL, PHP which was most used backend technologies in past. That means the backend
developer must have knowledge of Database and backend website logic too. The programmer which had knowledge of LAMP,
Javascript, CSS and HTML was Full-Stack developer. But today web sites is too complicated for one-man show. For example
in fronted we usually mixing Javascript + React or on backend we have Java with many frameworks or Node.js which like
Javascript on server side and many databases like PostgreSQL, Oracle, Microsoft SQL, MySQL, etc...

## Section 4: HTML5

Today we are using ```HTML5``` as default **HypeText** markup language. In the past times we used ```HTML4``` for so
long time or ```XHTML4.01``` which was a HTML mixed as ```XML``` document that means every *tag* must has opening tag
and closing tag to. In the example of basic ```HTML5``` scratch you can see ```<meta>``` tag which has no closing tag.
In ```XHTML4.01``` you shall write ```<meta charset="UTF-8"/>``` which defined opening and close tag in one line.
In ```HTML5``` this is not needed.

### The basic structure of HTML5 document

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>The Complete Web Developer in 2020: Zero to Mastery</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link href="css/style.css" rel="stylesheet">
    </head>
    <body>
        Show your content here!
    </body>
</html>
```

```<!DOCTYPE html>``` defines the this HTML5 document! For example this is very useful for you browser or for *google*
search engine too (you must have very fine page if you want be higher in the google result list)

```<html>``` is basic tag for whole page and one important attribute here is the language of webpage defined as
```lang``` attribute. The english in this case.

```head``` defines header of the document. Here you can set all *properties* for document like title, define character
set ```charset="UTF-8"``` and link the **stylesheet** (CSS) path for the webpage. Tag
```<meta name="viewport" content="width=device-width, initial-scale=1">``` defines the viewport of document and set
**initial-scale** what is useful for mobile devices (otherwise you will have too small fonts on you smartphone).

### Zero To Mastery: Resources

You can find useful resources here: <https://github.com/zero-to-mastery/complete-web-developer-manual>  
Here are captions for video learning: <https://github.com/zero-to-mastery/zero-to-mastery-captions>  
w3schools is very recommended for learning and explain about html tags: <https://www.w3schools.com>  
Alternative for w3schools is **MDN** <https://developer.mozilla.org/en-US>  
Visual Studio Code by **Microsoft** has many plugins which makes this a rich editor: <https://code.visualstudio.com>  

Links where you can ask or find the answer of your questions (it's normally that developer has many question about lot
of things which not understood perfectly)

Try rubber ducking: <https://rubberduckdebugging.com>  
The biggest database of answers for question who developer has: <https://stackoverflow.com>  
Reach out to communities on Discord <https://discordapp.com>

### HTML Tags

A few more things about **HTML** tags.

List for all **HTML5** tags: <https://www.w3schools.com/tags/default.asp>

```<h1>``` using for title of webpage and ```<h2>``` to ```<h6>``` are the subtitles for document.  
```<p>``` is paragraph tag (like a strophe in poetic). It's one logic part of text in your document. This means the
text is indented of another part of your document.

>If you type ```lorem``` in **Visual Studio Code** or **Sublime Text** (probably in more editors too) you get the
first strophe of *lorem ipsum* text (dummy text as replacement of real content). Look here <https://lipsum.com/>.
You can find a many languages for test of your character set for example.

```<b>``` is for **bold text** and ```<i>``` is for italic text 

Example

```html
<p><b>Lorem ipsum</b> is is simply dummy text of the <i>printing</i>...</p>
```

But today is better using ```<strong>``` for **bold text** and ```<em>`` for emphasis text because mobile devices.
So, the right example of code above should be:

```html
<p><strong>Lorem ipsum</strong> is is simply dummy text of the <em>printing</em>...</p>
```

```<ol>``` is ordered list

```html
<ol>
    <li>apple</li>
    <li>banana</li>
    <li>orange</li>
<ol>
```

```<ul>``` is unordered list (without numbers e.g.)

```html
<ul>
    <li>apple</li>
    <li>banana</li>
    <li>orange</li>
<ul>
```

or you can combine it!

```html
<h1>Welcome to our local restaurant</h1>
<p>Local cousine with <em>simple</em> but <strong>quality</strong> meals.</p>

<h2>Our meals with ingredients</h2>
<ol>
    <li>Hot Dog</li>
    <ul>
        <li>Roll</li>
        <li>Ketchup</li>
        <li>Mustard</li>
    </ul>
    <li>Tomato soup</li>
    <ul>
        <li>Bread</li>
        <li>Garlic</li>
        <li>Fresh basil</li>
        <li>Cherry tomatoes</li>
        <li>Virgin olive oil</li>
    </ul>
    <li>Drinks</li>
    <ul>
        <li>Orange juice</li>
        <li>Vanilla Milkshake</li>
        <li>Strawberry Milkshake</li>
    </ul>
</ol>
```
