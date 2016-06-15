---
layout: post
title:  "Question for a Programmer"
date:   2016-06-15 08:37:00 +0545
categories: ["techy_articles","guide"]
author: "Manish Marahatta"
---
 So I was Browsing through questions in quora and i found this extremely essential article.

 Q:Everyone tells me to stop using PHP. How else can I build a login-system, members area, etc.?<br>
 A:Maybe everyone is telling you this because they care about you!

I have programmed in C, C++, C#, Java, JavaScript, Perl, Python, PHP, Bash, Sh, Awk, Visual Basic, VBScript, Assembly, Scala, FoxPro, PL/SQL, Basic, Pascal, and Logo. I first started coding at age 8, in 1981. I think I am experienced enough to bring my alternative point of view to this table.

There are so many answers here that I hesitate to add to it, but feel compelled as the answers only marginally address your question as asked, and nearly all of them present one point of view, one that seems to reinforce your present bias. If that bias is why you came here to ask this question or why you are reading and enjoying the answers then stop here. If you are really asking a question or are someone else sharing the question and feel it has not been answered then read on.

The primary question posed here:

“How else can I build a login-system, members area, etc. ?”

There are an infinite number of answers to this question, and that it is asked shows a need to spend some time searching the answer out. A login-system and members area can be built in any programming language that can read environment variables and write output to the console. This is the core of the standard that first enabled the dynamic web, CGI (Common Gateway Interface). If you are are a web developer and do not understand the contract represented by CGI, then you owe it to yourself to change that. While in many ways we have moved on from that paradigm, in just as many we have not, and a thorough understanding of the subject is very basic knowledge that should be held by every web developer.

I consider the Thomas Boutell book “CGI Programming in C and Perl” to be one of the best, and simplest on the subject. While the examples are in C and Perl, the more important part is the coverage of the CGI contract between the web server and the application.

As I said we have largely moved on from that, there are now many frameworks that mask the monotony of CGI programming and speed development, PHP is only one of those. In some cases the framework has gone so far as to eliminate the CGI paradigm completely, though this is only truly the case in the very most modern languages like Node.js. The others implement the CGI interface in a deep layer, such as WSGI, mod_php, or numerous other wrappers around CGI. I am not suggesting that you program in CGI, I am suggesting you should understand it......<br>

 <a href="https://www.quora.com/Everyone-tells-me-to-stop-using-PHP-How-else-can-I-build-a-login-system-members-area-etc">Please continue reading</a>