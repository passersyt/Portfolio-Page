# Portfolio-Page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Shreyansh - Portfolio</title>
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
        <style>
        <style>
            body {
                * {
                    margin: 0;
                    padding: 0;
                }
    
                background-color: rgb(1, 1, 12);
                colour:white;
                font-family:'poppins',
                sans-serif;
            }
    
            nav {
                display: flex;
                justify-content: space-around;
                align-items: center;
                height: 100px;
                background-color: rgb(159, 159, 235);
            }
    
            nav ul {
                display: flex;
                justify-content: center;
            }
    
            nav ul li {
                list-style: none;
                margin: 0 23px;
    
            }
    
            nav ul li a {
                text-decoration: none;
                color: rgb(38, 38, 131);
                font-size: 1.2rem;
            }
    
            nav ul li a:hover {
                color: white;
            }
    
            .left {
                font-size: 2rem;
            }
    
            .firstSection {
                display: flex;
                justify-content: space-around;
                margin: 13px 0;
            }
    
            .firstSection div {
                width: 30%;
                margin: 40px;
            }
    
            .leftSection {
                width: 1%;
                font-size: 2.5rem;
                background-color: white;
                margin-top: 500px;
                text-color: lavender;
            }
    
            .rightSection {
                width: 10%;
                height: 20;
                margin: 70px;
                background-color: white;
            }
    
            .rightSection img {
                border: 1px;
                border-radius: 4px;
                width: 50%;
                margin-left: auto;
                margin-right: auto;
                margin-top: 1%;
                object-fit: contain;
                float: right;
                margin: 20px 0;
                border-radius: 5%;
            }
    
            #element {
                color: rgb(38, 38, 131);
            }
    
            .secondSection {
                max-width: 80vw;
                margin: auto;
                color: rgb(38, 38, 131);
                height: 80vh;
            }
    
            .secondSection h1 {
                font-size: 1.9rem;
            }
    
            .secondSection .box {
                background: rgb(38, 38, 131);
                width: 80vw;
                height: 2px;
                margin: 56px 0;
                display: flex;
            }
    
            main hr {
                border: 0;
                background: #9c97f1;
                height: 1.2px;
                margin: 40px 84px;
            }
    
            .secondSection .vertical {
                height: 93px;
                width: 1px;
                background-color: rgb(38, 38, 131);
                margin: 0 130px;
    
    
            }
    
    
    
            .vertical-title {
                position: relative;
                top: 100px;
                width: 150px;
                font-size: 18px;
    
            }
    
            .vertical-desc {
                position: relative;
                top: 120px;
                width: 120px;
                font-size: 13px;
            }
        </style>
    </head>
    
    <body>
        <header>
            <nav>
                <div class="left">PERSONAL PORTFOLIO</div>
                <div class="right">
                    <ul>
                        <li><a href="#home"> Home</a></li>
                        <li><a href="#about"> About</a></li>
                        <li><a href="#projects"> Projects</a></li>  
                    </ul>
                </div>
            </nav>
        </header>
    
        </header>
        <main>
            <section id="about" class="firstSection">
                <div class="leftSection"> </span> <span id="element"> </span> </break>
    
    
    
                </div>
                <div class="rightSection">
                    <img src="/WhatsApp Image 2024-10-25 at 18.50.12.jpeg" style="margin-right: 100px;">
    
                </div>
            </section>
            <hr style="border:0; background: #9c97f1; height: 1.2px; margin: 40px 84px;">
    
            <section id="projects" class="secondSection">
                <h1>PROJECTS</h1>
                <div class="box">
                    <div class="vertical">
                        <div class="vertical-title">
                            LPU Login[HTML CSS]
                        </div>
                        <div class="vertical-desc">
                            In Lpu Login we insert our User ID, Phone No., Password and confirm Password then we will submit it.
                            <br>
                            <br>
                            <a href="/Project1.html">Visit Project</a>
    
                        </div>
                    </div>
                    <div class="vertical">
                        <div class="vertical-title">
                          Marks Table[HTML CSS] 
                        </div>
                        <div class="vertical-desc">
                        In Marks Table we create a border, four column for Students, Maths, Physics, Computer Science and we will insert their values.
                        <br>
                        <br>
                        <a href="/Project.html">Visit Project</a>
                        </div>
    
                    </div>
                    <div class="vertical">
                        <div class="vertical-title">
                        Portfolio Page
                        </div>
                        <div class="vertical-desc">
                            Portfolio Page serves as a testament to my multifaceted skills and extensive projects across diverse domains.It's a dynamic display of my skills and creativity, reflecting a commitment to excellence in the digital realm.
                            <br>
                            <br>
                            <a href="/Project2.html">Visit Project</a>
                        </div>
    
                    </div>
                    <div class="vertical">
                        <div class="vertical-title">
                         Colour Box
                        </div>
                        <div class="vertical-desc">
                         In colour box we create 5 box and insert green colour in 4 box and leave 1 box blank.
                         <br>
                         <br>
                         <a href="/Project3.html">Visit Project</a>
                        </div>
    
                    </div>
            </section>
            
        </main>
    
        <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>
        <!-- Setup and start animation! -->
        <script>
            var typed = new Typed('#element', {
                strings: ['Hi! I am Shreyansh a first-year B.Tech student with an insatiable passion for all things Tech, coupled with a proficient grasp of a diverse range of soft skills.  '],
                typeSpeed: 30,
            });
        
            function smoothScroll(target, duration) {
                const targetElement = document.querySelector(target);
                const targetPosition = targetElement.offsetTop;
                const startPosition = window.pageYOffset;
                const distance = targetPosition - startPosition;
                let startTime = null;
        
                function animation(currentTime) {
                    if (startTime === null) startTime = currentTime;
                    const timeElapsed = currentTime - startTime;
                    const run = ease(timeElapsed, startPosition, distance, duration);
                    window.scrollTo(0, run);
                    if (timeElapsed < duration) requestAnimationFrame(animation);
                }
        
                function ease(t, b, c, d) {
                    t /= d / 2;
                    if (t < 1) return c / 2 * t * t + b;
                    t--;
                    return -c / 2 * (t * (t - 2) - 1) + b;
                }
        
                requestAnimationFrame(animation);
            }
        
            // Add click event listener to "Projects" link
            document.addEventListener('DOMContentLoaded', function() {
                const projectsLink = document.querySelector('a[href="#projects"]');
                const aboutLink = document.querySelector('a[href="#about"]');
                const contactLink = document.querySelector('a[href="#contact"]');
        
                projectsLink.addEventListener('click', function (e) {
                    e.preventDefault();
                    smoothScroll('#projects', 1000); // 1000ms (1 second) duration
                });
        
                aboutLink.addEventListener('click', function (e) {
                    e.preventDefault();
                    smoothScroll('#about', 1000); // 1000ms (1 second) duration
                });
        
                contactLink.addEventListener('click', function (e) {
                    e.preventDefault();
                    smoothScroll('#contact', 1000); // 1000ms (1 second) duration
                });
            });
    
        </script>
    </body>
    </html>
</head>
<body>
