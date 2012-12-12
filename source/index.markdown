---
layout: default
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
          <h1 >Only go camping?</h1>
          <p class="lead alt-scouts">Think again...</p>
          <a class="btn btn-large btn-primary" href="scouts">Join the adventure...</a>
        </div>
      </div>
    </div>
    <div class="item">
      <img src="images/scouts/scouts-karting.jpg" alt="">
      <div class="container">
        <div class="carousel-caption">
          <h1>Another example headline.</h1>
          <p class="lead">Cras justo odio, dapibus ac facilisis in, egestas eget quam. Donec id elit non mi porta gravida at eget metus. Nullam id dolor id nibh ultricies vehicula ut id elit.</p>
          <a class="btn btn-large btn-primary" href="#">Learn more</a>
        </div>
      </div>
    </div>
    <div class="item">
      <img src="images/scouts/scouts-karting.jpg" alt="">
      <div class="container">
        <div class="carousel-caption">
          <h1>One more for good measure.</h1>
          <p class="lead">Cras justo odio, dapibus ac facilisis in, egestas eget quam. Donec id elit non mi porta gravida at eget metus. Nullam id dolor id nibh ultricies vehicula ut id elit.</p>
          <a class="btn btn-large btn-primary" href="#">Browse gallery</a>
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

<div class="featurette">
  <img class="featurette-image pull-right" src="../assets/img/examples/browser-icon-chrome.png">
  <h2 class="featurette-heading">First featurette headling. <span class="muted">It'll blow your mind.</span></h2>
  <p class="lead">Donec ullamcorper nulla non metus auctor fringilla. Vestibulum id ligula porta felis euismod semper. Praesent commodo cursus magna, vel scelerisque nisl consectetur. Fusce dapibus, tellus ac cursus commodo.</p>
</div>

<hr class="featurette-divider">

<div class="featurette">
  <img class="featurette-image pull-left" src="../assets/img/examples/browser-icon-firefox.png">
  <h2 class="featurette-heading">Oh yeah, it's that good. <span class="muted">See for yourself.</span></h2>
  <p class="lead">Donec ullamcorper nulla non metus auctor fringilla. Vestibulum id ligula porta felis euismod semper. Praesent commodo cursus magna, vel scelerisque nisl consectetur. Fusce dapibus, tellus ac cursus commodo.</p>
</div>

<hr class="featurette-divider">

<div class="featurette">
  <img class="featurette-image pull-right" src="../assets/img/examples/browser-icon-safari.png">
  <h2 class="featurette-heading">And lastly, this one. <span class="muted">Checkmate.</span></h2>
  <p class="lead">Donec ullamcorper nulla non metus auctor fringilla. Vestibulum id ligula porta felis euismod semper. Praesent commodo cursus magna, vel scelerisque nisl consectetur. Fusce dapibus, tellus ac cursus commodo.</p>
</div>

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

