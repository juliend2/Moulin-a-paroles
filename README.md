Moulin à paroles
================

Moulin à paroles is a minimalist blogging engine. So, to better define what it
is, I will explain what it is not:

* It doesn't aim to be SEO-friendly
* It doesn't have a WYSIWYG
* It doesn't follow the [12-factor app](https://12factor.net) methodology; it's just a PHP script.
* It's not meant to be hyper-performant; (it doesn't use a database; it just writes posts to flat files)

What it aims to be is:

* simple to use, install and configure
* simple to read and understand the code, because of the hyper-minimalist codebase
* beautiful
* fun to use (for the writer as for the reader)
* readable

# ideas / to dos / nice to haves / rationale

* Using [Hyphenator](http://mnater.github.io/Hyphenator/) for displaying the
  text more nicely in reading mode
* Using [Markdown](https://michelf.ca/projets/php-markdown/) for the text formatting in writing mode
* Using PHP for it to be hosted on any kind of non-cloud (read: affordable,
  simple and old-school kind of) web hosting, because I don't think the cloud
  hosting solutions à-la-Heroku make it more simple to create simple websites,
  when you don't want to conform to a certain style of programming. I love
  old-school web hostings (Dreamhost is my fav) because it's so simple to use.
* This tool is not designed to play well with social networks (I don't care
  enough about Facebook and friends to implement Open Graph in reading mode.
  Maybe that will change if I find a minimalist way to do it)
* I'd like to make it easy to add photo posts, so I might implement a script
  that will receive a WebHook and store an attached picture data blob, and make
  it available as a post, so we'll have text and image posts, a bit like on tumblr.
  The heavy lifting of taking the picture with one's smartphone and sending
  through a WebHook could be done via an [IFTTT](https://ifttt.com) Applet.
