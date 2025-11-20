---
layout: archive
title: ""
permalink: /skills/
author_profile: true
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: 'Georgia', serif;
            background-color: #f7f7f7;
            color: #333;
            margin: 0;
            padding: 0;
            text-align: center;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
        }

        /* Ensure content has enough padding at the bottom */
        .content {
            flex: 1;
            padding-bottom: 50px; /* Added bottom padding */
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

        .separator {
            grid-column: 1 / -1;
            text-align: center;
            font-size: 24px;
            font-family: 'Georgia', serif;
            font-weight: bold;
            color: #1e3d8f;
            margin-top: 20px;
            margin-bottom: 20px;
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

        .skills-section {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            grid-template-rows: repeat(4, auto);
            gap: 20px;
            padding: 30px 20px;
            max-width: 1200px;
            margin: auto;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        .item {
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 15px;
            border-radius: 10px;
            background-color: #f9f9f9;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .item:hover {
            transform: translateY(-5px);
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.15);
        }

        .item img {
            width: 60px;
            margin-bottom: 15px;
        }

        .item p {
            font-size: 16px;
            margin: 5px 0;
            color: #333;
        }

        .subtext {
            font-size: 14px;
            color: #888;
        }

        /* Footer styling */
        footer {
            text-align: center;
            padding: 20px 0;
            background-color: #f1f1f1;
            color: #666;
            width: 100%;
            margin-top: auto;
        }

        footer a {
            text-decoration: none;
            color: #1e3d8f;
            font-weight: bold;
        }

        footer a:hover {
            color: #333;
        }

    </style>

<div class="content">
   <!-- Skills Section -->
<div class="separator">Skills</div>
<div class="skills-section">
    <div class="item">
        <img src="https://cdn-icons-png.flaticon.com/512/9402/9402518.png" alt="Project Management">
        <p>Waterfall, Agile, Scrum</p>
        <p class="subtext">Large Scale Project Management</p>
    </div>

    <div class="item">
        <img src="https://c7.alamy.com/comp/2D90ABN/eight-soft-skills-2D90ABN.jpg" alt="Soft Skills">
        <p>Inclusive Leadership, Business Communication</p>
        <p class="subtext">Soft Skills</p>
    </div>

    <div class="item">
        <span>
        <img src="https://img.icons8.com/color/96/000000/python.png" alt="Python Icon">
        <img src=" https://e7.pngegg.com/pngimages/656/766/png-clipart-computer-terminal-computer-icons-bash-others-miscellaneous-angle.png" alt="Python Icon">
        </span>       
        <p>Python, C, SQL, Bash</p>
        <p class="subtext">Programming Languages</p>
    </div>

    <div class="item">
        <img src="https://w7.pngwing.com/pngs/977/12/png-transparent-responsive-web-design-web-development-bootstrap-html-javascript-world-wide-web-text-trademark-logo.png" alt="Web Development">
        <p>HTML, CSS, Bootstrap, MERN, MEAN</p>
        <p class="subtext">Web Development</p>
    </div>
    
    <div class="item">
        <img src="https://hoffstech.com/wp-content/uploads/2021/08/dockerkubernetes.jpg" alt="Docker Icon">
        <p>Docker, Kubernetes</p>
        <p class="subtext">Container Orchestration</p>
    </div>

    <div class="item">
        <img src="https://cdn-icons-png.flaticon.com/512/4319/4319147.png" alt="Cloud Icon">
        <p>AWS, GCP</p>
        <p class="subtext">Cloud Computing</p>
    </div>

    <div class="item">
        <span>
        <img src="https://img.icons8.com/color/96/000000/linux.png" alt="Linux Icon">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2b/Kali-dragon-icon.svg/2048px-Kali-dragon-icon.svg.png" alt="Linux Icon">
        </span>
        <p>Linux, Kali Linux</p>
        <p class="subtext">Operating Systems</p>
    </div>

    <div class="item">
        <span>
        <img src="https://cdn.prod.website-files.com/61e1d8dcf4a5e16aab73f6b4/6436e5b8414672f2c5e6bf96_HvXhzF0cx90RWU_ej6Gv9N_nyQLdp0y9rSWk0XX89_wpyY_AJttyzmc8x5Q5XPjq1bT4U87X-2pZWbVfD8JsybS-MFV2vV-xKTTWr1n-TuKCIoyaAnGU9jK3kzDsyvnBVEeWoWyRjSjRvuj-4gBCacY.png" alt="Grafana Icon">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSbiA0ETD6XFeMk7fSPnZOUvEqReLuWvy08Rw&s" alt="Grafana Icon">
        </span>        
        <p>Prometheus, Grafana, Jaeger</p>
        <p class="subtext">Monitoring and Metrics</p>
    </div>

    <div class="item">
        <img src="https://fiverr-res.cloudinary.com/images/t_main1,q_auto,f_auto,q_auto,f_auto/gigs/204141243/original/d11ae65c36ac8119f6969a414afd1462ff16713d/a-database-design-and-integration-using-the-mysql-and-mongodb-database.png" alt="Database Icon">
        <p>MySQL, MongoDB</p>
        <p class="subtext">Databases</p>
    </div>

    <div class="item">
        <img src="https://cdn-icons-png.flaticon.com/256/8293/8293467.png" alt="IT Audit">
        <p>ISO, ITAF</p>
        <p class="subtext">IT Audit</p>
    </div>

    <div class="item">
        <img src="https://cdn-icons-png.flaticon.com/512/5671/5671489.png" alt="SIEM">
        <p>SIEM, XDR, EDR</p>
        <p class="subtext">Threat Detection and Defense Tools</p>
    </div>

    <div class="item">
        <img src="https://cdn.prod.website-files.com/606d79a3190d3a764c032a2c/6462496836e0a5e0bafd9d04_Frame%201817%20(1).png" alt="SOAR">
        <p>SOAR, Threat Intel</p>
        <p class="subtext">Threat Intelligence and Incident Response Platform</p>
    </div>

    <div class="item">
        <img src="https://www.shutterstock.com/image-vector/dlp-data-loss-prevention-acronym-260nw-2401819555.jpg" alt="DLP">
        <p>DLP, MDM</p>
        <p class="subtext">Data Privacy Tools</p>
    </div>

    <div class="item">
        <span>
        <img src="https://media.licdn.com/dms/image/D4D12AQG5hXvJJSbzsA/article-cover_image-shrink_600_2000/0/1696567657381?e=2147483647&v=beta&t=VwrFw3BHCE2jtPtI4oEnEb2NKnbcV624fKWznzD9R1w" alt="VAPT Tools">
        <img src="https://w7.pngwing.com/pngs/286/446/png-transparent-burp-suite-macos-bigsur-icon.png" alt="VAPT Tools">
        </span>        
        <p>NMAP, Nessus, Burpsuite</p>
        <p class="subtext">VAPT Tools</p>
    </div>

    <div class="item">
        <img src="https://www.ideagen.com/media/11748/grc-circle.png" alt="GRC">
        <p>GRC, ISO, COBIT</p>
        <p class="subtext">GRC</p>
    </div>

    <div class="item">
        <img src="https://static.vecteezy.com/system/resources/previews/021/761/374/original/incident-management-icon-style-vector.jpg" alt="ITIL">
        <p>ITIL, ISO</p>
        <p class="subtext">IT Incident Management</p>
    </div>
</div>
<footer>
</footer>

