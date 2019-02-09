---

layout: case-template 
date: 2014-09-01 00:00:00 Z
permalink: "/cases/icarusnova.html"

title: Icarusnova
category: Product Management
tags:
- Product Management
- Design Strategy
client: Finnair
photo-thumb: icarusnova
excerpt: Translating consumer and digital trends into possible future scenarios on how the future airport services would be.

---

<!--
Start About Section
==================================== -->
<section class="about-2 section bg-gray" id="about">
    <div class="container">
        <div class="row">
            <div class="col-12 col-md-5">
                <h4>Challenge </h4>
                <h2>Radically innovate the airport services.</h2>
            </div>
            <div class="col-12 col-md-7">
                <p>
                <b>Icarus Nova Discovery</b> is a product development firm largely working in the medical device and development sector.
                </p>
            </div>
        </div>         
        <!-- End row -->
    </div>     
    <!-- End container -->
</section> 
<!-- End section -->

<!-- Start Process Section -->
<section class="about section">
        <div class="container">
                <div class="row">
                        <div class="col-md-12">
                           <div class="block title">
                                <h4>Solution </h4>
                                <h1>Welcome to the future <br> of airport experience. </h1>
                                <span class="borderline"></span>
                <p>
Your ultimate travel assistant, Finn-e, greets you at the gate taking over all the operations from check-in to leisure activities within the airport. It intimates you with updates on your flight schedule and transforms into a complete in-flight assistant during the flight. Finn-e covers all your needs from airport to airport, letting you relax as you move around the globe.                 </p>
                            </div>
                        </div>
                    </div>
          <div class="row mb-50 justify-content-center">
            <div class="col-md-5 col-sm-12 pt-5">
              <img src="/images/cases/{{ page.client }}/1.jpg" class="img-fluid rounded shadow" alt="">
            </div>
            <div class="col-md-5 col-sm-12">
                <div class="content text-left">
                    <h3>Mapping technological trends.</h3>
                    <p>
                        Profiling emergent and future technologies based on their potential in providing value and benefits to different stakeholders - user, customers, service technicians.  
                    </p>
                </div>
            </div>
          </div>
          <div class="row mb-50 justify-content-center">
            <div class="col-md-5 col-sm-12">
                <div class="content text-right">
                    <h3>Digitalisation of service lifecycle.</h3>
                    <p>
                        Forecasted multiple future scenarios across different time periods to depict the utilisation of digital technologies throughout the service lifecycle operations.  
                    </p>
                </div>
            </div>
            <div class="col-md-5 col-sm-12 text-center pt-2" id="about-img1">
                <img src="/images/cases/{{ page.client }}/3.png" class="img-fluid rounded shadow" alt="">
            </div>
          </div>
          <div class="row mb-50 justify-content-center">
              <div class="col-md-5 col-sm-12">
                <img src="/images/cases/{{ page.client }}/7.jpg" class="img-fluid rounded shadow" alt="">
              </div>
              <div class="col-md-5 col-sm-12">
                <div class="content text-left">
                <h3>Transformation strategy framework.</h3>
                <p>
                        Profiling different technologies and their impact on the different stakeholders throughout the service lifecycle operations.  
                    </p>
                </div>
              </div>
            </div>
            <img src="{{site.url}}/images/cases/wartsila/0.jpg" class="case-poster text-center">
        <!-- End row -->
        </div> 
        <!-- End container -->
</section> 
<!-- End Process section -->

<div class="main-column">
<h1>{{ page.title }}</h1>
<h3>{{ page.category }}</h3>
<br>
<p>
<strong>Welcome to the future of travelling.</strong><br>
Finnair required us to conceptualise the future of the aircraft boarding experience. Through our research, journey mapping and systems mapping we conceptualised a robotic personal assistant. 
</p>
<p>
Your ultimate travel assistant, Finn-e, greets you at the gate taking over all the operations from check-in to leisure activities within the airport. It intimates you with updates on your flight schedule and transforms into a complete in-flight assistant during the flight. Finn-e covers all your needs from airport to airport, letting you relax as you move around the globe. 
</p>
</div>

<div class="main-column">
<h1>{{ page.title }}</h1>
<h3>{{ page.category }}</h3>
<br>
<p>
I did my internship at <strong>Icarus Nova</strong>. Icarus was a product development firm, rebranding themselves to compete in the medical device and development sector. 

My work was to audit their design and development process for their Entraview Lean project, with a core focus on project planning, collaboration and execution. Using design methods and benchmarking, I analysed the operations and provided them results that enable them to better understand their processes and activities. 

In addition I worked in researching the market to identify possible business development opportunities. A short strategy for market penetration and customer development was proposed. 
</p>
</div>

<div class="side-column">
<ul>
<h4> My role </h4>
<li>Product Management</li>
<li>Project Audit</li>
<li>Stakeholder Analysis</li>
<li>Process Development</li>
<li>Market Research</li> 
<br>

<div class="gallery">
{% for image in site.static_files %}
{% assign pathname = "/images/work/Icarusnova/" %}
{% if image.path contains pathname %}
<img src="{{ site.baseurl }}{{ image.path }}" alt="{{ page.title }} - image" class="gallery-item">
{% endif %}
{% endfor %}