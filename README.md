<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" href="Images/profile photo.jpg">
    <title>Aditya Lokhande - Portfolio ></title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="stylesheet" href="css/style.css">
</head>

<body>
    <nav class="navbar">
        <a href="#" class="logo">Aditya<span>Lokhande</span></a>
        <ul class="nav-links" id="navLinks">
            <li><a href="#home">Home</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
        <div class="hamburger" id="hamburger">
            <div class="line1"></div>
            <div class="line2"></div>
            <div class="line3"></div>
        </div>
    </nav>

    <section class="hero" id="home">
    <div class="container">
        <div class="hero-grid">
            <div class="hero-text">
                <h1>Hi, I'm <span>Aditya Lokhande</span></h1>
                <p>I'm a passionate <span class="profession">Full Java Stack Developer</span> creating modern web applications.</p>
                <div class="hero-btns">
                    <a href="#projects" class="btn primary">View My Work</a>
                    <a href="#contact" class="btn secondary">Contact Me</a>
                </div>
            </div>
            
            <div class="profile-display">
                <div class="profile-frame">
                    <img src="Images/profile photo.jpg" alt="Aditya Lokhande" class="profile-img">
                    <div class="profile-glow"></div>
                </div>
            </div>
        </div>
    </div>
</section>

    <section class="section projects" id="projects">
        <div class="container">
            <h2 class="section-title">My <span>Projects</span></h2>
            <div class="projects-container">
                <div class="project-card">
                    <div class="project-img">
                        <img src="Images/portfolio.png"
                            alt="portfolio">
                    </div>
                    <div class="project-info">
                        <h3>Portfolio-Website</h3>
                        <p>A responsive portfolio website built with HTML, CSS, and JavaScript to showcase my projects and demonstrate my foundational web development skills.</p>
                        <div class="project-tech">
                            <span>HTML:5</span>
                            <span>CSS</span>
                            <span>JavaScript</span>
                        </div>
                        <div class="project-links">
                            <a href="#" class="btn small secondary">Live Demo</a>
                            </div>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-img">
                        <img src="https://images.unsplash.com/photo-1460925895917-afdab827c52f?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=815&q=80"
                            alt="Analytics Dashboard">
                    </div>
                    <div class="project-info">
                        <h3>Data Analytics Dashboard</h3>
                        <p>Interactive dashboard with real-time data visualization</p>
                        <div class="project-tech">
                            <span>Angular</span>
                            <span>Python</span>
                            <span>D3.js</span>
                        </div>
                        <div class="project-links">
                            <a href="#" class="btn small secondary">Live Demo</a>
                            </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="section skills" id="skills">
        <div class="container">
            <h2 class="section-title">My <span>Skills</span></h2>
            <div class="skills-grid">
                <div class="skill-item">
                    <i class="fab fa-html5"></i>
                    <span>HTML5</span>
                </div>
                <div class="skill-item">
                    <i class="fab fa-css3-alt"></i>
                    <span>CSS3</span>
                </div>
                <div class="skill-item">
                    <i class="fab fa-js"></i>
                    <span>JavaScript</span>
                </div>
                <div class="skill-item">
                    <i class="fab fa-react"></i>
                    <span>React</span>
                </div>


                <div class="skill-item">
                    <i class="fab fa-java"></i>
                    <span>Java</span>
                </div>
                <div class="skill-item">
                    <i class="fas fa-leaf"></i>
                    <span>Spring Boot</span>
                </div>
                <div class="skill-item">
                    <i class="fas fa-database"></i>
                    <span>MySQL</span>
                </div>
                <div class="skill-item">
                    <img src="https://hibernate.org/images/hibernate-logo.svg" alt="Hibernate" class="hibernate-logo">
                    <span>Hibernate</span>
                </div>
                <div class="skill-item">
                    <i class="fas fa-handshake"></i> <span>Communication</span>
                </div>
            </div>
        </div>
    </section>

    <section class="section about" id="about">
        <div class="container">
            <h2 class="section-title">About <span>Me</span></h2>
            <div class="about-container">
                <div class="about-content">
                    <h3>Full Stack Developer</h3>
                    <p>I specialize in building responsive, user-friendly web applications using modern technologies.
                        With expertise in both frontend and backend development, I create seamless digital experiences
                        from concept to deployment.</p>
                    <div class="about-details">
                        <div class="detail">
                            <span>Name:</span>
                            <span>Aditya Lokhande</span>
                        </div>
                        <div class="detail">
                            <span>Email:</span>
                            <span>adityalokhande1204@gmail.com</span>
                        </div>
                        <div class="detail">
                            <span>Location:</span>
                            <span>Pune, India</span>
                        </div>
                        <div class="detail">
                            <span>Experience:</span>
                            <span> Fresher</span>
                        </div>
                    </div>
                    <a href="resume/Aditya Lokhande Resume .pdf" title="Aditya Lokhande's resume" target="_blank" class="btn primary"><i
                            class="fas fa-download"></i> Download CV</a>
                </div>
            </div>
        </div>
    </section>

    <section class="section contact" id="contact">
        <div class="container">
            <h2 class="section-title">Contact <span>Me</span></h2>
            <div class="contact-container">
                <div class="contact-info">
                    <div class="contact-item">
                        <i class="fas fa-envelope"></i>
                        <div class="contact-text">
                            <h3>Email</h3>
                            <p>adityalokhande1204@gmail.com</p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <i class="fas fa-phone"></i>
                        <div class="contact-text">
                            <h3>Phone</h3>
                            <p>+91 9322542392</p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <i class="fas fa-map-marker-alt"></i>
                        <div class="contact-text">
                            <h3>Location</h3>
                            <p>Pune, India</p>
                        </div>
                    </div>
                </div>
                <form class="contact-form"  action="https://formspree.io/f/xjkoelkr" method="POST">
                    <input type="hidden" name="_subject" value="New Portfolio Message!">
                    <input type="hidden" name="_template" value="table">
                    <input type="hidden" name="_captcha" value="false">
                    <input type="hidden" name="_next" value="https://yourportfolio.com/thank-you.html">

                    <div class="form-group">
                        <input type="text" name="name" placeholder="Your Name" required>
                    </div>
                    <div class="form-group">
                        <input type="email" name="email" placeholder="Your Email" required>
                    </div>
                    <div class="form-group">
                        <textarea name="message" placeholder="Your Message" required></textarea>
                    </div>
                    <button type="submit" class="btn primary">Send Message</button>
                </form>
            </div>
        </div>
    </section>

    <footer class="footer">
        <div class="container">
            <div class="footer-content">
                <div class="social-links">
                    <a href="https://github.com/adiii436" target="_blank"><i class="fab fa-github"></i></a>
                    <a href="https://www.linkedin.com/in/aditya lokhande/" target="_blank"><i
                            class="fab fa-linkedin"></i></a>
                    </div>
                <p>&copy; <span id="current-year"></span> Aditya Lokhande. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <script src="javaScript/script.js"></script>
</body>

</html>
