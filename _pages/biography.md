---
permalink: /
redirect_from: 
  - /biography/
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biography</title>
    <style>
        /* General Body Style */
        body {
            font-family: 'Georgia', serif;
            background-color: #f0f7fa;
            margin: 0;
            padding: 0;
            color: #333;
        }

        /* Main content container */
        .content {
            width: 128%;
            margin: 0;
            padding: 10px;
            padding-bottom: 20px; /* Added padding at the bottom */
            background-color: #ffffff;
            border-radius: 10px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        }

        .content h2 {
            font-size: 28px;
            color: #1e3d8f;
            font-weight: bold;
            margin-bottom: 20px;
            position: relative;
        }

        .content h2::after {
            content: '';
            display: block;
            width: 100%;
            height: 1px;
            background-color: #cccccc;
            margin-top: 10px;
        }

        .content p {
            font-size: 18px;
            line-height: 1.8;
            color: #333;
            margin-bottom: 20px;
            text-align: justify;
        }

        .content a {
            color: #1e3d8f;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        .content a:hover {
            color: #003399;
        }

        /* Style for Biography and Interests (Unchanged) */
        .certification-layout {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(400px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .certification-card {
            padding: 10px;
            background-color: #f9f9f9;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            font-family: 'Georgia', serif;
        }

        .certification-card h5,
        .certification-card p,
        .certification-card small {
            font-family: 'Georgia', serif;
            color: #333;
        }

        .certification-card h5 {
            font-size: 14px; /* Font size for headings */
            font-weight: bold; /* Keeping the heading bold */
        }

        .certification-card p {
            font-size: 15px; /* Font size for regular text */
        }

        /* Updated font style for Interests section */
        .certification-card li {
            font-size: 15px; /* Match font size of biography */
            font-family: 'Georgia', serif;
            line-height: 1.0; /* Match line-height of biography */
            color: #333;
            margin-bottom: 10px;
            text-align: justify;
        }

        .certification-card small {
            font-size: 14px; /* Font size for small text */
        }

        .certification-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.1);
        }

        .separator {
            grid-column: 1 / -1;
            text-align: center;
            font-size: 18px;
            font-weight: bold;
            color: #1e3d8f;
            margin-top: 0px;
            margin-bottom: 0px;
            position: relative;
        }

        .separator::after {
            content: '';
            display: block;
            width: 60%;
            height: 1px;
            background-color: #cccccc;
            margin: 10px auto;
        }

        /* New Style for Education Section (as per your uploaded image) */
        .education-layout {
            display: grid;
            grid-template-columns: 1fr;
            gap: 20px;
            margin-top: 20px;
        }

        .education-card {
            padding: 15px;
            background-color: #f9f9f9;
            border-radius: 10px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            display: flex;
            align-items: center;
        }

        .education-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
        }

        .education-card h5 {
            font-family: 'Georgia', serif;
            font-size: 15px; /* Matching font size to Interests section */
            font-weight: bold;
            color: #333;
            margin: 0;
        }

        .education-card small {
            font-size: 14px;
            color: #666;
        }

        .education-card img {
            width: 40px;
            height: 40px;
            margin-right: 20px;
        }

        .education-card p {
            font-size: 16px;
            color: #333;
            margin: 0;
        }

        /* Styling for Download CV link */
        .cv-link-wrapper {
            display: flex;
            align-items: center;
            margin-top: 20px;
        }

        .cv-link-wrapper img {
            width: 20px;
            height: 20px;
            margin-right: 10px;
        }

        .cv-link-wrapper a {
            font-size: 14px;
            font-family: 'Georgia', serif;
            color: #333;
            text-decoration: none;
        }

        .cv-link-wrapper a:hover {
            color: #1e3d8f;
        }

        /* Footer */
        footer {
            text-align: center;
            margin-top: 50px;
            font-size: 14px;
            color: #aaa;
            position: relative; /* Ensure the footer is positioned relative to the content */
            clear: both; /* Clear any floating elements */
            padding: 20px 0; /* Add padding to the footer */
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .certification-layout {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>

<div class="content">
    <!-- Full-width Biography Card -->
    <div class="certification-layout">
        <div class="separator">Profile</div>
        <!-- Biography Card without the Icon -->
        <div class="certification-card" style="grid-column: 1 / -1;">
            <div>
                <p>I am Bamidele Samuel Adelusi, a distinguished Software Developer, Data Scientist, Artificial Intelligence/Machine Learning Specialist, Cloud Solutions Architect and Business Intelligence Expert with over 15 years of experience developing software and applying data science and artificial intelligence (AI) to solve complex, real-world challenges across multiple sectors, including healthcare, retail, real estate, finance, SaaS, and beyond.
                With a Master of Science in Data Analytics and Research from University of Texas at Dallas – United States of America, a Master in Business Computing from University of Ibadan - Nigeria, and a Master of Business Administration in Financial Management from Ladoke Akintola University - Nigeria. Prior to my Master degrees, I graduated with a Post Graduate Diploma in Computer Science from Lagos State University - Nigeria, and a Computer Science major from Yaba College of Technology, Nigeria where I began my Computer Science journey. Recently, I added an additional AWS Solution Architect Professional to the list of my procefessional certifications.</p>
                <p>My career spans a broad range of domains, including software development, data science, artificial intelligence, machine learning, data analytics, big data, cloud computing, systems administration, and infrastructure management. I have been responsible for designing strategies, overseeing the development and implementation of major systems initiatives, and managing multiple concurrent projects, involving complex system integrations and the deployment of innovative software applications. I have consistently delivered value by aligning technology solutions with strategic business objectives.
                As a Software Engineer, Data Scientist, and Cloud Solutions Architect, I have applied this diverse skill sets to implement innovative and secure solutions, contributed to the growth and success of organizations.</p> 
                <p>However, my expertise spans several critical areas of data science, but I am particularly skilled in predictive analytics and the development of AI-powered solutions that help businesses make data-driven decisions. I have built a strong reputation for my ability to develop machine learning models that help organizations anticipate future trends, forecast demand, optimize operations, and drive strategic growth. One of my key strengths lies in creating innovative, AI-driven business intelligence strategies that solve some of the most pressing problems faced by industries today.</p> 
                <p>My continued involvement in both academia and industry ensures that I will stay at the forefront of technological advancements. As a thought leader in AI and data science, I will continue to contribute to the development of new solutions that address critical global challenges. By collaborating with like-minded professionals and organizations in the United States, I will play a key role in advancing AI and data science to benefit not only U.S. industries but also society at large.</p>
                <p>I am confident that my expertise in AI, machine learning, data science, software development and cloud computing will continue to have a lasting impact through my research, development, and collaborations, I will contribute to solving most pressing challenges, driving innovation, and remains at the forefront of global technology.</p>
                
                <!-- New Download CV section -->
                <div class="cv-link-wrapper">
                    <img src="https://www.oiml.org/en/ressources/icons/download-button.jpg/@@images/3139e560-3f59-4ee9-a5e4-71f0ee9535eb.png" alt="Download Icon">
                    <a href="/files/DeleAdelusiResume2026.pdf" class="cv-link" target="_blank">Download my resumé / CV</a> 
                </div>
            </div>
        </div>
    </div>

    <!-- New Style for Education Section -->
    <div class="education-layout">
        <!-- Education Section Separator -->
        <div class="separator">
            <span>Education</span>
        </div>

        <!-- Education Card 1 -->
        <div class="education-card">
            <img src="https://upload.wikimedia.org/wikipedia/commons/d/da/UTA_logomark.png" alt="Graduation Cap">
            <div>
                <h5>PhD in Computer Science and Engineering </h5>
                <p>2026 - 2028<br><small><a href="https://www.uta.edu/academics/schools-colleges/engineering/academics/departments/cse/" target="_blank">The University of Texas at Arlington (UTA)</a></small></p>
            </div>
        </div>

        <!-- Education Card 2 -->
        <div class="education-card">
            <img src="https://upload.wikimedia.org/wikipedia/commons/5/56/UT_Dallas_Emblem_-_Flame_Orange_%28Updated%29.jpg" alt="Graduation Cap">
            <div>
                <h5>MSc in Social Data Analytics and Research</h5>
                <p>2024<br><small><a href="https://epps.utdallas.edu/about/programs/cyber-big-data-analytics/master-of-science-in-social-data-analytics-and-research/" target="_blank">The University of Texas at Dallas (UTD)</a></small></p>
            </div>
        </div>

        <!-- Education Card 3 -->
        <div class="education-card">
            <img src="https://3.bp.blogspot.com/-4VQhkg9h7x8/W69d4xGMGWI/AAAAAAAACKA/hAJVHR2NlNAv-HssddGgJXIFcsHkDVi4ACLcBGAs/s1600/University%2Bof%2BIbadan%2B%2528UI%2529%2BDepartmental%2BCut%2BOff%2BMarks%2B%2528UPDATED%2529.png" alt="Graduation Cap">
            <div>
                <h5>Master in Business Computing</h5>
                <p>2018<br><small><a href="https://pgcollege.ui.edu.ng/program.php?department=Computer%20Science" target="_blank">University of Ibadan (UI)</a></small></p>
            </div>
        </div>

        <!-- Education Card 4 -->
        <div class="education-card">
            <img src="https://image.pngaaa.com/389/995389-middle.png" alt="Graduation Cap">
            <div>
                <h5>MBA in Financial Management</h5>
                <p>2008<br><small><a href="https://www.lautech.edu.ng/" target="_blank">Ladoke Akintola University of Technology (LAUTECH)</a></small></p>
            </div>
        </div>

        <!-- Education Card 5 -->
        <div class="education-card">
            <img src="https://upload.wikimedia.org/wikipedia/commons/3/3e/Lagos_State_University_logo.png" alt="Graduation Cap">
            <div>
                <h5>PGD in Computer Science</h5>
                <p>2006<br><small><a href="https://lasu.edu.ng/home/" target="_blank">Lagos State University (LASU)</a></small></p>
            </div>
        </div>

                <!-- Education Card 6 -->
        <div class="education-card">
            <img src="https://www.yabatech.edu.ng/yabawebadmin/upploads/61de664778bd0.png" alt="Graduation Cap">
            <div>
                <h5>HND in Computer Science and Engineering</h5>
                <p>2001<br><small><a href="https://www.yabatech.edu.ng/" target="_blank">Yaba College of Technology (YabaTech)</a></small></p>
            </div>
        </div>
    </div>

    
    <!-- Card Layout for Interests -->
    <div class="certification-layout">
        <!-- Interests Section Separator -->
        <div class="separator">Research Interest</div>
        <!-- Interests Card 1 -->
        <div class="certification-card">
            <div>
                <li>Machine Learning for Healthcare</li>
        		    <li>Artificial Intelligence</li>
        		    <li>Neural Networks and Deep Learning</li>
        		    <li>Microservices, Docker & Kubernetes Orchestration</li>
            </div>
        </div>

        <!-- Interests Card 2 -->
        <div class="certification-card">
            <div>
                <li>Cloud Computing & Infrastructure as Code</li>
                <li>Digital Transformation & Cloud-Native Modernization</li>
                <li>Software Engineering</li>
                <li>Data Mining</li>
            </div>
        </div>
    </div>

</div>

<footer>
    © 2025 by Adelusi Bamidele Samuel. All rights reserved.
</footer>

</body>
</html>
