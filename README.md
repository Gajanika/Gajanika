<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Full Stack Developer Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar">
        <div class="nav-container">
            <div class="nav-logo">
                <h2>Portfolio</h2>
            </div>
            <ul class="nav-menu">
                <li class="nav-item">
                    <a href="#home" class="nav-link">Home</a>
                </li>
                <li class="nav-item">
                    <a href="#about" class="nav-link">About</a>
                </li>
                <li class="nav-item">
                    <a href="#skills" class="nav-link">Skills</a>
                </li>
                <li class="nav-item">
                    <a href="#achievements" class="nav-link">Achievements</a>
                </li>
                <li class="nav-item">
                    <a href="#education" class="nav-link">Education</a>
                </li>
                <li class="nav-item">
                    <a href="#contact" class="nav-link">Contact</a>
                </li>
            </ul>
            <div class="hamburger">
                <span class="bar"></span>
                <span class="bar"></span>
                <span class="bar"></span>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-container">
            <div class="hero-content">
                <div class="hero-greeting">
                    <span class="greeting-text">Hello, I'm</span>
                </div>
                <h1 class="hero-title">Full Stack Developer</h1>
                <p class="hero-subtitle">Passionate and driven software developer with expertise in both frontend and backend technologies. Creating innovative solutions that make a meaningful impact in the industry.</p>
                <div class="hero-buttons">
                    <a href="#contact" class="btn btn-primary">
                        <i class="fas fa-envelope"></i>
                        Get In Touch
                    </a>
                    <a href="#achievements" class="btn btn-secondary">
                        <i class="fas fa-trophy"></i>
                        View Achievements
                    </a>
                </div>
                <div class="hero-stats">
                    <div class="stat-item">
                        <span class="stat-number">15+</span>
                        <span class="stat-label">Technologies</span>
                    </div>
                    <div class="stat-item">
                        <span class="stat-number">3+</span>
                        <span class="stat-label">Years Learning</span>
                    </div>
                    <div class="stat-item">
                        <span class="stat-number">1</span>
                        <span class="stat-label">Award Won</span>
                    </div>
                </div>
            </div>
            <div class="hero-visual">
                <div class="profile-card">
                    <div class="profile-image">
                        <i class="fas fa-user-circle"></i>
                    </div>
                    <div class="floating-icons">
                        <div class="tech-icon icon-1"><i class="fab fa-html5"></i></div>
                        <div class="tech-icon icon-2"><i class="fab fa-css3-alt"></i></div>
                        <div class="tech-icon icon-3"><i class="fab fa-js-square"></i></div>
                        <div class="tech-icon icon-4"><i class="fab fa-angular"></i></div>
                        <div class="tech-icon icon-5"><i class="fab fa-python"></i></div>
                        <div class="tech-icon icon-6"><i class="fas fa-database"></i></div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title">About Me</h2>
                <p class="section-subtitle">Driven by passion, shaped by experience, focused on innovation</p>
            </div>
            <div class="about-content">
                <div class="about-text">
                    <p class="about-description">
                        I am a passionate and driven Full Stack Software Developer with a strong foundation in both frontend and backend technologies. My journey began with early education at Somasuntharam Nursery and continued at J/ST. John Bosco's Vidyalayam, where I learned the importance of perseverance and smart work.
                    </p>
                    <p class="about-description">
                        As a member of the Board of Prefects at J/Holy Family Convent National School, I developed strong leadership abilities, social understanding, and communication skills that complement my technical expertise.
                    </p>
                    <div class="about-highlights">
                        <div class="highlight-item">
                            <i class="fas fa-code"></i>
                            <span>Full Stack Development</span>
                        </div>
                        <div class="highlight-item">
                            <i class="fas fa-users"></i>
                            <span>Leadership & Communication</span>
                        </div>
                        <div class="highlight-item">
                            <i class="fas fa-lightbulb"></i>
                            <span>Innovation & Problem Solving</span>
                        </div>
                    </div>
                </div>
                <div class="about-experience">
                    <h3>Volunteering Experience</h3>
                    <div class="experience-item">
                        <div class="experience-icon">
                            <i class="fas fa-chalkboard-teacher"></i>
                        </div>
                        <div class="experience-content">
                            <h4>ICT and Accounting Tutor</h4>
                            <span class="experience-period">May 2023 - March 2024</span>
                            <p>Self-initiated tutoring for A/L students, focusing on enhancing understanding of key concepts and practical applications.</p>
                        </div>
                    </div>
                    <div class="experience-item">
                        <div class="experience-icon">
                            <i class="fas fa-shopping-cart"></i>
                        </div>
                        <div class="experience-content">
                            <h4>Online Shopping Assistance</h4>
                            <span class="experience-period">Ongoing</span>
                            <p>Voluntarily assist community members with online purchases, enhancing skills in research, coordination, and time management.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="skills">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title">Technical Skills</h2>
                <p class="section-subtitle">Comprehensive expertise across the full development stack</p>
            </div>
            <div class="skills-grid">
                <div class="skill-category">
                    <h3>Frontend Technologies</h3>
                    <div class="skill-items">
                        <div class="skill-item">
                            <i class="fab fa-html5"></i>
                            <span>HTML</span>
                        </div>
                        <div class="skill-item">
                            <i class="fab fa-css3-alt"></i>
                            <span>CSS</span>
                        </div>
                        <div class="skill-item">
                            <i class="fab fa-js-square"></i>
                            <span>JavaScript</span>
                        </div>
                        <div class="skill-item">
                            <i class="fab fa-bootstrap"></i>
                            <span>Bootstrap</span>
                        </div>
                        <div class="skill-item">
                            <i class="fab fa-angular"></i>
                            <span>Angular</span>
                        </div>
                        <div class="skill-item">
                            <i class="fas fa-code"></i>
                            <span>TypeScript</span>
                        </div>
                    </div>
                </div>
                <div class="skill-category">
                    <h3>Backend Technologies</h3>
                    <div class="skill-items">
                        <div class="skill-item">
                            <i class="fas fa-hashtag"></i>
                            <span>C#</span>
                        </div>
                        <div class="skill-item">
                            <i class="fas fa-server"></i>
                            <span>.NET 8 Web API</span>
                        </div>
                        <div class="skill-item">
                            <i class="fab fa-java"></i>
                            <span>Java</span>
                        </div>
                        <div class="skill-item">
                            <i class="fab fa-python"></i>
                            <span>Python</span>
                        </div>
                        <div class="skill-item">
                            <i class="fas fa-leaf"></i>
                            <span>Spring Tool Suite</span>
                        </div>
                    </div>
                </div>
                <div class="skill-category">
                    <h3>Databases & Tools</h3>
                    <div class="skill-items">
                        <div class="skill-item">
                            <i class="fas fa-database"></i>
                            <span>SQL Server</span>
                        </div>
                        <div class="skill-item">
                            <i class="fas fa-database"></i>
                            <span>MongoDB</span>
                        </div>
                        <div class="skill-item">
                            <i class="fas fa-database"></i>
                            <span>MySQL</span>
                        </div>
                        <div class="skill-item">
                            <i class="fab fa-figma"></i>
                            <span>Figma</span>
                        </div>
                        <div class="skill-item">
                            <i class="fas fa-tools"></i>
                            <span>Postman</span>
                        </div>
                        <div class="skill-item">
                            <i class="fas fa-server"></i>
                            <span>XAMPP</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Achievements Section -->
    <section id="achievements" class="achievements">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title">Achievements</h2>
                <p class="section-subtitle">Recognition for innovation and excellence</p>
            </div>
            <div class="achievement-spotlight">
                <div class="achievement-card">
                    <div class="achievement-icon">
                        <i class="fas fa-trophy"></i>
                    </div>
                    <div class="achievement-content">
                        <h3>National Recognition</h3>
                        <h4>Sahasak Nimavum 2022</h4>
                        <p class="achievement-subtitle">National Inventions and Innovations Competition</p>
                        <p class="achievement-description">
                            My innovative project "School Time Table" was recognized at this prestigious competition organized by the Sri Lanka Inventors Commission under the Ministry of Education. This achievement reflects my passion for creating efficient solutions that improve how school timetables are organized and maintained.
                        </p>
                        <div class="achievement-details">
                            <div class="detail-item">
                                <i class="fas fa-calendar"></i>
                                <span>2022</span>
                            </div>
                            <div class="detail-item">
                                <i class="fas fa-building"></i>
                                <span>Ministry of Education</span>
                            </div>
                            <div class="detail-item">
                                <i class="fas fa-medal"></i>
                                <span>Innovation Award</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Education Section -->
    <section id="education" class="education">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title">Education Journey</h2>
                <p class="section-subtitle">Continuous learning and skill development</p>
            </div>
            <div class="education-timeline">
                <div class="timeline-item">
                    <div class="timeline-marker"></div>
                    <div class="timeline-content">
                        <h3>Bachelor of Information Technology</h3>
                        <h4>University of Moratuwa</h4>
                        <span class="timeline-period">Current</span>
                        <p>Focusing on Python development to become a versatile professional in the software industry.</p>
                        <div class="timeline-skills">
                            <span class="skill-tag">Python</span>
                            <span class="skill-tag">Software Engineering</span>
                            <span class="skill-tag">IT Systems</span>
                        </div>
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-marker"></div>
                    <div class="timeline-content">
                        <h3>Full Stack Software Development</h3>
                        <h4>Jaffna Technical College</h4>
                        <span class="timeline-period">Current</span>
                        <p>Expanding expertise in advanced development technologies and frameworks.</p>
                        <div class="timeline-skills">
                            <span class="skill-tag">Java</span>
                            <span class="skill-tag">MongoDB</span>
                            <span class="skill-tag">Spring Tool Suite</span>
                            <span class="skill-tag">MySQL</span>
                        </div>
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-marker"></div>
                    <div class="timeline-content">
                        <h3>Diploma in Software Programming</h3>
                        <h4>Unicom TIC</h4>
                        <span class="timeline-period">Completed</span>
                        <p>Comprehensive Full Stack Software Development program covering modern web technologies.</p>
                        <div class="timeline-skills">
                            <span class="skill-tag">HTML/CSS</span>
                            <span class="skill-tag">JavaScript</span>
                            <span class="skill-tag">Angular</span>
                            <span class="skill-tag">C#</span>
                            <span class="skill-tag">.NET</span>
                        </div>
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-marker"></div>
                    <div class="timeline-content">
                        <h3>Secondary Education</h3>
                        <h4>J/Holy Family Convent National School</h4>
                        <span class="timeline-period">Completed</span>
                        <p>Member of the Board of Prefects, developing leadership and communication skills.</p>
                        <div class="timeline-skills">
                            <span class="skill-tag">Leadership</span>
                            <span class="skill-tag">Communication</span>
                            <span class="skill-tag">Social Understanding</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title">Let's Connect</h2>
                <p class="section-subtitle">Ready to collaborate on innovative projects</p>
            </div>
            <div class="contact-content">
                <div class="contact-info">
                    <div class="contact-card">
                        <div class="contact-icon">
                            <i class="fas fa-envelope"></i>
                        </div>
                        <h4>Email</h4>
                        <p>developer@email.com</p>
                    </div>
                    <div class="contact-card">
                        <div class="contact-icon">
                            <i class="fab fa-linkedin"></i>
                        </div>
                        <h4>LinkedIn</h4>
                        <p>Connect with me</p>
                    </div>
                    <div class="contact-card">
                        <div class="contact-icon">
                            <i class="fab fa-github"></i>
                        </div>
                        <h4>GitHub</h4>
                        <p>View my projects</p>
                    </div>
                </div>
                <div class="contact-form-container">
                    <form class="contact-form">
                        <div class="form-group">
                            <input type="text" placeholder="Your Name" required>
                        </div>
                        <div class="form-group">
                            <input type="email" placeholder="Your Email" required>
                        </div>
                        <div class="form-group">
                            <input type="text" placeholder="Subject" required>
                        </div>
                        <div class="form-group">
                            <textarea placeholder="Your Message" rows="5" required></textarea>
                        </div>
                        <button type="submit" class="btn btn-primary">
                            <i class="fas fa-paper-plane"></i>
                            Send Message
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <h3>Full Stack Developer</h3>
                    <p>Creating innovative solutions that make a meaningful impact in the software industry.</p>
                    <div class="social-links">
                        <a href="#" class="social-link"><i class="fab fa-linkedin"></i></a>
                        <a href="#" class="social-link"><i class="fab fa-github"></i></a>
                        <a href="#" class="social-link"><i class="fab fa-twitter"></i></a>
                        <a href="#" class="social-link"><i class="fas fa-envelope"></i></a>
                    </div>
                </div>
                <div class="footer-section">
                    <h4>Quick Links</h4>
                    <ul>
                        <li><a href="#home">Home</a></li>
                        <li><a href="#about">About</a></li>
                        <li><a href="#skills">Skills</a></li>
                        <li><a href="#achievements">Achievements</a></li>
                        <li><a href="#education">Education</a></li>
                        <li><a href="#contact">Contact</a></li>
                    </ul>
                </div>
                <div class="footer-section">
                    <h4>Goal</h4>
                    <p>To continuously grow as a Full Stack Software Developer, contributing to innovative projects while expanding my skill set and enhancing my ability to make a meaningful impact in the industry.</p>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2025 Full Stack Developer Portfolio. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
