---
layout: wrapper
title:  "Development Diary #5"
date:   2019-02-27 12:00:00
categories: blog update
author: by Jalal
comments: true
published: true
---


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
