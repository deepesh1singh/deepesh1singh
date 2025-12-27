<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Deepesh Singh - Portfolio</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Inter:wght@300;400;600&display=swap');
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Inter', sans-serif;
            background: linear-gradient(135deg, #0a192f 0%, #172a45 100%);
            color: #cbd5e1;
            line-height: 1.6;
            overflow-x: hidden;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        /* Header Animation */
        .header-container {
            text-align: center;
            padding: 40px 20px;
            background: linear-gradient(180deg, rgba(10, 25, 47, 0.9) 0%, rgba(23, 42, 69, 0.7) 100%);
            border-radius: 20px;
            margin-bottom: 40px;
            position: relative;
            overflow: hidden;
        }
        
        .header-container::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(59, 130, 246, 0.1) 0%, transparent 70%);
            animation: pulse 8s infinite alternate;
        }
        
        @keyframes pulse {
            0% { transform: scale(1); opacity: 0.3; }
            100% { transform: scale(1.1); opacity: 0.5; }
        }
        
        .name {
            font-family: 'Orbitron', sans-serif;
            font-size: 3.5rem;
            font-weight: 700;
            background: linear-gradient(90deg, #ff6b35, #f7931e, #ffd23f, #06ffa5, #0693e3);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            margin-bottom: 10px;
            animation: slideIn 1s ease-out;
        }
        
        @keyframes slideIn {
            from { transform: translateY(-50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        
        .title {
            font-size: 1.8rem;
            color: #94a3b8;
            margin-bottom: 20px;
            animation: fadeIn 1.5s ease-out;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        
        .contact-info {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 20px;
        }
        
        .contact-item {
            display: flex;
            align-items: center;
            gap: 8px;
            padding: 10px 20px;
            background: rgba(30, 41, 59, 0.7);
            border-radius: 50px;
            transition: all 0.3s ease;
            animation: floatUp 0.8s ease-out;
            animation-fill-mode: both;
        }
        
        .contact-item:nth-child(1) { animation-delay: 0.2s; }
        .contact-item:nth-child(2) { animation-delay: 0.4s; }
        .contact-item:nth-child(3) { animation-delay: 0.6s; }
        .contact-item:nth-child(4) { animation-delay: 0.8s; }
        
        @keyframes floatUp {
            from { transform: translateY(30px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        
        .contact-item:hover {
            transform: translateY(-5px);
            background: rgba(59, 130, 246, 0.2);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
        }
        
        /* Section Styles */
        .section {
            background: rgba(15, 23, 42, 0.8);
            border-radius: 15px;
            padding: 30px;
            margin-bottom: 30px;
            border: 1px solid rgba(255, 255, 255, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            animation: fadeInUp 0.8s ease-out;
        }
        
        .section:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.4);
        }
        
        @keyframes fadeInUp {
            from { transform: translateY(30px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        
        .section-title {
            font-family: 'Orbitron', sans-serif;
            font-size: 2rem;
            color: #06ffa5;
            margin-bottom: 20px;
            position: relative;
            padding-bottom: 10px;
        }
        
        .section-title::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 100px;
            height: 3px;
            background: linear-gradient(90deg, #06ffa5, transparent);
        }
        
        /* Timeline Animation */
        .timeline-item {
            margin-bottom: 25px;
            padding-left: 20px;
            border-left: 3px solid #3b82f6;
            position: relative;
            animation: slideInRight 0.8s ease-out;
        }
        
        .timeline-item::before {
            content: '';
            position: absolute;
            left: -8px;
            top: 5px;
            width: 14px;
            height: 14px;
            border-radius: 50%;
            background: #3b82f6;
            box-shadow: 0 0 10px #3b82f6;
        }
        
        @keyframes slideInRight {
            from { transform: translateX(-30px); opacity: 0; }
            to { transform: translateX(0); opacity: 1; }
        }
        
        /* Skill Bars Animation */
        .skill-container {
            margin-bottom: 20px;
        }
        
        .skill-name {
            display: flex;
            justify-content: space-between;
            margin-bottom: 5px;
        }
        
        .skill-bar {
            height: 10px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 5px;
            overflow: hidden;
        }
        
        .skill-level {
            height: 100%;
            border-radius: 5px;
            background: linear-gradient(90deg, #ff6b35, #f7931e);
            transform: translateX(-100%);
            animation: fillBar 1.5s ease-out forwards;
        }
        
        @keyframes fillBar {
            to { transform: translateX(0); }
        }
        
        /* Project Cards Animation */
        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(350px, 1fr));
            gap: 25px;
            margin-top: 20px;
        }
        
        .project-card {
            background: rgba(30, 41, 59, 0.8);
            border-radius: 10px;
            padding: 25px;
            transition: all 0.3s ease;
            animation: fadeIn 0.8s ease-out;
            animation-fill-mode: both;
        }
        
        .project-card:nth-child(1) { animation-delay: 0.1s; }
        .project-card:nth-child(2) { animation-delay: 0.2s; }
        .project-card:nth-child(3) { animation-delay: 0.3s; }
        
        .project-card:hover {
            transform: translateY(-10px) scale(1.02);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.5);
        }
        
        .project-title {
            font-size: 1.5rem;
            color: #ffd23f;
            margin-bottom: 10px;
        }
        
        /* Badge Styles */
        .badge {
            display: inline-block;
            padding: 5px 12px;
            border-radius: 20px;
            font-size: 0.8rem;
            font-weight: 600;
            margin-right: 8px;
            margin-bottom: 8px;
            animation: popIn 0.5s ease-out;
        }
        
        @keyframes popIn {
            0% { transform: scale(0); }
            80% { transform: scale(1.1); }
            100% { transform: scale(1); }
        }
        
        .badge-blue { background: rgba(59, 130, 246, 0.2); color: #60a5fa; }
        .badge-green { background: rgba(34, 197, 94, 0.2); color: #4ade80; }
        .badge-purple { background: rgba(168, 85, 247, 0.2); color: #a855f7; }
        .badge-orange { background: rgba(249, 115, 22, 0.2); color: #fb923c; }
        
        /* Footer Animation */
        .footer {
            text-align: center;
            padding: 40px 20px;
            margin-top: 40px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            animation: fadeIn 2s ease-out;
        }
        
        .quote {
            font-style: italic;
            color: #94a3b8;
            margin-top: 20px;
            font-size: 1.2rem;
            animation: fadeIn 3s ease-out;
        }
        
        /* Typing Animation */
        .typing-container {
            margin: 20px 0;
        }
        
        .typing-text {
            font-family: 'Orbitron', sans-serif;
            font-size: 1.8rem;
            color: #ff6b35;
            overflow: hidden;
            white-space: nowrap;
            border-right: 3px solid #ff6b35;
            animation: typing 3.5s steps(40, end), blink-caret 0.75s step-end infinite;
        }
        
        @keyframes typing {
            from { width: 0; }
            to { width: 100%; }
        }
        
        @keyframes blink-caret {
            from, to { border-color: transparent; }
            50% { border-color: #ff6b35; }
        }
        
        /* Responsive Design */
        @media (max-width: 768px) {
            .name { font-size: 2.5rem; }
            .title { font-size: 1.4rem; }
            .contact-info { flex-direction: column; align-items: center; }
            .projects-grid { grid-template-columns: 1fr; }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header Section -->
        <div class="header-container">
            <h1 class="name">Deepesh Singh</h1>
            <div class="typing-container">
                <div class="typing-text">Software Engineer & IIT Kharagpur Student</div>
            </div>
            
            <div class="contact-info">
                <div class="contact-item">
                    <i class="fas fa-envelope"></i>
                    <span>deepesh002singh@gmail.com</span>
                </div>
                <div class="contact-item">
                    <i class="fas fa-phone"></i>
                    <span>+91-8382945057</span>
                </div>
                <div class="contact-item">
                    <i class="fab fa-github"></i>
                    <span>github.com/deepesh1singh</span>
                </div>
                <div class="contact-item">
                    <i class="fab fa-linkedin"></i>
                    <span>linkedin.com/in/deepesh-singh</span>
                </div>
            </div>
        </div>

        <!-- Professional Summary -->
        <div class="section">
            <h2 class="section-title">Professional Summary</h2>
            <p>Pursuing an integrated B.Tech and M.Tech in Computer Science and Engineering at IIT Kharagpur. Solid expertise in data structures and algorithms, web development, and applied machine learning, with a passion for tackling challenging problems.</p>
        </div>

        <!-- Education -->
        <div class="section">
            <h2 class="section-title">Education</h2>
            <div class="timeline-item">
                <h3>Indian Institute of Technology Kharagpur</h3>
                <p><strong>2022 - 2027</strong></p>
                <p>Bachelor and Master in Computer Science and Engineering</p>
                <p>CGPA: 5.99/10</p>
            </div>
            <div class="timeline-item">
                <h3>Jawahar Navodaya Vidyalaya, Lucknow</h3>
                <p><strong>2021</strong></p>
                <p>Class XII, CBSE - Score: 84.2%</p>
            </div>
        </div>

        <!-- Work Experience & Projects -->
        <div class="section">
            <h2 class="section-title">Work Experience & Projects</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <h3 class="project-title">Machine Learning-Based Differential Cryptanalysis of ASCON Permutation</h3>
                    <p><strong>May 2025</strong></p>
                    <ul>
                        <li>Developed ML-based differential distinguishers for ASCON permutation using CNN, LSTM, and LightGBM</li>
                        <li>Generated 100,000 data samples with equal split between random and real data</li>
                        <li>Achieved 100%, 100%, and 94.52% test accuracy for rounds 1–3</li>
                    </ul>
                    <div class="skill-container">
                        <span class="badge badge-blue">Python</span>
                        <span class="badge badge-green">TensorFlow</span>
                        <span class="badge badge-purple">PyTorch</span>
                        <span class="badge badge-orange">Machine Learning</span>
                    </div>
                </div>

                <div class="project-card">
                    <h3 class="project-title">BankBrain – Cloud-Ready Microservices Banking Backend</h3>
                    <p><strong>March 2025</strong></p>
                    <ul>
                        <li>Designed modular microservices architecture using Python and FastAPI</li>
                        <li>Implemented MCP-driven multi-agent system</li>
                        <li>Developed in-memory end-to-end smoke testing framework</li>
                    </ul>
                    <div class="skill-container">
                        <span class="badge badge-blue">Python</span>
                        <span class="badge badge-green">FastAPI</span>
                        <span class="badge badge-purple">Docker</span>
                        <span class="badge badge-orange">Kubernetes</span>
                    </div>
                </div>

                <div class="project-card">
                    <h3 class="project-title">Multimedia Database System</h3>
                    <p><strong>April 2025</strong></p>
                    <ul>
                        <li>Developed full-stack application with Node.js, Express.js, and SQLite</li>
                        <li>Implemented strong security features including JWT and bcrypt</li>
                        <li>Built system supporting multi-format media with real-time communication</li>
                    </ul>
                    <div class="skill-container">
                        <span class="badge badge-blue">Node.js</span>
                        <span class="badge badge-green">Express.js</span>
                        <span class="badge badge-purple">SQLite</span>
                        <span class="badge badge-orange">Socket.IO</span>
                    </div>
                </div>
            </div>
        </div>

        <!-- Skills -->
        <div class="section">
            <h2 class="section-title">Technical Skills</h2>
            <div class="skill-container">
                <div class="skill-name">
                    <span>Programming Languages</span>
                </div>
                <p>C, C++, Python, SQL, HTML/CSS, Verilog, Assembly</p>
            </div>
            
            <div class="skill-container">
                <div class="skill-name">
                    <span>Frameworks & Libraries</span>
                </div>
                <p>Pandas, NumPy, Matplotlib, PyTorch, Tkinter, C++ STL</p>
            </div>
            
            <div class="skill-container">
                <div class="skill-name">
                    <span>Databases & Tools</span>
                </div>
                <p>SQLite, PostgreSQL, Git, GitHub, VS Code, Docker, MongoDB, Kubernetes</p>
            </div>
            
            <div class="skill-container">
                <div class="skill-name">
                    <span>Core Competencies</span>
                </div>
                <p>Data Structures & Algorithms, Web Development, Object-Oriented Design</p>
            </div>
        </div>

        <!-- Awards & Certifications -->
        <div class="section">
            <h2 class="section-title">Awards & Certifications</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <h3 class="project-title">Academic Excellence</h3>
                    <ul>
                        <li>All India Category Rank 16 in JEE Advanced</li>
                        <li>Expert rating (1654) on Codeforces</li>
                        <li>Ranked 27th out of 27,876 in Codeforces Round 1043</li>
                        <li>Recipient of FFE Scholarship (2022–2027)</li>
                    </ul>
                </div>
                
                <div class="project-card">
                    <h3 class="project-title">Certifications</h3>
                    <ul>
                        <li>AWS Certified: Machine Learning Foundations</li>
                        <li>NTSE Scholar – National Talent Search Examination</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- Coursework -->
        <div class="section">
            <h2 class="section-title">Relevant Coursework</h2>
            <div class="skill-container">
                <p>Programming and Data Structures, Algorithms, Systems Programming, Computer Networks, Database Management Systems, Operating Systems, Machine Learning, Artificial Intelligence, Scalable Data Mining, Probability and Statistics</p>
            </div>
        </div>

        <!-- Footer -->
        <div class="footer">
            <div class="contact-info">
                <div class="contact-item">
                    <i class="fab fa-github"></i>
                    <a href="https://github.com/deepesh1singh" style="color: inherit; text-decoration: none;">GitHub Portfolio</a>
                </div>
                <div class="contact-item">
                    <i class="fas fa-globe"></i>
                    <a href="https://deepesh1singh.github.io/Deepesh-Portfolio/" style="color: inherit; text-decoration: none;">Personal Website</a>
                </div>
            </div>
            
            <p class="quote">"Code is poetry written in logic, and every bug is a haiku waiting to be debugged."</p>
            
            <p style="margin-top: 30px; color: #64748b;">© 2024 Deepesh Singh. All animations created with pure CSS.</p>
        </div>
    </div>

    <script>
        // Add scroll animations
        document.addEventListener('DOMContentLoaded', function() {
            const sections = document.querySelectorAll('.section');
            
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.style.animationPlayState = 'running';
                    }
                });
            }, { threshold: 0.1 });
            
            sections.forEach(section => {
                observer.observe(section);
            });
            
            // Skill bar animations on scroll
            const skillBars = document.querySelectorAll('.skill-level');
            const skillObserver = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.style.animationPlayState = 'running';
                    }
                });
            }, { threshold: 0.5 });
            
            skillBars.forEach(bar => {
                skillObserver.observe(bar);
            });
            
            // Typewriter effect for multiple lines
            const typewriterTexts = [
                "Software Engineer & IIT Kharagpur Student",
                "Machine Learning Enthusiast",
                "Full Stack Developer",
                "Problem Solver"
            ];
            
            let currentTextIndex = 0;
            const typingElement = document.querySelector('.typing-text');
            
            function typeWriter(text, i, callback) {
                if (i < text.length) {
                    typingElement.innerHTML = text.substring(0, i + 1);
                    setTimeout(() => typeWriter(text, i + 1, callback), 100);
                } else if (callback) {
                    setTimeout(callback, 1500);
                }
            }
            
            function startTypingAnimation() {
                typeWriter(typewriterTexts[currentTextIndex], 0, () => {
                    currentTextIndex = (currentTextIndex + 1) % typewriterTexts.length;
                    setTimeout(startTypingAnimation, 500);
                });
            }
            
            // Start the typing animation after initial load
            setTimeout(startTypingAnimation, 2000);
        });
    </script>
</body>
</html>
