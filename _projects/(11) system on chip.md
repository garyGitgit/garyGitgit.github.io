---
name: SoC Verification 
image: https://cdn2.iconfinder.com/data/icons/vivid/48/processor-512.png
tools: [Samsung Electronics, 2018-Present]
---

<h2 style="text-align:center;"> SoC Verification </h2>
<br/>

<figure class="image">
    <img src="https://images.samsung.com/is/image/samsung/p5/semiconductor/minisite/exynos/newsroom/blog-detail/detail-new-exynos-symbol-presents-exciting-possibilities-for-the-future.jpg" alt="drawing" style="width:500px;"/>
</figure>

<br/>

The projects were related to design verification for Exynos series in <b>S.LSI division, Samsung Electronics</b>.

<br/><br/>
<h4>  Table of Contents  </h4>
- <a href="#1">1. Regression Automation</a><br/>
- <a href="#2">2. Resource Management</a><br/>
- <a href="#3">3. AMBA Bus Verification</a><br/>

<br/>
<hr>
<br/>

<h3> <a name="1">1. Regression Automation </a></h3>
<br/>
<h4> Description </h4>
<p>
The goal of this project was <b>to automate SoC/IP regression workflow</b>. It standardized and improved individual verification engineers' workflow and finally reduced TAT time and bug reports after tape-out. <br/>
<br/>
My role was <b>to develop a user interface</b> for SoC/IP regression automation, including <b>Command Line Interface (CLI) and Graphical User Interface (GUI)</b>. CLI and GUI were developed in <b>Perl/Python</b> and <b>Vue.js/Electron</b> respectively. Django was used to develop a backend server, and Django REST Framework was used for REST API. <br/>
<br/>
Both <b>Oracle PL/SQL and MongoDB</b> was used to handle normalized data and denormalized data repsectively. I especially worked as a MongoDB administrator for distributed databases.
</p>
<p>
To see details, please refer to the paper in 'Related Articles' below.
 </p>

<br/>
<!-- <figure class="image">
    <img src="https://static.javatpoint.com/tutorial/software-testing/images/regression-testing-intro.png" alt="drawing" style="width:500px;"/>
    <figcaption class="image-caption">Figure 1. Regression test</figcaption>
</figure> -->

<h4>Skills</h4>
<div>
    <div class="chip lang">Python</div>
    <div class="chip lang">Perl</div>
    <div class="chip db">Oracle PL/SQL</div>
    <div class="chip db">MongoDB</div>
    <div class="chip devops">Nginx</div>
    <div class="chip devops">Gunicorn</div>
    <div class="chip frontend">Vue</div>
    <div class="chip frontend">Electron</div>
    <div class="chip backend">Django</div>
    <div class="chip backend">REST API</div>
</div>

<br/>

<h4>Period</h4>
1+ years
<div class="hori-timeline" dir="ltr">
    <ul class="list-inline events">
        <li class="list-inline-item event-list">
            <div class="px-4">
                <div class="event-date soft-primary">1 Jan</div>
                <h5 class="font-size-16">2020</h5>
                <p class="text-muted"></p>
            </div>
        </li>
        <li class="list-inline-item event-list">
            <div class="px-4">
                <div class="event-date soft-success">Present</div>
                <h5 class="font-size-16">2021</h5>
                <p class="text-muted"></p>
            </div>
        </li>
    </ul>
</div>

<h4>Related Articles</h4>
<ul>
   <li><a href="http://events.dvcon.org/2020/proceedings/papers/03_3.pdf">DVCon Paper (2020)</a></li>
</ul>
<br/>
<hr/>
<br/>

<h3><a name="2">2. Resource Management</a></h3>

<br/>

<h4>Description</h4>
<p>
The goal of this project was <b>to schedule SoC/IP emulation resource efficiently and maximize emulation utilization.</b> <br/>
<br/>
My role was to devleop <b>resource scheduling algorithm</b> to maximize resource utilization in different situations. To acheive the goal, I collected time series data into <b>Oracle DB</b> and analyzed data with <b>Jupyter, Seaborn and Pandas</b>. I also developed a dynamic resource scheduling algorithm in a data-driven way. <b>The algorithm increased resource utilization by 20% and reduced total pending time by 70%. </b>
</p>
<p> 
Furthermore, to find out a better optimal solution, I researched <b>Reinforcement Learning</b> for resource management. First, I developed training environment with <b>PyQT</b> in a event-driven way, and I applied <b>Double Deep Q Network (DDQN) algorithm</b>, an algorithm developed by DeepMind team. The research proved that DDQN algorithm had better performance than random algorithm or no algorithm in SoC/IP emulation resource management problem. 
</p>
<p>
To see details, please refer to the paper in 'Related Articles' below, and the techinical details are described in <a href="http://garyGitgit.github.io/projects/12-ml-data">machine learning/data analytics</a>.
 </p>

<br/>

<h4>Skills</h4>
<div>
    <div class="chip lang">Python</div>
    <div class="chip db">Oracle PL/SQL</div>
    <div class="chip theory">Reinforcement Learning</div>
    <div class="chip tools">PyQT</div>
    <div class="chip tools">Keras</div>
    <div class="chip tools">Jupyter</div>
    <div class="chip tools">Pycharm</div>
</div>

<br/>

<h4>Period</h4>
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

<h4>Related Articles</h4>
<ul>
   <li><a href="http://events.dvcon.org/Europe/2019/proceedings/papers/10_2.pdf">DVCon Paper (2019)</a></li>
</ul>
<br/>

<hr />
<br/>

<h3><a name="3">3. AMBA Bus Verification</a></h3>

<br/>

<h4>Description</h4>
<p>
The goal of this project was for AMBA Bus verification for Exynos design.<br/>
<br/>
My role was <b>to find out RTL bugs in APB and AHB</b>. APB, an AMBA Peripheral Bus, is widely used to communicate between CPU and peripherals such as UART, etc with low cost and low performance. AHB ,Advanced High Performance Bus, is mostly used for a high throughput and high performance such as data bus. I generated multiple testcases, including SFR test and burst tests with <b>System Verilog and IWB</b> and found out RTL bugs. <br/>
<br/>
I also automated bus verification workflow in <b>Python</b>.
</p>

<figure class="image">
    <img src="https://img1.daumcdn.net/thumb/R720x0.q80/?scode=mtistory2&fname=http%3A%2F%2Fcfile23.uf.tistory.com%2Fimage%2F143F30124B233B1C6D395D" alt="drawing" style="width:500px;"/>
    <figcaption class="image-caption">[AMBA Bus Protocol (ARM official guide)]</figcaption>
</figure>

<h4>Skills</h4>
<div>
    <div class="chip lang">System Verilog</div>
    <div class="chip lang">Python</div>
    <div class="chip tools">IWB</div>
    <div class="chip tools">Verdi</div>
</div>

<br/>

<h4>Period</h4>
5 months
<div class="hori-timeline" dir="ltr">
    <ul class="list-inline events">
        <li class="list-inline-item event-list">
            <div class="px-4">
                <div class="event-date soft-primary">1 June</div>
                <h5 class="font-size-16">2020</h5>
                <p class="text-muted"></p>
            </div>
        </li>
        <li class="list-inline-item event-list">
            <div class="px-4">
                <div class="event-date soft-success">31 Nov</div>
                <h5 class="font-size-16">2020</h5>
                <p class="text-muted"></p>
            </div>
        </li>
    </ul>
</div>

<hr />
<br/>

<h2>Other Projects</h2>
<p>You can go back or move to the other projects directly by pressing one of below items:</p>

<ul>
  <li><a href="https://garygitgit.github.io/projects">Overview</a></li>
  <li><a href="https://garygitgit.github.io/projects/12-human-activity-hci)">Human Acitvity Recognition/HCI</a></li>
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
    font-family: SFMono-Regular,Menlo,Monaco,Consolas,"Liberation Mono","Courier New",monospace;
    
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
