---
layout: page
title: About
comments: true
permalink: /about/
---

It's small library writen under C++ for 3d visualization with help of OpenGL 3.x. and a few repos with examples of using library.
The main target it's geting experance with 3d computer graphics.

The result of development must be visual 3d editor of Kochanek–Bartels splines.

### More Information

* The repo with library named glRender.
* The repo qtApp - example of using glRender in Qt application.
* The repo qtGlut - example of using glRender in GLUT application.

### Contact me

[sogimu@nxt.ru](mailto:sogimu@nxt.ru)

{% if page.comments %}
<div id="disqus_thread"></div>
<script>

/**
*  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
*  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables*/
/*
var disqus_config = function () {
this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
};
*/
(function() { // DON'T EDIT BELOW THIS LINE
var d = document, s = d.createElement('script');
s.src = '//https-glrender-github-io.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
{% endif %}
