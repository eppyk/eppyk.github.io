---
author: kieczkowska
comments: true
date: 2015-03-26 22:45:14+00:00
layout: post
link: https://kieczkowska.wordpress.com/2015/03/26/reasons-why-your-djangogirls-blog-isnt-working/
slug: reasons-why-your-djangogirls-blog-isnt-working
title: Reasons why your DjangoGirls blog isn’t working
wordpress_id: 8
categories:
- miscellaneous
tags:
- coding
- django
- djangogirls
- programming
- python
---

#### Stuck with the DjangoGirls tutorial? Your coach is busy at the moment? You’re doing the tutorial by yourself? Check out the most popular reasons why the blog isn’t working.

<blockquote>Don’t know what DjangoGirls is? Visit [djangogirls.org](http://djangogirls.org/) for more information, [tutorial.djangogirls.org](http://tutorial.djangogirls.org/) if you’re ready to build your first working web app now!</blockquote>

Basing on years of my biased experience as a DjangoGirls coach (joking, it’s not been even a year since DjangoGirls started, but the phrase sounds cool, doesn’t it?) I put together a list of the most popular reasons why the blog you’re creating suddenly doesn’t work anymore. 

#### **You’re in a wrong directory (folder)**

Please, always check if you're in the djangogirls directory! This is very important at all times, even (or especially!) when configuring git.

#### **The virtualenv is not activated**

How to check that? If at the beginning of a new line in your terminal you see (virtualenv), you’re fine. If not, go back and check for the command to activate the virtualenv (remember there are two - to create and to activate, and in this case we need the second one!).

#### **The file’s saved in a wrong directory**

#### **You used a command for different OS (operating system)**

Go back to the tutorial and check if the one you used is the right one.

#### **The server is not running**

If you’re refreshing your blog at the local address ([http://127.0.0.1:8000](http://127.0.0.1:8000)/) and the browsers tells you it’s not connected to the internet, you’re probably not running the server in your terminal. Search for the runserver command in the tutorial.

#### **It’s supposed not to work **

Always read one step ahead in the tutorial and see if actually the error you’re getting isn’t something you wanna see! The tutorial is designed in such a way that it teaches you to read the error messages and try to make sense out of them, so there’s a chance it’s actually a good thing that something is not working.

#### **There’s a typo**

Pretty self explanatory. Double check, please!

#### **You're not connected to the Internet** 

While Internet connection is not vital for every chapter of the tutorial, in some of them it’s a must. If you’re offline, you won’t be able to:

 - download Python, Django or a text editor;

 - download bootstrap;

 - see your blog at [xxx.herokuapp.com](http://xxx.herokuapp.com);

 - make your blog beautiful by having the Lobster font on it!

#### **'blog’ is not added to INSTALLED_APPS in mysite/settings.py**

OK, I know this may be strangely specific as opposed to the rest of the reasons, but surprisingly I’ve come across this problem often enough during my short career of a Django Girls coach (ha, ha). I don’t know why this step tends to be skipped, but it doesn’t hurt to check whether your ‘blog’ is where it should be. More context - it’s [chapter 9: “Django models”](http://tutorial.djangogirls.org/en/django_models/README.html).

Hope this post helps you even a tiny bit. Feel free to contact me if you have any suggestions as to what could be added to that list, I’d be great if we managed to create the ultimate Tutorial Checklist!
