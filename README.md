<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mobeen Rehman - Resume</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            padding: 40px 20px;
            line-height: 1.6;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            background: white;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
            border-radius: 10px;
            overflow: hidden;
        }

        .header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 50px 40px;
            text-align: center;
        }

        .header h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            letter-spacing: 2px;
            text-transform: uppercase;
        }

        .contact-info {
            font-size: 1.1em;
            margin-top: 15px;
        }

        .contact-info a {
            color: white;
            text-decoration: none;
            border-bottom: 2px solid rgba(255, 255, 255, 0.5);
            transition: border-color 0.3s;
        }

        .contact-info a:hover {
            border-bottom: 2px solid white;
        }

        .content {
            padding: 40px 50px;
        }

        .section {
            margin-bottom: 35px;
        }

        .section-title {
            font-size: 1.6em;
            color: #667eea;
            margin-bottom: 15px;
            padding-bottom: 10px;
            border-bottom: 3px solid #667eea;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .objective-text {
            color: #555;
            font-size: 1.05em;
            line-height: 1.8;
            text-align: justify;
        }

        .education-item, .experience-item {
            margin-bottom: 20px;
        }

        .job-title {
            font-size: 1.2em;
            font-weight: bold;
            color: #333;
        }

        .company {
            color: #667eea;
            font-weight: 600;
        }

        .date {
            color: #888;
            font-style: italic;
            font-size: 0.95em;
        }

        .description-list {
            margin-top: 10px;
            margin-left: 20px;
        }

        .description-list li {
            margin-bottom: 8px;
            color: #555;
            line-height: 1.7;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
            margin-top: 15px;
        }

        .skill-category {
            background: #f8f9fa;
            padding: 15px;
            border-radius: 8px;
            border-left: 4px solid #667eea;
        }

        .skill-category strong {
            color: #667eea;
            display: block;
            margin-bottom: 5px;
        }

        .qualifications-list {
            margin-top: 15px;
        }

        .qualification-item {
            margin-bottom: 15px;
            padding-left: 25px;
            position: relative;
        }

        .qualification-item:before {
            content: "▸";
            position: absolute;
            left: 0;
            color: #667eea;
            font-size: 1.3em;
        }

        .qualification-item strong {
            color: #667eea;
        }

        .projects-list li {
            margin-bottom: 10px;
            padding-left: 25px;
            position: relative;
            color: #555;
            line-height: 1.7;
        }

        .projects-list li:before {
            content: "●";
            position: absolute;
            left: 0;
            color: #667eea;
            font-size: 1.2em;
        }

        .why-section {
            background: linear-gradient(135deg, rgba(102, 126, 234, 0.1) 0%, rgba(118, 75, 162, 0.1) 100%);
            padding: 25px;
            border-radius: 8px;
            margin-top: 15px;
            border-left: 5px solid #667eea;
        }

        .why-section p {
            color: #555;
            line-height: 1.8;
            text-align: justify;
        }

        .footer {
            text-align: center;
            padding: 20px;
            background: #f8f9fa;
            color: #888;
            font-style: italic;
        }

        @media print {
            body {
                background: white;
                padding: 0;
            }
            .container {
                box-shadow: none;
                max-width: 100%;
            }
        }

        @media (max-width: 768px) {
            .header h1 {
                font-size: 1.8em;
            }
            .content {
                padding: 30px 25px;
            }
            .skills-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Mobeen Rehman</h1>
            <div class="contact-info">
                <a href="mailto:rehmanmobeen0@gmail.com">rehmanmobeen0@gmail.com</a> | 
                <a href="https://www.linkedin.com/in/mobeen-rehman-b34911327/">LinkedIn Profile</a>
            </div>
        </div>

        <div class="content">
            <div class="section">
                <h2 class="section-title">Objective</h2>
                <p class="objective-text">
                    Motivated Software Engineering student with hands-on experience in AI/ML and deep learning, seeking an AI Research Assistant Internship at DeepTutor. Passionate about leveraging AI tools to transform research reading and learning experiences.
                </p>
            </div>

            <div class="section">
                <h2 class="section-title">Education</h2>
                <div class="education-item">
                    <div class="job-title">Bachelor of Science in Software Engineering</div>
                    <div class="date">[Virtual University of Pakistan] | Expected Graduation: [2024-2028]</div>
                </div>
            </div>

            <div class="section">
                <h2 class="section-title">Professional Experience</h2>
                <div class="experience-item">
                    <div class="job-title">AI/ML Intern | <span class="company">Cosmic365.ai</span></div>
                    <div class="date">[March 2025] – [June 2025] (3 months)</div>
                    <ul class="description-list">
                        <li>Gained hands-on experience with deep learning and machine learning frameworks in a global AI-focused company</li>
                        <li>Developed Python-based solutions for AI-driven applications, improving proficiency in data processing and model implementation</li>
                        <li>Collaborated with remote teams across multiple time zones, demonstrating strong asynchronous communication and autonomous work capabilities</li>
                        <li>Applied ML algorithms to real-world business challenges, contributing to product development initiatives</li>
                    </ul>
                </div>
            </div>

            <div class="section">
                <h2 class="section-title">Technical Skills</h2>
                <div class="skills-grid">
                    <div class="skill-category">
                        <strong>Programming Languages</strong>
                        Python (Basics)
                    </div>
                    <div class="skill-category">
                        <strong>AI/ML Technologies</strong>
                        Deep Learning, Machine Learning, Neural Networks
                    </div>
                    <div class="skill-category">
                        <strong>Tools & Frameworks</strong>
                        TensorFlow/PyTorch (Basic), Jupyter Notebooks, Git
                    </div>
                    <div class="skill-category">
                        <strong>Soft Skills</strong>
                        Research & Analysis, Technical Reading, Critical Thinking
                    </div>
                </div>
            </div>

            <div class="section">
                <h2 class="section-title">Relevant Qualifications for DeepTutor</h2>
                <div class="qualifications-list">
                    <div class="qualification-item">
                        <strong>Research-Oriented Mindset:</strong> Strong interest in exploring complex materials and academic papers, with proven ability to learn and synthesize technical information independently
                    </div>
                    <div class="qualification-item">
                        <strong>AI Tool Proficiency:</strong> Extensive experience working with AI-native tools and frameworks during internship at Cosmic365.ai
                    </div>
                    <div class="qualification-item">
                        <strong>Structured Feedback:</strong> Demonstrated ability to evaluate AI systems and provide actionable insights for improvement
                    </div>
                    <div class="qualification-item">
                        <strong>Collaborative Approach:</strong> Experience working in distributed teams with asynchronous communication
                    </div>
                    <div class="qualification-item">
                        <strong>Time Commitment:</strong> Available 10–20+ hours per week for hands-on experimentation and testing
                    </div>
                    <div class="qualification-item">
                        <strong>Language Proficiency:</strong> Fluent in English with strong written and verbal communication skills
                    </div>
                </div>
            </div>

            <div class="section">
                <h2 class="section-title">Projects & Interests</h2>
                <ul class="projects-list">
                    <li>Actively exploring AI-driven reading comprehension and natural language processing applications</li>
                    <li>Passionate about understanding how AI can enhance learning workflows and research productivity</li>
                    <li>Eager to contribute to early-stage products that democratize access to advanced research tools</li>
                </ul>
            </div>

            <div class="section">
                <h2 class="section-title">Why DeepTutor?</h2>
                <div class="why-section">
                    <p>
                        I'm excited about DeepTutor's mission to make research reading more interactive and insightful. My background in AI/ML combined with my passion for autonomous learning aligns perfectly with your goal of building AI-native tools for "vibe researching." I'm eager to test, refine, and help shape DeepTutor while gaining exposure to cutting-edge AI-driven research workflows.
                    </p>
                </div>
            </div>
        </div>

        <div class="footer">
            &copy; 2025 MOBEEN REHMAN | ALL RIGHTS RESERVED 
        </div>
    </div>
</body>
</html>
