<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">

<title>Aswin R | Technical Lead</title>

<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

<style>

body{
font-family: 'Segoe UI',sans-serif;
background:#f5f7fa;
}

.hero{
background:linear-gradient(120deg,#0f2027,#203a43,#2c5364);
color:white;
padding:100px 0;
}

.profile-img{
width:140px;
height:140px;
border-radius:50%;
border:5px solid white;
}

.section-title{
font-weight:700;
margin-bottom:30px;
}

.skill-card{
background:white;
padding:20px;
border-radius:10px;
box-shadow:0 5px 20px rgba(0,0,0,0.08);
transition:0.3s;
}

.skill-card:hover{
transform:translateY(-5px);
}

.timeline{
border-left:3px solid #0d6efd;
padding-left:25px;
}

.timeline-item{
margin-bottom:30px;
}

.project-card{
border:none;
box-shadow:0 5px 25px rgba(0,0,0,0.1);
transition:0.3s;
}

.project-card:hover{
transform:translateY(-5px);
}

footer{
background:#0f2027;
color:white;
padding:20px;
}

</style>
</head>

<body>

<!-- HERO -->

<section class="hero text-center">

<div class="container">

<img src="https://avatars.githubusercontent.com/u/33830946?v=4" class="profile-img mb-3">

<h1>Aswin R</h1>

<h4>Senior Software Engineer</h4>

<p class="lead">
iOS | Android | Web
</p>

<!--<a class="btn btn-light m-2">Download Resume</a>
<a class="btn btn-outline-light m-2">Contact</a>-->

</div>

</section>

<!-- ABOUT -->

<section class="container py-5">

<h2 class="section-title text-center">About Me</h2>

<p class="text-center">

Senior Software Engineer with strong expertise in <b>mobile application development</b>, building
secure, scalable and high-performance applications across <b>iOS and Android platforms</b>.
Experienced in networking, SDK integration, performance optimization and delivering
production-grade mobile solutions.

Focused on engineering excellence, architecture design and solving complex
mobile system challenges.

</p>

</section>

<!-- SKILLS -->

<section class="container py-5">

<h2 class="section-title text-center">Skills</h2>

<div class="row g-4">

<div class="col-md-4">
<div class="skill-card">
<h5>Mobile Development</h5>
<p>iOS, Swift, UIKit, Android, Kotlin, WebView Integration</p>
</div>
</div>

<div class="col-md-4">
<div class="skill-card">
<h5>Networking</h5>
<p>REST APIs, Retrofit, URLSession, WebRTC</p>
</div>
</div>

<div class="col-md-4">
<div class="skill-card">
<h5>Architecture</h5>
<p>MVC, MVVM, Clean Architecture</p>
</div>
</div>

<div class="col-md-4">
<div class="skill-card">
<h5>Performance</h5>
<p>Memory Optimization, Profiling, Debugging</p>
</div>
</div>

<div class="col-md-4">
<div class="skill-card">
<h5>Tools</h5>
<p>Git, Xcode, Android Studio</p>
</div>
</div>

<div class="col-md-4">
<div class="skill-card">
<h5>Other</h5>
<p>Security Compliance, SDK Development, App Optimization</p>
</div>
</div>

</div>

</section>

<!-- EXPERIENCE -->

<section class="container py-5">

<h2 class="section-title text-center">Experience</h2>

<div class="timeline">

<div class="timeline-item">

<h5>Senior Software Engineer</h5>
<p><b>Mobile Development</b></p>

<ul>
<li>Developed scalable mobile applications across iOS and Android.</li>
<li>Implemented secure networking layers and API integrations.</li>
<li>Optimized performance for large scale production apps.</li>
</ul>

</div>

<div class="timeline-item">

<h5>Software Engineer</h5>

<ul>
<li>Designed mobile SDK components.</li>
<li>Integrated complex third-party APIs.</li>
<li>Delivered high reliability production features.</li>
</ul>

</div>

</div>

</section>

<!-- PROJECTS -->

<section class="container py-5">

<h2 class="section-title text-center">Featured Projects</h2>

<div class="row g-4">

<div class="col-md-4">

<div class="card project-card">

<div class="card-body">

<h5 class="card-title">Mobile SDK Development</h5>

<p>
Designed and developed a reusable mobile SDK enabling
secure integrations for enterprise mobile applications.
</p>

</div>

</div>

</div>

<div class="col-md-4">

<div class="card project-card">

<div class="card-body">

<h5 class="card-title">High Performance Networking</h5>

<p>
Built optimized networking layers with robust error handling
and retry mechanisms.
</p>

</div>

</div>

</div>

<div class="col-md-4">

<div class="card project-card">

<div class="card-body">

<h5 class="card-title">Mobile Security Enhancements</h5>

<p>
Implemented secure authentication and data protection mechanisms
for mobile platforms.
</p>

</div>

</div>

</div>

</div>

</section>

<!-- EDUCATION -->

<section class="container py-5">

<h2 class="section-title text-center">Education</h2>

<div class="text-center">

<p><b>B.Tech in Computer Science</b></p>

<p>Cochin University of Science and Technology</p>

</div>

</section>

<!-- CERTIFICATIONS -->

<section class="container py-5">

<h2 class="section-title text-center">Certifications</h2>

<ul class="text-center list-unstyled">

<li>Networking Certification</li>

</ul>

</section>

<!-- CONTACT -->

<section class="container py-5 text-center">

<h2 class="section-title">Contact</h2>

<p>Email: aswinrathees.tech@gmail.com</p>

<p><a href="https://www.linkedin.com/in/aswin-rathees/" target="_blank">LinkedIn Profile</a></p>

<p><a href="https://github.com/aswinrathees" target="_blank">GitHub Profile</a></p>

</section>

<footer class="text-center">

© 2026 Aswin R — Senior Software Engineer Portfolio

</footer>


<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>

<script>

window.addEventListener("scroll",function(){

const elements=document.querySelectorAll(".skill-card");

elements.forEach(el=>{
const position=el.getBoundingClientRect().top;
const screen=window.innerHeight;

if(position<screen-100){
el.style.opacity=1;
el.style.transform="translateY(0)";
}

})

})

</script>

</body>
</html>