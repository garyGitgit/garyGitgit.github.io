---
name: Machine Learning / Data Analytics
image: https://cdn3.iconfinder.com/data/icons/research-element/1000/graph-512.png
tools: [Samsung Electronics, 2019-Present]
<!-- external_url: https://www.google.com -->
---

<h2 style="text-align:center;"><code>Machine Learning / Data Analytics</code></h2>

<br/>

<figure class="image">
    <img src="https://www.smartdatacollective.com/wp-content/uploads/2018/11/top-7-data-analytics-tools-2019.jpg" alt="drawing" style="width:500px;"/>
</figure>
<br/>
<code>
    The projects are related to machine learning and data analytics to solve problems in <b>S.LSI division, Samsung Electronics</b>.
</code>

<br/>
<h4><code>Table of Contents</code></h4>
- <code><a href="#1">1. Reinforcement Learning for Resource Management</a></code><br/>
- <code><a href="#2">2. Simulation Log Analytics for Testcase Similarity</a><code><br/>

<br/>
<hr>
<br/>

<h3><code><a name="1"> 1. Reinforcement Learning for Resource Management</a></code></h3>
<br/>

<h4><code>Description</code></h4>
<p>
<code>
This project has been motivated <b>to maximize SoC/IP emulation resource utilization with reinforcement learning</b>. The heuristic based approach has improved resource utilization (<a href='https://garygitgit.github.io/projects/11-system-on-chip'>SoC Verfication</a>), however, environments are too diverse to define algorithms and polcies depending on each situation. <b>Double Deep Q Network (DDQN)</b>, which is one of the basic algorithm by DeepMind, has been applied to solve this problem.</code>
</p>
<p><code>
My role was to <b>develop a simulation environment, implemented and trained DDQN model</b>. The training data has been collected from the previous data collected in Oracle DB. As a result, it has been shown that DDQN algorithm is better performance than random policy and no policy.
</code></p>

<figure class="image">
    <img src="https://drive.google.com/uc?id=13fJT9B2aiRNWWALF-6yPYo6uUQrnSb0F" alt="drawing" style="width:1000px;"/>
    <figcaption class="image-caption"><code>[Reward in each episode on training (left), comparision between trained model and no policy (right)]</code></figcaption>
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
1 year
<div class="hori-timeline" dir="ltr">
    <ul class="list-inline events">
        <li class="list-inline-item event-list">
            <div class="px-4">
                <div class="event-date soft-primary">1 Jan</div>
                <h5 class="font-size-16">2019</h5>
                <p class="text-muted"></p>
            </div>
        </li>
        <li class="list-inline-item event-list">
            <div class="px-4">
                <div class="event-date soft-warning">31 Oct</div>
                <h5 class="font-size-16">DVCon</h5>
                <p class="text-muted"></p>
            </div>
        </li>
        <li class="list-inline-item event-list">
            <div class="px-4">
                <div class="event-date soft-success">31 Dec</div>
                <h5 class="font-size-16">2019</h5>
                <p class="text-muted"></p>
            </div>
        </li>
    </ul>
</div>

<h4><code>Related Articles</code></h4>
<ul>
   <li><a href="http://events.dvcon.org/Europe/2019/proceedings/papers/10_2.pdf"><code>DVCon Paper (2019)</code></a></li>
</ul>
<br/>

<hr />
<br/>

<h3><code>2. NLP for Testcase Similarity</code></h3>

<br/>

<h4><code>Description</code></h4>
<p><code>
This project has been motivated <b>to find out meaningful information from hundreds TBs of simulation log data</b>. Even if each simulation generated large amount of log data, they mostly discarded after simulation. My role was <b>to store simulation log data into MongoDB, distributed NoSQL data and analyze log data with Natural Language Processing (NLP) technique. </b> <b>Word2Vec and Spacy</b> has been used to handle log data, and <b>T-SNE</b> has been used to find out the vector distance between each logs.<br/>
<br/>
As a result, meaningful similarity has been found in each logs, which was not demonstrated in user-defined features. 
</code>
</p>

<br/>

<h4><code>Skills</code></h4>
<div>
    <div class="chip lang">Python</div>
    <div class="chip theory">Word2Vec</div>
    <div class="chip tools">Spacy</div>
    <div class="chip tools">T-SNE</div>
    <div class="chip tools">Juypter</div>
</div>

<br/>

<h4><code>Period</code></h4>
2 months
<br/>
<div class="hori-timeline" dir="ltr">
    <ul class="list-inline events">
        <li class="list-inline-item event-list">
            <div class="px-4">
                <div class="event-date soft-primary">24 Aug</div>
                <h5 class="font-size-16">2020</h5>
                <p class="text-muted"></p>
            </div>
        </li>
        <li class="list-inline-item event-list">
            <div class="px-4">
                <div class="event-date soft-success">31 Oct</div>
                <h5 class="font-size-16">2020</h5>
                <p class="text-muted"></p>
            </div>
        </li>
    </ul>
</div>

<br/>
<hr />
<br/>

<h2><code>Other Projects</code></h2>
<p><code>You can go back or move to the other projects directly by pressing one of below items:</code></p>
<ul>
  <li><code><a href="https://garygitgit.github.io/projects">Overview</a></code></li>
  <li><code><a href="https://garygitgit.github.io/projects/11-system-on-chip">SoC Verfication</a></code></li>
  <li><code><a href="https://garygitgit.github.io/projects/13-sw-infra">Software Infrastructure (DevOps)</a></code></li>
  <li><code><a href="https://garygitgit.github.io/projects/14-human-activity-hci)">Human Acitvity Recognition/HCI</a></code></li>
  <li><code><a href="https://garygitgit.github.io/projects/15-mobile">Mobile</a></code></li>
  <li><code><a href="https://garygitgit.github.io/projects/16-webpag">Web/Web Application</a></code></li>
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

</style>