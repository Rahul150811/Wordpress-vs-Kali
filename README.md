# Week-7-8---Wordpress-vs-Kali

This week we learned about Wordpress and about its vulnerability. I had problems and error with the setup installation but after I resolved the issues it was fun to learn and exploit the WP vulnerability.

WPscan - a wordpress security scanner, found 94 vulneraibilities in WP 4.2 version. With the knowledge I have gained from codepath, I selected few vulnerabilities which I was capable to exploit.

One of the vulnerabiity I exploited was HTML injection which is a type 2 cross-site scripting vulnerability (Stored XSS). I was able to embed my HTML script in order to get reverrse 
Whenever I access wpdistillery website, it shows the login page first.

CVE-2015-3440

![rnta0eqs](https://user-images.githubusercontent.com/76186933/162019260-76cb2c64-288b-4f2e-9a98-d6a629b9bb59.gif)




Playing with Wordpress project, I found one more vulnerability where I can add javacript code to the website title. This vulnerability is still exist on various website. For example, you trying to watch a movie on some free website and you click on one of the movie but instead playing, you are redirected to some other website or ad pops up. In below GIF, I tried to show how vulnerable wordpress 4.2 version was to XSS. 
![30bmt4tz](https://user-images.githubusercontent.com/76186933/162029400-3a7be0dc-0ea6-4613-a74e-4cbe8ee7fc22.gif)

From the above GIF, you can learn a lesson. Never click on untrusted or unknown link. It could be a severe attack.
