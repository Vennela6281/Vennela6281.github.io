<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title> Portfolio</title>

<style>
/* ===== RESET ===== */
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: "Segoe UI", sans-serif;
}

body{
    background:#0b0b0b;
    color:#fff;
}

/* ===== NAVBAR ===== */
header{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:20px 8%;
    background:#000;
    border-bottom:2px solid #ff7a00;
}

.logo{
    font-size:26px;
    font-weight:bold;
    color:#ff7a00;
    letter-spacing:2px;
}

nav a{
    color:#fff;
    margin-left:25px;
    text-decoration:none;
    font-weight:500;
}

nav a:hover{
    color:#ff7a00;
}

/* ===== HERO ===== */
.hero{
    height:90vh;
    display:flex;
    align-items:center;
    justify-content:space-between;
    padding:0 8%;
}

.hero-text h1{
    font-size:50px;
    line-height:1.2;
}

.hero-text span{
    color:#ff7a00;
}

.hero-text p{
    margin:20px 0;
    color:#ccc;
    max-width:500px;
}

.hero-btn{
    padding:12px 30px;
    background:#ff7a00;
    color:#000;
    text-decoration:none;
    font-weight:bold;
    border-radius:30px;
}

.hero-box{
    width:260px;
    height:260px;
    border:4px solid #ff7a00;
    display:flex;
    align-items:center;
    justify-content:center;
    font-size:22px;
    font-weight:bold;
}

/* ===== SECTIONS ===== */
section{
    padding:70px 8%;
}

.title{
    font-size:32px;
    margin-bottom:40px;
    color:#ff7a00;
    text-align:center;
}

/* ===== ABOUT ===== */
.about p{
    max-width:800px;
    margin:auto;
    line-height:1.8;
    color:#ccc;
    text-align:center;
}

/* ===== SKILLS ===== */
.skills-box{
    max-width:600px;
    margin:auto;
}

.skill{
    margin-bottom:25px;
}

.skill p{
    margin-bottom:6px;
}

.progress{
    background:#222;
    height:10px;
    border-radius:20px;
}

.progress span{
    display:block;
    height:10px;
    background:#ff7a00;
    border-radius:20px;
}

.html{width:90%;}
.css{width:85%;}
.java{width:70%;}

/* ===== PROJECTS ===== */
.project-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:25px;
}

.project{
    border:2px solid #ff7a00;
    padding:25px;
    text-align:center;
}

.project h3{
    margin-bottom:10px;
}

/* ===== CONTACT ===== */
.contact form{
    max-width:400px;
    margin:auto;
    display:flex;
    flex-direction:column;
}

.contact input,
.contact textarea{
    margin-bottom:15px;
    padding:12px;
    background:#111;
    border:1px solid #ff7a00;
    color:#fff;
}

.contact button{
    padding:12px;
    background:#ff7a00;
    border:none;
    font-weight:bold;
    cursor:pointer;
}

/* ===== FOOTER ===== */
footer{
    background:#000;
    text-align:center;
    padding:20px;
    border-top:2px solid #ff7a00;
}
</style>
</head>

<body>

<!-- NAVBAR -->
<header>
    <div class="logo">Portfolio</div>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<!-- HERO -->
<section class="hero" id="home">
    <div class="hero-text">
        <h1>I’m <span>Vennela gurram</span><br>Frontend Developer</h1>
        <p>
            Focused and motivated Computer Science student building clean and user-friendly web interfaces using HTML and CSS.
        </p>
        <a href="#contact" class="hero-btn">Contact Me</a>
    </div>

    <div class="hero-box">
        Image
    </div>
</section>

<!-- ABOUT -->
<section class="about" id="about">
    <h2 class="title">About Me</h2>
    <p>
       I am a Computer Science student passionate about web development and emerging technologies. I enjoy building clean and user-friendly websites while continuously improving my technical, professional, and interview skills. My goal is to grow as a software developer and work on real-world projects.
    </p>
</section>

<!-- SKILLS -->
<section id="skills" style="padding:40px; background:#0b0b0b; color:white;">

    <h2 style="text-align:center; color:#ff7a00; font-size:32px;">
        Skills
    </h2>

    <!-- TECHNICAL SKILLS -->
    <div style="border:2px solid #ff7a00; padding:20px; margin-bottom:30px;">
        <h3 style="color:#ff7a00; text-align:center;">Technical Skills</h3>

        <p>HTML</p>
        <div style="background:#222; height:10px;">
            <div style="width:80%; height:10px; background:#ff7a00;"></div>
        </div>

        <p>CSS</p>
        <div style="background:#222; height:10px;">
            <div style="width:80%; height:10px; background:#ff7a00;"></div>
        </div>

        <p>Python</p>
        <div style="background:#222; height:10px;">
            <div style="width:65%; height:10px; background:#ff7a00;"></div>
        </div>

        <p>Java</p>
        <div style="background:#222; height:10px;">
            <div style="width:20%; height:10px; background:#ff7a00;"></div>
        </div>

        <p>AI</p>
        <div style="background:#222; height:10px;">
            <div style="width:55%; height:10px; background:#ff7a00;"></div>
        </div>

        <p>Metaverse</p>
        <div style="background:#222; height:10px;">
            <div style="width:40%; height:10px; background:#ff7a00;"></div>
        </div>

        <p>Generative AI</p>
        <div style="background:#222; height:10px;">
            <div style="width:50%; height:10px; background:#ff7a00;"></div>
        </div>

        <p>Data</p>
        <div style="background:#222; height:10px;">
            <div style="width:40%; height:10px; background:#ff7a00;"></div>
        </div>
    </div>

    <!-- PROFESSIONAL SKILLS -->
    <div style="border:2px solid #ff7a00; padding:20px; margin-bottom:30px;">
        <h3 style="color:#ff7a00; text-align:center;">Professional Skills</h3>

        <p>Communication Bootcamp</p>
        <div style="background:#222; height:10px;">
            <div style="width:75%; height:10px; background:#ff7a00;"></div>
        </div>

        <p>Presentation Skills</p>
        <div style="background:#222; height:10px;">
            <div style="width:70%; height:10px; background:#ff7a00;"></div>
        </div>

        <p>Time Management Skills</p>
        <div style="background:#222; height:10px;">
            <div style="width:65%; height:10px; background:#ff7a00;"></div>
        </div>
    </div>

    <!-- INTERVIEW SKILLS -->
    <div style="border:2px solid #ff7a00; padding:20px;">
        <h3 style="color:#ff7a00; text-align:center;">Interview Skills</h3>

        <p>Interview Preparation Course</p>
        <div style="background:#222; height:10px;">
            <div style="width:70%; height:10px; background:#ff7a00;"></div>
        </div>
    </div>

</section>
<h2 style="color:white;">Certificates</h2>

<a href="hackathons.html"
   style="display:block; font-weight:bold; font-size:20px; color:#ff7a00; margin:8px 0;">
   Hackathons
</a>

<a href="courses.html"
   style="display:block; font-weight:bold; font-size:20px; color:#ff7a00; margin:8px 0;">
   Course Completions
</a>

<a href="internships.html"
   style="display:block; font-weight:bold; font-size:20px; color:#ff7a00; margin:8px 0;">
   Internships
</a>

<a href="fellowships.html"
   style="display:block; font-weight:bold; font-size:20px; color:#ff7a00; margin:8px 0;">
   Fellowships
</a>

<a href="offerletters.html"
   style="display:block; font-weight:bold; font-size:20px; color:#ff7a00; margin:8px 0;">
   Offer Letters
</a>







<!-- PROJECTS -->
<section id="projects" style="padding:40px; background:#0b0b0b; color:white;">

    <h2 style="text-align:center; color:#ff7a00; font-size:32px;">
        Projects
    </h2>

    <div style="display:flex; flex-wrap:wrap; gap:25px; justify-content:center; margin-top:30px;">

        <!-- Project 1: Community Service -->
        <div style="border:2px solid #ff7a00; width:300px; padding:15px; text-align:center;">
            <img src="community.jpg"
                 alt="Community Service Project"
                 style="width:100%; height:160px; object-fit:cover;">
            <h3 style="color:#ff7a00; margin-top:10px;">
                Community Service Project
            </h3>
            <p style="line-height:1.6;">
                Worked on a college-organized community service project focused on
                social awareness and real-world problem solving.
            </p>
        </div>

        <!-- Project 2: Smart Timetable Scheduler -->
        <div style="border:2px solid #ff7a00; width:300px; padding:15px; text-align:center;">
            <img src="timetable.jpg"
                 alt="Smart Timetable Scheduler"
                 style="width:100%; height:160px; object-fit:cover;">
            <h3 style="color:#ff7a00; margin-top:10px;">
                Smart Timetable Scheduler
            </h3>
            <p style="line-height:1.6;">
                Developed a smart timetable scheduling system as a group project to
                efficiently organize classes and time slots.
            </p>
        </div>

        <!-- Project 3: EV Electric Vehicles Website -->
        <div style="border:2px solid #ff7a00; width:300px; padding:15px; text-align:center;">
            <img src="ev.jpg"
                 alt="EV Electric Vehicles Website"
                 style="width:100%; height:160px; object-fit:cover;">
            <h3 style="color:#ff7a00; margin-top:10px;">
                EV – Electric Vehicles Website
            </h3>
            <p style="line-height:1.6;">
                Created a group-based informational website on Electric Vehicles,
                highlighting features, benefits, and future scope.
            </p>
        </div>

    </div>

</section>


<!-- CONTACT -->
<section class="contact" id="contact">
    <h2 class="title">Contact</h2>

    <form>
        <input type="text" placeholder="Your Name">
        <input type="email" placeholder="Your Email">
        <textarea placeholder="Message"></textarea>
        <button>Send</button>
    </form>
</section>

    </div>





<!-- FOOTER -->
<footer>
    <p>Gurram Vennela Portfolio</p>
</footer>

</body>
</html>
