---
layout: post
title: "Enumerable #group_by"
modified:
categories: blog
excerpt:
tags: []
image:
  feature:
date: 2014-06-08T18:54:30-04:00
---
<h2>Enumerable #group_by</h2>
<p>The enumerable group_by method takes a list and groups it from parameters that the developer sets up. There are a variety of ways that a list can be grouped from the group_by method. I shall go over 2 situations.
But first let me create an array and make it equal a dinosaur variable:
<br>
<br>
dinosaur = ["Tyrranosaurus", "Allosaurus", "Brachiosaurus", "Triceratops", "Ankylosaurus", "Baryonyx"]
</p>

<h2>1st Situation</h2>
<p>Here we are grouping the strings of the array by the first letter of the dinosaur names</p>
<img src="http://i.minus.com/iJHvgAtDtytN1.png"/>
<p>As you can see the "T"s, "A"s, and "B"s are all grouped together.
<br>(The comment line shows what the output would be.)
</p>

<h2>2nd Situation</h2>
<p>Here we are grouping the strings of the array by the length of the dinosaur names</p>
<img src="http://i.minus.com/iKjwOYWvhV2Qx.png"/>
<p>As you can see the dinosaur names are grouped based on how many characters are in each name.</p>
