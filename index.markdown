---
layout: page
sidebar: false
comments: false
sharing: false
---

<!-- Carousel
================================================== -->
<div id="myCarousel" class="carousel slide">
  <div class="carousel-inner">
    <div class="item active">
      <img src="images/scouts/scouts-karting.jpg" alt="">
      <div class="container">
        <div class="carousel-caption scouts">
          <h1 class="alt-scouts">Scouts</h1>
          <h1 >Only go</h1>
          <h1 >camping?</h1>
          <p class="lead alt-scouts">Think again...</p>
          <a class="btn btn-large btn-primary" href="scouts">Join the adventure...</a>
        </div>
      </div>
    </div>
    <div class="item">
      <img src="images/beavers/lots-of-beavers.jpg" alt="">
      <div class="container">
        <div class="carousel-caption scouts">
          <h1 class="scouts">Friends and Fun!</h1>
          <p class="lead scouts">That's our Motto</p>
          <a class="btn btn-large btn-primary" href="beavers">Join the beavers...</a>
        </div>
      </div>
    </div>
    <div class="item">
      <img src="images/cubs/Group.jpg" alt="">
      <div class="container">
        <div class="carousel-caption cubs">
          <h1 class="cubs">Friendship,</h1><br> 
          <h1><span class="cubs-yellow">Fun,</span></h1><br> 
          <h1><span class="cubs-red">Adventure!</span></h1>
          <p class="lead cubs">we're Baughurst Cub Scouts!</p>
          <a class="btn btn-large btn-cubs-primary" href="cubs">Join the cubs...</a>
        </div>
      </div>
    </div>
  </div>
  <a class="left carousel-control" href="#myCarousel" data-slide="prev">&lsaquo;</a>
  <a class="right carousel-control" href="#myCarousel" data-slide="next">&rsaquo;</a>
</div><!-- /.carousel -->



<!-- Marketing messaging and featurettes
================================================== -->
<!-- Wrap the rest of the page in another container to center all the content. -->

<section class="container marketing">

  <!-- Three columns of text below the carousel -->
<section class="row">
  <article class="span4">
## Baughurst Scouts
The beaver, cub and scout groups welcome both boys and girls from 6 to 14 years.

The Baughurst scout group is part of the [Silchester District](http://www.silchester-scouts.org.uk), which is in turn part of the [Hampshire County](http://www.scouts-hants.org.uk).

<a class="btn" href="scouts">Scouts &raquo;</a>
<a class="btn" href="cubs">Cubs &raquo;</a>
<a class="btn" href="beavers">Beavers &raquo;</a>
  </article><!-- /.span4 -->
  <article class="span4">

## Baughurst Guides

The rainbow, brownie and guide groups welcome girls from 5 to 14 years.  

<a class="btn" href="guides">Guides &raquo;</a>
<a class="btn" href="brownies">Brownies &raquo;</a>
<a class="btn" href="rainbows">Rainbows &raquo;</a>
</article><!-- /.span4 -->
<article class="span4">
## Help us raise funds!
<!-- Here's my badge to show support for Baughurst Scout and Guide Group. They raise funds with easyfundraising.org.uk -->
<a href="http://www.easyfundraising.org.uk/causes/baughurstsgg/?badge=mycause_large_DF8KIW_1WKLJR.png&amp;u=1WKLJR&amp;urp=1WKLJR" class="easyfundraisingBadge"><img src="http://www.easyfundraising.org.uk/images/thanks-for-badging/mycause_large_DF8KIW_1WKLJR.png" border="0" alt="easyfundraising.org.uk"></a>

Support us for **FREE** when you do your shopping on the web!
This is **absolutely FREE for you** but raises much needed funds for the group.  
<a class="btn" href="easy-fundraising">Find out more &raquo;</a>
  
</article><!-- /.span4 -->
</section><!-- /.row -->


<!-- START THE FEATURETTES -->

<hr class="featurette-divider">

<article class="featurette">
  <img class="featurette-image pull-right" src="images/group-camp.jpg">
  <h2 class="featurette-heading">Joint camp <span class="muted"> celebrates our 20th anniversary!</span></h2>
  <p class="lead">All the sections gathered for a weekend of fun!</p>

The group celebrated a milestone year with a weekend camp at Thirtover. Rainbows, Beavers, Brownies, Cubs, Guides and Scouts gathered to celebrate 20 years of being a joint group.

Activities included a rope course, grass-sledging, archery, fire-lighting, and wood or soap-carving before the day ended with a barbecue and camp fire. The whole group had a brilliant time. 

<blockquote>
  <p>We wanted to celebrate the achievement of being together as a joint Scout and Guide group for 20 years and we think we are fairly unique.</p>
  <small><cite title="Source Title">Viv Salem, Group Guide Leader</cite></small>
</blockquote>

We had a longer wait than planned for our camp.  Twice we were forced to cancel the event as torrential rain swamped the camp site.  Doggedly we waited out the terrible weather of 2012.  Third time lucky!</p>
</article>

<hr class="featurette-divider">



<hr class="featurette-divider">

<!-- /END THE FEATURETTES -->

<script>
  !function ($) {
    $(function(){
      // carousel demo
      $('#myCarousel').carousel()
    })
  }(window.jQuery)
</script>

</section>  



<!--div class="span9">
  {% assign index = true %}
  {% for post in paginator.posts %}
  {% assign content = post.content %}
    <article>
      {% include article.html %}
    </article>
  {% endfor %}
  <ul class="pager">
    {% if paginator.next_page %}
    <li class="previous"><a href="{{paginator.next_page}}">&larr; Older</a></li>
    {% endif %}
    <li><a href="/blog/archives">Blog Archives</a></li>
    {% if paginator.previous_page %}
    <li class="next"><a href="{{paginator.previous_page}}">Newer &rarr;</a></li>
    {% endif %}
  </ul>
</div-->

