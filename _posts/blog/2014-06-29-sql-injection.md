---
layout: post
title: "SQL Injection"
modified:
categories: blog
excerpt:
tags: []
image:
feature:
date: 2014-06-29T19:05:14-04:00
---

<img id = "first_img" src ="http://imgs.xkcd.com/comics/exploits_of_a_mom.png"/>
<p>
SQL Injection is a code injection technique used to attack data applications with SQL statements. The attacker would insert/inject a SQL query via the input data to exploit and manipulate sensitive data within databases. SQL injection occurs when data enters a program from an untrusted source. 
<br><br>
Web applications allow people to submit and retrieve data to/from a database over the Internet using a web browser.
Features such as login pages, financial websites, search pages, and shopping carts are susceptible to SQL Injection attacks because the fields available for user input allow SQL statements to pass through and query the database directly.
<br><br>
<h3>SQL Injection Defense</h3>
There are a variety of methods that can be used to prevent SQL Injection Attacks.
<br>
<h4>Input restrictions</h4>
One can limit the amount of characters required in security situations so as to prevent any lengthy SQL codes from entering the program. One can also require a limited set of  characters to prevent any "creative" usage of the said characters.   
<br><br>
<h4>Sanitize user input</h4>
As it sounds, sanitizing the user input means checking and cleaning the input of a user for certain characters that appear suspicious. Flags would be raised if there were keywords used related to SQL queries. Even illegal characters such as ' or ; can be rejected and only a select handful of characters can be used instead. 
</p>
