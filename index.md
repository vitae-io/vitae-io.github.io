---
layout: base
title: "Vitae"
css:
  - /assets/css/index.css
ext-css:
  - //fonts.googleapis.com/css?family=Roboto:400,700
js:
  - /assets/js/index.js
ext-js:
  - //cdn.jsdelivr.net/npm/particles.js@2.0.0/particles.min.js
---

<div id="header" class="cut1" markdown="1">

<div id="header-inner" markdown="1">

# Your Resume. Crafted with AI. {#title}

## Vitae is a first-of-its-kind resume editor, empowered by AI. Create a resume customized for ATS that showcases your best accomplishments and suggests real-time edits tailored with keywords that job recruiters look for. {#subtitle}

</div>

<div id="particles-js"></div>

</div>

<div id="main-sections">

<div id="services-out" class="page-section cut1">
  <div id="demo">
    <div class="section-title">How It Works</div>
    <div id="services-list">
      <div class="service">
        <img class="service-img" alt="Service image" src="/assets/img/demo_1.gif" />
      </div>
      <div class="demo">
        <img class="service-img" alt="Service image" src="/assets/img/scale-flexiple/Successful completion of project.png" />
        <div class="service-text">Group workshops and private tutoring</div>
      </div>
      <div id="demo-break"></div>
      <div class="demo">
        <img class="service-img" alt="Service image" src="/assets/img/scale-flexiple/Bug tracking.png" />
        <div class="service-text">Code review and optimization of Shiny apps and workflows</div>
      </div>
      <div class="demo">
        <img class="service-img" alt="Service image" src="/assets/img/scale-flexiple/Work risk-free.png" />
        <div class="service-text">Professional quality R packages and custom solutions</div>
      </div>
    </div>

  </div>
</div>

<div id="testimonials" class="page-section grey-section cut2">
  <div id="testimonials">
    <div class="section-title">Testimonials</div>
    <div id="aboutus-text">
      It's a great service!
    </div>
  </div>
</div>

<div id="aboutus-out" class="page-section grey-section cut2">
  <div id="aboutus">
    <div class="section-title">About Us</div>
    <div id="aboutus-text">
      AttaliTech was launched in 2016 as the world's <b>first</b> Shiny consulting firm. The goal was simple: provide a one-stop shop for any and all of your Shiny needs, while adhering to the <b>highest standards</b>. Today, AttaliTech is a <b>global leader</b> in providing top quality R/Shiny services and is trusted by over 100 companies worldwide. We take pride in knowing you won't get better quality anywhere else.<br/><br/><b>We're certain of it.</b>
    </div>
  </div>
</div>

<div id="clients-out" class="page-section cut1">
  <div id="clients">
    <div class="section-title">Land a job with your dream company... </div>
    <div id="clients-subtitle">Clients range from startups to universities to Fortune 500 companies</div>
    <div id="client-logos">
      {% for client in site.data.clients %}
        <a class="client-img" href="{{ client.url }}" title="{{ client.name }}">
          <img alt="{{ client.name }}" src="/assets/img/logos/{{ client.img }}" />
        </a>
      {% endfor %}
    </div>
  </div>
</div>

<div class="cut-buffer"></div>

<div id="cta-out" class="page-section">
  <div id="cta">
    <div class="section-title">Take Your Shiny Apps to the Highest Level</div><br/>
  </div>
  <a href="/contact" class="actionbtn">
    <span class="far fa-envelope" aria-hidden="true"></span>
    Contact Us
  </a>
</div>

</div>