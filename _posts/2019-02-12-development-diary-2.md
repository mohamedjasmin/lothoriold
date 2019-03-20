---
layout: wrapper
title:  "Development Diary #2"
date:   2019-02-12 12:00:00
categories: blog update
author: by Jalal
comments: true
published: true
---

After taking a short break for the Christmas holidays, the programmers were back hard at work to improve the game and add as many useful features to the game. We started off by removing the hotkeys the MVP made use of to move from scene to scene and instead made it possible to move from scene to scene using in area signals, making the travelling between scenes much more natural and even makes the map look cleaner. The programmers also made many quality of life improvements as well as adding features. One improvement included being able to traverse between scenes naturally (i.e. leaving through the north town exit leads to south exit of main scene), instead of travelling to the origin point of a scene every time you move between scenes. Furthermore, the ability to save character information by including relevant information such as health in the global singleton script was added to improve the overall experience.  

One of the break-through additions to the game was the inventory system. Not only was it a dynamically loaded inventory system, it also meant the programmers were able to pick up items off the floor. The inventory system was overlaid on the UI; with an icon for the item and a small number for the amount collected. Having an inventory led us to the decision to have NPCs drop items instead of just blood – which takes us to another new addition; the coin pouch. The coin pouch was added in a similar fashion to the inventory, displayed on the UI with a counter. The NPCs drop coins so when the main character goes over the coins, it increments the coin pouch by 5. 

The inventory system was certainly a breakthrough achievement as it opened many other avenues. Once the code for the inventory system existed, the programmers were able to create functions that made use of the inventory system. The shop system works by going to a stall area in the town, opening a new scene with a few textured buttons with the icons of the products the character could potentially purchase if they had enough coins. If they had enough coins, their coin counter would be decremented, and the inventory counter would be incremented. 

Another feature our programmers added was the quest tracking system. The game is able to detect whether you have started a quest or not which is assisted by the data dictionary of all quests, detailing the name, status (i.e started or not), description, and reward in terms of coins. Once the dictionary existed, the programmers were able to create call functions in order to make a quest log. It was done dynamically so as more quests are added to the dictionary, it would in turn be added to the quest log.


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
