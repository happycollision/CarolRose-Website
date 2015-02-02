---
layout: page
title: Video/Audio
permalink: /media/
main_nav: true
sort: 0
---

{% comment %}


Carol,
You can add videos from YouTube and Vimeo here. For audio, use Soundcloud.
(Actually, you can use whatever you want, but your website styles expect those three sources)

Get the embed code from whatever the source material is, and wrap it in a `div` tag as shown below.
If you want to label your videos, do that with an `h3` tag. Caption with a `p` tag.



Tags look like this:


<div class="video"> </div>

<h3> </h3>

<p> </p>





With content inside them, they look like this:


<div class="video"> Your embed code here </div>

<h3> Your title here </h3>

<p> Your caption here </p>





Spaces and line returns inside tags don't matter, so you can make them easier to read when they are "nested" inside each other by using line returns liberally and by using spaces at the beginnings of lines.




<div class="video">

  <h3> This title goes inside the "video div" </h3>

  (Your Embed Code Goes Here)

  <p> If you have something to say about a video, it can go here </p>

</div>





<div class="audio">

  <h3> This title goes inside the "audio div" </h3>

  Your Embed Code Goes Here  

  <p> If you have something to say about a video, it can go here </p>

</div>




Here are two `div` sets that you can copy/paste below for your use. Remember to delete unused `h3` and `p` tags.


<div class="video">
  
  <h3> TITLE HERE </h3>
  
  EMBED CODE HERE
  
  <p> COMMENT HERE </p>

</div>


###############################################################################
###############################################################################
###############################################################################
###############################################################################
###############################################################################
###############################################################################

Everything below this next line will show up on your site.
{% endcomment %}





## Example Videos




<div class="video">

  <h3> Charlie Bit Me! </h3>

  <iframe width="640" height="480" src="https://www.youtube.com/embed/_OBlgSz8sSM?rel=0&amp;showinfo=0" frameborder="0" allowfullscreen></iframe>

  <p> And that really hurt! </p>

</div>




<div class="video">
  
  <iframe width="640" height="480" src="https://www.youtube.com/embed/CMNry4PE93Y?rel=0&amp;showinfo=0" frameborder="0" allowfullscreen></iframe>

  <p> I didn't include a title with this one, just because. You'll see in the code that there is no `h3` tag.</p>

</div>





<div class="video">
  
  <h3> Crazy Paper Video </h3>

  <iframe src="//player.vimeo.com/video/58022280?color=c9ff23&title=0&byline=0&portrait=0" width="500" height="281" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
  
</div>












## Example Audio

<div class="audio">
  
  <h3> The Sun My Heart - "Kansas City Star"</h3>

  <iframe width="100%" height="450" scrolling="no" frameborder="no" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/79954049&amp;auto_play=false&amp;hide_related=false&amp;show_comments=true&amp;show_user=true&amp;show_reposts=false&amp;visual=true"></iframe>

  <p> This is a girl I knew in high school and some dude I don't know. </p>

</div>



<div class="audio">
  
  <h3> Dan Denton - "Bklyn To KC"</h3>

  <iframe width="100%" height="150" scrolling="no" frameborder="no" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/184064894&amp;auto_play=false&amp;hide_related=false&amp;show_comments=true&amp;show_user=true&amp;show_reposts=false&amp;visual=false"></iframe>

  <p> My Bro. I futzed with the embed code on this one. Near the end, I changed it to "visual=false" instead of true and I changed the height near the beginning to 150 instead of 450.</p>

</div>





