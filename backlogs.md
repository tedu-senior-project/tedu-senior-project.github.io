---
layout: index
title: Backlogs
---

<ul class="nav nav-tabs" id="myTab" role="tablist">
  <li class="nav-item" role="presentation">
    <a class="nav-link active" id="home-tab" data-toggle="tab" href="#home3" role="tab" aria-controls="home3" aria-selected="true">SPRINT 3 (Latest) </a>
  </li>
  <li class="nav-item" role="presentation">
    <a class="nav-link" id="home-tab" data-toggle="tab" href="#home2" role="tab" aria-controls="home2" aria-selected="false">SPRINT 2</a>
  </li>
  <li class="nav-item" role="presentation">
    <a class="nav-link" id="home-tab" data-toggle="tab" href="#home" role="tab" aria-controls="home" aria-selected="false">SPRINT 1 </a>
  </li>
  <li class="nav-item" role="presentation">
    <a class="nav-link" id="profile-tab" data-toggle="tab" href="#profile" role="tab" aria-controls="profile" aria-selected="false">CMPE 491</a>
  </li>
  
</ul>
<div class="tab-content" id="myTabContent"> 
<div class="tab-pane fade show active" id="home3" role="tabpanel" aria-labelledby="home-tab">

    {% include 492sprint3.html %}

  </div>
<div class="tab-pane fade show " id="home2" role="tabpanel" aria-labelledby="home-tab">

    {% include 492sprint2.html %}

  </div>
  <div class="tab-pane fade" id="home" role="tabpanel" aria-labelledby="home-tab">

    {% include 492sprint1.html %}

  </div>
  <div class="tab-pane fade" id="profile" role="tabpanel" aria-labelledby="profile-tab">
  

  {% include 491backlog.html %}


<br>

  </div>
</div>