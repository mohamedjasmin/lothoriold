---
layout: wrapper
title:  "Development Diary #1"
date:   2018-12-05 12:00:00
categories: blog update
author: by Jalal
comments: true
published: true
---


The Lothori programmers have been hard at work to create a fantastic RPG with a heart-wrenching storyline. Every feature we have sought to implement, we have done to perfection, leaving no bug untouched. We have embarked upon a journey wherein we are creating an exciting game that will give players an experience like no other.

In the past week we have carried out a number of changes and additions to the game. For example, the user interface, or UI, has been reworked to better follow good programming habits. Many new scenes were created, breaking down the UI into smaller and smaller parts and were put together like lego. Breaking the UI down into smaller parts meant an increase in abstraction, which is beneficial. Regardless, the UI rework did not come without its hitches. Firstly, the UI overlay would not move with the character’s perspective when it moved into a different area of the map – something the end user would not appreciate! To resolve we had to remove the UI from the main map scene and add it to the scene which controls the camera viewpoint. 
Another addition was the new cave scene. This cave scene features a couple common enemies and a firepit. Having a new scene meant we had to do something to connect the main world scene to the cave scene. We did this through the use of signals, detecting whether the player was within a certain collision area, before loading another scene. The scripts to enter the cave and exit the cave were fairly similar, which saved us time.

Another feature added in relation to the camera, was the zoom-out feature, which enabled the player to get a better view of the map. The camera zooms out when the player presses the w button.
Furthermore, we added the ability to pause the game by pressing the key ‘p’. The result is the game essentially freezing, with a grey tint overlay.







{% if page.comments %} 
<div id="disqus_thread"></div>
<script>
(function() { // DON'T EDIT BELOW THIS LINE
var d = document, s = d.createElement('script');
s.src = 'https://lothori16.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
{% endif %}
