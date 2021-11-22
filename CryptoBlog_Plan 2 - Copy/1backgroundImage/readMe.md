
TDRN::

implement the icon in the nav



JUNK ::


i have a div around the nav, if i write position: static on it, then it will be fine, position change

write the position differently 
position fixed top nav bars

have establish a good menu, have established good margined nav with logo, all the names and annotations are by the book, everything scales, fix the thign wehre the burger icon wont show, need an icon to click so we get the menu, the menu should show active classes you're in as well as the page, and title must be correct, by the book, established a perfect species of nav menu scale header above main
like we were ttaught the main contetn, like all the blogsposts, they are unique to the site and the key to the specific site, all that goes in the main, all the lbogs, the nav is on all sites, jsut a tool to use the sites, so it is in header above all fo that, on top under meta,, nav querystring, api fetch foreach remove some, specifying is if you are without for each, foreach wants all of it, no  need to handpick ,for eahc allo oo ff iitttt, nav is completedd nav nav headerrr, main titles, as long as code is clean, titles anmd main and h1 h2 h3, then we're all goodd, main area specific to site, the actual reason for the site in mainnnnnn

from the internet: 
2

Normally, it's better to use "position: fixed;" for navigation bars on top. So, your css can do like this:

.logo-img{
    position: fixed;
    margin: 10px 15px 15px 10px;
    left: 0;
    display:inline;
}

.bg-div{
    background:#333;
    height: 50px;
}

.bg-div nav {
    position: fixed;
    display:inline;
    right: 0;
}




CHECK HERE:: https://github.com/Noroff-Education/lesson-task-htmlcss-module4-lesson4/tree/answers

FOR LAYOUT:: MODULE 4 ---READ COMMON LAYOUTS 4.4 MODULE ¤ HTML AND CSS

find the styling that actually styles the head, it's all in the header, just keep track of that , it's background color in tha header bacgrkound-color

  nav nav position: fixed; navv nav nav

the header creates a space that maintains the whole top of thee page, header isolates and is all around it's content, nothing wil slip, header is solid

problem, menu is good, find a way to get only the necessary code, pøosition absolute at the top, 
need the icon to display mobile menu
use the menu, top mennu, where is backdrop. 










TDRN::

implement nav, take inspiration from the onie already made 




  WIHD::


impllement this:: 

<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta name="description" content="Get real authentic, hand-crafted guitars from Guitar Kings" />
    <title>Guitar Kings | Home</title>
    <link rel="preconnect" href="https://fonts.gstatic.com" />
    <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet" />
    <link href="css/styles.css" rel="stylesheet" />
    <link href="css/index.css" rel="stylesheet" />
    <link href="css/media.css" rel="stylesheet" />
    <script src="https://kit.fontawesome.com/b318972c4d.js" crossorigin="anonymous"></script>
  </head>


hallo:::

 
<nav>: The Navigation Section element

The <nav> HTML element represents a section of a page whose purpose is to provide navigation links, either within the current document or to other documents. Common examples of navigation sections are menus, tables of contents, and indexes.




THIS IS THE RECOMMENDED MODULE eXAMPLE OF NAV ST>YLING:: 

nav {
  margin-left: 25px;
  display: none;
  position: fixed;
  top: 45px;
  background: var(--color-header-footer);
  z-index: 1000;
  right: 0px;
}

nav ul {
  padding: 0px;
}

nav li {
  display: block;
  padding: 20px 30px;
}

#hamburger-menu {
  display: none;
}

#hamburger-menu:checked ~ nav {
  display: block;
}