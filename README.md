<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Data Scientist Portfolio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #fff;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
        }

        header {
            text-align: center;
            padding: 60px 0 40px;
            border-bottom: 1px solid #e0e0e0;
        }

        .site-title {
            font-size: 2.5em;
            font-weight: 300;
            margin-bottom: 10px;
            color: #2c3e50;
        }

        .site-title a {
            color: inherit;
            text-decoration: none;
        }

        .subtitle {
            font-size: 1.2em;
            color: #7f8c8d;
            margin-bottom: 20px;
        }

        nav {
            margin-top: 30px;
        }

        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 30px;
            flex-wrap: wrap;
        }

        nav a {
            color: #3498db;
            text-decoration: none;
            font-size: 1em;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #2980b9;
        }

        .hero {
            display: flex;
            align-items: center;
            gap: 50px;
            margin: 60px 0;
            flex-wrap: wrap;
        }

        .hero-text {
            flex: 1;
            min-width: 300px;
        }

        .hero-image {
            flex: 0 0 250px;
        }

        .hero-image img {
            width: 100%;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        .greeting {
            font-size: 1.3em;
            margin-bottom: 30px;
            color: #34495e;
        }

        .contact-info {
            margin-top: 20px;
        }

        .contact-info a {
            color: #3498db;
            text-decoration: none;
            margin-right: 20px;
        }

        section {
            margin: 60px 0;
        }

        h1 {
            font-size: 2em;
            font-weight: 400;
            margin-bottom: 30px;
            color: #2c3e50;
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
        }

        h2 {
            font-size: 1.5em;
            font-weight: 400;
            margin: 30px 0 15px;
            color: #34495e;
        }

        h3 {
            font-size: 1.2em;
            font-weight: 400;
            margin: 20px 0 10px;
            color: #34495e;
        }

        p {
            margin-bottom: 15px;
            text-align: justify;
        }

        .highlight-box {
            background: #f8f9fa;
            border-left: 4px solid #3498db;
            padding: 20px;
            margin: 20px 0;
            border-radius: 5px;
        }

        .project-card {
            background: #fff;
            border: 1px solid #e0e0e0;
            padding: 25px;
            margin: 30px 0;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
            transition: box-shadow 0.3s;
        }

        .project-card:hover {
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }

        .project-title {
            font-size: 1.3em;
            color: #2c3e50;
            margin-bottom: 10px;
        }

        .project-link {
            display: inline-block;
            margin-top: 15px;
            color: #3498db;
            text-decoration: none;
            font-weight: 500;
        }

        .project-link:hover {
            text-decoration: underline;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .skill-category {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 8px;
        }

        .skill-category h3 {
            color: #3498db;
            margin-bottom: 15px;
        }

        .skill-category ul {
            list-style: none;
        }

        .skill-category li {
            padding: 5px 0;
            color: #555;
        }

        .metric {
            font-weight: 600;
            color: #27ae60;
        }

        footer {
            text-align: center;
            padding: 40px 0;
            border-top: 1px solid #e0e0e0;
            margin-top: 60px;
            color: #7f8c8d;
            font-size: 0.9em;
        }

        @media (max-width: 768px) {
            .hero {
                flex-direction: column-reverse;
            }

            .hero-image {
                flex: 0 0 200px;
            }

            nav ul {
                gap: 15px;
            }

            .site-title {
                font-size: 2em;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1 class="site-title"><a href="#">Your Name</a></h1>
            <p class="subtitle">Data Scientist | Machine Learning Engineer</p>
            <nav>
                <ul>
                    <li><a href="#about">About</a></li>
                    <li><a href="#experience">Experience</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </header>

        <section class="hero">
            <div class="hero-text">
                <p class="greeting">Hi, welcome to my portfolio! 👋</p>
                <p>I am a data scientist with expertise in machine learning, NLP, and predictive analytics. I have a proven track record of driving business outcomes through data-driven solutions that optimize decision-making and create sustainable growth.</p>
                <div class="contact-info">
                    <a href="mailto:your.email@example.com">📧 Email</a>
                    <a href="https://linkedin.com/in/yourprofile" target="_blank">💼 LinkedIn</a>
                    <a href="https://github.com/yourusername" target="_blank">💻 GitHub</a>
                </div>
            </div>
            <div class="hero-image">
                <img src="https://via.placeholder.com/250x300/3498db/ffffff?text=Your+Photo" alt="Your Name">
            </div>
        </section>

        <section id="about">
            <h1>About My Work</h1>
            <p>My work focuses on leveraging advanced machine learning techniques to solve real-world business challenges. I specialize in building predictive models, natural language processing applications, and scalable data solutions that drive measurable impact.</p>
            
            <p>I believe in the power of data to transform businesses and improve decision-making processes. My approach combines technical rigor with business acumen to deliver solutions that are not only technically sound but also aligned with organizational goals.</p>
        </section>

        <section id="experience">
            <h1>Key Achievements</h1>
            
            <div class="highlight-box">
                <h2>🌟 Driving Revenue Growth</h2>
                <p>Reactivated over <span class="metric">20,000 corporate accounts</span> through advanced churn mitigation models, resulting in a <span class="metric">NGN 2.29 trillion increase</span> in customer deposits and driving sustainable business growth.</p>
            </div>

            <div class="highlight-box">
                <h2>🌟 Expanding Market Reach</h2>
                <p>Developed a segmentation model targeting female SMEs, achieving a <span class="metric">1,428% growth in loans</span> and a <span class="metric">NGN 1 trillion loan growth</span>, contributing to 61% of total interest income.</p>
            </div>

            <div class="highlight-box">
                <h2>🌟 Delivering Scalable Solutions</h2>
                <p>Designed and deployed an AI chatbot, reducing turnaround time for <span class="metric">2,000+ staff</span> and cutting operational expenses while improving internal efficiency and <span class="metric">customer satisfaction scores by 48%</span>.</p>
            </div>
        </section>

        <section id="projects">
            <h1>Selected Projects</h1>

            <div class="project-card">
                <h2 class="project-title">Natural Language Processing: End-to-End Sentiment Analysis</h2>
                <p>Built a comprehensive sentiment analysis solution using Flask to create a web API for real-time sentiment prediction and bulk analysis through CSV file uploads. This solution provides actionable insights into customer sentiment, enabling businesses to better understand customer feedback and improve their strategies.</p>
                <p><strong>Key Technologies:</strong> Python, Flask, XGBoost, SHAP, NLTK, Pandas, Matplotlib, HTML/CSS</p>
                <p><strong>Impact:</strong> Enabled real-time processing of customer feedback with 92% accuracy, providing immediate actionable insights for business decision-making.</p>
                <a href="#" class="project-link">View Project →</a>
            </div>

            <div class="project-card">
                <h2 class="project-title">Customer Churn Prediction & Analysis</h2>
                <p>Developed a comprehensive churn prediction system combining SQL analytics with machine learning models. Used advanced SQL techniques to extract insights from multi-year customer data, then trained and deployed the most efficient model based on rigorous evaluation criteria.</p>
                <p><strong>Key Technologies:</strong> Python, SQL (MySQL, PostgreSQL), Scikit-learn, Deep Learning (Keras, TensorFlow)</p>
                <p><strong>Impact:</strong> Identified at-risk customers with 85% precision, enabling proactive retention strategies that reduced churn by 23%.</p>
                <a href="#" class="project-link">View Project →</a>
            </div>

            <div class="project-card">
                <h2 class="project-title">Interactive Data Mining Dashboard</h2>
                <p>Analyzed customer behavior patterns and built predictive models using R. Deployed an interactive interface using Shiny on GitHub, allowing stakeholders to explore data insights and model predictions in real-time.</p>
                <p><strong>Key Technologies:</strong> R, Shiny, ggplot2, caret, dplyr</p>
                <p><strong>Impact:</strong> Democratized data access across teams, reducing report generation time by 70% and improving data-driven decision-making.</p>
                <a href="#" class="project-link">View Project →</a>
            </div>

            <div class="project-card">
                <h2 class="project-title">[Add Your Advanced Project Here]</h2>
                <p>Describe your advanced project here. What problem did you solve? What technologies did you use? What was the impact?</p>
                <p><strong>Key Technologies:</strong> List your tech stack</p>
                <p><strong>Impact:</strong> Describe the measurable outcomes</p>
                <a href="#" class="project-link">View Project →</a>
            </div>
        </section>

        <section id="skills">
            <h1>Technical Skills</h1>
            
            <div class="skills-grid">
                <div class="skill-category">
                    <h3>Programming & Tools</h3>
                    <ul>
                        <li>Python (3+ years)</li>
                        <li>SQL</li>
                        <li>R</li>
                        <li>Flask</li>
                        <li>Git</li>
                    </ul>
                </div>

                <div class="skill-category">
                    <h3>Data Platforms</h3>
                    <ul>
                        <li>Google BigQuery</li>
                        <li>Azure Synapse</li>
                        <li>MS SQL Server</li>
                        <li>MySQL</li>
                        <li>PostgreSQL</li>
                    </ul>
                </div>

                <div class="skill-category">
                    <h3>Analytics & Reporting</h3>
                    <ul>
                        <li>Power BI</li>
                        <li>Tableau</li>
                        <li>MS Excel</li>
                        <li>Microsoft 365</li>
                        <li>Power Apps</li>
                    </ul>
                </div>

                <div class="skill-category">
                    <h3>Machine Learning</h3>
                    <ul>
                        <li>Scikit-learn</li>
                        <li>TensorFlow & Keras</li>
                        <li>PyTorch</li>
                        <li>Azure ML</li>
                        <li>LLMs</li>
                    </ul>
                </div>

                <div class="skill-category">
                    <h3>Specializations</h3>
                    <ul>
                        <li>Natural Language Processing</li>
                        <li>Predictive Analytics</li>
                        <li>Data Wrangling</li>
                        <li>Model Deployment</li>
                        <li>Basic MLOps</li>
                    </ul>
                </div>
            </div>
        </section>

        <section id="contact">
            <h1>Let's Connect</h1>
            <p>I'm always interested in discussing new opportunities, collaborations, or just connecting with fellow data enthusiasts. Feel free to reach out!</p>
            
            <div class="highlight-box">
                <p><strong>📧 Email:</strong> <a href="mailto:your.email@example.com">your.email@example.com</a></p>
                <p><strong>📍 Location:</strong> Your City, Country</p>
                <p><strong>🌐 LinkedIn:</strong> <a href="https://linkedin.com/in/yourprofile" target="_blank">linkedin.com/in/yourprofile</a></p>
                <p><strong>💻 GitHub:</strong> <a href="https://github.com/yourusername" target="_blank">github.com/yourusername</a></p>
            </div>
        </section>

        <footer>
            <p>&copy; 2024 Your Name. All rights reserved.</p>
            <p>Inspired by excellent portfolio designs in the data science community</p>
        </footer>
    </div>
</body>
</html>
