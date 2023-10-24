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

# Your Resume. <br> Crafted with <span style="color:RoyalBlue">AI</span>. {#title}

<style>
img {
  max-width: 70%;
  height: auto;
}
</style>

<img class="mockup" alt="mockup" src="/assets/img/macbook-mockup.png"/>

## Vitae is a first-of-its-kind resume editor, empowered by AI. <br> Create a resume customized for ATS that suggests real-time edits tailored with keywords that job recruiters look for. {#subtitle}

</div>

<div id="particles-js"></div>

</div>

<div id="main-sections">

<div id="demo" class="page-section black-section">
  <div id="demo">
    <div class="section-title">How It Works</div>
      <div id="demo-list">
        <div class="container">
          <div class="image">
            <img src="/assets/img/demo_1.gif"/>
          </div>
          <div class="text">
            <h1>Fill out our interactive online editor with your resume entry. Vitae will evaluate your bullet point and score it based off of Grammar, Structure, Impact, Collaboration, Leadership, and Technical Skills.</h1>
          </div>
        </div>
        <div id="demo-break"></div>
        <div class="container">
          <img class="image" alt="Demo gif" src="/assets/img/demo_2.gif" />
          <span>Review any suggestions Vitae makes for your bullet point on the right. Choose an updated entry based off the skill you want to emphasize.</span>
        </div>
        <div id="demo-break"></div>
        <div class="demo">
          <img class="demo-img" alt="Demo gif" src="/assets/img/demo_3.gif" />
          <span>Download your resume—you're one step closer to getting your dream job!</span>
        </div>
    </div>
  </div>

<div id="clients-out" class="page-section">
  <div id="clients">
    <div class="client-title">Land a job with your dream company... </div>
    <div id="client-logos">
      {% for client in site.data.clients %}
        <a class="client-img" title="{{ client.name }}">
          <img alt="{{ client.name }}" src="/assets/img/logos/{{ client.img }}" />
        </a>
      {% endfor %}
    </div>
  </div>
</div>

<div class="cut-buffer"></div>

<div id="cta-out" class="page-section">
  <div id="cta">
    <div class="section-title">Have any feedback? We'd love to hear from you!</div><br/>
  </div>
  <a href="mailto:jiahao303@gmail.com?subject=Vitae Inquiry" class="actionbtn">
    <span class="far fa-envelope" aria-hidden="true"></span>
    Contact Us
  </a>
</div>

</div>