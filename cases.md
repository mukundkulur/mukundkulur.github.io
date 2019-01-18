---
title: muku. | Work
permalink: "/cases.html"
layout: default
---
<!--
=================
Hero Area
================= 
-->
<section class="hero-area header-area">
    <div class="container">
        <div class="row">
            <div class="col-12 title">
                <div class="block text-center">
                    <p><h1>Cross-pollinating ideas, <br> methods, and insights<br> across domains.</h1></p>
                    <span class="borderline"></span>
                </div>
            </div>
        </div>
    </div>
</section> 
<!--
Start About Section
==================================== -->
<section class="about-2 section bg-gray" id="about">
    <div class="container">
        <div class="row">
            <div class="col-12 col-md-5">
                <h2>Driving the change to kick-start innovation.</h2>
            </div>
            <div class="col-12 col-md-7">
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quae deleniti ipsa labore necessitatibus culpa veritatis quo accusantium, neque enim ea ad eaque iure, quas tempore velit, quibusdam dolor illo! Explicabo.</p>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquid quisquam maiores iste soluta, nihil dolorem?</p>
            </div>
        </div>         
        <!-- End row -->
    </div>     
    <!-- End container -->
</section> 
<!-- End section -->

<!--
=================
Free tools section
================= 
-->
<section class="team section" id="team">
    <div class="container">
        <div class="row">
            <div class="col-md-12">
               <div class="block title">
                    <h4>My Works</h4>
                    <h1>SHOWCASE.</h1>
                    <span class="borderline"></span>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illum reiciendis quasi itaque, obcaecati atque sit!</p>
                </div>
            </div>
        </div>
        <div class="row">
        {% for cases in site.cases %}
             <!-- case -->
            <div class="col-12 col-md-3 col-sm-6">
                <div class="cases text-center">
                    <div class="case-photo">
                        <!-- case photo -->
                        <img class="img-fluid" src="{{site.url}}/images/case-index/{{ cases.photo-thumb }}.jpg" alt="">
                        <!-- /case photo -->
                    </div>
                    <!-- case name & designation -->
                    <div class="case-content">
                        <h3>{{ cases.title }}</h3>
                        <p>{{ cases.date | date_to_string }}</p>
                        <p>{{ cases.excerpt }}</p>
                    </div>
                    <!-- /case name & designation -->
                    <div class="case-more">
                        <a class="btn btn-main" href="{{ site.baseurl }}{{ cases.permalink }}">Read more</a>
                    </div>
                </div>
            </div>
            <!-- end case -->
        {% endfor %}
        </div>
        <!-- End row -->
    </div>
    <!-- End container -->
</section>


<!--
=================
Contact Section
================= 
-->
<section class="contact-us section bg-gray" id="contact">
  <div class="container mt-3">
    <div class="row">
      <div class="col">
        <div class="title text-center">
          <h4>How can I help you?</h4>
          <h2>ENQUIRIES.</h2>
          <span class="borderline"></span>
          <p>
          No two companies needs are the same. That's why I customize services on the need basis for each startup and any multi-nationals around the globe. Contact me to discuss how we can together find the right package to meet your needs. 
          No strings attached. <br><!-- 
          Do you have a problem you need to define?<br>
          Do you have an idea to take forward? <br>
          Do you need help to rethink your strategy?<br>
          Do you have a problem in taking your product to market?<br> -->
          </p>
        </div>
      </div>
    </div>
    <!-- End row -->

  <!-- Map & Contact Form -->
  <div class="row">
    <div id="map" class="col-12 col-md-6">
      <div class="mapouter">
        <div class="gmap_canvas">
          <iframe id="gmap_canvas" src="https://maps.google.com/maps?q=78%20kavya%20fort%2C%20east%20lokamanya%20street%20rspuram%20coimbatore&t=&z=13&ie=UTF8&iwloc=&output=embed" frameborder="0" scrolling="no" marginheight="0" marginwidth="0"></iframe>
        </div>
      </div>
    </div> 
    <!-- -->
    <div class="col-12 col-md-6 contact-form pt-2">
      <form id="contact-form" method="post" action="https://formspree.io/info@mukundkulur.com" role="form">
          <div class="form-group">
            <input type="text" placeholder="Your Name" class="form-control" name="name" id="name">
          </div>					
          <div class="form-group">
            <input type="email" placeholder="Your Email" class="form-control" name="email" id="email">
          </div>					
          <div class="form-group">
            <input type="text" placeholder="Subject" class="form-control" name="subject" id="subject">
          </div>
          <div class="form-group pt-4">
            <textarea rows="6" placeholder="Message" class="form-control" name="message" id="message"></textarea>	
          </div>					
          <div id="success" class="success">
            Thank you. The Mailman is on His Way :)
          </div>					
          <div id="error" class="error">
            Sorry, don't know what happened. Try later :(
          </div>					
          <div id="cf-submit" class="pt-1">
            <input type="submit" id="contact-submit" class="btn btn-transparent" value="Submit">
          </div>											
        </form>
    </div>
  </div>
</div>  
</section>
 <!-- end row -->
<!-- / End Contact Details -->
<!-- end container -->
<!-- end section -->