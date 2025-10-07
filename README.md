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
/* ===== Modern Color Palette ===== */
:root {
    /* Base Colors */
    --bg: #f8f9fa;
    --surface: #ffffff;
    --surface-alt: #f1f3f5;
    --text: #495057;
    --text-light: #868e96;
    --heading: #212529;
    
    /* Accent Colors */
    --primary: #4dabf7;
    --primary-dark: #339af0;
    --secondary: #20c997;
    --error: #fa5252;
    
    /* UI Elements */
    --btn-text: #ffffff;
    --image-border: #e9ecef;
    --nav-bg: rgba(255, 255, 255, 0.95);
    --card-bg: #ffffff;
    --footer-bg: #343a40;
    
    /* Shadows */
    --shadow-sm: 0 1px 3px rgba(0, 0, 0, 0.1);
    --shadow-md: 0 4px 6px rgba(0, 0, 0, 0.1);
    --shadow-lg: 0 10px 15px rgba(0, 0, 0, 0.1);
}

/* ===== Base Styles ===== */
*,
*::before,
*::after {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
    line-height: 1.6;
    background-color: var(--bg);
    color: var(--text);
    overflow-x: hidden;
}

a {
    text-decoration: none;
    color: inherit;
}

img {
    max-width: 100%;
    height: auto;
    display: block;
}

.container {
    width: 90%;
    max-width: 1200px;
    margin: 0 auto;
}

.section {
    padding: 6rem 0;
}

.section-title {
    text-align: center;
    font-size: 2.5rem;
    margin-bottom: 3rem;
    color: var(--heading);
    position: relative;
}

.section-title span {
    color: var(--primary);
}

.section-title::after {
    content: '';
    position: absolute;
    bottom: -12px;
    left: 50%;
    transform: translateX(-50%);
    width: 80px;
    height: 4px;
    background-color: var(--primary);
    border-radius: 2px;
}

.btn {
    display: inline-block;
    padding: 0.8rem 1.8rem;
    border-radius: 50px;
    font-weight: 600;
    transition: all 0.3s ease;
    border: 2px solid transparent;
    cursor: pointer;
    font-size: 1rem;
}

.btn.primary {
    background-color: var(--primary);
    color: var(--btn-text);
    box-shadow: var(--shadow-sm);
}

.btn.primary:hover {
    background-color: var(--primary-dark);
    transform: translateY(-2px);
    box-shadow: var(--shadow-md);
}

.btn.secondary {
    background-color: transparent;
    border-color: var(--primary);
    color: var(--primary);
}

.btn.secondary:hover {
    background-color: var(--primary);
    color: var(--btn-text);
    transform: translateY(-2px);
    box-shadow: var(--shadow-sm);
}

.btn.small {
    padding: 0.5rem 1.2rem;
    font-size: 0.9rem;
}

/* ===== Component Styles ===== */
/* Navbar */
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1.5rem 2rem;
    position: fixed ;
    top: 0;
    left: 0;
    width: 100%;
    z-index: 1000;
    transition: all 0.3s ease;
    background-color: var(--nav-bg);
    box-shadow: var(--shadow-sm);
    backdrop-filter: blur(10px);
}

.logo {
    font-size: 1.5rem;
    font-weight: 700;
    color: var(--heading);
}

.logo span {
    color: var(--primary);
}

.nav-links {
    display: flex;
    list-style: none;
}

.nav-links li {
    margin-left: 2rem;
}

.nav-links a {
    color: var(--heading);
    font-weight: 500;
    font-size: 1rem;
    position: relative;
    padding: 0.5rem 0;
    transition: color 0.3s ease;
}

.nav-links a:hover {
    color: var(--primary);
}

.nav-links a::after {
    content: '';
    position: absolute;
    width: 0;
    height: 2px;
    background: var(--primary);
    bottom: 0;
    left: 0;
    transition: width 0.3s ease;
}

.nav-links a:hover::after {
    width: 100%;
}

.hamburger {
    display: none;
    cursor: pointer;
    z-index: 1001;
}

.hamburger div {
    width: 25px;
    height: 3px;
    background-color: var(--heading);
    margin: 5px;
    transition: all 0.3s ease;
}

/* Hero Section */
/* Hero Layout */
.hero{
     padding-top: 150px; 
    margin-top: 0; 
}
.hero-grid {
    display: grid;
    grid-template-columns: 1.2fr 1fr;
    align-items: center;
    gap: 3rem;
    position: relative;
}

.hero-text {
    z-index: 2;
}

/* ===== Hero Text Styles ===== */
.hero-text {
    z-index: 2;
    max-width: 600px; /* Added max-width for better readability */
}

.hero-text h1 {
    font-size: 3.5rem;
    line-height: 1.2;
    margin-bottom: 1.5rem;
    color: var(--heading);
    font-weight: 800;
    animation: fadeInLeft 0.8s ease-out;
}

.hero-text p {
    font-size: 1.25rem;
    line-height: 1.6;
    margin-bottom: 2.5rem;
    color: var(--text);
    animation: fadeInLeft 0.8s ease-out 0.2s;
    animation-fill-mode: both;
}

.profession {
    color: var(--primary);
    font-weight: 600;
    position: relative;
    display: inline-block;
}

.profession::after {
    content: '';
    position: absolute;
    width: 100%;
    height: 3px;
    background-color: var(--primary);
    bottom: -5px;
    left: 0;
    transform: scaleX(0);
    transform-origin: right;
    transition: transform 0.4s ease;
}

.hero-text:hover .profession::after {
    transform: scaleX(1);
    transform-origin: left;
}

.hero-btns {
    display: flex;
    gap: 1.5rem;
    animation: fadeInLeft 0.8s ease-out 0.4s;
    animation-fill-mode: both;
}
.profile-display {
    position: relative;
    display: flex;
    justify-content: flex-end;
}

.profile-frame {
    width: 100%;
    max-width: 360px;
    aspect-ratio: 1/1;
    border-radius: 20px;
    overflow: hidden;
    position: relative;
    border: 8px solid #ffffff;
    box-shadow: 
        0 15px 30px rgba(0, 0, 0, 0.1),
        0 0 0 1px rgba(0, 0, 0, 0.05);
    transition: transform 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.1);
}

.profile-img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: top center;
    filter: grayscale(15%) contrast(110%);
    transition: all 0.4s ease;
}

.profile-frame:hover .profile-img {
    filter: grayscale(0%) contrast(100%);
}

.profile-frame:hover .profile-glow {
    background: linear-gradient(
        45deg,
        rgba(77, 171, 247, 0.25) 0%,
        rgba(77, 171, 247, 0) 70%
    );
}

/* Responsive Design */
@media (max-width: 992px) {
    .hero-grid {
        grid-template-columns: 1fr;
        text-align: center;
    }
    
    .profile-display {
        justify-content: center;
        margin-top: 3rem;
    }
    
    .hero-btns {
        justify-content: center;
    }
}

@media (max-width: 576px) {
    .profile-frame {
        max-width: 280px;
    }
}
/* Projects Section */
.projects-container {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(350px, 1fr));
    gap: 2.5rem;
    margin-top: 3rem;
}

.project-card {
    background-color: var(--card-bg);
    border-radius: 12px;
    overflow: hidden;
    box-shadow: var(--shadow-md);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.project-card:hover {
    transform: translateY(-10px);
    box-shadow: var(--shadow-lg);
}

.project-img {
    height: 220px;
    overflow: hidden;
}

.project-img img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.5s ease;
}

.project-card:hover .project-img img {
    transform: scale(1.1);
}

.project-info {
    padding: 1.8rem;
}

.project-info h3 {
    font-size: 1.4rem;
    margin-bottom: 0.8rem;
    color: var(--heading);
}

.project-info p {
    color: var(--text-light);
    margin-bottom: 1.5rem;
    font-size: 0.95rem;
}

.project-tech {
    display: flex;
    flex-wrap: wrap;
    gap: 0.6rem;
    margin-bottom: 1.5rem;
}

.project-tech span {
    background-color: var(--primary);
    color: white;
    padding: 0.3rem 0.9rem;
    border-radius: 50px;
    font-size: 0.8rem;
    font-weight: 500;
}

.project-links {
    display: flex;
    gap: 1rem;
}

/* Skills Section */
.skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(130px, 1fr));
    gap: 2rem;
    margin-top: 3rem;
}

.skill-item {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 0.8rem;
    padding: 1.8rem 1rem;
    background-color: var(--surface);
    border-radius: 12px;
    transition: all 0.3s ease;
    box-shadow: var(--shadow-sm);
    border: 1px solid var(--image-border);
}

.skill-item:hover {
    transform: translateY(-5px);
    box-shadow: var(--shadow-md);
    border-color: var(--primary);
}

.skill-item i {
    font-size: 2.8rem;
    color: var(--primary);
}

.skill-item span {
    font-weight: 600;
    color: var(--text);
    font-size: 0.95rem;
}
.hibernate-logo {
    width: 3.5rem; /* Match other icons' size */
    height: 3.5rem;
    object-fit: contain;
    transition: transform 0.3s ease;
}

.skill-item:hover .hibernate-logo {
    transform: scale(1.1); /* Match hover effect */
}

/* About Section */
.about-container {
    display: flex;
    align-items: center;
    gap: 4rem;
    margin-top: 3rem;
}

.about-img {
    flex: 1;
    /* display: flex; */
    justify-content: center;
   
}

.about-img img {
    /* max-width: 100%; */
    border-radius: 12px;
    box-shadow: var(--shadow-lg);
    transition: transform 0.3s ease;
}

.about-img img:hover {
    transform: scale(1.02);
}

.about-content {
    flex: 1;
}

.about-content h3 {
    font-size: 1.8rem;
    margin-bottom: 1.5rem;
    color: var(--heading);
}

.about-content p {
    color: var(--text);
    margin-bottom: 2rem;
    line-height: 1.7;
}

.about-details {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 1.2rem;
    margin-bottom: 2.5rem;
}

.detail {
    display: flex;
    gap: 0.8rem;
}

.detail span:first-child {
    font-weight: 600;
    color: var(--heading);
}

.detail span:last-child {
    color: var(--text);
}

/* Contact Section */
.contact-container {
    display: flex;
    gap: 4rem;
    margin-top: 3rem;
}

.contact-info {
    flex: 1;
    display: flex;
    flex-direction: column;
    gap: 1.8rem;
}

.contact-item {
    display: flex;
    align-items: flex-start;
    gap: 1.5rem;
    background-color: var(--surface);
    padding: 2rem;
    border-radius: 12px;
    box-shadow: var(--shadow-sm);
    transition: transform 0.3s ease;
    border: 1px solid var(--image-border);
}

.contact-item:hover {
    transform: translateY(-5px);
    box-shadow: var(--shadow-md);
}

.contact-item i {
    font-size: 1.8rem;
    color: var(--primary);
    margin-top: 0.3rem;
}

.contact-text h3 {
    font-size: 1.3rem;
    margin-bottom: 0.5rem;
    color: var(--heading);
}

.contact-text p {
    color: var(--text);
    font-size: 0.95rem;
}

.contact-form {
    flex: 1;
    background-color: var(--surface);
    padding: 2.5rem;
    border-radius: 12px;
    box-shadow: var(--shadow-sm);
    border: 1px solid var(--image-border);
}

.form-group {
    margin-bottom: 1.8rem;
}

.form-group input,
.form-group textarea {
    width: 100%;
    padding: 1rem;
    border: 1px solid #dee2e6;
    border-radius: 8px;
    background-color: var(--surface);
    color: var(--text);
    font-family: inherit;
    font-size: 1rem;
    transition: all 0.3s ease;
}

.form-group input:focus,
.form-group textarea:focus {
    outline: none;
    border-color: var(--primary);
    box-shadow: 0 0 0 3px rgba(77, 171, 247, 0.2);
}

.form-group textarea {
    min-height: 180px;
    resize: vertical;
}

/* Footer */
.footer {
    background-color: var(--footer-bg);
    color: white;
    padding: 3rem 0;
    text-align: center;
}

.footer-content {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.social-links {
    display: flex;
    justify-content: center;
    gap: 1.8rem;
    margin-bottom: 1.5rem;
}

.social-links a {
    color: white;
    font-size: 1.5rem;
    transition: all 0.3s ease;
    width: 45px;
    height: 45px;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    background-color: rgba(255, 255, 255, 0.1);
}

.social-links a:hover {
    color: white;
    background-color: var(--primary);
    transform: translateY(-3px);
}

/* Animations */
@keyframes fadeInLeft {
    from {
        opacity: 0;
        transform: translateX(-30px);
    }
    to {
        opacity: 1;
        transform: translateX(0);
    }
}

@keyframes fadeInRight {
    from {
        opacity: 0;
        transform: translateX(30px);
    }
    to {
        opacity: 1;
        transform: translateX(0);
    }
}

/* Responsive Styles */
@media screen and (max-width: 992px) {
    .hero {
        flex-direction: column;
        text-align: center;
        padding: 7rem 0 3rem;
    }

    .hero-content {
        padding-right: 0;
        margin-bottom: 4rem;
        display: flex;
        flex-direction: column;
        align-items: center;
    }

    .hero-btns {
        justify-content: center;
    }

    .about-container {
        flex-direction: column;
    }

    .contact-container {
        flex-direction: column;
    }
}

@media screen and (max-width: 768px) {
    .nav-links {
        position: fixed;
        top: 0;
        right: 0;
        height: 100vh;
        width: 70%;
        max-width: 300px;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        background-color: var(--nav-bg);
        box-shadow: -5px 0 15px rgba(0, 0, 0, 0.1);
        clip-path: circle(0px at 90% -10%);
        -webkit-clip-path: circle(0px at 90% -10%);
        transition: all 0.8s ease-out;
        pointer-events: none;
    }

    .nav-links.open {
        clip-path: circle(1500px at 90% -10%);
        -webkit-clip-path: circle(1500px at 90% -10%);
        pointer-events: all;
    }

    .nav-links li {
        margin: 1.5rem 0;
        opacity: 0;
    }

    .nav-links.open li {
        opacity: 1;
    }

    .nav-links li:nth-child(1) {
        transition: all 0.5s ease 0.2s;
    }

    .nav-links li:nth-child(2) {
        transition: all 0.5s ease 0.3s;
    }

    .nav-links li:nth-child(3) {
        transition: all 0.5s ease 0.4s;
    }

    .nav-links li:nth-child(4) {
        transition: all 0.5s ease 0.5s;
    }

    .nav-links li:nth-child(5) {
        transition: all 0.5s ease 0.6s;
    }

    .hamburger {
        display: block;
    }

    .hamburger.open .line1 {
        transform: rotate(-45deg) translate(-5px, 6px);
    }

    .hamburger.open .line2 {
        opacity: 0;
    }

    .hamburger.open .line3 {
        transform: rotate(45deg) translate(-5px, -6px);
    }

    .projects-container {
        grid-template-columns: 1fr;
    }

    .skills-grid {
        grid-template-columns: repeat(auto-fill, minmax(110px, 1fr));
    }
}

@media screen and (max-width: 576px) {
    .navbar {
        padding: 1.2rem;
    }

    .hero {
        padding: 6rem 0 2rem;
    }

    .hero-btns {
        flex-direction: column;
        align-items: center;
    }

    .image-container {
        width: min(300px, 100%);
        height: min(300px, 100%);
    }

    .about-details {
        grid-template-columns: 1fr;
    }

    .section {
        padding: 4rem 0;
    }

    .section-title {
        font-size: 2rem;
    }

    .contact-item {
        flex-direction: column;
        align-items: center;
        text-align: center;
    }

    .contact-item i {
        margin-bottom: 0.8rem;
    }
}
