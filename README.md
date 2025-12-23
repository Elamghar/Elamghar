<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EL Houcine AMGHAR - GitHub Profile</title>
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
            min-height: 100vh;
        }
        
        .container {
            max-width: 900px;
            margin: 0 auto;
            background: white;
            border-radius: 15px;
            padding: 40px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
        }
        
        .header {
            text-align: center;
            margin-bottom: 40px;
        }
        
        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin: 0 auto 20px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 60px;
        }
        
        h1 {
            font-size: 2.5em;
            color: #333;
            margin-bottom: 10px;
        }
        
        .subtitle {
            color: #667eea;
            font-size: 1.1em;
            margin-bottom: 20px;
        }
        
        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin: 20px 0;
            flex-wrap: wrap;
        }
        
        .social-badge {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            padding: 8px 16px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            text-decoration: none;
            border-radius: 25px;
            transition: transform 0.3s;
            font-size: 0.9em;
        }
        
        .social-badge:hover {
            transform: translateY(-3px);
        }
        
        .section {
            margin-bottom: 35px;
        }
        
        .section-title {
            font-size: 1.5em;
            color: #333;
            margin-bottom: 15px;
            padding-bottom: 10px;
            border-bottom: 3px solid #667eea;
            display: inline-block;
        }
        
        .about-text {
            color: #555;
            line-height: 1.8;
            margin-bottom: 10px;
            font-size: 1em;
        }
        
        .tech-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        
        .tech-category {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 10px;
            border-left: 4px solid #667eea;
        }
        
        .tech-category h4 {
            color: #667eea;
            margin-bottom: 12px;
            font-size: 1.05em;
        }
        
        .tech-items {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
        }
        
        .tech-badge {
            background: white;
            color: #667eea;
            padding: 6px 12px;
            border-radius: 20px;
            border: 1px solid #667eea;
            font-size: 0.9em;
            font-weight: 500;
        }
        
        .experience-item {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 10px;
            margin-bottom: 15px;
            border-left: 4px solid #667eea;
        }
        
        .experience-title {
            color: #667eea;
            font-weight: bold;
            margin-bottom: 5px;
        }
        
        .experience-desc {
            color: #666;
            font-size: 0.95em;
            line-height: 1.6;
            margin-top: 8px;
        }
        
        .stats-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
            margin-top: 20px;
        }
        
        .stat-box {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 20px;
            border-radius: 10px;
            text-align: center;
        }
        
        .stat-number {
            font-size: 2em;
            font-weight: bold;
            margin-bottom: 5px;
        }
        
        .stat-label {
            font-size: 0.9em;
            opacity: 0.9;
        }

        .specialization {
            background: linear-gradient(135deg, #667eea15 0%, #764ba215 100%);
            border: 2px solid #667eea;
            padding: 20px;
            border-radius: 10px;
            margin: 20px 0;
        }

        .specialization h3 {
            color: #667eea;
            margin-bottom: 15px;
        }

        .specialization ul {
            list-style: none;
            color: #555;
        }

        .specialization li {
            padding: 8px 0;
            padding-left: 25px;
            position: relative;
        }

        .specialization li:before {
            content: "→";
            position: absolute;
            left: 0;
            color: #667eea;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header -->
        <div class="header">
            <div class="profile-img">👨‍💻</div>
            <h1>EL Houcine AMGHAR</h1>
            <p class="subtitle">AI & Data Engineer | 5th Year CS Student @ ENSA Marrakech</p>
            
            <div class="social-links">
                <a href="https://linkedin.com/in/el-houcine-amghar-87811a242" class="social-badge">
                    💼 LinkedIn
                </a>
                <a href="https://github.com/Elamghar" class="social-badge">
                    🐙 GitHub
                </a>
                <a href="mailto:elhoucineamghar9@gmail.com" class="social-badge">
                    📧 Email
                </a>
                <a href="tel:+212610111243" class="social-badge">
                    📱 +212 610 111243
                </a>
            </div>
        </div>

        <!-- About -->
        <div class="section">
            <h2 class="section-title">👨‍💻 About Me</h2>
            <p class="about-text">
                5th-year Computer Science student specializing in <strong>AI & Data Engineering</strong> at ENSA Marrakech. 
                Passionate about building scalable ML systems with hands-on experience in industrial AI applications at Stellantis. 
                Finalist at GITEX Africa 2025 competition.
            </p>
            <p class="about-text">
                <strong>Seeking internship opportunities</strong> to deepen expertise in ML Engineering, NLP, and Data Pipeline Architecture.
            </p>
        </div>

        <!-- Specialization -->
        <div class="specialization">
            <h3>🎯 AI & Data Engineer Specialization</h3>
            <ul>
                <li><strong>Machine Learning:</strong> YOLOv8, CNN, RNN, XGBoost, BERT, LLM Fine-tuning & Quantization</li>
                <li><strong>NLP & LLM:</strong> NER, RAG, spaCy, Darija Language Models, Document Processing</li>
                <li><strong>Data Pipeline:</strong> ETL Design, Data Collection & Preprocessing, Feature Engineering</li>
                <li><strong>Backend & APIs:</strong> FastAPI, Flask, Spring Boot, Microservices Architecture</li>
                <li><strong>Data Storage:</strong> PostgreSQL, MongoDB, Data Warehousing, Vector Databases</li>
                <li><strong>Cloud & DevOps:</strong> Docker, AWS (S3, EC2), CI/CD, GitHub</li>
            </ul>
        </div>

        <!-- Tech Stack -->
        <div class="section">
            <h2 class="section-title">🛠️ Languages & Tools</h2>
            
            <div class="tech-grid">
                <div class="tech-category">
                    <h4>🐍 Languages</h4>
                    <div class="tech-items">
                        <span class="tech-badge">Python</span>
                        <span class="tech-badge">SQL</span>
                        <span class="tech-badge">Java</span>
                        <span class="tech-badge">JavaScript</span>
                        <span class="tech-badge">TypeScript</span>
                    </div>
                </div>

                <div class="tech-category">
                    <h4>🤖 AI & ML</h4>
                    <div class="tech-items">
                        <span class="tech-badge">PyTorch</span>
                        <span class="tech-badge">YOLOv8</span>
                        <span class="tech-badge">XGBoost</span>
                        <span class="tech-badge">spaCy</span>
                        <span class="tech-badge">OpenCV</span>
                        <span class="tech-badge">scikit-learn</span>
                    </div>
                </div>

                <div class="tech-category">
                    <h4>📊 Data Processing</h4>
                    <div class="tech-items">
                        <span class="tech-badge">Pandas</span>
                        <span class="tech-badge">NumPy</span>
                        <span class="tech-badge">PySpark</span>
                        <span class="tech-badge">Kaggle</span>
                    </div>
                </div>

                <div class="tech-category">
                    <h4>🔧 Backend & API</h4>
                    <div class="tech-items">
                        <span class="tech-badge">FastAPI</span>
                        <span class="tech-badge">Flask</span>
                        <span class="tech-badge">Spring Boot</span>
                        <span class="tech-badge">Django</span>
                    </div>
                </div>

                <div class="tech-category">
                    <h4>💾 Databases</h4>
                    <div class="tech-items">
                        <span class="tech-badge">PostgreSQL</span>
                        <span class="tech-badge">MongoDB</span>
                        <span class="tech-badge">MySQL</span>
                    </div>
                </div>

                <div class="tech-category">
                    <h4>☁️ Cloud & DevOps</h4>
                    <div class="tech-items">
                        <span class="tech-badge">Docker</span>
                        <span class="tech-badge">AWS</span>
                        <span class="tech-badge">Git/GitHub</span>
                        <span class="tech-badge">CI/CD</span>
                    </div>
                </div>
            </div>
        </div>

        <!-- Experience -->
        <div class="section">
            <h2 class="section-title">💼 Professional Experience</h2>
            
            <div class="experience-item">
                <div class="experience-title">🏭 PFA Internship – AI Process Optimization @ Stellantis</div>
                <p class="about-text"><strong>Jul 2025 – Sep 2025</strong></p>
                <div class="experience-desc">
                    • Collected & processed industrial data for ML model training<br>
                    • Developed object detection & classification models (YOLOv8)<br>
                    • Built NLP-based ChatBot for technical document processing (RAG)<br>
                    • Tech: YOLOv8, PyTorch, OpenCV, Flask, XGBoost
                </div>
            </div>

            <div class="experience-item">
                <div class="experience-title">🌱 Internship – SDG Platform Development @ Cadi Ayyad University</div>
                <p class="about-text"><strong>Jul 2025 – Sep 2025</strong></p>
                <div class="experience-desc">
                    • Built web application for SDG tracking & monitoring<br>
                    • Designed & implemented ETL data pipeline<br>
                    • Tech: Django, PostgreSQL
                </div>
            </div>

            <div class="experience-item">
                <div class="experience-title">💻 IT Support & Full-Stack Development @ ORMVAH</div>
                <p class="about-text"><strong>Jul 2024 – Aug 2024</strong></p>
                <div class="experience-desc">
                    • Developed real-time chat web application
                </div>
            </div>
        </div>

        <!-- Key Projects -->
        <div class="section">
            <h2 class="section-title">🚀 Featured Projects</h2>
            
            <div class="experience-item">
                <div class="experience-title">SmartRoute – Route Optimization Platform</div>
                <div class="experience-desc">
                    Geospatial data collection & ML pipeline for route optimization<br>
                    <strong>Tech:</strong> Spring Boot, Angular, XGBoost, Flask, Python
                </div>
            </div>

            <div class="experience-item">
                <div class="experience-title">Billwise – AI-Powered Finance Assistant</div>
                <div class="experience-desc">
                    Microservices architecture with NER model for SMS bill parsing<br>
                    <strong>Tech:</strong> FastAPI, spaCy, PostgreSQL, MongoDB, Python
                </div>
            </div>

            <div class="experience-item">
                <div class="experience-title">HackIA 1337 – Darija Language Chatbot</div>
                <div class="experience-desc">
                    Conversational AI in Moroccan dialect using LLM fine-tuning & quantization<br>
                    <strong>Tech:</strong> LLM, Quantization, Fine-tuning, Python
                </div>
            </div>

            <div class="experience-item">
                <div class="experience-title">🏆 IA4SDG11 Competition – GITEX Africa 2025 (Finalist)</div>
                <div class="experience-desc">
                    Event detection system using BERT & NER for Twitter data analysis<br>
                    <strong>Tech:</strong> BERT, Twitter API, Python, NLP
                </div>
            </div>
        </div>

        <!-- Stats -->
        <div class="section">
            <h2 class="section-title">🔥 GitHub Activity</h2>
            <div class="stats-container">
                <div class="stat-box">
                    <div class="stat-number">5+</div>
                    <div class="stat-label">ML Projects</div>
                </div>
                <div class="stat-box">
                    <div class="stat-number">3+</div>
                    <div class="stat-label">Data Pipelines</div>
                </div>
                <div class="stat-box">
                    <div class="stat-number">2</div>
                    <div class="stat-label">Internships</div>
                </div>
                <div class="stat-box">
                    <div class="stat-number">1</div>
                    <div class="stat-label">Competition Finalist</div>
                </div>
            </div>
        </div>

        <!-- Education & Languages -->
        <div class="section">
            <h2 class="section-title">🎓 Education & Languages</h2>
            <p class="about-text">
                <strong>Degree:</strong> Engineering in Computer Science (In Progress 2021-2026)<br>
                <strong>Institution:</strong> ENSA Marrakech<br>
                <strong>Languages:</strong> Arabic (Native) • French (Fluent) • English (Fluent)
            </p>
        </div>
    </div>
</body>
</html>
