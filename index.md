---
layout: page
title: Home
feed: atom.xml
---
{% include JB/setup %}

  {% for post in site.posts %}
    
  <div class="full">
  	
    <h1 class="entry-title">
      <a href="{{ post.url }}" title="{{ post.title }}" rel="bookmark">{{ post.title }}</a>
    </h1>

    <div class="entry-content full-content">
      {{ post.content }}
      <!--<div class="clear"></div>-->
    </div>
  	  	    
  	  	    <p class="comments-link">
      <a href='{{post.url}}/#disqus_thread'>Add a Comment</a>
    </p>

    <!--Author name-->  
    <address class="signature">
    <a class="author" href="/contact.html">{{ post.author }}</a> 
    <span class="date">{{ post.date | date_to_long_string }}</span>
    <span class="location">{{ page.location }}</span>
  	</address><!--Author name-->
  	
  	<div class="rule"><hr/></div>
  	<p></p>
  	<!--<p class="alt-font tight">
      Posted in&nbsp;
      {% for category in post.categories %}
      <a href="/categories/{{ category }}" title="{{ category }}" rel="category tag">{{ category }}</a>
      {% endfor %}
    </p>-->

  </div>

{% endfor %}
    
<div align="center">
<em>Follow me via</em><br> <a href="/atom.xml"><img src="/images/rss.jpg"></a> <a href="https://twitter.com/#!/mickelsp"><img src="images/twitter.png"></a>
<a href="http://github.com/mickelsp"><img src="/images/github.png"></a> <a href="https://plus.google.com/114926118372366903256/"><img src="images/gplus.jpg"></a>
</div>

<script type="text/javascript">
    window._idl = {};
    _idl.variant = "banner";
    _idl.campaign = "idl_launch";
    (function() {
        var idl = document.createElement('script');
        idl.type = 'text/javascript';
        idl.async = true;
        idl.src = ('https:' == document.location.protocol ? 'https://' : 'http://') + 'members.internetdefenseleague.org/include/?url=' + (_idl.url || '') + '&campaign=' + (_idl.campaign || '') + '&variant=' + (_idl.variant || 'banner');
        document.getElementsByTagName('body')[0].appendChild(idl);
    })();
</script>
  



