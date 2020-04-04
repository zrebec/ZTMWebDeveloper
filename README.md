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

At first, try add exact this button onto your webpage

```html
<button class="btn btn-primary">Default</button>
```

As you can see you can combine more classes on one ```class``` attribute separated by space.

>Never use space in you class or id names. Space is reserved separator for combining

and change your ```index.html``` to ```register.html```. Of course, please, don't forget change anchor in ```nav```
and edit ```action``` attribute in registration form as well.

Then create new ```index.html``` with content like:

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/style.min.css">
    <title>SEE - Social Algorithm</title>
</head>
<body>
    <header>
        <a href="index.html">
            <img src="res/logo.png" height="64" alt="SEE - Social Network logo" style="float: left; margin-right: 20pt;">
        </a>
        <h1>SEE - Social Algorithm</h1>
        <nav>
            <a href="index.html">Home</a> |
            <a href="register.html">Registration</a> |
            <a href="principles.html">Our principles</a> |
            <a href="login.html">Login</a>
        </nav>
        <hr>
    </header>
    <section>
        <button class="btn btn-primary">Default</button>
        <h2>Home</h2>
        <p><strong>Lorem Ipsum</strong> is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been
        the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled
        it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic
        typesetting, remaining essentially unchanged. It was popularized in the 1960s with the release of Letraset sheets
        containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including
        versions of Lorem Ipsum.</p>
    </section>
</body>
</html>
```

>don't forget add ```<a href="index.html">Home</a> |``` to every document in your webpage.

### CSS Basics

The main principe of CSS file (should end with ```.css```) is very easy:

```css
Selector {
    Property: value;
}
```

Selector could be CSS class (starting with dot), ID (starting with hashtag) or HTML tag. Look at this one:

```css
html, body {
    padding: 0;
    margin: 0;
}

.button {
    background-color: black;
    color: white;
    border: 1px solid white;
    padding: 5px;
}

#container {
    max-width: 800px;
}

/*Selector {
    Property: value;
}*/
```

And save it as ```style.css```

The example have 4 selectors. 1st and 2nd are HTML tags. You can separate more selectors with comma. The properties
for ```html``` and ```body``` will be same. class ```.button``` tells that you want all HTML tags which will contains
```class="button"``` will have black background with white, it will have border with white color and thick of the border
will be 1 pixel and text inside the tag will be padded 5 pixels of borders.  
The ID container tell that tag with ID container (```id="container"```) will have 800 pixels maximum width. It is usable
when you want make your page with some maximum width. Then you can all your content encapsulate into ```container``` id.
The last thing is just comment (just for orientation, no any selector will be affected).
Example:

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Example</title>
        <link rel="stylesheet" type="text/css" href="style.css">
    </head>
<body>
    <section id="container">
        <button class=".button">Submit</button>
    </section>
</body>
</html>
```

>Don't forget link all your HTML documents with CSS file with ```link``` tag as you can see above. The css file must be
in the same folder than ```index.html```. Or you can change path css file into subfolder "styles" but then don't forget
edit relative path in link (we learned about relative paths and absolute paths long time ago).

Of course, if you want you can combine css stylesheets and use more css files in one or more HTML documents.

Example:

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Example</title>
        <link rel="stylesheet" type="text/css" href="style.css">
        <link rel="stylesheet" type="text/css" href="style2.css">
        <link rel="stylesheet" type="text/css" href="style3.css">
    </head>
<body>
    <section id="container">
        <button class=".button">Submit</button>
    </section>
</body>
</html>
```

**!IMPORTANT: Please don't forget, that CSS is shortcut for Cascading StyleSheet!**. This means that the latest file
(in our case ```style3.css```) will have bigger priority then file before. If you will have selector ```p``` (paragraph)
in ```style2.css``` with ```color: red;``` and then with ```color: green``` in ```style3.css``` your paragraph will have
green text color because properties are in conflict. If you will have just ```background-color: black``` in
```style3.css``` for ```p``` selector then you will have red text on black background because properties are not int
conflict and selector can be combined.

>The best way is start with selector which affect most things and goes down with more and more specific elements, id's
or classes. You should start with ```html``` or ```body``` then probably some containers like ```header```, ```main```,
```article```, ```section```, ```aside``` and many more which affect you page and then some headings, paragraphs, etc...
You should continue then with id's and classes at last. Remember, you can separate selector for sections, tags, ids and
classes in more .css files but don't forget link at all in your ```<head>```.
>Remember: ```class``` with the same value can you unlimited times in your web. But id only once in whole document!

#### Small about borders

Borders you can define in different ways. ```border: 2px solid black``` makes all borders 2 pixels weight with black
color. ```border-width: 20px 5px;``` makes you 20px from top and bottom and 5px from left and right.

How do you display a border like this:

The top border = 10 pixels  
The bottom border = 5 pixels  
The left border = 20 pixels  
The right border = 1pixel?  

Right answer is:

```css
border-width:10px 1px 5px 20px;
```

The global formula for ```border-width``` is: ```border-width: top right bottom left```

Look at this picture:

![Border values schema](https://i.imgur.com/VW8Cwv0.png "Border values schema")

#### Set styles with all ways

You don't need creating separate .css file if you have short or easy one document. Then you can use more ways to set
properties of your selector.

The first way is make ```style``` attribute into HTML element. For example
```<h1 style="background-color: green; text-transform: uppercase;">``` causes that this (yes, only this)
```<h1>``` element will have green background and uppercase text. But if you will have another ```<h1>``` without this
```style``` attribute, this will be not affected.

That's the reason why second way is better. You can add ```<style></style>``` into your ```<head></head>``` tag.

Example:

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Example</title>
        <style>
            h1 {
                background-color: green;
                text-transformation: uppercase;
            }
        </style>
    </head>
<body>
    <section id="container">
        <h1>First title</h1>
        <h1>Second title</h1>
    </section>
</body>
</html>
```

This causes that all of your ```h1``` will be on green background with uppercase texts.

The advantage of this ways are that you don't need transfer 2 or more file, but just 1 HTML file with your document.
But disadvantage is that is not very useful with larger projects or more HTML documents.

### Advanced CSS

### Useful links

At first you can visit <https://css-tricks.com/almanac> which is great resource for understand how advanced css works.
You can find there syntax and using of all properties, articles, videos and many more. And the most important is
**Almanac** in this website because you cannot remember all selectors with all possible properties. But you must know
where you can find the right information. **Almanac** can helps you because information here are the best way how
you can implement something. If you're use the google you can be confused with different ways of implementation and
not every is the right way for all browsers. And **Almanac** is easy to read and understand.

The second useful tool is <http://paletton.com/>. This website can helps you with the choose the right color schemes
in your website.

Also it's recommended install some color picker into your browser. Like
<https://chrome.google.com/webstore/detail/colorpick-eyedropper/ohcpnigalekghcmgcdcenkpelffpdolg/related> for
**Google Chrome**.

If you want add background image to your website, try visit <https://unsplash.com> where you can find quality images
for free.

I want use this image into my header of our website <https://unsplash.com/photos/qjCHPZbeXCQ>. Download the file and
make directory ```res``` as resources in your project and copy file there. Then rename it to ```header-background.jpg```
Also I edited this file because it was too large. I crop only 4096px x 500px because my header never will be taller than
500px

How to implement that?

```css
header {
    background: url('res/header-background.jpg') no-repeat;
}
```

Easy, right?

If you will want make website with background image, you can use property ```background-size: cover``` to fit whole
image into your site.

Now we want change our header and make our links to unordered list.

```html
<nav>
    <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="register.html">Registration</a></li>
        <li><a href="principles.html">Our principles</a></li>
        <li><a href="login.html">Login</a></li>
    </ul>
</nav>
```

and edit our css file:

```css
nav ul {
    padding: 0px; margin: 0px;
}

nav li {
    display: inline-block;
    list-style-type: none;
    margin-right: 15px;
}

a, a:visited {
    color: black;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}
```

Much better, right? You can see what all properties means in **Almanac** mentioned above.
The right question is, why I used ```nav ul``` and ```nav li```? Because I want affect unordered list only in our
navigation. Without using ```nav``` you affect all unordered lists. You can try that and look at **Our principles**.

### CSS Selectors

As you see above, we used many selectors like ```nav```, ```ul```, ```li```, ```a``` with some properties. You can
read about that properties in **Almanac** of we can a bit explain here.

What selectors win out in the cascade depends on:

- Specificity
- Importance
- Source order

#### Importance of css selectors

##### Specificity

Specificity means how specify is your declaration. For example ```p.blue``` is more specify that just ```p``` because
the style will be applied only with paragraphs with class set to **blue**.

Let's try to this with your css:

```css
p.blue {
    background-color: lightblue;
}

p {
    background-color: silver;
}
```

and change HTML:

```html
<p>This will have silver background</p>
<p class="blue">This will have lightblue background</p>
```

From all examples before you know that last element should win. So all paragraphs should have silver background.
But second paragraph will have blue background because it's more specify than usual paragraph. if you add to your second
paragraph attribute ```style="background-color: red"``` the paragraph background will be red because style using inside
HTML is the most specify for that HTML element.

You can see specificity calculator here <https://specificity.keegan.st>

##### Importance

It's just based on ```!import``` value on some property in some selector (look below)

##### Source order

It's ordering the files, elements or classes. The latest wins (this was explained above). For example if I have

#### element element

if you will use something like ```nav ul```, that means that you want affect unordered lists in ```nav``` block. The
same effect is with classes. If you will use ```aside .button``` you will affect only elements with attribute
```class="button"``` in ```aside``` block. Other *.button* classes will be untouched.

```html
<section>
    <button class="button">Standard button</button>
</section>
<aside>
    <button class="button">Submit</button>
</aside>
```

and css

```css
aside .button {
    background-color: wheat;
}
```

#### element, element

If you want affect more selectors, just use comma. For example with ```html, body {margin: 0; padding: 0}``` you will
affect ```html``` and ```body``` elements.

#### element > element

Select all child elements that has parent element. For example ```h2 > p``` means that I want all paragraphs where
parent is 2nd heading. This is a little tricky.

Let's try this:

```css
p > span {
    background-color; yellow;
}
```

and I will have HTML like

```html
<p>
    This is <span>yellow background</span> in our website using the parent > child css property.
</p>
```

You changed background color because your ```<span>``` has ```<p>``` element as parent. But if you change your html
into

```html
<p>
    This is <strong><span>yellow background</strong></div> in our website using the parent > child css property.
</p>
```

nothing happens because your span has parent ```<strong>``` element and not paragraph. But if you remove **>** from your
css file and replace it just with space you will have bold text on yellow background because then your ```<span>```
doesn't need paragraph as parent, just it must be under ```<p>``` section.

Don't worry if you fully understand. Other selectors contains 90% of your work and this one of the hardest selectors.

>In later we will using **bootstrap** and then you doesn't need to know this tricky selectors.

#### element + element

The element+element selector is used to select elements that is placed immediately after (not inside) the first
specified element. Let's try change your css file:

```css
p+span {
    background-color: yellow;
}
```

and change HTML file

```html
<p>
    <span>This is span with original background (usually white if you aren't change background in html tag e.g.)</span>
</p>
<span>This is span with yellow background</span>
```

The first span hasn't yellow background and the second has. Because ```element+element``` affect the element after
element defined before. In this case. The second ```<span>``` is the next-one after ```<p>```.
Third or other else ```<span>``` will not be affected if they will exactly not after ```</p>```.

#### star (like wildcard)

The next selector is **star** (*). This selector affect everything on document and should be used in first position in
your first css style. It's the most global selector. For example, if you setup ```* {text-align: center;}``` all texts
will be centered unless you specify other text align in later (for example ```p {text-align: left;}```) which affect
only p element but others will stay centered.

But you can all use all selectors inside other selector.

```css
* {
    background-color: silver;
}


div * {
    background-color: yellow;
}
```

with HTML

```html
<p>Silver background</p>
<div><p>yellow background</p></div>
```

caused that second paragraph will have yellow background. All other elements will have silver background.

#### Attribute value contains

The [attribute~=value] selector is used to select elements with an attribute value containing a specified word.

Try CSS:

```css
[title~=flower] {
  border: 5px solid yellow;
}
```

And HTML:

```html
<img src="klematis.jpg" title="klematis flower" width="150" height="113">
<img src="img_flower.gif" title="flowers" width="224" height="162">
<img src="landscape.jpg" title="landscape" width="160" height="120">
```

This cause that first image will have yellow border because ```title``` contains word **flower**
><https://www.w3schools.com/cssref/sel_attribute_value_contains.asp>

#### :only-child selector

Select elements which are child only other element.

```css
ul li:only-child {
    background-color: yellow;
}
```

selects the only ```<li>``` elements that are in a ```<ul>``` and change background color to yellow.

#### :hover

With ```:hover``` you can affect element when you go with cursor over this element.

For example:

```css
h2:hover {
    background-color: fuchsia;
}
```

caused that heading background color will be changed to fuchsia when my cursor overs any 2nd heading element.

#### :last-child, :first-child and :nth-child(n)

If you have the same class in more elements, the first one will be affected using ```:first-child``` and last will be
affected using ```:last-child```. Let's try edit your html at first:

```html
<section>
    <div class="person">John Smith</div>
    <div class="person">John Wick</div>
    <div class="person">Dr. Jekyll</div>
    <div class="person">Mr. Hyde</div>
</section>
```

then try add to your css:

```css
.person {
    background-color: silver;
}
.person:first-child {
    background-color: gold;
}
.person:last-child {
    background-color: green;
}
.person:nth-child(2) {
    background-color: magenta;
}
```

**John Smith** will have gold background and **Mr. Hyde** will be greenish. **John Wick** will be in mange background
and person named **Dr. Jekyll** will have silver background.
Remember, that you must encapsulate your elements into one parent element. As you can see, I have one ```<section>```
as parent and under it i can have many other ```<div>```s. But if you don't encapsulate, it will not work because css
don't know what ```<div>``` should select.

>For :first-child to work in IE8 and earlier, a DOCTYPE must be declared.

#### :nth-last-child(n)

The :nth-last-child(n) selector matches every element that is the nth child, regardless of type, of its parent, counting
from the last child.
>n can be a number, a keyword, or a formula.

```html
<!DOCTYPE html>
<html>
<head>
<style>
  p:nth-last-child(4) {
    background: red;
  }
</style>
</head>
<body>
  <p>The first paragraph.</p>
  <p>The second paragraph.</p>
  <p>The third paragraph.</p>
  <p>The fourth paragraph.</p>
</body>
</html>
```

Selects **The first paragraph** because it's the last paragraph in parent ```body``` counting from back.

But, let it try a bit harder:

```html
<!DOCTYPE html>
<html>
<head>
<style>
  p:nth-last-child(1) {
    background: red;
  }
</style>
</head>
<body>
  <p>The first paragraph.</p>
  <div>Section 1</div>
  <p>The second paragraph.</p>
  <div>Section 2</div>
  <p>The third paragraph.</p>
  <div>
      <p>Section 3</p>
  </div>
  <p>The fourth paragraph.</p>
</body>
</html>
```

```nth-last-child(1)``` selects **The fourth paragraph.** and also **Section 3** because before
**The fourth paragraph.** we have **Section 3** also as paragraph.
```nth-last-child(2)``` selects nothing (incorrect formula)
```nth-last-child(3)``` selects **The third paragraph.**
```nth-last-child(4)``` selects nothing (incorrect formula)
```nth-last-child(5)``` selects **The second paragraph.**
```nth-last-child(6)``` selects nothing (incorrect formula)
```nth-last-child(7)``` selects **The first paragraph.**

#### :nth-of-type()

The :nth-of-type(n) selector matches every element that is the nth child, of a particular type, of its parent.
>can be a number, a keyword, or a formula

```html
<!DOCTYPE html>
<html>
<head>
<style>
  p:nth-of-type(3) {
    background: red;
  }
</style>
</head>
<body>
  <p>The first paragraph.</p>
  <div>Section 1</div>
  <p>The second paragraph.</p>
  <div>Section 2</div>
  <p>The third paragraph.</p>
  <div>
      <p>Section 3</p>
  </div>
  <p>The fourth paragraph.</p>
</body>
</html>
```

selects **The third paragraph.**. You can also change it to ```p:nth-of-type(odd)``` which selects all odd paragraphs.
Red background will have values **The first paragraph.** because it's first, **The third paragraph.** because it's a
third paragraph in our body. Then will be selected also **Section 3** because it's a first paragraph under another
parent (```<div>```). If you change style to ```div p:nth-of-type(3)``` only **Section 3** will be selected because it's
first paragraph inside ```<div>``` element.

#### :empty

selects only element which is empty

```html
<p></p>
<p>A paragraph.</p>
<p>Another paragraph.</p>
```

with ```p:empty {width: 100px; height: 20px; background: #ff0000;}``` in css selects only first paragraph and set his
width 100px, height 20px and his background will be red. Another paragraphs have content inside and will be selected.

#### !important

The last one is property ```!important```. This ***Not recommended** because you have trouble if you want will affect
the same element (or class, or id, anything) later. ```!important``` caused that this property wasn't be changed later.

Example:

```css
p {
    color: pink !important;
}

p {
    color: green;
}
```

What's happens? All texts in ```p``` element stay pink and cannot be changed later (or in another css file). Please try
avoid this.

>!important is a breaker of cascading rules.

#### Recap of CSS selectors

```.class``` affect element with ```class="class"```
```#id``` affect element with ```id="id"```. Remember, the name of ID must be unique for whole document. You cannot use
**#id** twice in your HTML.
```element``` affect any HTML element (like ```p```, ```body```, ```nav```, ```section```, ```h1```).
```element, element``` affects with same style more elements (it's like if you write ```element``` twice in your css
with same properties). For example I can affect ```html``` and ```body``` then ```html, body {}``` in your css
```element element``` affect element under in some other element (detail explain above).
```element > element``` The element>element selector is used to select elements with a specific parent.
>Elements that are not directly a child of the specified parent, are not selected.
```element + element``` The element+element selector is used to select elements that is placed immediately after
(not inside) the first specified element.
```:hover``` affect when I go with cursor over the element (this is called event method)
```:last-child``` affect last child of element
```:first-child``` affect first child of element
```:nth-child(n)``` selects all n child elements into another element
```!important``` **This is not recommended**. It caused that any css property later cannot affect my property defined
before.

#### Play with selectors

If you want improve your skills try this game: <https://flukeout.github.io>

#### CSS Colors

You have more ways to add ```color``` or ```background-color``` or color in ```border``` property. Doesn't matter.

The first way is the css name of the color. This is simplest method because you can use colors in words (like blue,
black, red, wheat, lightgreen, navy and many more). But remember, that you are limited only with known css colors.

If you want setup custom color from picker mentioned above you can write with hexadecimal color code like
```color: #0162ac``` or as rgb color like ```color: rbg(255, 0, 0)```. In **rgb** color just remember that you have
range from **0** to **255** (8-bit number representation). The first number is for red, second one is green and last one
is for blue. That means that our font color will be just red.
>Remember that any rgb color can be represented in hexadecimal number and vice versa.

If you want add some transparency in  your selector, hexadecimal numbers are useless. In this case you can use
```color: rgba(255, 0, 0, 0.6)```. **rgba** means Read, Green, Blue and Alpha. Alpha is a transparency level from 0 to 1
. 0 means total transparent and 1 mean nontransparent color.

Lets add some transparency into our 2nd level of headings:

```css
h2 {
    background-color: rgba(255, 23, 12, 0.2);
}
```

### Text and Fonts

Typography is the very important part of CSS. With default browser fonts your page never will be nice.

Text manipulation:

- ```text-decoration: underline``` underlines the text in selector
- ```text-decoration: line-through``` draw line in center of text (like if you want remove text on paper)
- ```text-decoration: overline``` draw line over text
- ```text-decoration: underline overline``` draw line over and under text
- ```text-transform: uppercase``` Transforms all characters to uppercase
- ```text-transform: lowercase``` Transforms all characters to lowercase
- ```text-transform: capitalize``` Transforms the first character of each word to uppercase
- ```line-height: 20px``` Set each line of text 20 pixels height

Font manipulation:

- ```font-weight: bold``` text in selector will be bold
- ```font-style: italic``` text in selector will be italic
- ```font-style: oblique``` text in selector will be oblique
- ```font-size: 150%``` set font size to 1,5x larger that is the parent or root font size
- ```font-size: 12pt``` set font size 12 points in selector

#### Font Family

It's a more complex

- ```font-family: Georgia, "Time New Roman"``` Set font family to Georgia. If Georgia font is not available for the
browser or doesn't exists in operating system, continues try set **Times New Roman** font.

But you can simple define CSS predefined fonts. It's a keywords which select the available font for browser in some font
family.

- ```font-family: monospace``` set monospaced font

Built-in font family styles in css are: ```sans-serif```, ```serif```, ```monospace```.
**sans-serif** is best for display output (like monitors, mobile screens)  
**serif** are using usually for printing
**monospace** are for display piece of code or console output (or for your whole webpage if you want)

The good idea is add one of this built-in fonts on last place in ```font-family``` property. For example if you want
show some code in Windows, you can use: ```font-family: Consolas, monospace```. Consolas are available in all windows
starting with Windows 7. In linux will be used available monospaced font (e.g. **Lucida Mono** or **Ubuntu Mono**). In
older windows will be used **Courier New** probably.

The last thing is the your custom fonts set as font family. This is platform or browser independent because your browser
download font from server and just use it.

Example of use:

```css
@import url('https://fonts.googleapis.com/css?family=Open+Sans|Roboto&display=swap&subset=latin-ext');
body {
    font-family: 'Open Sans', sans-serif;
}

h1 {
    font-family: 'Roboto', sans-serif;
}
```

This download fonts from google fonts (free for use) named **Roboto** and **Open Sans**. Use it as ```font-family```.
>You can generate import link in <https://fonts.google.com>. Just select the fonts by click on the **+** icon. In the
right bottom corner you fill write "n Families Selected" (n means number how many fonts you selected). Just click on it
and clink on **@IMPORT**, copy link starts with ```@import``` in ```<style>``` element and put in your css file. Then
you can use those font families.

### Images in css

Instead of HTML you can use images in your css (for example like a background shows above). The advantage is that you
can write on this pictures (or put another HTML elements) because css is another layer than your HTML content. But
beware. If you have css in some subfolder and not in directory where you have HTML content, you must set right paths to
get image (you can relative path with use ```../images``` which means go upper directory and then go to images) or
better way is use absolute path.

For example you want put image upper left in paragraph and you want have text around the image try use in your css file
```img.top-left {float: left;}``` which caused that ```<img>``` element with class **top-left** use the **float**
property to left side.

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        img.top-left {float: left; margin-right: 2rem; margin-bottom: 2rem;}
    </style>
</head>
<body>
  <p>
    <img src="https://i.pravatar.cc/300" class="top-left">
    <strong>Lorem Ipsum</strong> is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been
    the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled
    it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic
    typesetting, remaining essentially unchanged. It was popularized in the 1960s with the release of Letraset sheets
    containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including
    versions of Lorem Ipsum.
</p>
</body>
</html>
```

But it's recommended after next element set css property to ```clear: both;``` because **float** property caused that
not only text in your paragraph will flow around the image, but everything under the image finished.

### CSS Box Model

At first, look at this picture
![Box Model](https://www.washington.edu/accesscomputing/webd2/student/unit3/images/boxmodel.gif "Box Model")
This image showing box modeling in CSS.

#### Margin

It's indent object including his borders. You can imagine that top of your head and the ceiling. How many space you have
? That's the margin of you and ceiling. Box objects usually has some margin. If you put ```<p>``` or ```<h1>``` in your
document, you can see that it's a indented about your another text. Otherwise ```<div>``` has no margin

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Margin Example</title>
    <style>
        body {font-family: sans-serif; font-size: 2em;}
        h1 {background-color: yellow; border: 20px solid red;}
        span { background-color: lightcoral; }
        div { background-color: silver; }
        p { background-color: fuchsia;}
    </style>
</head>
<body>
    <section>
        <h1>&lt;h1&gt; is a box object with margin </h1>
        <span>&lt;span&gt; is inline object</span><br>
        <div>&lt;div&gt; is box object without margin indent</div>
        <span>another &lt;span&gt; as proof for paragraph</span><br>
        <p>&lt;p&gt; is box object with margin indent</p>
    </section>
</body>
</html>
```

Shows you something like this:

![Example of ](https://i.imgur.com/3CiiPAo.jpg "Example Of Box Model")

#### Border

Border is like skin on your body. Yes, it's very thin but keep your body safe of outer. Border it's the same. In example
above you can see that I put border to biggest heading. It's space between padding (your fat) and margin (outside).

```css
border: 1px solid black;
```

or

```css
border-width: 5px 2px 7px 1px;
border-color: yellow;
border-style: solid;
```

if you want different border thick of each side. If can imagine a clock starts at 12am and count clockwise (which means
the first value it top, second is right, 3rd is bottom and last is left border).

#### Padding

Padding is your fat. Keep safe your internal organs inside the body and it's space between it and your skin. Default
no object who I know has padding. You can setup it by:

```css
padding: 5px;
```

or

```css
padding-left: 5pt;
padding-top: 10pt;
padding-bottom: 15pt;
padding-left: 1pt;
```

if you want different paddings of each side. This is small different as border because padding has nothing like color or
style.

#### Content

So, content is your life... It is your internal organs. Content has no width, height or something else. It's just your
content. You don't need setup anything here.
