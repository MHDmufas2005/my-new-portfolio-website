<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Mufas Portfolio</title>

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet" />

    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet" />

    <link href="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.css" rel="stylesheet" />

    <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css" rel="stylesheet" />

    <link rel="stylesheet" href="style.css" />
</head>

<body>
    <div id="social-bar" data-aos="fade-down" data-aos-duration="700">
        <div class="social-icons" id="social-icon-toggle" title="Show Social Links">
            <i class="bi bi-share-fill"></i>
            <span class="tooltip">Social Media</span>
        </div>
    </div>
<!--
    <div id="social-links-panel">
        <a href="https://facebook.com/yourprofile" target="_blank"><i class="bi bi-facebook"></i> Facebook</a>
    </div>
-->
    <div id="top-button-bar" data-aos="fade-down" data-aos-duration="700">  
        <a href="#contact" class="btn btn-outline-warning">Contact Me</a>
        <a href="#skills" class="btn btn-outline-warning">Skills</a>
        <a href="#more" class="btn btn-outline-warning">Certificates</a>
        <a href="#experience" class="btn btn-outline-warning">Experience</a>
        <a href="#projects" class="btn btn-outline-warning">Projects</a>
        <a href="#education" class="btn btn-outline-warning">Education</a>
        <a href="#about" class="btn btn-outline-warning">About Me</a>
    </div>

    <div id="hamburger-menu" aria-label="Toggle navigation" tabindex="0" role="button" title="Menu">
        <span></span>
        <span></span>
        <span></span>
    </div>

    <nav class="navbar navbar-expand-lg" data-aos="" data-aos-duration="800">
        <div class="container">
            <a class="navbar-brand" href="#">M.MOHAMED MUFAS</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="https://web.facebook.com/mohamedmufas2005" target="_blank" aria-label="Facebook" rel="noopener"><i class="bi bi-facebook"></i></a></li>
                    <li class="nav-item"><a class="nav-link" href="https://www.instagram.com/mohamed___mufas/" target="_blank" aria-label="Instagram" rel="noopener"><i class="bi bi-instagram"></i></a></li>
                    <li class="nav-item"><a class="nav-link" href="https://www.linkedin.com/in/mohamed-mufas-muf2005/" target="_blank" aria-label="LinkedIn" rel="noopener"><i class="bi bi-linkedin"></i></a></li>
                    <li class="nav-item"><a class="nav-link" href="https://github.com/MHDmufas2005" target="_blank" aria-label="GitHub" rel="noopener"><i class="bi bi-github"></i></a></li>
                    <li class="nav-item"><a class="nav-link" href="https://t.me/edman_mfz" target="_blank" aria-label="Telegram" rel="noopener"><i class="bi bi-telegram"></i></a></li>
                    <li class="nav-item"><a class="nav-link" href="mailto:mohamedmufas.muf@gmail.com" aria-label="Email"><i class="bi bi-envelope"></i></a></li>
                    <li class="nav-item"><a class="nav-link" href="https://twitter.com/yourprofile" target="_blank" aria-label="Twitter" rel="noopener"><i class="bi bi-twitter"></i></a></li>
                    <li class="nav-item"><a class="nav-link" href="https://www.threads.net/@yourprofile" target="_blank" aria-label="Threads" rel="noopener"><i class="bi bi-chat-dots"></i></a></li>
                </ul>
            </div>
        </div>
    </nav>

    <section id="hero" data-aos="fade-up">
        <div class="container">
            <div class="row">
                <div class="col-md-6 text-center text-md-start" data-aos="fade-right" data-aos-delay="200">
                    <h2>FULL STACK DEVELOPER & SYSTEM ADMINISTRATOR</h2>
                    <p class="mt-3">passionate Full Stack Developer and Cybersecurity Enthusiast with experience in System Administration and IT Support. Skilled in creating secure,
                        scalable web applications, managing IT infrastructures, and solving complex technical challenges. Driven by innovation,
                        problem-solving, and a mission to bridge technology with security.</p>
                </div>
                <div class="col-md-6 text-center" data-aos="zoom-in" data-aos-delay="400">
                    <img src="profile.jpg" alt="Mufas Profile Photo" class="img-fluid" width="50%
                    ", height="300px"/>
                </div>
            </div>
        </div>
    </section>

    <section id="about" data-aos="fade-up" data-aos-delay="100">
        <div class="container">
            <h2 class="section-title" data-aos="fade-down" data-aos-delay="200">About Me</h2>
            <p class="text-center" data-aos="fade-up" data-aos-delay="300">
                I'm a dedicated IT professional with a passion for cybersecurity, system administration, and digital marketing.
                Skilled in networking, softwaring, troubleshooting, and effective communication with clients and teams.
            </p>
        </div>
    </section>

    <section id="skills" data-aos="fade-up" data-aos-delay="100">
        <div class="container">
            <h2 class="section-title" data-aos="fade-down" data-aos-delay="200">Skills</h2>
            <div class="row">
                <div class="col-md-4" data-aos="fade-up" data-aos-delay="300">
                    <div class="card p-3 mb-4">
                        <h5 class="card-title">IT & Networking</h5>
                        <p class="card-text">System administration, network configuration, troubleshooting, and security monitoring.</p>
                    </div>
                </div>
                <div class="col-md-4" data-aos="fade-up" data-aos-delay="400">
                    <div class="card p-3 mb-4">
                        <h5 class="card-title">Communication & Leadership</h5>
                        <p class="card-text">Excellent public speaking, interpersonal communication, leadership, and teamwork skills.</p>
                    </div>
                </div>
                <div class="col-md-4" data-aos="fade-up" data-aos-delay="500">
                    <div class="card p-3 mb-4">
                        <h5 class="card-title">Office & Technical Tools</h5>
                        <p class="card-text">Advanced MS Office, data entry, digital marketing tools, graphic design, and AI foundations.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="experience" data-aos="fade-up" data-aos-delay="100">
        <div class="container">
            <h2 class="section-title" data-aos="fade-down" data-aos-delay="200">Experience</h2>
            <div class="card p-3 mb-4" data-aos="fade-up" data-aos-delay="300">
                <h5 class="card-title">CANOPUS IT SOLUTION</h5>
                <p>IT SUPPORT ENGINEER</p>
            </div>

            <div class="card p-3 mb-4" data-aos="fade-up" data-aos-delay="300">
                <h5 class="card-title">PORT CITY BPO PVT LTD</h5>
                <p>SDE OFFICER</p>
            </div>

            <div class="card p-3 mb-4" data-aos="fade-up" data-aos-delay="300">
                <h5 class="card-title">AL DAR ISLAMIC MEDIA</h5>
                <p>PROPRIETOR</p>
            </div>

            <div class="card p-3 mb-4" data-aos="fade-up" data-aos-delay="300">
                <h5 class="card-title">AWI WEALTH INSTITUTE - CANADA</h5>
                <p>digital media marketing executive</p>
            </div>
        </div>
    </section>

    <section id="education" data-aos="fade-up" data-aos-delay="100">
        <div class="container">
            <h2 class="section-title" data-aos="fade-down" data-aos-delay="200">Education</h2>
            <div class="row">
                <div class="col-md-6" data-aos="fade-right" data-aos-delay="300">
                    <div class="card p-3 mb-4">
                        <h5 class="card-title">UNIVERSITY OF COLOMBO</h5>
                        <p class="card-text">Bachelor’s Degree in Information Technology (Reading)</p>
                    </div>
                </div>
                <div class="col-md-6" data-aos="fade-left" data-aos-delay="400">
                    <div class="card p-3 mb-4">
                        <h5 class="card-title">Dharus Salam Arabic College</h5>
                        <p class="card-text">Advanced Higher & Sharee’a Studies (2019–2024)</p>
                    </div>

                    <div class="col-md-6" data-aos="fade-left" data-aos-delay="400">
                        <div class="card p-3 mb-4">
                            <h5 class="card-title">CENTER OF EXCELLENCE - Manchester UK</h5>
                            <p class="card-text">Diploma of superLearner-psychology (2021)</p>
                        </div>
                    </div>

                    <div class="col-md-6" data-aos="fade-left" data-aos-delay="400">
                        <div class="card p-3 mb-4">
                            <h5 class="card-title">CASED INSTITUTE ACADEMY</h5>
                            <p class="card-text">Diploma In Artificial Intelligence</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="more" data-aos="fade-up" data-aos-delay="100">
        <div class="container">
            <h2 class="section-title" data-aos="fade-down" data-aos-delay="200">Certificates</h2>
            <div class="row">
                <div class="col-md-4" data-aos="zoom-in" data-aos-delay="300">
                    <div class="card p-3 mb-4">
                        <h5 class="card-title">Cybersecurity & Technical</h5>
                        <p class="card-text">Ethical Hacking (CEH v11), Cisco Cybersecurity, IoT by SLTC/IEEE, System Admin (ELC UK)</p>
                    </div>
                </div>
                <div class="col-md-4" data-aos="zoom-in" data-aos-delay="400">
                    <div class="card p-3 mb-4">
                        <h5 class="card-title">Professional Courses</h5>
                        <p class="card-text">MBA, Marketing Strategy, LinkedIn Marketing, Leadership Management (Udemy, ICAS, Hillston)</p>
                    </div>
                </div>
                <div class="col-md-4" data-aos="zoom-in" data-aos-delay="500">
                    <div class="card p-3 mb-4">
                        <h5 class="card-title">Management Diplomas</h5>
                        <p class="card-text">HRM, Psychology, English & Computing, Super Learner, Media & Marketing, Arabic Grammar</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="languages" data-aos="fade-up" data-aos-delay="100">
        <div class="container">
            <h2 class="section-title" data-aos="fade-down" data-aos-delay="200">Language Fluency</h2>
            <div class="language-list" data-aos="fade-up" data-aos-delay="300">
                <div class="language-item">
                    <h5>English</h5>
                    <p>Fluent</p>
                </div>
                <div class="language-item">
                    <h5>Arabic</h5>
                    <p>Advanced</p>
                </div>
                <div class="language-item">
                    <h5>Korean</h5>
                    <p>Intermediate</p>
                </div>
                <div class="language-item">
                    <h5>TAMIL</h5>
                    <p>NATIVE</p>
                </div>
                <div class="language-item">
                    <h5>SINHALA</h5>
                    <p>Fluent</p>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" data-aos="fade-up" data-aos-delay="100">
        <div class="container text-center">
            <h2 class="section-title" data-aos="fade-down" data-aos-delay="200">Contact Me</h2>
            <p>Email: mohamedmufas.muf@gmail.com</p>
            <p>Phone: +94 77 2005 974 / +94 75 2005 964</p>
            <p>Location: Colombo, Sri Lanka</p>
            <p>LinkedIn: <a href="https://www.linkedin.com/in/mohamed-mufas-muf2005/" class="text-warning" target="_blank">View Profile</a></p>
            <div class="mt-3">
                <a href="MY.mfs'%20Cv.pdf" class="btn btn-warning" download>Download My CV (PDF)</a>
            </div>
        </div>
    </section>

    <footer data-aos="fade-up" data-aos-delay="100">
        <div class="container">
            <p>&copy; 2025 M. Mohamed Mufas. All rights reserved.</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

    <script src="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.js"></script>

    <script src="script.js"></script>
</body>

</html>
