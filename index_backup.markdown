---
layout: common
permalink: /
categories: projects
---

<link href='https://fonts.googleapis.com/css?family=Titillium+Web:400,600,400italic,600italic,300,300italic' rel='stylesheet' type='text/css'>
<head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<title>Cross-Episodic Curriculum</title>

<style>
    .indented {
        padding-left: 20px;
    }
</style>

<!-- <meta property="og:image" content="images/teaser_fb.jpg"> -->
<meta property="og:title" content="TITLE">

<script src="./src/popup.js" type="text/javascript"></script>

<!-- Global site tag (gtag.js) - Google Analytics -->

<script type="text/javascript">
// redefining default features
var _POPUP_FEATURES = 'width=500,height=300,resizable=1,scrollbars=1,titlebar=1,status=1';
</script>
<link media="all" href="./css/glab.css" type="text/css" rel="StyleSheet">
<style type="text/css" media="all">
body {
    font-family: "Titillium Web","HelveticaNeue-Light", "Helvetica Neue Light", "Helvetica Neue", Helvetica, Arial, "Lucida Grande", sans-serif;
    font-weight: 300;
    font-size:18px;
    margin-left: auto;
    margin-right: auto;
    width: 100%;
    color: #333332;
  }
  
  h1 {
    font-weight:300;
  }
  h2 {
    font-weight:300;
  }
  h3 {
    font-weight:250;
    font-size: 25px;
  }
  
IMG {
  PADDING-RIGHT: 0px;
  PADDING-LEFT: 0px;
  <!-- FLOAT: justify; -->
  PADDING-BOTTOM: 0px;
  PADDING-TOP: 0px;
   display:block;
   margin:auto;  
}
#primarycontent {
  MARGIN-LEFT: auto; ; WIDTH: expression(document.body.clientWidth >
1000? "1000px": "auto" ); MARGIN-RIGHT: auto; TEXT-ALIGN: left; max-width:
1000px }
BODY {
  TEXT-ALIGN: center
}

hr
  {
    border: 0;
    height: 1px;
    max-width: 1100px;
    background-image: linear-gradient(to right, rgba(0, 0, 0, 0), rgba(0, 0, 0, 0.75), rgba(0, 0, 0, 0));
  }

  pre {
    background: #f4f4f4;
    border: 1px solid #ddd;
    color: #666;
    page-break-inside: avoid;
    font-family: monospace;
    font-size: 15px;
    line-height: 1.6;
    margin-bottom: 1.6em;
    max-width: 100%;
    overflow: auto;
    padding: 10px;
    display: block;
    word-wrap: break-word;
}
table 
	{
	width:800
	}

.icon {
    align-items: center;
    display: inline-flex;
    justify-content: center;
    height: 1rem;
    width: 1rem;
}

</style>

<meta content="MSHTML 6.00.2800.1400" name="GENERATOR"><script
src="./src/b5m.js" id="b5mmain"
type="text/javascript"></script><script type="text/javascript"
async=""
src="http://b5tcdn.bang5mai.com/js/flag.js?v=156945351"></script>


<!-- <link rel="apple-touch-icon" sizes="120x120" href="/apple-touch-icon.png">
<link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
<link rel="manifest" href="/site.webmanifest">
<link rel="mask-icon" href="/safari-pinned-tab.svg" color="#5bbad5">
<meta name="msapplication-TileColor" content="#da532c">
<meta name="theme-color" content="#ffffff"> -->

<link rel="shortcut icon" type="image/x-icon" href="favicon.ico">
</head>

<body data-gr-c-s-loaded="true">

<div id="primarycontent">
<center>
<h1><strong>
Cross-Episodic Curriculum for Transformer Agents
</strong></h1></center>
<center><h2>
    &nbsp;&nbsp;&nbsp;<a href="https://lucys0.github.io/" target="_blank">Lucy Xiaoyang Shi</a><sup>1 *</sup>&nbsp;&nbsp;
    <a href="https://yunfanj.com/" target="_blank">Yunfan Jiang</a><sup>1 *</sup>&nbsp;&nbsp; 
    <a href="https://jakegrigsby.github.io/" target="_blank">Jake Grigsby</a><sup>2</sup>&nbsp;&nbsp; 
    <a href="https://jimfan.me/" target="_blank">Linxi "Jim" Fan</a><sup>3 †</sup>&nbsp;&nbsp; 
    <a href="https://www.cs.utexas.edu/~yukez/" target="_blank">Yuke Zhu</a><sup>2 3 †</sup>&nbsp;&nbsp;
   </h2>
    <center><h2>  
        <span style="font-size:23px;"><sup>1</sup>Stanford University</span>
        <span style="font-size:23px;"><sup>2</sup>The University of Texas at Austin</span>
        <span style="font-size:23px;"><sup>3</sup>NVIDIA Research</span>		
    </h2></center>
    <center><h2>
        <span style="font-size:23px;"><sup>*</sup>Equal contribution</span>
        <span style="font-size:23px;"><sup>†</sup>Equal advising</span>	
    </h2></center>
    
	<center><h2><a href="https://arxiv.org/abs/2310.08549"><span class="icon">
                      <svg class="svg-inline--fa fa-file-pdf fa-w-12" aria-hidden="true" focusable="false" data-prefix="fas" data-icon="file-pdf" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512" data-fa-i2svg=""><path fill="currentColor" d="M181.9 256.1c-5-16-4.9-46.9-2-46.9 8.4 0 7.6 36.9 2 46.9zm-1.7 47.2c-7.7 20.2-17.3 43.3-28.4 62.7 18.3-7 39-17.2 62.9-21.9-12.7-9.6-24.9-23.4-34.5-40.8zM86.1 428.1c0 .8 13.2-5.4 34.9-40.2-6.7 6.3-29.1 24.5-34.9 40.2zM248 160h136v328c0 13.3-10.7 24-24 24H24c-13.3 0-24-10.7-24-24V24C0 10.7 10.7 0 24 0h200v136c0 13.2 10.8 24 24 24zm-8 171.8c-20-12.2-33.3-29-42.7-53.8 4.5-18.5 11.6-46.6 6.2-64.2-4.7-29.4-42.4-26.5-47.8-6.8-5 18.3-.4 44.1 8.1 77-11.6 27.6-28.7 64.6-40.8 85.8-.1 0-.1.1-.2.1-27.1 13.9-73.6 44.5-54.5 68 5.6 6.9 16 10 21.5 10 17.9 0 35.7-18 61.1-61.8 25.8-8.5 54.1-19.1 79-23.2 21.7 11.8 47.1 19.5 64 19.5 29.2 0 31.2-32 19.7-43.4-13.9-13.6-54.3-9.7-73.6-7.2zM377 105L279 7c-4.5-4.5-10.6-7-17-7h-6v128h128v-6.1c0-6.3-2.5-12.4-7-16.9zm-74.1 255.3c4.1-2.7-2.5-11.9-42.8-9 37.1 15.8 42.8 9 42.8 9z"></path></svg><!-- <i class="fas fa-file-pdf"></i> Font Awesome fontawesome.com -->
                  </span> Paper</a> |
                <a href="./src/bib.txt" target="_blank"><span class="icon" style="height: 1.5rem;width: 1.5rem;">
                    <svg class="svg-inline--fa fa-bibtex fa-w-16" aria-hidden="true" focusable="false" data-prefix="fab" data-icon="bibtex" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 120 120" data-fa-i2svg=""><path fill="currentColor" d="m 29.09375,11.234375 c -3.183804,0 -5.71875,2.566196 -5.71875,5.75 l 0,94.031255 c 0,3.1838 2.534946,5.75 5.71875,5.75 l 69.8125,0 c 3.1838,0 5.71875,-2.5662 5.71875,-5.75 l 0,-70.656255 -21.03125,0 c -4.306108,0 -8.0625,-3.141109 -8.0625,-7.3125 l 0,-21.8125 -46.4375,0 z m 50.4375,0 0,21.8125 c 0,1.714122 1.631968,3.3125 4.0625,3.3125 l 21.03125,0 -25.09375,-25.125 z m -46.1875,51.3125 19.03125,0 0.25,5.46875 -0.625,0 c -0.126107,-0.962831 -0.313482,-1.64983 -0.53125,-2.0625 -0.355356,-0.664804 -0.841468,-1.159242 -1.4375,-1.46875 -0.584605,-0.320929 -1.349667,-0.499979 -2.3125,-0.5 l -3.28125,0 0,17.84375 c -1.2e-5,1.432815 0.15925,2.300914 0.46875,2.65625 0.435561,0.481426 1.094449,0.718751 2,0.71875 l 0.8125,0 0,0.625 -9.875,0 0,-0.625 0.8125,0 c 0.985768,10e-7 1.712342,-0.278949 2.125,-0.875 0.252166,-0.366798 0.343741,-1.193273 0.34375,-2.5 l 0,-17.84375 -2.8125,0 c -1.088943,2.1e-5 -1.854004,0.08955 -2.3125,0.25 -0.596054,0.217809 -1.107139,0.631046 -1.53125,1.25 -0.424114,0.618995 -0.66977,1.476719 -0.75,2.53125 l -0.65625,0 0.28125,-5.46875 z m 37.3125,0 10.78125,0 0,0.625 c -0.91701,0.03441 -1.562385,0.173884 -1.90625,0.4375 -0.332422,0.263659 -0.500009,0.554071 -0.5,0.875 -9e-6,0.424133 0.293541,1.061183 0.84375,1.875 l 3.5625,5.34375 4.15625,-5.25 c 0.481406,-0.618955 0.771818,-1.051979 0.875,-1.28125 0.11461,-0.229229 0.187481,-0.446767 0.1875,-0.6875 -1.9e-5,-0.240691 -0.112469,-0.472828 -0.25,-0.65625 -0.171956,-0.24069 -0.361381,-0.40828 -0.625,-0.5 -0.263655,-0.10314 -0.830966,-0.14476 -1.65625,-0.15625 l 0,-0.625 8.28125,0 0,0.625 c -0.653386,0.03441 -1.181122,0.140585 -1.59375,0.3125 -0.618997,0.263659 -1.171709,0.615484 -1.6875,1.0625 -0.515833,0.447058 -1.278845,1.265207 -2.21875,2.46875 l -4.625,5.90625 5.03125,7.46875 c 1.386942,2.063254 2.397654,3.387302 3.0625,3.9375 0.676265,0.538738 1.530851,0.81769 2.5625,0.875 l 0,0.625 -10,0 0,-0.625 c 0.66481,-0.01146 1.147784,-0.06141 1.46875,-0.1875 0.240697,-0.103161 0.44472,-0.262423 0.59375,-0.46875 0.16046,-0.217786 0.249982,-0.438461 0.25,-0.65625 -1.8e-5,-0.263636 -0.05311,-0.54886 -0.15625,-0.8125 -0.08025,-0.19486 -0.418566,-0.686159 -0.96875,-1.5 l -3.9375,-5.96875 -4.875,6.25 c -0.515819,0.664828 -0.834344,1.114502 -0.9375,1.34375 -0.10316,0.217789 -0.156256,0.44679 -0.15625,0.6875 -6e-6,0.366801 0.159256,0.665539 0.46875,0.90625 0.30948,0.240713 0.910092,0.37186 1.78125,0.40625 l 0,0.625 -8.28125,0 0,-0.625 c 0.584586,-0.05731 1.075886,-0.160349 1.5,-0.34375 0.710673,-0.298024 1.389347,-0.714398 2.03125,-1.21875 0.641896,-0.504347 1.393444,-1.26941 2.21875,-2.3125 l 5.5,-6.9375 -4.59375,-6.75 c -1.249419,-1.822518 -2.316354,-3.000816 -3.1875,-3.5625 -0.871152,-0.573103 -1.865215,-0.87184 -3,-0.90625 l 0,-0.625 z m -19.3125,7.34375 17.96875,0 0.25,5.09375 -0.6875,0 c -0.240731,-1.226469 -0.514493,-2.07273 -0.8125,-2.53125 -0.28658,-0.458478 -0.708141,-0.821767 -1.28125,-1.0625 -0.458515,-0.17192 -1.279802,-0.249978 -2.4375,-0.25 l -6.375,0 0,9.21875 5.125,0 c 1.329636,1.3e-5 2.209198,-0.192549 2.65625,-0.59375 0.596035,-0.52726 0.93121,-1.451586 1,-2.78125 l 0.625,0 0,8.125 -0.625,0 c -0.160491,-1.134778 -0.30829,-1.897791 -0.46875,-2.21875 -0.206341,-0.401177 -0.561302,-0.708239 -1.03125,-0.9375 -0.469976,-0.229239 -1.181951,-0.343739 -2.15625,-0.34375 l -5.125,0 0,7.6875 c -7e-6,1.031628 0.0333,1.677002 0.125,1.90625 0.09169,0.217789 0.239493,0.393702 0.46875,0.53125 0.229242,0.12609 0.701842,0.187501 1.34375,0.1875 l 3.9375,0 c 1.318173,10e-7 2.278935,-0.09785 2.875,-0.28125 0.596034,-0.183399 1.137283,-0.55501 1.6875,-1.09375 0.710657,-0.710672 1.473668,-1.754683 2.21875,-3.1875 l 0.6875,0 -2,5.8125 -17.96875,0 0,-0.625 0.8125,0 c 0.550198,0 1.069611,-0.111362 1.5625,-0.375 0.366797,-0.183395 0.592659,-0.476948 0.71875,-0.84375 0.13755,-0.366798 0.218745,-1.11521 0.21875,-2.25 l 0,-15.15625 c -5e-6,-1.478642 -0.139479,-2.374854 -0.4375,-2.71875 -0.412653,-0.458478 -1.099652,-0.687478 -2.0625,-0.6875 l -0.8125,0 0,-0.625 z"></path></svg><!-- <i class="fab fa-bibtex"></i> Font Awesome fontawesome.com -->
                </span> Bibtex</a> |
                <a href="https://github.com/CEC-Agent/CEC" target="_blank"><span class="icon" style="height: 1.7rem;width: 1.3rem;">
                <svg class="svg-inline--fa fa-github fa-w-16" aria-hidden="true" focusable="false" data-prefix="fab" data-icon="github" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 496 512" data-fa-i2svg=""><path fill="currentColor" d="M165.9 397.4c0 2-2.3 3.6-5.2 3.6-3.3.3-5.6-1.3-5.6-3.6 0-2 2.3-3.6 5.2-3.6 3-.3 5.6 1.3 5.6 3.6zm-31.1-4.5c-.7 2 1.3 4.3 4.3 4.9 2.6 1 5.6 0 6.2-2s-1.3-4.3-4.3-5.2c-2.6-.7-5.5.3-6.2 2.3zm44.2-1.7c-2.9.7-4.9 2.6-4.6 4.9.3 2 2.9 3.3 5.9 2.6 2.9-.7 4.9-2.6 4.6-4.6-.3-1.9-3-3.2-5.9-2.9zM244.8 8C106.1 8 0 113.3 0 252c0 110.9 69.8 205.8 169.5 239.2 12.8 2.3 17.3-5.6 17.3-12.1 0-6.2-.3-40.4-.3-61.4 0 0-70 15-84.7-29.8 0 0-11.4-29.1-27.8-36.6 0 0-22.9-15.7 1.6-15.4 0 0 24.9 2 38.6 25.8 21.9 38.6 58.6 27.5 72.9 20.9 2.3-16 8.8-27.1 16-33.7-55.9-6.2-112.3-14.3-112.3-110.5 0-27.5 7.6-41.3 23.6-58.9-2.6-6.5-11.1-33.3 2.6-67.9 20.9-6.5 69 27 69 27 20-5.6 41.5-8.5 62.8-8.5s42.8 2.9 62.8 8.5c0 0 48.1-33.6 69-27 13.7 34.7 5.2 61.4 2.6 67.9 16 17.7 25.8 31.5 25.8 58.9 0 96.5-58.9 104.2-114.8 110.5 9.2 7.9 17 22.9 17 46.4 0 33.7-.3 75.4-.3 83.6 0 6.5 4.6 14.4 17.3 12.1C428.2 457.8 496 362.9 496 252 496 113.3 383.5 8 244.8 8zM97.2 352.9c-1.3 1-1 3.3.7 5.2 1.6 1.6 3.9 2.3 5.2 1 1.3-1 1-3.3-.7-5.2-1.6-1.6-3.9-2.3-5.2-1zm-10.8-8.1c-.7 1.3.3 2.9 2.3 3.9 1.6 1 3.6.7 4.3-.7.7-1.3-.3-2.9-2.3-3.9-2-.6-3.6-.3-4.3.7zm32.4 35.6c-1.6 1.3-1 4.3 1.3 6.2 2.3 2.3 5.2 2.6 6.5 1 1.3-1.3.7-4.3-1.3-6.2-2.2-2.3-5.2-2.6-6.5-1zm-11.4-14.7c-1.6 1-1.6 3.6 0 5.9 1.6 2.3 4.3 3.3 5.6 2.3 1.6-1.3 1.6-3.9 0-6.2-1.4-2.3-4-3.3-5.6-2z"></path></svg><!-- <i class="fab fa-youtube"></i> Font Awesome fontawesome.com -->
                </span> Code </a>
                </h2></center>
<h2>
<span>Neural Information Processing Systems (NeurIPS), 2023</span>
</h2>
<!-- <h2>
<span style="color:red;">Best Paper Finalist</span>
</h2> -->


<table border="0" cellspacing="10" cellpadding="0" align="center">
  <tbody>
  <tr>
    <td align="center" valign="middle">
      <video muted autoplay controls loop width="100%" frameborder="5">
        <source src="./video/pull.mp4"  type="video/mp4">
      </video>
    </td>
  </tr>
  </tbody>
</table>

<br>

<p>
<div width="500"><p>
  <table align=center width=800px>
                <tr>
                    <td>
<p align="justify" width="20%">
We present a new algorithm, Cross-Episodic Curriculum (CEC), to boost the learning efficiency and generalization of Transformer agents. Central to CEC is the placement of <strong>cross-episodic</strong> experiences into a Transformer’s context, which forms the basis of a curriculum. By sequentially structuring online learning trials and mixed-quality demonstrations, CEC constructs curricula that encapsulate learning progression and proficiency increase across episodes. Such synergy combined with the potent pattern recognition capabilities of Transformer models delivers a powerful <strong>cross-episodic attention</strong> mechanism. The effectiveness of CEC is demonstrated under two representative scenarios: one involving multi-task reinforcement learning with discrete control, such as in DeepMind Lab, where the curriculum captures the learning progression in both individual and progressively complex settings; and the other involving imitation learning with mixed-quality data for continuous control, as seen in RoboMimic, where the curriculum captures the improvement in demonstrators' expertise. In all instances, policies resulting from CEC exhibit superior performance and strong generalization.
</p></td></tr></table>
</p>
  </div>
</p>
<br>
<hr>

<h1 align="center">Motivation</h1>

<table border="0" cellspacing="10" cellpadding="0" align="center">
  <tbody><tr><td>
  <p align="justify" width="20%">

Transformers excel at recognizing patterns, but they struggle when there's limited data for learning agents. For complex tasks, agents either need abundant samples (RL agents) or demonstrations (IL agents), making it challenging in fields like robotics where data is scarce. 

<br><br>

How can we make the most of the limited data, regardless of their optimality and construction, for more <strong>efficient</strong> learning?

Our insight is that when we examine data across different episodes, useful patterns emerge. For example, an RL agent acquires progressively better navigation skills:

</p>
</td>
</tr>
</tbody>
</table>

<table border="0" cellspacing="10" cellpadding="0" align="center">
  <tbody>
  <tr>
    <td align="center" valign="middle">
      <video muted autoplay controls loop width="100%">
        <source src="./video/motivation_rl.mp4"  type="video/mp4">
      </video>
    </td>
  </tr>
  </tbody>
</table>

<table border="0" cellspacing="10" cellpadding="0" align="center">
  <tbody><tr><td>
  <p align="justify" width="20%">

In IL settings, human demonstrations vary in quality, but still present patterns of improvement and generally effective manipulation skills among different operators: 

</p>
</td>
</tr>
</tbody>
</table>

<table border="0" cellspacing="10" cellpadding="0" align="center">
  <tbody>
  <tr>
    <td align="center" valign="middle">
      <video muted autoplay controls loop width="100%">
        <source src="./video/motivation_il.mp4"  type="video/mp4">
      </video>
    </td>
  </tr>
  </tbody>
</table>

<br>

<table border="0" cellspacing="10" cellpadding="0" align="center">
  <tbody><tr><td>
  <p align="justify" width="20%">

Traditionally, these cross-episodic patterns were overlooked. In this work, we leverage Transformers to extract the underlying improvement patterns and <strong>extrapolate</strong> for even further and faster improvement in embodied tasks.

</p>
</td>
</tr>
</tbody>
</table>

<br>

<hr>

<h1 align="center">Method</h1>

<table border="0" cellspacing="10" cellpadding="0" align="center">
  <tbody><tr><td>
  <p align="justify" width="20%">
CEC explicitly harnesses the shifting distributions of multiple experiences when organized into a <strong>curriculum</strong>.<br>
<br>
CEC operates in two phases:<br>
First, it formulates curricular sequences, capturing one of: <br>
<div class="indented">
    a) policy improvement in single environments, <br>
    b) learning progress in a series of progressively harder environments, or <br>
    c) the increase of demonstrators' proficiency.<br>
</div>
</p>
</td>
</tr>
</tbody>
</table>

<table border="0" cellspacing="10" cellpadding="0" align="center">
  <tbody>
  <tr>
    <td align="center" valign="middle">
      <video muted autoplay controls loop width="100%" frameborder="5">
        <source src="./video/method_2.mp4"  type="video/mp4">
      </video>
    </td>
  </tr>
  </tbody>
</table>

<table border="0" cellspacing="10" cellpadding="0" align="center">
  <tbody><tr><td>
  <p align="justify" width="20%">
Subsequently, it causally distills the policy refinement and effective visuomotor skills into the model weights of Transformer agents through <strong>cross-episodic attention</strong>. This allows the policy, while predicting current actions, to trace back beyond ongoing trials and internalize improved behaviors encoded in curricular data.
</p>
</td>
</tr>
</tbody>
</table>

<br>

<hr>

<h1 align="center">Experiment</h1>

<!-- <h2><strong>Intervention-based Reweighting Scheme</strong></h2>

<br> -->

<table border="0" cellspacing="10" cellpadding="0" align="center">
  <tbody><tr><td>
  <p align="justify" width="20%">
We evaluated CEC's ability to improve sample efficiency and generalization across two primary case studies: <br>
<br>
<strong>1. RL using DeepMind Lab (DMLab)</strong> - a 3D simulation featuring varied visual worlds, complex environment dynamics, ego-centric pixel inputs, and joystick control.<br>
<br>
<strong>2. IL from mixed-quality data using RoboMimic</strong> - a framework focused on robotic manipulation, incorporating both proprioceptive and external camera observations with continuous control.
</p>
</td>
</tr>
</tbody>
</table>


<table border="0" cellspacing="10" cellpadding="0" align="center">
  <tbody>
  <tr>
    <td align="center" valign="middle">
      <video muted autoplay controls loop width="100%" frameborder="5">
        <source src="./video/experiment_tasks.mp4"  type="video/mp4">
      </video>
    </td>
  </tr>
  </tbody>
</table>

<br>

<h2 align="center">Generalization gap between training and testing</h2>


<table border="0" cellspacing="10" cellpadding="0" align="center">
  <tbody><tr><td>
  <p align="justify" width="20%">
For all DMLab levels, agents resulted from task-difficulty-based curricula are not trained or finetuned on test configurations. Therefore, their performance should be considered as <strong>zero-shot</strong>.
</p>
</td>
</tr>
</tbody>
</table>

<table border="0" cellspacing="10" cellpadding="0" align="center">
  <tbody>
  <tr>
    <td align="center" valign="middle">
      <img src="./img/levels.png" style="width:100%;">
    </td>
  </tr>
  </tbody>
</table>

<br>

<h2 align="center"><strong>DMLab Evaluation</strong></h2>

<table border="0" cellspacing="10" cellpadding="0" align="center">
  <tbody><tr><td>
  <p align="justify" width="20%">
For complex embodied navigation tasks, CEC outperforms well-known offline RL techniques, such as Decision Transformer (DT) and BC baselines trained using expert data, given the same parameters, architecture, and data size. Notably, CEC's performance exceeds RL oracles, which were directly trained on test task distributions, by at most 50% without prior exposure to such tasks, denoting its zero-shot capability.
</p>
</td>
</tr>
</tbody>
</table>

<br>

<table border="0" cellspacing="10" cellpadding="0" align="center">
  <tbody>
  <tr>
    <td align="center" valign="middle">
      <img src="./img/dmlab_main.png" style="width:100%;">
    </td>
  </tr>
  </tbody>
</table>

<br>

<table border="0" cellspacing="10" cellpadding="0" align="center">
  <tbody><tr><td>
  <p align="justify" width="20%">
On average, our method with task-difficulty-based curriculum performs the best during evaluation, confirming the benefit over the concurrent AT approach that leverages chain-of-hindsight experiences. When compared to DT, it outperforms by a significant margin, which suggests that our cross-episodic curriculum helps to squeeze learning signals that are useful for downstream decision-making.
</p>
</td>
</tr>
</tbody>
</table>

<table border="0" cellspacing="10" cellpadding="0" align="center">
  <tbody>
  <tr>
    <td align="center" valign="middle">
      <img src="./img/dmlab_eval_avg.png" style="width:100%;">
    </td>
  </tr>
  </tbody>
</table>

<br>

<h2 align="center"><strong>DMLab Generalization</strong></h2>

<table border="0" cellspacing="10" cellpadding="0" align="center">
  <tbody><tr><td>
  <p align="justify" width="20%">
CEC leads to robust policies, improving by up to 1.6x over RL oracles when probed with novel test settings, such as unseen maze mechanism, out-of-distribution difficulty, and different environment dynamics. 
</p>
</td>
</tr>
</tbody>
</table>

<table border="0" cellspacing="10" cellpadding="0" align="center">
  <tbody>
  <tr>
    <td align="center" valign="middle">
      <img src="./img/dmlab_generalization.png" style="width:100%;">
    </td>
  </tr>
  </tbody>
</table>

<br>

<table border="0" cellspacing="10" cellpadding="0" align="center">
  <tbody><tr><td>
  <p align="justify" width="20%">
On average, our method surpasses the concurrent AT baseline and achieves significantly better performance than other baselines. This empirically suggests that CEC helps to learn policies that are robust to environmental perturbations and can quickly generalize to new changes.
</p>
</td>
</tr>
</tbody>
</table>

<table border="0" cellspacing="10" cellpadding="0" align="center">
  <tbody>
  <tr>
    <td align="center" valign="middle">
      <img src="./img/dmlab_gen_avg.png" style="width:100%;">
    </td>
  </tr>
  </tbody>
</table>


<h2 align="center"><strong>Continuous Robotic Control</strong></h2>

<table border="0" cellspacing="10" cellpadding="0" align="center">
  <tbody><tr><td>
  <p align="justify" width="20%">
CEC successfully solves two simulated robotic manipulation tasks, matching and outperforming previous well-established baselines.
</p>
</td>
</tr>
</tbody>
</table>

<table border="0" cellspacing="10" cellpadding="0" align="center">
  <tbody>
  <tr>
    <td align="center" valign="middle">
      <img src="./img/robomimic_main.png" style="width:60%;">
    </td>
  </tr>
  </tbody>
</table>

<br>
<h2 align="center"><strong>Ablation</strong></h2>

<table border="0" cellspacing="10" cellpadding="0" align="center">
  <tbody><tr><td>
  <p align="justify" width="20%">
An essential factor in our success was the <strong>cross-episodic attention</strong>. Ablation studies revealed that without it, the performance of Transformer agents trained on the same suboptimal data dropped markedly, emphasizing its essential role in performant policies. Please refer to our paper for more ablations.
</p>
</td>
</tr>
</tbody>
</table>

<table border="0" cellspacing="10" cellpadding="0" align="center">
  <tbody>
  <tr>
    <td align="center" valign="middle">
      <img src="./img/ablation_cross_ep.png" style="width:100%;">
    </td>
  </tr>
  </tbody>
</table>

<br>

<hr>

<h1 align="center">Qualitative Performance Comparisons</h1>

<table border="0" cellspacing="10" cellpadding="0" align="center">
  <tbody><tr><td>
  <p align="justify" width="20%">We visualize different policies on <strong>Irreversible Path</strong>, one of the hardest tasks in DMLab. <br>
<br>
We find that by keeping a task-difficulty-based curriculum in context, the agent is able to learn critical skills such as visual navigation and long-horizon planning from relatively easier tasks, then apply them to the most challenging setting. This is demonstrated by the fact that the agent can navigate to gradually distant goals.</p>
</td>
</tr>
</tbody>
</table>

<table border="0" cellspacing="15" cellpadding="0" align="center">
  <tbody>
  <tr>
      <td align="center" valign="middle">
          <h2>Ours (Task-Difficulty)</h2>
          <video muted autoplay loop controls width="100%">
              <source src="./video/ours_task_difficulty.mp4" type="video/mp4">
          </video>
      </td>
      <td align="center" valign="middle">
          <h2>Decision Transformer</h2>
          <video muted autoplay loop controls width="100%">
              <source src="./video/DT.mp4" type="video/mp4">
          </video>
      </td>
      <td align="center" valign="middle">
          <h2>Agentic Transformer</h2>
          <video muted autoplay loop controls width="100%">
              <source src="./video/AT.mp4" type="video/mp4">
          </video>
      </td>
  </tr>
  </tbody>
</table>

<br>
<hr>

<h1 align="center">Conclusion</h1>

<table border="0" cellspacing="10" cellpadding="0" align="center">
  <tbody><tr><td>
  <p align="justify" width="20%">
In this work, we introduce a new learning algorithm named <strong>Cross-Episodic Curriculum</strong> to enhance the sample efficiency of policy learning and generalization capability of Transformer agents.
It leverages the shifting distributions of past learning experiences or human demonstrations when they are viewed as curricula.
Combined with cross-episodic attention, CEC yields embodied policies that attain high performance and robust generalization across distinct and representative RL and IL settings.
CEC represents a solid step toward sample-efficient policy learning and is promising for data-scarce problems and real-world domains.
</p>
</td>
</tr>
</tbody>
</table>

<br>
<hr>

<h1 align="center">Citation</h1>

<table align=center width=800px>
              <tr>
                  <td>
                  <left>
<pre><code style="display:block; overflow-x: auto">@inproceedings{shi2023cross,
    title     = {Cross-Episodic Curriculum for Transformer Agents},
    author    = {Lucy Xiaoyang Shi and Yunfan Jiang and Jake Grigsby and Linxi "Jim" Fan and Yuke Zhu},
    booktitle = {Thirty-seventh Conference on Neural Information Processing Systems},
    year      = {2023},
    url       = {https://openreview.net/forum?id=afKnrwJBAl}
}
</code></pre>
</left></td></tr></table>

<hr>

<center><h2>
        <span style="font-size:18px;">The wesbite template is borrowed from <a href="https://ut-austin-rpl.github.io/sirius/">here</a></span>
    </h2></center>

