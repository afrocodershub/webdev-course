# LEARNING TO CRAWL
# BEGINNING HTML AND CSS

Okay so what are we doing here now , why are you here today ?.
Let me guess, you want to be a **web developer** !!. Wow that's
great news. I assure you that, you are at the right place and
you will do just fine with the **Afro Coders Hub** family.

Now let's see ...
  If you are on this page right now, if you have chosen to
be a developer and have taken the first step to search for a way,
then in your mind , you are a web developer now.


  So you are walking down the street and you meet this new friend
who wants to know more about you. There is no time for you to
tell him/her about all the cool stuff about you. And you want to,
so you get an idea and think , "Why don't I give my new friend a link to
my personal website where he/she will know me and get all my available
contacts, also I have posted my work there too, so he/she will know I
am a web developer"
"


Well then there is a problem, you don't have a website. You don't even
know how to go about it. Fortunately for today, you are gonna build one,
and understand how it works like a boss !!.

For any task to be completed , one needs tools. If a carpenter wants to
build a chair, he needs tools like a hammer, chisel and other carpentry
stuff. For a web developer you will also need tools.

Now here are the basic tools you are gonna need for your website.

* Text Editor
* Browser
* HyperText Markup Language
* Cascading Style Sheet

And also you are gonna need materials like a carpenter would need wood.
The materials you generally need is content ( text and media ). And you are
going to use the above mentioned tools to process the content into a website
and showcase it to the world through the internet.


## Enough of the talk let's do the do !

> " I hear and I forget. I see and I remember. I do and I understand. "
> Confucius

### 1. Getting Started

Organization is necessary so we create a folder and name it
**personal_website** and create three new folders inside it and name one  **css** and the other **fonts** and the last **img**

  Now open your text editor,  i recommend [atom text editor](https://atom.io) and create a new file called *index.html*
and save it into the **personal_website/** folder you created.

  And you might me wondering, what is this *index.html* thingie !!
. Well this file you just created is a file that your browser can use to display the content you want in an orgainized and meaningful manner. So now what content do you  want to display with your  browser. Stuff like your picture , your name , your short bio, links to your social media accounts and your interests. Right ??

Now open *index.html* and fill it with this code (your first code !!)

``` html
<!DOCTYPE>
  <html>
  <head>
    <title>afrocat is my name</title>
  </head>
  <body>
    <header>
      <h1> Afrocat </h1>
      <p>
        Welcome to my website !!!
      </p>
    </header>
    <img src="img/" alt="my picture" />
    <div class="bio">
      Pellentesque et dignissim lorem, ac interdum ipsum.
      Cras nec commodo lacus. Sed velit diam, ornare non
      est vel, faucibus tempor nisl. Quisque massa velit,
       laoreet nec fringilla a, maximus et nisi. Integer
       justo mi, posuere a quam id, eleifend dapibus eros.
       Proin sed libero dui. Nulla porttitor enim quis mi
       imperdiet ullamcorper. Nulla ac orci blandit magna
       rhoncus aliquam a et mi. Fusce ullamcorper, dui at
       suscipit ornare, eros quam fermentum purus, id elem
       entum ipsum purus eget libero. Duis nec justo ac mi
       commodo finibus. Nunc dictum volutpat odio at iacul
       is.
    </div>
    <div class="interest">
      <h3> My skills and interest </h3>
      <ul>
        <li>Dancing</li>
        <li>Taking pictures of my laptop</li>
        <li>Creating websites</li>
        <li>Reading Charles Bukowski</li>
      </ul>
    </div>

  </body>
  </html>
```
