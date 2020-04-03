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
- #alumni - Ask graduates about this course questions
- #womenintech - For the female coders out there
- #job-hunting - Anything related to finding a job as a developer
- #code100 - To join a community of students dedicated to code every day for 100 days. You can join anytime.
- #command-room - Commands for bot like ```!rank``` for view your card.

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
- Hosting the separate scripts on nearby server (like css, javascript or some
parts of web pages)
- Custom mirroring (expensive)
- Using service like cloudflare
- Using modern HTML elements like ```<picture>``` for smaller images on small
devices (usually more than 80% daily internet users using a smartphone for internet
browsing)

### Epilogue

The author of ZTM Web Development (Andrei Neagoie) was inspired by this article:
<https://zerotomastery.io/blog/learn-to-code-in-2020-get-hired-and-have-fun-along-the-way/>
Web developer monthly blog: <https://zerotomastery.io/blog/?tag=WDM>

## Section 3: History Of The Web

### WWW vs Internet

Author of World Wide Web: **Sir Tim Berners-Lee** in 1989

The good history lesson is on <https://www.vox.com/a/internet-maps>

In the past every internet page (every computer) had only it's IP address and you had to know known the respective IP address.
Sir **Tim Berners-Lee** arrives with World Wide Web (www) which means that whole page works under www roof.
He created the first web page as well (server and www page).

>The first website was in 1991 and the copy of that is on <info.cern.ch/hypertext/WWW/TheProject.html>

### HTML, CSS, Javascript

- HTML: Structure and data of web page (text)
- CSS: How web page will look
- Javascript: Advanced and interactive functionality of web page

### Developer Fundamentals

We have many devices to browse the internet (like notebooks, tablets or mobile phones) today and each of one must process
HTML, CSS and Javascript files to desired result. That's the reason why are fundamentals of web developmentally important.
The cornerstone of it is the testing your website on each individual device.
Web browsers can help with it as well because they can offer simulated mobile devices, different screen resolutions, etc...

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

#### Few more HTML text formatting tags

- ```<b>``` is for **bold text**.
- ```<i>``` is for *italic text*.
- ```<mark>``` for highlight text.
- ```<del>``` is for strikeout the text.
- ```<q>``` is for "Quotation text".
- ```<blockquote cite="link">Quoted text</blockquote>``` for quote citation text
- ```<bdo dir="rtl">Right to left text</bdo>``` for right to left text orientation

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
    <li>Privacy</li>
    <li>Security</li>
    <li>Usability</li>
<ol>
```

```<ul>``` is unordered list (without numbers e.g.)

```html
<ul>
    <li>We never show your name or birth year without your permit!</li>
    <li>Your data never be sell to third party site!</li>
<ul>
```

or you can combine it!

```html
<h1>Our principles</h1>
<p>See our <em>strong</em> but <strong>simple</strong> principles.</p>

<ol>
    <li>Privacy</li>
    <ul>
        <li>We never show your name or birth year without your permit!</li>
        <li>Your data never be sell to third party site!</li>
    </ul>
    <li>Security</li>
    <ul>
        <li>Always using https connection</li>
        <li>We are crypt your password with modern security algorithms</li>
    </ul>
    <li>Usability</li>
    <ul>
        <li>Easy use</li>
        <li>Modern algorithms to find the opposite</li>
    </ul>
</ol>
```

>For highlight text you shall use ```<mark>Highlight text</mark>``` tag (not shown above, but please, remember it!)

#### Closing tags

Closing tags usually closing with backslash and name the tag. But some tags has no closing tag. It's called non-pairing
tags. For example ```<br>``` which is **break line** or ```<hr>``` for example which is **horizontal line**. So, add
after the title of your page one **horizontal line**. In **XHTML**

```html
<h1>SEE - Social Network</h1>
<hr>
<p>Welcome to <strong>new</strong> <em>social network</em>. Our goal is look an ideal partner width
    minimum information about you.</p>
```

In **XHTML** which I mentioned above you must should write this tags like ```<br />``` or ```<hr />```.

#### Images

The basic tag for image is ```<img>``` in most **HTML** versions (in **HTML5** too sure).  
The more about ```img``` you can find in: <https://www.w3schools.com/tags/tag_img.asp>  
Very important attributes are ```src``` what is source where HTML server can find the image and description for image
as ```alt``` attribute. This attributes is important when browser cannot display the image (broken link e.g.), if
your browser doesn't support images (like **lynx** in linux) and it's important for text-readers as well.

We can try add some free image into our page

```html
<img src="https://cdn.pixabay.com/photo/2016/03/31/21/20/anthropomorphized-animals-1296354_960_720.png"
height="64" alt="SEE - Social Network logo" style="float: left; margin-right: 20pt;">
<h1>SEE - Social Network</h1>
<hr>
<p>Welcome to <strong>new</strong> <em>social network</em>. Our goal is look an ideal partner width
    minimum information about you.</p>
```

I added ```width``` attribute because original logo is too large and ```style``` with ```float``` because I want text
next to the image and not under the image (this can be explained later).  
For the specify size of image you can use **CSS styles** as well or you can add ```height``` attribute is you want some
special proportionals of image. But it's enough to leave ```width``` then image is height is corrected for keep image
proportions.

![Webpage logo](https://i.imgur.com/OVP14jD.png "Webpage logo")

#### Anchors

Anchors are reference links to another website (usually another part of our website)  
Basic structure:

```<a href="link to other document" >```

Make our logo clickable for return to main page (usually index.html)

```html
 <a href="index.html">
    <img src="https://cdn.pixabay.com/photo/2016/03/31/21/20/anthropomorphized-animals-1296354_960_720.png"
    height="64" alt="SEE - Social Network logo" style="float: left; margin-right: 20pt;">
</a>
<h1>Welcome to our Social Network</h1>
```

You can use **hashtag** if you want link to some part in same document. For example if you have long document like some
license you can add **hashtags** for to start of page and links to chapters.  
Example in our page:

```html
<h1>Welcome to our local Social Network</h1>
<hr>
<p>Welcome to <strong>new</strong> <em>social network</em>. Our goal is look an ideal partner width
minimum information about you.</p>
<a href="index.html">Registration</a> |
<a href="principles.html">Our principles</a> |
<a href="login.html">Login</a>
<h2>Please, register today!</h2>
```

In anchors you can set ```target``` attribute if you want open the new document in new window for example. Then anchor
will look like ```<a href="index.html/new_document" target="_blank">```

#### Relative vs Absolute path

In anchors you can use **relative** or **absolute** paths. Relative means that you targeting in some html file which is
in your directory on server where you have main file (mostly is it ```index.html``` because most server are
pre-configured) for this file as basic page. Like in our previous example we redirecting our ```index.html``` if you
click on the logo which is relative path. And our logo in ```img``` tag has ```https://cdn.pixabay.com...``` which is
absolute path. That means the absolute path contains full path to document including the server and relative path
doesn't. As homework you can re-write our anchor on logo of page to absolute path. (hint: don't forget to server
name and document name.)

#### Exercises and more resources

If you want text of your HTML skill you shall visit <https://www.w3schools.com/html/html_quiz.asp>  
For training a more skill try advanced exercises in <https://www.w3schools.com/html/exercise.asp>

If you need more information about HTML tags the resource is
<https://www.freecodecamp.org/learn/responsive-web-design/basic-html-and-html5>

## Section 5: Advanced HTML5

### Forms

As usually you can find lot of help in <https://www.w3schools.com/tags/tag_form.asp>

The basic tag is ```form```. You can use a many inputs under form. Usually are used in ```input``` tag witch types like
```text```, ```password```, ```email```, ```date``` or ```submit``` (for send the form) as ```type``` attribute.  
You can also set minim and maximum length of each field by set ```minlength``` and ```maxlength``` attribute.  
If you want to use that some field must be required (not empty) you do it with ```required``` attribute.  
To select from pickup list you can do it by ```select``` tag. To allow select multiple values you can use ```multiple```
attribute.

Let's do it small registration form for our page:

```html
<form action="index.html" name="registration" method="GET">
    <fieldset>
        <legend>Basic information</legend>
        <div>
            <label>First Name*: </label>
            <input type="text" name="first_name" minlength="2" title="Please, start with your First name" required>
        </div>
        <div>
            <label>Middle Name: </label>
            <input type="text" name="middle_name" title="Middle name if you have">
        </div>
        <div>
            <label>Last Name*: </label>
            <input type="text" name="last_name" minlength="2" title="Everyone has Last name, right?" required>
        </div>
        <div>
            <label>Email*: </label>
            <input type="email" name="email" title="What is your primary contact email address please?" required>
        </div>
        <div>
            <label>Birthday*: </label>
            <input type="date" name="birthday" title="Don't worry. We want your birthday just for better algorithm to find your ideal opposite" required>
        </div>
        <div>
            <label>Gender*: </label>
            <select name="gender" title="Are you Female, Male or something other?" required>
                <option value="female">Female</option>
                <option value="male">Male</option>
                <option value="other">Other</option>
            </select>
        </div>
    <small>Please note that password is not required because you get temporary password for first login to your email.</small>
    </fieldset>
    <fieldset>
        <legend>What are you looking?</legend>
        <div>
            <label>I'm looking for: </label>
            <input type="checkbox" name="looking_for" value="date" title="If you're looking date"> Date
            <input type="checkbox" name="looking_for" value="talk" title="Are you interested just about talk?"> Talk
            <input type="checkbox" name="looking_for" value="flirt" title="Do you love flirt?"> Flirt
            <input type="checkbox" name="looking_for" value="unspecified" title="Nobody know what's happens"> We Will see
        </div>
        <div>
            <label>I'm here for: </label>
            <input type="checkbox" name="seeking_for" value="woman" title="Do you want woman?"> Woman
            <input type="checkbox" name="seeking_for" value="man" title="Prefer men?"> Man
            <input type="checkbox" name="seeking_for" value="couple" title="Are you into couples?"> Couple
            <input type="checkbox" name="seeking_for" value="same_gender_couple" title="I want the same gender couple"> Same gender couple
            <input type="checkbox" name="seeking_for" value="unknown" title="You can edit this later"> I don't know yet
        </div>
        <div>
            <label>What age range do you looking for?: </label>
            <input type="number" name="age_range" min="18" max="99" title="Do you looking bunny, your age or someone older?">
        </div>
        <div>
            <label>Are you here first time?: </label>
            <input type="radio" name="first_visit" title="Yes, I'm first time here"> Yes
            <input type="radio" name="first_visit" title="No, I used this network before"> No
        </div>
    </fieldset>
    <fieldset>
        <legend>Other</legend>
        <div>
            <label>Hell about you something: </label>
            <br>
            <textarea name="bio" rows="5" cols="30" title="What about your additional bio?"></textarea>
        </div>
    </fieldset>
    <input type="submit" value="Register">
</form>
```

Uh, it's a bit long, yeah? Don't worry. It's easier as it looks. As you can see the most tags in form are ```input```.  
With ```label``` you can enclosing your field name. It's usually recommended. You can see that **First Name**,
**Last Name**, **Email** are ```required```.  
Birthday is required as well because you must know how age do you want to find as opposite. If value of ```type```
is email, browser supporting HTML5 display mini calendar.  
```checkbox``` type with common name and different values allows you to select more values in one section. Instead of
```checkbox``` is ```radio``` which allow you only one value.  
The last used tag is ```select``` for select how our customers wants improve our page. Of course, you can add
```multiple``` but we don't want it because we want to see what customers most wants.  
```textarea``` allow you write more than one row (```input``` allows only one row text) and that's the reason why we
used it for bio of person who registering.  
```input``` with type ```reset``` reset your form and with ```submit``` submit your form.  
All of 3 separate section encapsulate into ```fieldset``` for better orientation. The ```legend``` tag inside
```fieldset``` is something like title of group.

>Please remember that ```name``` is very important in each input field. ```value``` is very important as well specially
in radio buttons, checkboxes or pick-lists.

So, let fill our form:

![Registration form](https://i.imgur.com/2TunkKT.png "Registration form")

After click on **Register** button you can see a so long URL like:

```output
index.html?first_name=Martin&middle_name=&last_name=Fox&email=fakeemail%40fake.info&birthday=2020-04-03&gender=male&looking_for=date&looking_for=flirt&seeking_for=woman&seeking_for=couple&age_range=30&first_visit=on&bio=I+will+write+something+about+me+later
```

Let's get started with parsing. The first parameter in any **URL** is after ```?```. All others are after ```&```. If we
want parse this form, we can make a new line after **?** and then after every **&**.

```output
?first_name=Martin
&middle_name=
&last_name=Fox
&email=fakeemail%40fake.info
&birthday=2020-04-03
&gender=male
&looking_for=date
&looking_for=flirt
&seeking_for=woman
&seeking_for=couple
&age_range=30&first_visit=on
&bio=I+will+write+something+about+me+later
```

As you can see it's easy. Every value what we fill in form are now in our URL with your as well. The most used and
**strong recommended** method is submit the form as **POST** method! You can do that with add ```method="POST"``` in our
```form``` tag. Try it and you will see that your url will ends with **registration.html**. This is also called
**backend** method.

#### Input restrictions

Some attributes are allowed only in HTML5 but then you can have richer document. Look at this webpage:
<https://www.w3schools.com/html/html_form_input_types.asp>. There are listed restrictions for HTML5 and for older HTML
as well. For example ```min``` and ```max``` value are new HTML5 and allows you set a number range in our form.

For example, we don't need a full birthday of us customer, it's enough known his age. Replace the ```Birthday``` input
with ```number``` instead of ```date``` and set minimum value 15 years and maximum value 120 years.

```html
<label>birthday: </label><input type="number" name="birthday" min="15" max="120">
```

Try register and value lower than 15 or higher than 120. You should see error message.

### Few more HTML tags

For comment in your HTML you should use ```<!-- Comment -->```. Try add some comments to your registration form for
better orientation.

```<div>``` and ```<span>``` are for separating sections. ```<div>``` break line after end (after ```</div>```) and
```<span>``` is usually using for CSS styles. The difference is ```<div>``` is **block** tag and ```<span>``` is inline
tag which means that content will continue in same line after end of span.

But don't worry with this elements now, in later we will use CSS styles for form formatting.

### HTML vs HTML5

The basic concepts of HTML5 is more tags like ```nav```, ```article```, ```header```, ```footer``` for layout of your
document. It's the big evolution of classic HTML.

Let's get quick look of HTML5 features:

```<article>``` - specifies independent, self-contained content.  
```<aside>``` - defines some content aside from the content it is placed in.  
```<figcaption>``` - defines a caption for a ```<figure>``` element.  
```<figure>``` - specifies self-contained content, like illustrations, diagrams, photos, code listings, etc.  
```<footer>``` - defines a footer for a document or section.  
```<header>``` -  element represents a container for introductory content or a set of navigational links.  
```<main>``` - specifies the main content of a document.  
```<mark>``` - defines marked text.  
```<nav>``` - defines a set of navigation links.  
```<section>``` - defines sections in a document, such as chapters, headers, footers, or any other sections of the
document.  
```<summary>``` - defines a visible heading for the ```<details>``` element. The heading can be clicked to view/hide
the details.  
```<time>``` - tag defines a human-readable date/time.  
```<audio>``` - playing audio file (usually .wav format) Look here for more info:
<https://www.w3schools.com/html/html5_audio.asp>  
```<video>``` - play video files (for use look here: <https://www.w3schools.com/html/html5_video.asp>).

All of this tag and layout of page you can see here: <https://www.w3schools.com/html/html5_semantic_elements.asp>

All tags list above are new in HTML5 which means that document can be read by old browsers but layout probably not will
be displayed as you wish. Of course, you can solve the website for older browsers by using standard ```<div>``` and
```<span>``` tags but then you must solve it in CSS usually and result might not be grateful.

Using the new HTML5 tags is useful for searching machines too (like google e.g.). It's a more readable by machines and
your website can be higher in google results probably.

>**Homework**: Edit **index.html** (our main page of website) and encapsulate our header into HTML5 tag for heading,
links encapsulate to navigation tag and add some nice footer.

### Epilogue of HTML and HTML5

>Spending all of your time learning and memorizing all of the html tags and attributes is not the most efficient use of
your time. Most job interviews of a web developer will never test this knowledge. What you want to do instead is this:
Understand how you can use HTML, and how to use online resources to find html tags and attributes that you need. A great
developer is someone who knows how to find solution to problems and knows where to look. No developer can memorize
everything, especially when we start learning CSS and Javascript.

## Section 6: CSS

Cascading style sheets
