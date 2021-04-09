---
name: Human Activity Recognition / HCI
image: https://cdn3.iconfinder.com/data/icons/corona-medical-activity/100/Patient_pickup_Icon-512.png
tools: [HCI / Mobile Healthcare Lab, 2017-2018]
<!-- external_url: https://www.google.com -->
---

<h2 style="text-align:center;">Human Activity Recognition / HCI</h2>
<br/>
<figure class="image">
    <img src="https://cdn.pixabay.com/photo/2015/07/02/10/29/smartwatch-828786_960_720.jpg" alt="drawing" style="width:500px;"/>
</figure>
<br/>

 <p>The projects were related <b>to recognize human activities from mobile devices</b>, such as wearable devices and mobile phones, in <b>Mobile Healthcare/HCI lab</b> and <b>IoT startup</b>. </p>

<br/>
<h4>Table of Contents</h4>
- <a href="#1">1. Activity Recognition with Wearable Devices</a><br/>
- <a href="#2">2. Human Proximity Recognition</a><br/>
- <a href="#3">3. Sleep Respiration Monitoring</a><br/>
- <a href="#4">4. 3D Virtual Mobile Interface</a><br/>

<br/>
<hr>
<br/>

<h3><a name="1">1. Activity Recognition with Wearable Devices</a></h3>
<br/>

<h4>Description</h4>
<p>

The goal of this project was <b>to develop fully automated table tennis scoring system based on smartwatches and mobile phones</b>. Smartwatches were used to recognize swing gestures and classify their swing types. Mobile phones were used to recognize which side a ball is dropped.

</p>

<p>
My role was to <b>develop human activity recognition algorithm</b> and <b>design the software architecture of the project</b>. Swing data were collected from Android smartwatches, and swing gestures were classified into 3 type: forehand, backhand and no swing(NULL), based on various sensors. The software architecture consisted of gesture recognition, <b>sound detection with FFT and Wifi-Direct</b> technology. 
</p>

<p>
To see details, please refer to the paper in 'Related Articles' below.
 </p>

<figure class="image">
    <img src="https://drive.google.com/uc?id=1BJr03AlFKioEElL6Ho67CuraVkJSxUVW" alt="drawing" style="width:1000px;"/>
    <figcaption class="image-caption"><i>Swing detection algorithm (top) and implementation of the architecture (bottom)</i></figcaption>
</figure>

<br/>
<h4>Skills</h4>
<div>
    <div class="chip lang">Java</div>
    <div class="chip theory">FFT</div>
    <div class="chip tools">Android</div>
    <div class="chip tools">Android Wearable</div>
</div>

<br/>

<h4>Period</h4>
1+ years
<div class="hori-timeline" dir="ltr">
    <ul class="list-inline events">
        <li class="list-inline-item event-list">
            <div class="px-4">
                <div class="event-date soft-primary">1 Mar</div>
                <h5 class="font-size-16">2017</h5>
                <p class="text-muted"></p>
            </div>
        </li>
        <li class="list-inline-item event-list">
            <div class="px-4">
                <div class="event-date soft-success">30 June</div>
                <h5 class="font-size-16">2018</h5>
                <p class="text-muted"></p>
            </div>
        </li>
    </ul>
</div>

<h4>Related Articles</h4>
<ul>
   <li><a href="http://jiita.org/v3n103/">[Paper] JIITA (2019)</a></li>
   <li><a href="http://www.iadisportal.org/digital-library/automatic-table-tennis-scoring-system-based-on-smart-wearable-devices">[Paper] IADIS (2018)</a></li>
   <li><a href="https://drive.google.com/file/d/19G6qlyg7FrMxjag_xdcJuz_fxEOXCcVE/view?usp=sharing">[Video] Demo</a></li>
   <li><a href="https://drive.google.com/file/d/19G6qlyg7FrMxjag_xdcJuz_fxEOXCcVE/view?usp=sharing">[Video] Swing detection</a></li>
</ul>
<br/>
<hr />
<br/>

<h3><a name="2">2. Human Proximity Recognition</a></h3>
<br/>

<h4>Description</h4>
<p>

The goal of this project was <b>to develop human proximity algorithm</b>to lock and unlock a smart bike lock automatically. 
<br/>
<br/>
My role was to <b>analyze Received Signal Strength Indication (RSSI), from Bluetooth Low Energy (BLE) from IoT devices and develop the proximity algorithm to detect owners' approach</b>. As the nRF chip generated raw RSSI data, noise in the raw data were filtered with Kalman filter.
</p>
<p>
To see details, please refer to the paper in 'Related Articles' below.
 </p>
<br/>

<div class="video-container"><iframe class="responsive-iframe" src="https://www.youtube.com/embed/E7TS0-HIPew" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>

<br/>
<h4>Skills</h4>
<div>
    <div class="chip lang">Java</div>
    <div class="chip theory">Kalman Filter</div>
    <div class="chip tools">nRF SDK</div>
    <div class="chip tools">Android</div>
</div>

<br/>

<h4>Period</h4>
7 months
<div class="hori-timeline" dir="ltr">
    <ul class="list-inline events">
        <li class="list-inline-item event-list">
            <div class="px-4">
                <div class="event-date soft-primary">31 July</div>
                <h5 class="font-size-16">2016</h5>
                <p class="text-muted"></p>
            </div>
        </li>
        <li class="list-inline-item event-list">
            <div class="px-4">
                <div class="event-date soft-success">1 March</div>
                <h5 class="font-size-16">2017</h5>
                <p class="text-muted"></p>
            </div>
        </li>
    </ul>
</div>

<h4>Related Articles</h4>
<ul>
   <li><a href="">[Video] NBC News (2017 MWC)</a></li>
   <li><a href="">[Video] AP News (2017 MWC)</a></li>
   <li><a href="">[Video] Reuter (2017 MWC)</a></li>
</ul>
<br/>
<hr />
<br/>

<h3><a name="3">3. Sleep Respiration Monitoring</a></h3>
<br/>

<h4>Description</h4>
<p>

The goal of this project was <b>to track human respiration rate on sleeping</b>.
<br/>
<br/>
My role was to <b>develop a server to collect respiration data on sleep and visualize status in real time</b>. The stress test was performed to measure how much data one server could handle in a second. 
</p>
<p>
To see details, please refer to the paper in 'Related Articles' below.
 </p>
<br/>
<figure class="image">
    <img src="https://ieeexplore.ieee.org/mediastore_new/IEEE/content/media/6287639/8948470/9075220/shin1-2989336-small.gif" alt="drawing" style="width:500px;"/>
    <figcaption class="image-caption"><i>Architecture of tele-monitoring system for sleep and respiration</i></figcaption>
</figure>

<br/>
<h4>Skills</h4>
<div>
    <div class="chip lang">Python</div>
    <div class="chip lang">HTML, CSS, Javascript</div>
    <div class="chip tools">Chart.js</div>
    <div class="chip tools">Django</div>
</div>

<br/>

<h4>Period</h4>
4 months
<div class="hori-timeline" dir="ltr">
    <ul class="list-inline events">
        <li class="list-inline-item event-list">
            <div class="px-4">
                <div class="event-date soft-primary">1 Mar</div>
                <h5 class="font-size-16">2020</h5>
                <p class="text-muted"></p>
            </div>
        </li>
        <li class="list-inline-item event-list">
            <div class="px-4">
                <div class="event-date soft-success">1 July</div>
                <h5 class="font-size-16">2020</h5>
                <p class="text-muted"></p>
            </div>
        </li>
    </ul>
</div>

<h4>Related Articles</h4>
<ul>
   <li><a href="https://ieeexplore.ieee.org/document/9075220?denied=">[Paper] IEEE Open Access (2020)</a></li>
</ul>
<br/>
<hr />
<br/>

<h3><a name="4">4. 3D Virtual Mobile Interface</a></h3>
<br/>

<h4>Description</h4>
<p>

The goal of this project was <b>to improve a smartphone usability for the elderly with conversational 3D virtual assistant</b>. To acheive the goal, 3D virtual companion replaced the original interface with speech-recognition and 3D interface. </p>

<p>

My role was to <b>design software architecture and develop application logic layer between 3D interface and NLP engine</b>. The application logic layer received user's speech, converted it into text, and transfer speech data to NLP engine. And next, the 3D virtual companion was rendered according to anlayzed intention based on users' speech. The implemented functions included making calls, sending text messages, checking weather condition and executing some applications.
</p>
<br/>
<figure class="image">
    <img src="https://drive.google.com/uc?id=1fTrkUyzRfRYR02-Xd5BU-7wnu9P9QWCj"/>
    <figcaption class="image-caption"><i>3D virtual companion acts depending on weather condition</i></figcaption>
</figure>

<br/>
<h4>Skills</h4>
<div>
    <div class="chip lang">Java</div>
    <div class="chip lang">C#</div>
    <div class="chip tools">Android</div>
    <div class="chip tools">Unity</div>
    <div class="chip tools">api.ai</div>
</div>

<br/>

<h4>Period</h4>
4 months
<div class="hori-timeline" dir="ltr">
    <ul class="list-inline events">
        <li class="list-inline-item event-list">
            <div class="px-4">
                <div class="event-date soft-primary">1 April</div>
                <h5 class="font-size-16">2017</h5>
                <p class="text-muted"></p>
            </div>
        </li>
        <li class="list-inline-item event-list">
            <div class="px-4">
                <div class="event-date soft-success">31 July</div>
                <h5 class="font-size-16">2017</h5>
                <p class="text-muted"></p>
            </div>
        </li>
    </ul>
</div>



<h4>Related Articles</h4>
<ul>
   <li><a href="https://ieeexplore.ieee.org/document/7988642">[Paper] ISUVR (2017)</a></li>
</ul>
<br/>
<hr />
<br/>

<h2>Other Projects</h2>
<p>You can go back or move to the other projects directly by pressing one of below items:</p>

<ul>
  <li><a href="https://garygitgit.github.io/projects">Overview</a></li>
  <li><a href="https://garygitgit.github.io/projects/11-system-on-chip">SoC Verification</a></li>
  <li><a href="https://garygitgit.github.io/projects/13-ml-data">Machine Learning/Data Analytics</a></li>
  <li><a href="https://garygitgit.github.io/projects/14-mobile">Mobile</a></li>
  <li><a href="https://garygitgit.github.io/projects/15-webpage">Web/Web Application</a></li>
  <li><a href="https://garygitgit.github.io/projects/16-sw-infra">Software Infrastructure (DevOps)</a></li>
</ul>

<!-- my style -->
<script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>
<style>
body{
  font-family: 'Roboto', sans-serif;
}
.chip{
    display: inline-block;
    padding: 0 15px;
    height: 30px;
    font-family: 'Roboto', sans-serif;
    font-size: 12px;
    line-height: 30px;
    border-radius: 25px;
    background-color: #f1f1f1;
}
.lang{
    background-color: #673AB7;
    color: #FFFFFF;
}
.db{
    background-color: #009688;
    color: #FFFFFF;
}
.frontend{
    background-color: #0D47A1;
    color: #FFFFFF;
}
.backend{
    background-color: #FF5722;
    color: #FFFFFF;
}
.devops{
    background-color: #607D8B;
    color: #FFFFFF;
}
.tools{
    background-color: #FF6F00;
    color: #FFFFFF;
}
.theory{
    background-color: #0288D1;
    color: #FFFFFF;
}
.hori-timeline .events {
    border-top: 3px solid #e9ecef;
}
.hori-timeline .events .event-list {
    display: block;
    position: relative;
    text-align: center;
    padding-top: 70px;
    margin-right: 0;
}
.hori-timeline .events .event-list:before {
    content: "";
    position: absolute;
    height: 36px;
    border-right: 2px dashed #dee2e6;
    top: 0;
}
.hori-timeline .events .event-list .event-date {
    position: absolute;
    top: 38px;
    left: 0;
    right: 0;
    width: 75px;
    margin: 0 auto;
    border-radius: 4px;
    padding: 2px 4px;
}
@media (min-width: 1140px) {
    .hori-timeline .events .event-list {
        display: inline-block;
        width: 24%;
        padding-top: 45px;
    }
    .hori-timeline .events .event-list .event-date {
        top: -12px;
    }
}
.soft-primary {
    background-color: rgb(64,144,203)!important;
    color: #FFFFFF;
}
.soft-success {
    background-color: rgb(71,189,154)!important;
    color: #FFFFFF;
}
.soft-danger {
    background-color: rgb(231,76,94)!important;
}
.soft-warning {
    background-color: rgb(249,213,112)!important;
}
.card {
    border: none;
    margin-bottom: 24px;
    -webkit-box-shadow: 0 0 13px 0 rgba(236,236,241,.44);
    box-shadow: 0 0 13px 0 rgba(236,236,241,.44);
}
.image-caption{
  text-align: center;
}
.video-container {
  position: relative;
  overflow: hidden;
  width: 100%;
  padding-top: 56.25%; /* 16:9 Aspect Ratio (divide 9 by 16 = 0.5625) */
}
/* Then style the iframe to fit in the container div with full height and width */
.responsive-iframe {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  width: 100%;
  height: 100%;
}
</style>
