---
layout: wrapper
title:  "Development Diary #4"
date:   2019-02-20 12:00:00
categories: blog update
author: by Jalal
comments: true
published: true
---

One of the break-through additions to the game was the inventory system. Not only was it a dynamically loaded inventory system, it also meant the programmers were able to pick up items off the floor. The inventory system was overlaid on the UI; with an icon for the item and a small number for the amount collected. Having an inventory led us to the decision to have NPCs drop items instead of just blood – which takes us to another new addition; the coin pouch. The coin pouch was added in a similar fashion to the inventory, displayed on the UI with a counter. The NPCs drop coins so when the main character goes over the coins, it increments the coin pouch by 5. 




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
