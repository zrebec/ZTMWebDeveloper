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
- ```<s>``` for stroke the text
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

At first, look at this picture:

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

Setup of margin is just ```margin: 5pt;``` or

```css
margin-top: 5pt;
margin-right: 2pt;
margin-bottom: 10pt;
margin-left: 7pt;
```

or easier ```margin: 5pt 2pt 10pt 7pt;``` or even shorter like ```margin: 10pt 50pt;``` where first value are from top
and bottom and second value are from left and right.

if you want different margin from each side (like padding).

Width ```margin``` you can also centered some objects e.g. Margin has valid value ```auto```. For example, if you want
center your page (if you have some **container** ```<div>``` width fixed width like 800px - or any value), you can
center it very easy:

```css
.container {
    margin: 0 auto;
}
```

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

##### Circle borders

If you're interested about circle images try set ```border-radius: 50%``` to class which applying in your image.

```css
.img-rounded {
    border-color: blue;
    border-width: 10px;
    border-style: solid;
    border-radius: 50%;
}
```

#### Padding

Padding is your fat. Keep safe your internal organs inside the body and it's space between it and your skin. Default
no object who I know has padding. You can setup it by:

```css
padding: 5px;
```

or

```css
padding-top: 10pt;
padding-right: 5pt;
padding-bottom: 15pt;
padding-left: 1pt;
```

or easier by ``padding: 10pt 5pt 15pt 1pt`` (like in border) or even shorter ```padding: 10pt 50pt``` where first value
are from top and bottom and second value are from left and right.

if you want different paddings of each side. This is small different as border because padding has nothing like color or
style.

#### Content

So, content is your life... It is your internal organs. If you want change the size of content, you shall use

```css
width: 20pt
height: 20pt;
```

This causes that your content will be square with 20 points width and height.

>Just remember, margin is outside of border, padding is inside of border
>Try developer tools in your browser and if you click on your element you will see margin, border, padding and content.

#### Displaying block and inline objects

As you can see, inline objects like ```<span>``` ends where content ends too. Block object like ```<div>``` take all space
in the same line. If you want shorter ```<div>``` you can set

```css
div {
    display: inline-block;
}
```

This causes that ```<div>``` ends when content ends too. Of course, you can set ```display: block``` for span. Then span
will take whole line and will be displayed as block.

The special display modes are ```flex``` and ```grid``` but we explain this later.

**Flex**: <https://css-tricks.com/snippets/css/a-guide-to-flexbox>
**Grid**: <https://css-tricks.com/snippets/css/complete-guide-grid>

### px vs em vs rem

**px** means pixes are absolute value for size of some element.
**em** size is inherited from parent element
**rem** size is inherited from root element

Example:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Margin Example</title>
    <style>
        html {font-family: monospace; font-size: 10px; color: white}
        p {background-color: #06a; font-size: 2rem; padding: 5px;}
        p.rem {background-color: fuchsia; font-size: 1.5rem}
        span.em {background-color: teal; font-size: 2em }
    </style>
</head>
<body>
    <section>
        <p>This is double size from root. That means, this should has 20px.</p>
        <p class="rem">
            <span class="em">
                This font size is inherited from parent element (div). 2em means double size of parent. Parent has
                1.5rem which means 30px because 15 * 2 = 30.
            </span>
            This font size is inherited from root element (body). 2rem double size from root
            This should be same size as previous paragraph. This is 15px because 10*1.5 = 15.
        </p>
    </section>
</body>
</html>
```

you should see something like this picture

![px vs em vs rem size](https://i.imgur.com/NltJ6wD.jpg "px vs em vs rem size")

Well, here is developer console as your best your friend

Computed size for ```<p>```
![Computed size for p](https://i.imgur.com/8lYxCht.jpg "Computed size for p")

Computed size for ```<p class="rem">```
![Computed size p.rem](https://i.imgur.com/fMte5Q0.jpg "Computed size p.rem")

Computed size for ```<span class="em">```
![Computed size span.rem](https://i.imgur.com/P16l9Yu.jpg "Computed size span.em")

>Remember, that root element is ```html``` in all normal HTML5 documents.

## Section 7: Advanced CSS

### Critical Render Path

If you have larger project and download content from external server like fonts via **Google Fonts API**, then your
own css and your HTML code, this could takes a some time.

Good way how to save a time is a minimizing your CSS. Usually you have many lines in your css file in bigger website.

Many Developer Text editors (like my favorite Visual Studio Code which you can download here
<https://code.visualstudio.com/Download>) or IDE supports minimizing css files. My favorite for this is plugin for
Visual Studio Code called "Live Sass Compiler". It's a compiler from scss files into css files (Sass is css
preprocessor).

If you have access to some minimizer css files in your editor, try online version <https://www.cleancss.com/css-minify/>
Just paste you full css here and the result will be minimized css which you can save as styles.min.css (always keep your
original version too) and then change the path in ```<link rel="stylesheet" type="text/css" href="styles.css">``` to
your minimized css file name.

### CSS Variables

You can using variables in your css. The advantages of variable is, that you can change some property value at once and
everything will be changed where variable was used. You can define variable in any selector but I can recommend to use
```:root``` selector. From this you variable will be accessible anywhere in css file.

Example

```css
:root {
    --heading-color: #a00;
}

h1 {
    color: var(--heading-color, red);
}
```

It's easy. The biggest heading try use variable ```--heading-color``` as value of ```color``` property. If fail, use
```red``` color instead of (this is called fallback value).

If you are not niggardly to lines in your css you can better improve your fallback to set ```color``` property to
```red``` before using var. If customer's browsers doesn't know ```var```, you heading will be still red. If knows,
set color by variable. You know that one of CSS rules that ordering? Last winning, right?

#### CSS variables overriding

As I said, I recommending to use ```:root``` selector. But sometimes this could be counterproductive in some cases.
But is still solution here. You can reassign variable in class or any other selector.

```css
:root {
    --button-color: #06a;
}

.submit-button {
    --button-color: green;
}

.button {
    color: var(--button-color, blue);
}
```

Then just call ```<button class="submit-button button" value="button">Submit</button>``` in your HTML file. Your button
will be green instead of blue. If you remove ```submit-button``` from class, it will be blue back.

This is useful with combination **media query** ```@media (max-width: 350px)```. Here you can redefine variables for
small devices.

Remember. Variable cannot be just a color. It could be size, font-style, font-family, almost everything aht that's the
reason why is useful with **media query** combination. You can set in ```:root``` some sizes and redefine this variables
using ```@media (max-width: 350px)```.

```css
:root {
    --penguin-size: 300px;
    --penguin-skin: gray;
}

@media (max-width: 350px) {
    :root {  
        --penguin-size: 200px;
        --penguin-skin: black;
    }
}
```

### FLexBox

Now, we will creating a real website. Full responsive image gallery. As we shows above, you can set to some element
```display``` property in your css file. We explained ```inline``` and ```block``` or ```inline-block```. I mentioned
that we have also flexbox which you set by ```display: flex;``` in your css file.

At first, we will need some images and create basic html

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="style.css">
    <title>Full Responsive Gallery Website</title>
</head>
<body>
    <h1>Life in the Wild</h1>
    <div class="container">
        <img src="/gallery/images/" alt="Image 1">
        <img src="/gallery/images/" alt="Image 2">
        <img src="/gallery/images/" alt="Image 3">
        <img src="/gallery/images/" alt="Image 4">
        <img src="/gallery/images/" alt="Image 5">
        <img src="/gallery/images/" alt="Image 6">
        <img src="/gallery/images/" alt="Image7">
        <img src="/gallery/images/" alt="Image 8">
        <img src="/gallery/images/" alt="Image 9">
        <img src="/gallery/images/" alt="Image 10">
    </div>
</body>
</html>
```

You need a download some images or just use external links in <https://www.pexels.com/> or <https://i.pravatar.cc/800>.
800 is the size image. **pravatar** always return you the random image.

At 2dn you must create also ```style.css``` sure with this basic content:

```css
.container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

h1 {
    font-family: fantasy;
    font-size: 3em;
    text-align: center;
}

img {
    width: 450px;
    margin: 5px;
    border: 1px solid black;
}
```

As you can see we used class ```.container``` in our ```<div>``` for flex displaying style.

#### Common properties for flexbox container

##### justify-content

Options for ```justify-content``` (horizontal aligns):

```flex-start```: Items align to the left side of the container.  
```flex-end```: Items align to the right side of the container.  
```center```: Items align at the center of the container.  
```space-between```: Items display with equal spacing between them.  
```space-around```: Items display with equal spacing around them.  

##### align-items

Options for ```align-items``` (vertical aligns):

```flex-start```: Items align to the top of the container.  
```flex-end```: Items align to the bottom of the container.  
```center```: Items align at the vertical center of the container.  
```baseline```: Items display at the baseline of the container.  
```stretch```: Items are stretched to fit the container.  

##### flex-direction

Options for ```flex-direction```. This CSS property defines the direction items are placed in the container:

```row```: Items are placed the same as the text direction.  
```row-reverse```: Items are placed opposite to the text direction.  
```column```: Items are placed top to bottom.  
```column-reverse```: Items are placed bottom to top.  

##### flex-wrap

```flex-wrap``` property specifies whether the flexible items should wrap or not. Default value is nowrap.

```nowrap```: Every item is fit to a single line.
```wrap```: Items wrap around to additional lines.
```wrap-reverse```: Items wrap around to additional lines in reverse.

##### flex-flow

The two properties ```flex-direction``` and ```flex-wrap``` are used so often together that the shorthand property
```flex-flow``` was created to combine them. This shorthand property accepts the value of one of the two properties
separated by a space.

##### align-content

Property modifies the behavior of the flex-wrap property. It is similar to align-items, but instead of aligning flex
items, it aligns flex lines. Default value is ```stretch```.

```flex-start```: Lines are packed at the top of the container.
```flex-end```: Lines are packed at the bottom of the container.
```center```: Lines are packed at the vertical center of the container.
```space-between```: Lines display with equal spacing between them.
```space-around```: Lines display with equal spacing around them.
```stretch```: Lines are stretched to fit the container.

```css
flex-flow: row wrap;
```

#### Individual properties for flexbox items

##### order

Sometimes reversing the row or column order of a container is not enough. In these cases, we can apply the order
property to individual items. By default, items have a value of 0, but we can use this property to also set it to a
positive or negative integer value (-2, -1, 0, 1, 2).

```css
.specify-picture {order: 2;}
```

##### align-self

Another property you can apply to individual items is ```align-self```. This property accepts the same values as
```align-items``` and its value for the specific item.

```css
.specify-picture {align-self: flex-end;}
```

If anything is not understood try flexbox cheatsheet where you can find all flexbox properties with illustrations. Just
visit <https://darekkay.com/dev/flexbox-cheatsheet.html>

You can play with this justify-content and play flexbox game calls flexbox froggy <https://flexboxfroggy.com/> which
covers flexbox vs bootstrap which will be covered in next step. Please, try this game to become be a prepared for create
any flexbox content.

#### CSS Positioning

```static``` Default CSS position for element
```relative``` like ```static``` but you can adjust it with ```top```, ```right```, ```bottom```, ```left```
```absolute``` Fixed to his parent and you can adjust selector with ```top```, ```right```, ```bottom```, ```left```
```fixed``` make static position of selector related to root parent. This is useful for menu for example (scrolling on
the page doesn't affect this). You can adjust it with ```top```, ```right```, ```bottom```, ```left```.
```float```: TBD
```sticky```: TBD
```z-index```: TBD

### CSS 3

CSS3 is a standard in this time. But some browsers still not have full support. Look at the useful links which helps
you resolve a problem which css3 feature is supported or what you have an alternatives.

#### Useful links for CSS3

CSS Browser Support Reference: <https://w3schools.com/cssref/css3_browsersupport.asp>  
Can I use it? <https://caniuse.com>  
What CSS to prefix? <http://shouldiprefix.com>  
Autoprefixer CSS online: <https://autoprefixer.github.io>

Try change your css file. Edit ```img``` selector with add ```transition: all 0.5s;``` and add event img:hover (on mouse
over).

```css
img {
    width: 450px;
    margin: 5px;
    border: 1px solid black;
    transition: all 0.5s;
}

img:hover {
    transform: scale(1.2);
}
```

This feature caused that your pictures will scale from ```1.0``` (initial size) to ```1.2``` (about 20% bigger). But
all not browsers supports this feature. Try this change on all browsers you have. If doesn't work, try search on
previous link which this feature is supported by your browser and which version (of course, check version of your
browser).

Some properties like ```user-select``` as well are not fully supported in all browsers. In time when I'm writing this
documentation ```user-select``` is supported in **Microsoft Edge** with ```-ms-``` prefix and with ```-webkit-``` prefix
in **Safari** for example. This means, that this is a new feature in this browser, it's not fully implemented, but you
can use it with prefix as experimental feature.

Another great resource is <https://caniuse.com> where you can check if some feature is implemented in current version
of many browsers (or with what version supports this feature) and also you can see there usage version of that browser
in market right now.

![Can I use it](https://i.imgur.com/ZZMDAIa.jpg "Can I use it")

As you can see on the picture, CSS3 ```transition``` property is fully supported expect **Opera Mini** in the present.

If you're more interested about about ```transition``` and properties joined with feature like ```scale```, ```rotate```
, try visit <https://thoughtbot.com/blog/transitions-and-transforms>. It's another great resource.

#### How check is your page is responsive

Many developers has only few browsers on laptop or desktop and probably 1 or 2 cell phones. So, how check you, how your
website will be images in many devices?

Answer is your browser. For example in **Google Chrome** go to **Developer tools** and you can click on the mobile phone
in top left corner (it should be icon next for select element which we used above).

>Responsive design should be your priority when you develop website

#### Improve your CSS skills

Try visit <https://www.freecodecamp.org/learn/responsive-web-design/basic-css> and you can training your css skills.

## Section 8: Bootstrap 4, Templates, And Building Your Startup Landing Page

### How to start With Bootstrap

Visit the page <https://getbootstrap.com> and you can click on download and download CSS and JS files and integrate to
your project or better way is just click to **Get started** button and integrate into your HTML files CSS stylesheet and
3 JS files.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css"
        integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
    <title>Bootstrap Landing Page</title>
</head>
<body>

    <h1>Content of your landing page will be here</h1>

    <script src="https://code.jquery.com/jquery-3.4.1.slim.min.js"
        integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n"
        crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"
        integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo"
        crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js"
        integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6"
        crossorigin="anonymous"></script>

</body>
</html>
```

>As you can see I put JS files to the end of my page!

As you can know, calling external JS file you can put anywhere. To the head or to your body. In this way it's better
to end of the page because we want functionality load after the content load. If you will put JS files at the start or
into your heading, user will waiting to load all JS files and then start begin your content. If course, sometimes you
need load javascript (before page rendering) because page rendering can depends on some JS files. But not in this case.

Now we can add Navigation bar. Just search **Navbar** in **Components** on bootstrap page or visit
<https://getbootstrap.com/docs/4.4/components/navbar>. Just copy the code from the page and put to your landing page.

Also, add **Jumbotron** and finally *Live Demo* code from **Modal** component. Your code should look like this:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css"
        integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
    <title>Bootstrap Landing Page</title>
</head>
<body>

    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <a class="navbar-brand" href="#">Navbar</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto">
            <li class="nav-item active">
                <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Link</a>
            </li>
            <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown"
                    aria-haspopup="true" aria-expanded="false">Dropdown</a>
                <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                <a class="dropdown-item" href="#">Action</a>
                <a class="dropdown-item" href="#">Another action</a>
                <div class="dropdown-divider"></div>
                <a class="dropdown-item" href="#">Something else here</a>
                </div>
            </li>
            <li class="nav-item">
                <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Disabled</a>
            </li>
            </ul>
            <form class="form-inline my-2 my-lg-0">
            <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
            <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
            </form>
        </div>
    </nav>

    <div class="jumbotron">
        <h1 class="display-4">Hello, world!</h1>
        <p class="lead">This is a simple hero unit, a simple jumbotron-style component for calling extra attention to featured content or information.</p>
        <hr class="my-4">
        <p>It uses utility classes for typography and spacing to space content out within the larger container.</p>
        <a class="btn btn-primary btn-lg" href="#" role="button">Learn more</a>
    </div>

    <!-- Button trigger modal -->
    <button type="button" class="btn btn-primary" data-toggle="modal" data-target="#exampleModal">
    Launch demo modal
    </button>

    <!-- Modal -->
    <div class="modal fade" id="exampleModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
        <div class="modal-dialog" role="document">
            <div class="modal-content">
            <div class="modal-header">
                <h5 class="modal-title" id="exampleModalLabel">Modal title</h5>
                <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                <span aria-hidden="true">&times;</span>
                </button>
            </div>
            <div class="modal-body">
                ...
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
                <button type="button" class="btn btn-primary">Save changes</button>
            </div>
            </div>
        </div>
    </div>

    <script src="https://code.jquery.com/jquery-3.4.1.slim.min.js"
        integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n"
        crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"
        integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo"
        crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js"
        integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6"
        crossorigin="anonymous"></script>

</body>
</html>
```

Yes, it's a bunch of copy-paste code but as you can see you have built responsive website with search button and
jumbotron panel and modal window (this part is addicted to javascript). And it's fully responsive. And how long it
takes? 5 or 10 minutes? Of course, now you can customize the website (edit navigation bar, change jumbotron). I show
you how we can change the button for **Modal Window**.

As you can see button **Launch demo modal** has ```class="btn btn-primary"```. If you click on **Buttons** in Bootstrap
page in **Components** you can see there are many button classes like *Primary*, *Secondary*, *Warning*, *Light* or
*Dark*. But I want make my button in pink color. The best way what can do is add next class like ```btn-pink``` and it
own in your own stylesheet (remember, you stylesheet must be loaded after the Bootstrap stylesheet because as you
remember, order in CSS is important criteria).

```css
.btn-pink {
    background-color: pink;
    color: black;
}

.btn-pink:hover {
    background-color: fuchsia;
    color: white;
}
```

Then change in your HTML

```html
<button type="button" class="btn btn-primary btn-pink" data-toggle="modal" data-target="#exampleModal">
    Try Me!
</button>
```

As you can see, now is your button is pink and fuchsia when your mouse over on the button. As you can see, border still
keeps from ```btn-primary```. You can change also border color and many others.

The second way is just *override* class ```btn-primary``` in your stylesheet. Just change what you want. Other
properties will keep from btn-primary declared before (in Bootstrap css file).

This should be result in big display

![Bootstrap landing Page Big](https://i.imgur.com/6gd52Ct.jpg "Bootstrap landing Page Big")

And it should looks like this in small displays and clicked on *hamburger menu* icon in top right.

![Bootstrap landing Page Small](https://i.imgur.com/Nki2eSe.jpg "Bootstrap landing Page Small")

### Bootstrap Grid

The most information can be found here <https://getbootstrap.com/docs/4.0/layout/grid>.

You shall have ```container``` class which determine your css grid. The ```row``` define the one row in grid.
```col-sm``` is a small column in a grid. The basic responsive grid with 3 columns you can determine as:

```html
<div class="container">
    <div class="row">
        <div class="col" style="background-color:mediumvioletred">
        One of three columns
        </div>
        <div class="col" style="background-color: mediumspringgreen;">
        One of three columns
        </div>
        <div class="col" style="background-color: lightblue;">
        One of three columns
        </div>
    </div>
</div>
```

>Important! Number of columns of each row is **12** as maximum!

One row can has **12** columns. ```col-sm``` defines small column with auto size. If column wil not fit in one
row, it will be wraped into more rows. You can try example above and simulate mobile device in your browser developer's
mode.

If you remove container the row will be on whole your space in block. ```container``` class defines the size according
to which column is used.  
For ```col-sm``` ```container``` class has **540px**. The exact sizes you find in description above.

As we explained above the size of row is **12** columns. If you want different sizes of columns you can make it like
this

```html
<div class="row">
    <div class="col col-2" style="background-color:mediumvioletred">
    One of three columns
    </div>
    <div class="col col-6" style="background-color: mediumspringgreen;">
    One of three columns
    </div>
    <div class="col col-4" style="background-color: lightblue;">
    One of three columns
</div>
```

>If your toal will be more than 12, last colulmn will be on next line

If you try this example

```html
<div class="row">
    <div class="col col-6 col-md-12" style="background-color:mediumvioletred">
    One of three columns
    </div>
    <div class="col col-3 col-md-6" style="background-color: mediumspringgreen;">
    One of three columns
    </div>
    <div class="col col-4 col-md-6" style="background-color: lightblue;">
    One of three columns
    </div>
</div>
```

Your result will be that first row will in whole row (space) and second and trird column will be divided at half in
second row.

>Try change ```col-4``` back to ```col-3``` and you will see that on small dispalys columns will be in row row and
>in bigger displays it will be divided.

Great grid system is the one of most advantages in **Bootstrap**.

This example divides your row in 2 rows util you screen will be not wider than *720px*.

```html
<div class="container">
    <div class="row">
        <div class="col-12 col-md-6" style="background-color:mediumvioletred">
        One of three columns
        </div>
        <div class="col-6 col-md-3" style="background-color: mediumspringgreen;">
        One of three columns
        </div>
        <div class="col-6 col-md-3" style="background-color: lightblue;">
        One of three columns
    </div>
</div>
```

My best example is have 3 columns on each row on small displays. 2 columns on medium and 1 column if you have large
display.

```html
<div class="container">
    <div class="row">
        <div class="col col-sm-12 col-md-6 col-lg-4" style="background-color:mediumvioletred">
        One of three columns
        </div>
        <div class="col col-sm-12 col-md-6 col-lg-4" style="background-color: mediumspringgreen;">
        One of three columns
        </div>
        <div class="col col-sm-12 col-md-12 col-lg-4" style="background-color: lightblue;">
        One of three columns
        </div>
    </div>
</div>
```

An you can mix with ```mixins``` (CSS pre processor), put columns in flexbox on top, middle or bottom. See on the
in start of this chapter

### Free resources for Web developer

Short sections. Just look at this resources:

<https://zerotomastery.io/resources/>

The links always changing in time, so keep this to have current view

Just small look on most interested:

- Metatag generator: <https://metatags.io>
- Lorem pixum (like lorem ipsum but images): <https://picsum.photos>
- Git branching: <https://learngitbranching.js.org>
- Logo maker: <https://www.squarespace.com/logo>

### Startup Landing Page

Creating startup landing page with simple email form. Step by step.

At first we will need 3 files. Header image (bigger is better), ```index.html``` file and style ```css``` file.

At first, we should make HTML file ```index.html```

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, shrink-to-fit=no">
    <title>Startup</title>

    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css?family=Montserrat" rel="stylesheet">

    <!-- Bootstrap CSS from a CDN. This way you don't have to include the bootstrap file yourself -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">

    <!-- Your own stylesheet -->
    <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
    <h1 class="text-uppercase">We &hearts; Hares</h1>
    <button>Find out more</button>
</body>
</html>
```

and css file

```css
body, html {
    /* We want cover full width and full height of page */
    width: 100%;
    height: 100%;
    font-family: 'Montserrat', sans-serif;
}
```

Please, look that we have 100% width and height of page because we want full cover display with our page,

**Wait!** We don't have a class ```text-uppercase``` with our stylesheet. How it's possible that we have uppercase
text? **Bootstrap**! Remember. You should just **remember** or *google* some useful classes in this framework.

Next step is background image. At first look here <https://css-tricks.com/perfect-full-page-background-image>.  
Add to your ```body, html``` this lines

```css
background: url(background.jpg) no-repeat center center fixed; 
-webkit-background-size: cover;
-moz-background-size: cover;
-o-background-size: cover;
background-size: cover;
```

This causes that your background will cover whole page.

>Don't forget to set correct path from your css file to your background file

The next this is edit our ugly button to **Bootstrap** button. Change our button in ```index.html```

```html
<button class="btn btn-primary">Find out more</button>
```

Yes, it's nicer but we want it even more nice. So we can add our class and then add it to our button. Please, remember
that you have almost unlimited classes in your element. So, let's make own css class for button

```css
.btn-cover {
    padding: 1rem 2rem;
    border-radius: 300px;
    font-weight: bold;
    text-transform: uppercase;
    background-color: limegreen;
    border: 1px solid white;
}

.btn-cover:hover {
    background-color: lime;
    border: 1px solid black;
    color: black;
}
```

We changed color, border and text color in our button. And made it more rounded with ```border-radius```. Do you
remember explaining css above?

In css file we can add ```<h1>``` element to make it more nice and prepare a ```heart``` class

```css
h1 {
    font-weight: bold;
    color: white;
    font-size: 3rem;
}

.heart {
    color: #a00;
    font-size: 4rem;
    text-shadow: -1px -1px 0 #fff, 1px -1px 0 #fff, -1px 1px 0 #fff, 1px 1px 0 #fff;
}
```

As next we want add small hr over our button. Let's start with this html snippet (just replace button and add
```<hr>``` above it)

```html
<hr>
<button class="btn btn-primary btn-cover">Find out more</button>
```

Now we must edit ```<hr>``` in our css class

```css
hr {
    border: 2px solid white;
    max-width: 60%;
}
```

```max-width``` defines selector's maximum width. And ```border``` is needed because it's only one way how to change
look of default ```<hr>```.

We made a bigger heading, even bigger heart symbol and made stroke around our heart by ```text-shadow```.
For more information how ```text-shadow``` works, visit <https://www.w3schools.com/cssref/css3_pr_text-shadow.asp>

> Try make a red heart to assign ```heart``` class as new element ```<span>``` in our heading

Now the page looks much better but we want a center it because this is still ugly. So, how we can do that?

At first, try look at <https://getbootstrap.com/docs/4.3/utilities/flex>

Now you shall wrap your body content into ```<div class="container">``` and into one ```row``` class.

```html
<div class="container">
    <div class="row">
        <h1 class="text-uppercase">We <span class="heart">&hearts;</span> Rabbits, Bunnies and Hares in whole world</h1>
        <hr>
        <button class="btn btn-primary btn-cover">Find out more</button>
    </div>
</div>
```

As you can see, we lost ```<hr>``` element. Because row is a one row and ```<hr>``` divider looks like another row.
We can solve it by divide our heading and rest of document into ```<header>``` element and ```section``` element with
**Bootstrap** class for text centering.

Look at ```container``` now

```html
<div class="container">
        <div class="row">
        <header class="text-center">
            <h1 class="text-uppercase">We <span class="heart">&hearts;</span> Rabbits, Bunnies and Hares in whole world</h1>
        </header>
        <section class="text-center">
            <hr>
            <button class="btn btn-primary btn-cover">Find out more</button>
        </section>
    </div>
</div>
```

Now, it's still looks strange. Why? Ah... Because we have 3 parts in one row. Do you remember that in CSS grid you have
exact **12** columns? So, try add next class after ```text-center```. And what class? Of course, ```col-12``` because
we want separate header as one row and section as the second one.

```html
<div class="container">
    ....
    <header class="text-center col-12">
    ....
    <section class="text-center col-12">
    ....
</div>
```

Now, we have almost expected result but our heading, line and button are not in center of the page. How we can solve it?
Do you remember to **Flexbox**? So, **Bootstrap** has own solution for flexbox utilities. Try visit
<https://getbootstrap.com/docs/4.4/utilities/flex>. Here you can find many classes for responsive variations.

To activate **flexbox** in **Boostrap** is use to ```d-flex``` class. We must add it to our ```<body>```.
But it's still not enough. Almost noting happens.

**Probably do you ask why ```<body>``` element? Because our ```container``` is a small ```<div>```. You can inspect our
```container``` in your browser by developers tools. If you find our ```container``` you can see that browser highlight
you just small block. And we center it over whole body.

Look at this picture:

![Container div](https://i.imgur.com/7Wuh52V.png "Container div")

So, clear? If you apply ```d-flex``` and ```align-items``` classes just to your container, it's center items only in
your container which is small with ```static``` position still on top on the page.  
Your ```<body>``` element should look like this:

```html
<body class="d-flex align-items-center">
```

**Remember!** You must set the body with 100% width and height. Otherwise, your ```<body>``` will be still small on
```<html>``` element and it will be still not centered vertically.

>If you want 100% height container, you can try add **bootstrap** class ```h-100``` into your container div.

The last this which want to do is add buffer (extra space) between our heading and ```section``` element. There are 2
ways. 1 one you know very well. It's enough add ```margin-bottom``` to your heading, right?  
Right, this can helps. But 2nd way is create extra buffer div without content. How we can do that? Just add a new div
with class ```buffer``` and ```col-12``` (because you want occupy whole row) and then create ```buffer``` height in your
css.

```html
...
</header>
<div class="buffer col-12"></div>
<section class="text-center col-12">
...
```

```css
height: 4rem
```

Advantage of 2nd way is that you can are more flexible to adding extra content, set another background color or anything
else. But choose better way for you. But don't forget to check it on mobile devices via your browser's
*developer console*.

>As homework you can try add extra buffer between heading and section as you seen above and also add space between
>line and button via 1st way

### Mailchimp

If you click on the button, nothing happens. But we want to contact us on extra page. In this solution we used
<https://mailchimp.com>. Mailchimp is an email marketing service. We use free account. With **Sign up** create your
contact. But it's recommended add real eamil adress in sign up process but not your home address (becuase you can get
lot of spam if your landing page will be online).

You must sign up, then create *Audience* and *Lading page* via Campaigns and make steps how page wants. After all
successful steps you should dive URL address like *<https://mailchi.mp/.................>*  It.s Enough to add this
address to ```<a>``` element around your button

```html
<a href="https://mailchi.mp/"><button class="btn btn-primary btn-cover">Find out more</button></a>
```

Then you can control the clicks on the buttons, real subscribers (your audience) and much more.

### Putting your website online

We created a more great pages. But all of them are still offline (on our local address). So, now we much put it online
because it's the alpha and omega of webpages, isn't?

