---
layout: post
title:  "Exam questions!"
date:   2015-11-04 07:55:00
categories: exam
---

###What do you think of pre-compiling your CSS?

####Compare to regular CSS
Pre-compiled CSS allows using variables, nesting and simple aritmetik to make the CSS files without writing the same code over and over again and makes them easier to maintain.
Other than that it is very similar to regular CSS, both how it is written and pre-compiled CSS makes regular CSS when it processes it.

####Which techniques did you use?
I used variables and nesting.

####Pros and cons?
Pros:
<ul>
  <li>Less css to maintain since variables and simple aritmetik can be used.</li>
  <li>Can use several files without affecting performance since they are put together when processed.</li>
  <li>Nesting, mostly a cleaner way to set nested values.</li>
</ul>
Cons:
<ul>
  <li>Harder to find what line problems occur.</li>
  <li>Harder to use than regular css since it requires tools to use it.</li>
  <li>Longer building time.</li>
</ul>

###What do you think of static site generators?
They are good because they make websites that are much faster than normally and they make independant sites that dont need databases, php and other things.

####What type of projects are they suitable for?
I think it is usually worth using static site generators if it can be done since it gives a huge performance boost.

When there is a lot of content that updates often I don't think a static website works very good, since it has to be rebuilt all the time.
Another example of when it would not be good to use static websites is when the website contains a lot of dynamic features, unless they are handled by other websites like disqus chat.

###What is robots.txt and how have you configure it for your site?
robots.txt is a text file that robots use to tell them what they are supposed to not look at. It is up to the robots to choose if they are following the rules in the file or not.
I set the rules to allow google bot on everything but not all other robots are not allowed anywhere.

###What is humans.txt and how have you configure it for your site?
humans.txt is a text file that says who made the site. The purpose of this file is to make it possible to give the developers credits without actually putting that information directly
 on the site since the owner of the site most likely dont want that information directly on the site.

###How did you implements comments to blog posts
I made an account on disqus and added localhost as one of the allowed hosts and copied the universal code and made a new file with it that got included at the end of the post.html file.
I also set comments to true in the YAML Front Matter at the top of post.html.

###What is Open Graph and how do you make use of it?
Open Graph makes sure that the right content is shown when linking the site on social media like facebook or twitter. This is done by setting meta values.
