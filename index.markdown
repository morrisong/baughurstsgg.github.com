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
          <a class="btn btn-large btn-primary" href="scouts">Join the adventure &raquo;</a>
        </div>
      </div>
    </div>
    <div class="item">
      <img src="images/beavers/Group.jpg" alt="">
      <div class="container">
        <div class="carousel-caption beavers">
          <h1 class="beavers"><span class="beaver-brown">Friends</span> <span class="beaver-sandy">and</span> <span class="beaver-red">Fun!</span></h1>
          <p class="lead beavers">That's our Motto</p>
          <a class="btn btn-large btn-beavers-primary" href="beavers">Join the beavers &raquo;</a>
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
          <a class="btn btn-large btn-cubs-primary" href="cubs">Join the cubs &raquo;</a>
        </div>
      </div>
    </div>
  </div>
  <a class="left carousel-control" href="#myCarousel" data-slide="prev">&lsaquo;</a>
  <a class="right carousel-control" href="#myCarousel" data-slide="next">&rsaquo;</a>
</div><!-- /.carousel -->

<!-- ##########NEWS###########-->
<hr class="span12 featurette-divider">

<section class="rowFluid">
<article class="span8">
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

<section class="span4">
  <img class="pull-right" src="images/group-camp.jpg">
</section>
</section>
<!-- ########## END OF NEWS ###########-->

<hr class="span12 featurette-divider">

  <!-- Three columns of text below the carousel -->
<section class="rowFluid">
  <article class="span4 guides">

## Baughurst Guides

The rainbow, brownie and guide groups welcome girls from 5 to 14 years.  

<a class="btn btn-guides-primary" href="guides">Guides &raquo;</a>
<a class="btn btn-brownies-primary" href="brownies">Brownies &raquo;</a>
<a class="btn btn-guides-alt" href="rainbows">Rainbows &raquo;</a>
</article><!-- /.span4 -->

<article class="span4">
<!-- Here's my badge to show support for Baughurst Scout and Guide Group. They raise funds with easyfundraising.org.uk -->
<a href="http://www.easyfundraising.org.uk/causes/baughurstsgg/?badge=mycause_large_DF8KIW_1WKLJR.png&amp;u=1WKLJR&amp;urp=1WKLJR" class="easyfundraisingBadge"><img src="http://www.easyfundraising.org.uk/images/thanks-for-badging/mycause_large_DF8KIW_1WKLJR.png" border="0" alt="easyfundraising.org.uk"></a>

Support us for **FREE** when you do your shopping on the web!
This is **absolutely FREE for you** but raises much needed funds for the group.  

<a class="btn btn-info" href="easy-fundraising">Find out more &raquo;</a>
  
</article><!-- /.span4 -->
  <article class="span4">
## Baughurst Scouts
The beaver, cub and scout groups welcome both boys and girls from 6 to 14 years.

The Baughurst scout group is part of the [Silchester District](http://www.silchester-scouts.org.uk), which is in turn part of the [Hampshire County](http://www.scouts-hants.org.uk).

<a class="btn btn-primary" href="scouts">Scouts &raquo;</a>
<a class="btn btn-cubs-primary" href="cubs">Cubs &raquo;</a>
<a class="btn btn-beavers-primary" href="beavers">Beavers &raquo;</a>
  </article><!-- /.span4 -->
  
</section><!-- /.row -->




<!-- /END THE FEATURETTES -->

<script>
  !function ($) {
    $(function(){
      // carousel demo
      $('#myCarousel').carousel()
    })
  }(window.jQuery)
</script>



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

