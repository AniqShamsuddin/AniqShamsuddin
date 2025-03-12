<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aniq Shamsuddin | Cybersecurity Professional</title>
    <style>
        :root {
            --primary: #2a2f4f;
            --secondary: #917fb3;
            --accent: #fde68a;
            --background: #f8fafc;
            --text: #1e293b;
            --card-bg: #ffffff;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        }
        
        body {
            background-color: var(--background);
            color: var(--text);
            line-height: 1.6;
            padding: 0;
            margin: 0;
            min-height: 100vh;
        }
        
        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 2rem;
        }
        
        header {
            background-color: var(--primary);
            color: white;
            padding: 3rem 0;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        
        header::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(to right, var(--primary), var(--secondary));
            opacity: 0.8;
            z-index: 0;
        }
        
        .header-content {
            position: relative;
            z-index: 1;
        }
        
        .profile-pic {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 4px solid var(--accent);
            margin-bottom: 1.5rem;
            object-fit: cover;
            background-color: #ddd;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 1.5rem;
        }
        
        .profile-pic-text {
            font-size: 3rem;
            color: var(--primary);
        }
        
        h1 {
            font-size: 2.8rem;
            margin-bottom: 0.5rem;
        }
        
        .tagline {
            font-size: 1.2rem;
            opacity: 0.9;
            margin-bottom: 1.5rem;
        }
        
        section {
            margin: 2.5rem 0;
            padding: 1.5rem;
            background-color: var(--card-bg);
            border-radius: 12px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s, box-shadow 0.3s;
        }
        
        section:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.1);
        }
        
        h2 {
            color: var(--primary);
            font-size: 1.5rem;
            margin-bottom: 1rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        
        .project-card, .cert-card {
            padding: 1rem;
            border-radius: 8px;
            margin-bottom: 1rem;
            background-color: rgba(145, 127, 179, 0.1);
            border-left: 4px solid var(--secondary);
        }
        
        .project-title, .cert-title {
            font-weight: 600;
            font-size: 1.1rem;
            margin-bottom: 0.5rem;
        }
        
        .project-desc, .cert-desc {
            color: #555;
            font-size: 0.95rem;
        }
        
        .social-links {
            display: flex;
            gap: 1rem;
            justify-content: center;
            margin-top: 1rem;
        }
        
        .social-links a {
            display: flex;
            align-items: center;
            gap: 0.5rem;
            text-decoration: none;
            color: white;
            background-color: var(--secondary);
            padding: 0.6rem 1.2rem;
            border-radius: 50px;
            font-weight: 500;
            transition: background-color 0.3s;
        }
        
        .social-links a:hover {
            background-color: var(--primary);
        }
        
        .social-icon {
            width: 20px;
            height: 20px;
        }
        
        footer {
            text-align: center;
            padding: 1.5rem;
            background-color: var(--primary);
            color: white;
            margin-top: 3rem;
        }
        
        .skills-container {
            display: flex;
            flex-wrap: wrap;
            gap: 0.5rem;
            margin-top: 1rem;
        }
        
        .skill-tag {
            background-color: var(--accent);
            color: var(--primary);
            padding: 0.4rem 0.8rem;
            border-radius: 50px;
            font-size: 0.85rem;
            font-weight: 500;
        }
        
        @media (max-width: 768px) {
            .container {
                padding: 1rem;
            }
            
            header {
                padding: 2rem 0;
            }
            
            h1 {
                font-size: 2.2rem;
            }
            
            section {
                padding: 1rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="header-content">
            <div class="profile-pic">
                <span class="profile-pic-text">A</span>
            </div>
            <h1>Aniq Shamsuddin</h1>
            <p class="tagline">Cybersecurity Professional | Ethical Hacker | Security Enthusiast</p>
            <div class="social-links">
                <a href="https://www.linkedin.com/in/aniqshamsuddin" target="_blank">
                    <svg class="social-icon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                        <path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"></path>
                        <rect x="2" y="9" width="4" height="12"></rect>
                        <circle cx="4" cy="4" r="2"></circle>
                    </svg>
                    LinkedIn
                </a>
                <a href="mailto:contact@aniqshamsuddin.com">
                    <svg class="social-icon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                        <path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"></path>
                        <polyline points="22,6 12,13 2,6"></polyline>
                    </svg>
                    Email
                </a>
            </div>
        </div>
    </header>
    
    <div class="container">
        <section>
            <h2>
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                    <path d="M20 7h-9"></path>
                    <path d="M14 17H5"></path>
                    <circle cx="17" cy="17" r="3"></circle>
                    <circle cx="7" cy="7" r="3"></circle>
                </svg>
                About Me
            </h2>
            <p>
                I'm a passionate cybersecurity professional dedicated to protecting digital assets and infrastructure. 
                With expertise in vulnerability assessment and penetration testing, I help organizations strengthen 
                their security posture against evolving threats.
            </p>
            <div class="skills-container">
                <span class="skill-tag">Network Security</span>
                <span class="skill-tag">Penetration Testing</span>
                <span class="skill-tag">Vulnerability Assessment</span>
                <span class="skill-tag">Security Compliance</span>
                <span class="skill-tag">Threat Hunting</span>
            </div>
        </section>
        
        <section>
            <h2>
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                    <path d="M12 12m-3 0a3 3 0 1 0 6 0a3 3 0 1 0 -6 0"></path>
                    <path d="M2 12c0 -3.5 2.5 -6 6 -6c3.5 0 6 2.5 6 6"></path>
                    <path d="M14 12c0 -3.5 2.5 -6 6 -6c3.5 0 6 2.5 6 6"></path>
                </svg>
                Cybersecurity Projects
            </h2>
            
            <div class="project-card">
                <div class="project-title">Vulnerability Scanner</div>
                <div class="project-desc">
                    Developed a custom vulnerability scanner to identify security weaknesses in network infrastructure. The tool automates the detection of common vulnerabilities and provides detailed remediation steps.
                </div>
            </div>
            
            <div class="project-card">
                <div class="project-title">Security Monitoring Dashboard</div>
                <div class="project-desc">
                    Created a real-time security monitoring dashboard that aggregates alerts from multiple sources and visualizes potential threats for faster incident response.
                </div>
            </div>
        </section>
        
        <section>
            <h2>
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                    <path d="M4 7a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2h-12a2 2 0 0 1 -2 -2v-12z"></path>
                    <path d="M16 3v4"></path>
                    <path d="M8 3v4"></path>
                    <path d="M4 11h16"></path>
                    <path d="M11 15h1"></path>
                    <path d="M12 15v3"></path>
                </svg>
                Certifications
            </h2>
            
            <div class="cert-card">
                <div class="cert-title">Google Cybersecurity Professional Certificate</div>
                <div class="cert-desc">
                    Comprehensive training in cybersecurity fundamentals, including network security, system architecture, and incident response.
                </div>
            </div>
            
        </section>
        
        <section>
            <h2>
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                    <path d="M3 12h1m8 -9v1m8 8h1m-15.4 -6.4l.7 .7m12.1 -.7l-.7 .7"></path>
                    <path d="M9 16a5 5 0 1 1 6 0a3.5 3.5 0 0 0 -1 3a2 2 0 0 1 -4 0a3.5 3.5 0 0 0 -1 -3"></path>
                    <path d="M9.7 17l4.6 0"></path>
                </svg>
                Currently Learning
            </h2>
            
            <div class="cert-card">
                <div class="cert-title">CompTIA Security+ Certification</div>
                <div class="cert-desc">
                    Preparing for this industry-standard certification to validate my expertise in network security, compliance and operational security, threats and vulnerabilities, and more.
                </div>
            </div>
        </section>
    </div>
    
    <footer>
        <p>&copy; 2025 Aniq Shamsuddin. All rights reserved.</p>
    </footer>
</body>
</html>
