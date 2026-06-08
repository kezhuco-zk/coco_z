<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ke Zhu | Educational Leadership Portfolio</title>

    <link rel="stylesheet" href="style.css">

    <style>
        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
        }

        body{
            font-family: "Segoe UI", Arial, sans-serif;
            line-height:1.8;
            color:#333;
            background:#fafafa;
        }

        header{
            background:#1f3c5a;
            color:white;
            text-align:center;
            padding:100px 20px;
        }

        header h1{
            font-size:3rem;
            margin-bottom:15px;
        }

        header p{
            font-size:1.2rem;
            max-width:700px;
            margin:auto;
        }

        nav{
            background:white;
            box-shadow:0 2px 10px rgba(0,0,0,0.08);
            position:sticky;
            top:0;
            z-index:100;
        }

        nav ul{
            display:flex;
            justify-content:center;
            list-style:none;
        }

        nav li{
            margin:0 20px;
        }

        nav a{
            display:block;
            padding:18px;
            text-decoration:none;
            color:#1f3c5a;
            font-weight:600;
        }

        section{
            max-width:1100px;
            margin:80px auto;
            padding:0 20px;
        }

        h2{
            color:#1f3c5a;
            margin-bottom:20px;
            font-size:2rem;
        }

        .about{
            text-align:center;
        }

        .about p{
            max-width:800px;
            margin:auto;
        }

        .cards{
            display:grid;
            grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
            gap:25px;
            margin-top:30px;
        }

        .card{
            background:white;
            padding:25px;
            border-radius:12px;
            box-shadow:0 4px 15px rgba(0,0,0,0.08);
        }

        .card h3{
            margin-bottom:10px;
            color:#1f3c5a;
        }

        .research-list{
            background:white;
            padding:30px;
            border-radius:12px;
            box-shadow:0 4px 15px rgba(0,0,0,0.08);
        }

        .research-list ul{
            padding-left:20px;
        }

        .skills{
            display:flex;
            flex-wrap:wrap;
            gap:15px;
            margin-top:20px;
        }

        .skill{
            background:#1f3c5a;
            color:white;
            padding:10px 18px;
            border-radius:25px;
        }

        footer{
            background:#1f3c5a;
            color:white;
            text-align:center;
            padding:40px;
            margin-top:80px;
        }

        .button{
            display:inline-block;
            margin-top:25px;
            padding:12px 24px;
            background:white;
            color:#1f3c5a;
            text-decoration:none;
            border-radius:6px;
            font-weight:bold;
        }
    </style>
</head>

<body>

<header>
    <h1>Ke Zhu</h1>
    <p>
        Educational Leadership Student | Researcher | Educational Innovator
    </p>

    <a href="#about" class="button">Explore My Portfolio</a>
</header>

<nav>
    <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#internship">Internship</a></li>
        <li><a href="#research">Research</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>

<section id="about" class="about">
    <h2>About Me</h2>

    <p>
        I am a Master's student in Educational Leadership with interests in
        educational leadership, higher education management, STEM education,
        gender equity, and educational innovation. My work combines academic
        research with practical experience in educational administration and
        institutional leadership.
    </p>
</section>

<section id="internship">
    <h2>Internship Portfolio</h2>

    <div class="cards">

        <div class="card">
            <h3>Intellectual Property Management</h3>
            <p>
                Participated in reviewing semester intellectual property
                ledgers, achievement verification, and data organization.
            </p>
        </div>

        <div class="card">
            <h3>Innovation Education Projects</h3>
            <p>
                Assisted in project screening, documentation review,
                and innovation program management.
            </p>
        </div>

        <div class="card">
            <h3>Leadership Support</h3>
            <p>
                Worked closely with college leadership to observe strategic
                decision-making and organizational coordination.
            </p>
        </div>

        <div class="card">
            <h3>Educational Governance</h3>
            <p>
                Supported policy implementation, quality assurance,
                and institutional management activities.
            </p>
        </div>

    </div>
</section>

<section id="research">
    <h2>Research Interests</h2>

    <div class="research-list">

        <ul>
            <li>Mentor Leadership and STEM Women's Learning Efficacy</li>
            <li>Distributed Leadership in Educational Organizations</li>
            <li>Leadership in Higher Education Public Relations Crises</li>
            <li>Educational Innovation and School Transformation</li>
            <li>Alternative School Design and Future Learning Models</li>
        </ul>

    </div>
</section>

<section id="skills">
    <h2>Professional Skills</h2>

    <div class="skills">

        <div class="skill">Educational Leadership</div>
        <div class="skill">Academic Writing</div>
        <div class="skill">Systematic Review</div>
        <div class="skill">PRISMA Analysis</div>
        <div class="skill">SPSS</div>
        <div class="skill">NVivo</div>
        <div class="skill">Research Design</div>
        <div class="skill">Project Management</div>

    </div>
</section>

<section id="contact">
    <h2>Contact</h2>

    <p>Email: your-email@example.com</p>
    <p>GitHub: github.com/yourusername</p>
    <p>LinkedIn: linkedin.com/in/yourprofile</p>

</section>

<footer>
    <p>© 2026 Ke Zhu | Educational Leadership Portfolio</p>
</footer>

</body>
</html>
