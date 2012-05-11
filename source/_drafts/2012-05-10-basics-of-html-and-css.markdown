---
layout: post
type: text
title: "Basics of HTML and CSS"
date: 2012-05-10 22:09
text: 
  title: "Basics of HTML and CSS"
permalink: 2012/05/basics-of-html-and-css
---

When Tim Berners-Lee created the modern Internet in the 1990s, he created what all of the web is based on—HTML. HTML (or Hypertext Markup Language), along with CSS (Cascading Stylesheets) and JavaScript is what the web is written in. But before learning how to make websites, it is important to know how they work.

// Insert stuff about how client, servers work.

HTML is made of _tags_. A tag is surrounded by carots ("<" and ">"). For example, a tag for bolded text is `<strong>`. Most tags should be closed, so there is a closing tag. A closing tag is essentially the same as the opening tag, with the addition of a forward-slash after the first carot. So, the full markup for bolded text would be `<strong>Hello world!</strong>`.

Also encapsulated within an opening tag are _attributes_. Different tags have different attributes. A tag for a link would have the `href` attribute to designate the location of the link. So, in use, a link tag would look like `<a href="http://google.com">El Goog</a>`.

To make web pages, you nest tags within each other.

<code>
  <section>
    <p>I'm within a section tag!</p>
  </section>
</code>

// Moar...

Here's example of a valid HTML page.

<!DOCTYPE html>
<html>
  <head>
    <title>Hello world!</title>
  </head>
  <body>
    <p>Hello, world! I'm HTML!</p>
  </body>
</html>

_In HTML5, you can leave out a majority of this code—`<html>` is assumed._