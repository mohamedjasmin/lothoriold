---
layout: wrapper
title:  "Development Diary #3"
date:   2019-02-12 12:00:00
categories: blog update
author: by Jalal
comments: true
published: true
---

After taking a short break for the Christmas holidays, the programmers were back hard at work to improve the game and add as many useful features to the game. We started off by removing the hotkeys the MVP made use of to move from scene to scene and instead made it possible to move from scene to scene using in area signals, making the travelling between scenes much more natural and even makes the map look cleaner. The programmers also made many quality of life improvements as well as adding features. One improvement included being able to traverse between scenes naturally (i.e. leaving through the north town exit leads to south exit of main scene), instead of travelling to the origin point of a scene every time you move between scenes. Furthermore, the ability to save character information by including relevant information such as health in the global singleton script was added to improve the overall experience.  




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
