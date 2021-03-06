---
layout: post
title: "Ruby Class"
modified:
categories: blog
excerpt:
tags: []
image:
feature:
date: 2014-06-15T18:59:24-04:00
---
<img id = "first_img" src ="http://rubylearning.com/images/class.gif"/>
<p>
EVERYTHING IS AN OBJECT. I'd like to clear the air before I started. Ruby is an OOP Language - An <strong>Object</strong> Oriented Programming Language. So what does that mean? That everything is an object. Everything... 

I would like to talk about Ruby Classes. What are Ruby Classes? Well to start off, they are a certain kind of object. You can, via the class, set what an object is, what an object does, and how an object works. Now the first thing that you must do is create a class.
<br>
<br>
<img class ="class_img" src = "http://i.minus.com/ibcCB9MEKIzYLK.png"/>
<br>
<br>
As you can see you first type in "class" then "any name you want for the class" and finally "end". For this example I will create a class called "Alien". 
<br>
<br>
Now I will set up the class so that it has some sort of "characteristic" or parameter. In order to do something like that I have to create a method, more specifically an initialize method. The initialize method is added when a new object is created. It is an instance method that takes an argument and assigns it to an instance variable.
<br>
<br>
This class Alien will have one parameter: alien_num. We put in the argument into the parenthesis that's next to the initialize. Once we've added that argument in, we also need to make sure that the argument is set as an instance variable. Instance variables are created by adding an @ in front of the word. This way I can use them in any method within the class and it'll retain the same identity throughout, unless I want to change it to something else. 
<br>
<br>    
<img class ="class_img" src = "http://i.minus.com/icvDxK97dIOX8.PNG"/>
<br>
<br>
After creating the initialize method. I would like to create another instance method. This instance method will take the argument @alien_num and pass it through some conditions that will return strings given the right conditions. I'd like to give the instance method the name attack, since I'd like to attack these aliens.
<br>
<br>
<img class ="class_img" src = "http://i7.minus.com/jbi5cSEUOdfcyg_e.jpg"/>
<br>
<br>
These are the conditions:
When alien_num is greater than or equal to 100, the method will return "Deploy laser sword."
When alien_num is less than or equal to 50 and greater than 5, the method will return "Fire laser gun."
When alien_num is less than or equal to 5, the method will return "Beat the up."
<br>
<br>
Although, I have set up these conditions, if I were to run this code nothing would happen. That's because we haven't created a new object that would be run through the conditions. 
<br>
<br>
Here are three objects that give three different alien_num so that all three conditions will be run.
<br>
<br>
<img class ="class_img" src = "http://i6.minus.com/jQjF2XPfe1Pua_e.jpg"/> 
<br>
<br>    
Now that we've created these objects, I'd like to run the attack method on each object. 
<br>
<br>
<img class ="class_img" src = "http://i3.minus.com/jbz1kFoA6ERjQ7_e.jpg"/>
<br>
<br>
I will run the code. These are the results:
<br>
<br>
<img class ="class_img" src = "http://i1.minus.com/jGfTK33bn5DPN_e.jpg"/>
<br>
<br>
Put all together, this is what the entire code should look like.
<br>
<br>
<img class ="class_img" src = "http://i3.minus.com/jbxv7v2pYpQj2N_e.jpg"/>



</p>
