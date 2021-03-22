---
name: Human Activity Recognition / HCI
image: https://cdn3.iconfinder.com/data/icons/corona-medical-activity/100/Patient_pickup_Icon-512.png
tools: [HCI / Mobile Healthcare Lab, 2017-2018]
<!-- external_url: https://www.google.com -->
---

<h2 style="text-align:center;"><code>Human Activity Recognition / HCI</code></h2>
<br/>
<figure class="image">
    <img src="https://cdn.pixabay.com/photo/2015/07/02/10/29/smartwatch-828786_960_720.jpg" alt="drawing" style="width:500px;"/>
</figure>
<br/>
<code>
    The projects are related <b>to recognize human activities from mobile devices</b>, such as wearable devices and mobile devices, in <b>Mobile Healthcare/HCI lab</b> and <b>IoT startup</b>.
</code>
<br/><br/>
<h4><code>Table of Contents</code></h4>
- <code><a href="#1">1. Sleep Respiration Monitoring</a></code><br/>
- <code><a href="#2">2. Activity Recognition with Wearable Devices</a></code><br/>
- <code><a href="#3">3. Human Proximity Recognition</a><code><br/>
- <code><a href="#4">4. 3D Virtual Mobile Interface</a><code><br/>

<br/>
<hr>
<br/>

<h3><code><a name="1"> 1. Sleep Respiration Monitoring</a></code></h3>
<br/>

<h4><code>Description</code></h4>
<p>
<code>
This project has been motivated <b>to track human respiration rate on sleeping</b>.
<br/>
<br/>
My role was to <b>develop a server to collect respiration data on sleep and display the status in real time</b>. The system had also gone through stree test to measure how the server would handle real time data given sleep respiration data transferred in high rate. 
</code></p>
<p><code>
To see details, please refer to the paper in 'Related Articles' below.
 </code></p>
<br/>
<figure class="image">
    <img src="https://ieeexplore.ieee.org/mediastore_new/IEEE/content/media/6287639/8948470/9075220/shin1-2989336-small.gif" alt="drawing" style="width:500px;"/>
    <figcaption class="image-caption"><i><code>Architecture of tele-monitoring system for sleep and respiration</code></i></figcaption>
</figure>

<br/>
<h4><code>Skills</code></h4>
<div>
    <div class="chip lang">Python</div>
    <div class="chip lang">HTML, CSS, Javascript</div>
    <div class="chip tools">Chart.js</div>
    <div class="chip tools">Django</div>
</div>

<br/>

<h4><code>Period</code></h4>
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

<h4><code>Related Articles</code></h4>
<ul>
   <li><a href="https://ieeexplore.ieee.org/document/9075220?denied="><code>[Paper] IEEE Open Access (2020)</code></a></li>
</ul>
<br/>
<hr />
<br/>

<h3><code><a name="2"> 2. Activity Recognition with Wearable Devices</a></code></h3>
<br/>

<h4><code>Description</code></h4>
<p>
<code>
This project has been motivated <b>to develop fully automated table tennis scoring system based on wearble devices and mobile phones</b>. Wearable devices have been used to recognize and classify users' swing gesture and swing types, and mobile phones have been used to recognize which side the ball is dropped.
</code>
</p>

<p><code>
My role was to <b>analyze swing gestures and design the arcthitecture of the project</b>. Swing data have been collected from Android smartwatch and swing gestures are classified into 3 type: forehand, backhand and no swing. <b>Accelerometer and gravity sensors</b> are used to detect swing gestures, and the noise data has been filtered with filtering algorithms. The project architecture has been designed to integrate gesture recognition, <b>sound detection with FFT and Wifi-Direct</b> for communication. 
</code></p>

<p><code>
To see details, please refer to the paper in 'Related Articles' below.
 </code></p>

<figure class="image">
    <img src="https://drive.google.com/uc?id=1BJr03AlFKioEElL6Ho67CuraVkJSxUVW" alt="drawing" style="width:1000px;"/>
    <figcaption class="image-caption"><i><code>Swing detection algorithm (top) and implementation of the architecture (bottom)</code></i></figcaption>
</figure>

<br/>
<h4><code>Skills</code></h4>
<div>
    <div class="chip lang">Python</div>
    <div class="chip db">Oracle PL/SQL</div>
    <div class="chip theory">Reinforcement Learning</div>
    <div class="chip theory">DDQN</div>
    <div class="chip tools">Keras</div>
    <div class="chip tools">PyQT</div>
    <div class="chip tools">Pandas</div>
    <div class="chip tools">Numpy</div>
    <div class="chip tools">Seaborn</div>
</div>

<br/>

<h4><code>Period</code></h4>
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

<h4><code>Related Articles</code></h4>
<ul>
   <li><a href="http://jiita.org/v3n103/"><code>[Paper] JIITA (2019)</code></a></li>
   <li><a href="http://www.iadisportal.org/digital-library/automatic-table-tennis-scoring-system-based-on-smart-wearable-devices"><code>[Paper] IADIS (2018)</code></a></li>
   <li><a href="https://drive.google.com/file/d/19G6qlyg7FrMxjag_xdcJuz_fxEOXCcVE/view?usp=sharing"><code>[Video] Demo</code></a></li>
   <li><a href="https://drive.google.com/file/d/19G6qlyg7FrMxjag_xdcJuz_fxEOXCcVE/view?usp=sharing"><code>[Video] Swing detection</code></a></li>
</ul>
<br/>
<hr />
<br/>

<h3><code><a name="3"> 3. Human Proximity Recognition</a></code></h3>
<br/>

<h4><code>Description</code></h4>
<p>
<code>
This project has been motivated <b>to develop human proximity algorithm to lock and unlock a smart bike lock</b>. 
<br/>
<br/>
My role was to <b>analyze RSSI, Received Signal Strength Indication, from Bluetooth Low Energy (BLE) in the Android phone and develop the algorithm to detect owners' presence</b>. Kalman filter has been used to filter the noise in RSSI and detect owners.
</code></p>
<p><code>
To see details, please refer to the paper in 'Related Articles' below.
 </code></p>
<br/>

<div class="container"><iframe class="responsive-iframe" src="https://www.youtube.com/embed/E7TS0-HIPew" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<br/>
<h4><code>Skills</code></h4>
<div>
    <div class="chip lang">Java</div>
    <div class="chip theory">Kalman Filter</div>
    <div class="chip tools">nRF SDK</div>
    <div class="chip tools">Android</div>
</div>

<br/>

<h4><code>Period</code></h4>
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

<h4><code>Related Articles</code></h4>
<ul>
   <li><a href=""><code>[Video] NBC News (2017 MWC)</code></a></li>
   <li><a href=""><code>[Video] AP News (2017 MWC)</code></a></li>
   <li><a href=""><code>[Video] Reuter (2017 MWC)</code></a></li>
</ul>
<br/>
<hr />
<br/>
<h3><code><a name="4"> 4. 3D Virtual Mobile Interface</a></code></h3>
<br/>

<h4><code>Description</code></h4>
<p>
<code>
This project has been motivated <b>to improve smartphone usabilty for the elderly.</b>. To acheive the goal, 3D virtual companion has replaced the original interface with speech-recognition and 3D interface. </code></p>

<p>
<code>
My role was to <b>design the overall architecture and develop application logic layer between 3D interface and NLP engine</b>. The application logic layer received a user's speech from STT, reorganize texts and transfer speech data to NLP engine. And next, 3D virtual companion was rendered according to anlayzed intention based on users' speech. The implemented functions included making calls, sending text messages, checking weather condition and executing some applications.
</code></p>
<br/>
<figure class="image">
    <img src="https://drive.google.com/uc?id=1fTrkUyzRfRYR02-Xd5BU-7wnu9P9QWCj"/>
    <figcaption class="image-caption"><i><code>3D virtual companion acts depending on the weather</code></i></figcaption>
</figure>

<br/>
<h4><code>Skills</code></h4>
<div>
    <div class="chip lang">Java</div>
    <div class="chip lang">C#</div>
    <div class="chip tools">Android</div>
    <div class="chip tools">Unity</div>
    <div class="chip tools">api.ai</div>
</div>

<br/>

<h4><code>Period</code></h4>
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

<h4><code>Related Articles</code></h4>
<ul>
   <li><a href="https://ieeexplore.ieee.org/document/7988642"><code>[Paper] ISUVR (2017)</code></a></li>
</ul>
<br/>
<hr />
<br/>

<h2><code>Other Projects</code></h2>
<p><code>You can go back or move to the other projects directly by pressing one of below items:</code></p>

<ul>
  <li><code><a href="https://garygitgit.github.io/projects">Overview</a></code></li>
  <li><code><a href="https://garygitgit.github.io/projects/11-system-on-chip">SoC Verification</a></code></li>
  <li><code><a href="https://garygitgit.github.io/projects/13-ml-data">Machine Learning/Data Analytics</a></code></li>
  <li><code><a href="https://garygitgit.github.io/projects/14-mobile">Mobile</a></code></li>
  <li><code><a href="https://garygitgit.github.io/projects/15-webpage">Web/Web Application</a></code></li>
  <li><code><a href="https://garygitgit.github.io/projects/16-sw-infra">Software Infrastructure (DevOps)</a></code></li>
</ul>

<!-- my style -->
<script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>
<style>
code{
    color: #000000;
}
.chip{
    display: inline-block;
    padding: 0 15px;
    height: 30px;
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
.container {
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