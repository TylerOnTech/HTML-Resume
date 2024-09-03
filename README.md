<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tyler Kunkel's Profile</title>
    <style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap');

        body {
            font-family: 'Montserrat', sans-serif;
            background-color: #121212;
            color: #e0e0e0;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }

        .container {
            max-width: 800px;
            margin: auto;
            padding: 20px;
            background-color: #1c1c1c;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.8);
            overflow: hidden;
        }

        .header {
            text-align: center;
            padding: 50px 0;
            background: linear-gradient(135deg, #f97300, #ffcc00);
            margin-bottom: 20px;
            border-radius: 10px 10px 0 0;
        }

        .header img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            border: 5px solid #ffffff;
        }

        .nav {
            text-align: center;
            margin-bottom: 30px;
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            width: 100%;
            background-color: #1c1c1c;
            padding: 10px 0;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.5);
        }

        .nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
        }

        .nav ul li {
            margin: 0 15px;
        }

        .nav a {
            color: #ffcc00;
            text-decoration: none;
            font-weight: bold;
            text-transform: uppercase;
            transition: color 0.3s;
        }

        .nav a:hover {
            color: #f97300;
        }

        .container, .intro, .lite-section, .section, .skills, .joyful-element {
            margin-top: 50px; /* Adjust this value if necessary */
        }

        .contact-info {
            text-align: center;
            padding: 20px;
            background-color: #2b2b2b;
            margin-bottom: 30px;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.8);
            color: #f0f0f0;
            font-size: 1.2em;
        }

        .contact-info p {
            margin: 10px 0;
        }

        .intro {
            background-color: #2b2b2b;
            padding: 40px;
            border-radius: 10px;
            margin-bottom: 30px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.8);
            text-align: center;
        }

        .intro h1 {
            color: #ffcc00;
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        .intro p {
            color: #f0f0f0;
            font-size: 1.2em;
            line-height: 1.8;
        }

        .lite-section {
            margin-bottom: 30px;
            padding: 30px;
            background-color: #333;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.8);
            text-align: center;
            color: #ffcc00;
            font-weight: bold;
            font-size: 1.5em;
            letter-spacing: 1px;
        }

        .section {
            margin-top: 30px;
        }

        .section h2 {
            color: #f97300;
            font-size: 2em;
            margin-bottom: 20px;
            text-transform: uppercase;
            letter-spacing: 2px;
            text-align: center;
        }

        .section p {
            margin: 15px 0;
            background-color: #333;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.7);
            line-height: 1.8;
            font-size: 1.1em;
        }

        .section ul {
            padding: 0 20px;
            list-style-type: disc;
        }

        .section a {
            color: #f97300;
            font-weight: bold;
            text-decoration: none;
            transition: color 0.3s;
        }

        .section a:hover {
            color: #ffcc00;
        }

        .skills {
            margin-top: 50px;
            padding: 30px;
            background-color: #333;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.8);
        }

        .skills h2 {
            color: #ffcc00;
            text-align: center;
            font-size: 2em;
            margin-bottom: 20px;
            text-transform: uppercase;
        }

        .skills .skill {
            margin: 15px 0;
            background-color: #2b2b2b;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.7);
            font-size: 1.1em;
            position: relative;
        }

        .skills .skill span {
            color: #f97300;
            font-weight: bold;
            position: absolute;
            right: 20px;
            top: 50%;
            transform: translateY(-50%);
            font-size: 1.5em;
        }

        .video-section {
            margin-top: 50px;
            padding: 40px;
            background-color: #2b2b2b;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.8);
            text-align: center;
        }

        .video-section h2 {
            color: #ffcc00;
            font-size: 2em;
            margin-bottom: 20px;
            text-transform: uppercase;
        }

        .video-section iframe {
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.7);
        }

        .joyful-element {
            margin-top: 50px;
            padding: 40px;
            background: linear-gradient(135deg, #f97300, #1c1c1c);
            border-radius: 15px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.8);
            text-align: center;
            color: #ffffff;
        }

        .joyful-element h2 {
            font-size: 2.2em;
            margin-bottom: 20px;
            text-transform: uppercase;
        }

        .joyful-element p {
            font-size: 1.3em;
            line-height: 1.8;
            margin-bottom: 20px;
        }

        .joyful-element iframe {
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.7);
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <img src="https://storage.mlcdn.com/account_image/1087109/6zLWwrpIdz5zZETcZzr9WPE4RYKtnVnkn1I6sUcQ.jpg" alt="Profile Picture">
        </div>

        <!-- Navigation Links -->
        <div class="nav">
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#professional-journey">Professional Journey</a></li>
                <li><a href="#skill-development">Skill Development</a></li>
                <li><a href="#highlighted-projects">Highlighted Projects</a></li>
                <li><a href="#saas-websites">SaaS Websites</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#motivation">Motivation</a></li>
            </ul>
        </div>

        <!-- Contact Information Section -->
        <div class="contact-info">
            <p>Email: tylerkunkel1629@gmail.com</p>
            <p>Phone: (260) 797-1629</p>
            <p>Location: Fort Wayne, Indiana </p>
        </div>
    </div>

    <div class="intro" id="home">
        <h1>Hello, I'm Tyler Kunkel</h1>
        <p>
            I'm a passionate web designer with a strong focus on creating visually appealing and user-centered designs. With a diverse skill set and a commitment to continuous learning, I have successfully contributed to various projects across different industries. Explore my work and discover how I can bring value to your team at MailerLite.
        </p>
    </div>

    <div class="lite-section">
        I'm excited to bring my "Lite" touch to the MailerLite team, blending creativity with practical design to enhance user experiences.
    </div>

    <div class="video-section">
        <h2>Why I Want to Join MailerLite</h2>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/[YourVideoID]" frameborder="0" allowfullscreen></iframe>
    </div>

    <div class="section" id="professional-journey">
        <h2>My Professional Journey</h2>
        <p>
            With a strong foundation in both DevOps and social media management, I bring a unique blend of technical and creative skills to every project. My experience in DevOps has equipped me with the expertise to optimize development processes, enhance operational efficiency, and ensure the stability and scalability of applications. On the other hand, my role as a Social Media Manager has honed my ability to craft compelling content, engage with diverse audiences, and drive brand growth across multiple platforms. This diverse background allows me to approach challenges from both a technical and creative perspective, making me a versatile and valuable asset to any team. I am confident that my ability to integrate these skill sets will enable me to contribute effectively to both the technical and marketing aspects of any project I undertake.
        </p>

        <h3 style="color: #f97300;">Current Role</h3>
        <p>
            <strong>Social Media Manager/Content Creator at Black Box Fragrance</strong> (January 2023 - Present)
        </p>
        <ul>
            <li>Managed social media presence and content creation, driving growth across multiple platforms.</li>
            <li>Developed and implemented strategies to boost brand awareness and customer engagement on Instagram, YouTube, and TikTok.</li>
            <li>Created visual and written content to reflect the brand’s identity and messaging, leading to increased online interaction and sales.</li>
            <li>Handled performance analytics and adjusted strategies to improve reach and engagement.</li>
        </ul>

        <h3 style="color: #f97300;">Internship Experience</h3>
        <p>
            <strong>Help Desk Engineer Internship at Remote Labs</strong> (February 2023 - February 2024)
        </p>
        <ul>
            <li>Monitored security alerts and incidents using a wide range of security tools, including cutting-edge cloud security solutions.</li>
            <li>Provided technical support to end-users for security-related issues in cloud environments.</li>
            <li>Assisted in the development, implementation, and maintenance of security policies, procedures, and controls for both on-premises and cloud infrastructures.</li>
        </ul>

        <p>
            <strong>Python Developer Internship at Lowe’s Companies</strong> (February 2022 - January 2023)
        </p>
        <ul>
            <li>Designed and deployed Python-based applications, streamlining business processes and significantly improving operational efficiency.</li>
            <li>Collaborated with cross-functional teams to gather requirements and translate them into technical specifications.</li>
            <li>Conducted thorough testing and debugging to ensure high-quality software performance and reliability.</li>
        </ul>

        <p>
            <strong>DevOps Engineer Internship at MedPro Group</strong> (January 2021 - January 2022)
        </p>
        <ul>
            <li>Implemented and maintained CI/CD pipelines, enhancing deployment efficiency and ensuring operational stability.</li>
            <li>Managed containerized applications using Docker and Kubernetes, improving deployment efficiency and system reliability.</li>
            <li>Utilized Python for complex scripting and automation tasks, contributing significantly to system reliability and performance improvements.</li>
        </ul>

        <p>
            These roles have given me a strong foundation in both the technical and creative aspects of technology and content management, allowing me to bring a unique blend of skills to any project I work on.
        </p>
    </div>

    <div class="section" id="skill-development">
        <h2>Skill Development & Inspiration</h2>
        <p>
            <strong>Official Qualifications:</strong> I am almost finished with a computer science degree from Purdue University.
        </p>
        <p>
            <strong>Mentors and Teachers:</strong> Thomas Bolinger was my biggest mentor and favorite teacher, guiding me through complex concepts and projects.
        </p>
        <p>
            <strong>Staying Up-to-Date:</strong> I am always teaching myself new things, keeping up to date with a blend of YouTube, TikTok, and Reddit. I also have many friends in the industry to trade new knowledge with.
        </p>
        <p>
            <strong>Sources of Inspiration:</strong> I draw inspiration from the classics like Steve Jobs, Bill Gates, Alan Turing, and Bjarne Stroustrup. I'm also very big into watching podcasts hosted by Lex Fridman.
        </p>
    </div>

    <div class="section" id="highlighted-projects">
        <h2>Highlighted Projects</h2>
        <p>
            One of my proudest accomplishments is the website I designed for <a href="https://outbackcoatings.com/" target="_blank">Outback Coatings</a>. This project showcases my ability to create a sleek, modern website that aligns with the brand's identity and enhances user experience.
        </p>
        <p>
            Currently, I am working on an exciting project that involves building a personal budgeting app using a modern tech stack:
        </p>
        <ul>
            <li><strong>Frontend:</strong> React with TypeScript - Utilizing TypeScript for better type safety and predictability in a large-scale project.</li>
            <li><strong>Backend:</strong> GraphQL with Apollo Server - Creating a flexible and efficient API that allows the frontend to request only the data it needs.</li>
            <li><strong>Database:</strong> MongoDB with Mongoose - Leveraging MongoDB's scalability and Mongoose's schema-based data modeling.</li>
            <li><strong>Authentication:</strong> Auth0 - Integrating a robust authentication solution that supports various methods like email/password and social logins.</li>
            <li><strong>Hosting and Deployment:</strong> Vercel/Netlify - Deploying the app using platforms that offer seamless deployment and serverless functions.</li>
            <li><strong>State Management:</strong> Redux Toolkit - Simplifying state management with Redux Toolkit for scalable and maintainable state handling.</li>
            <li><strong>UI Framework:</strong> Material-UI or Tailwind CSS - Creating a responsive and professional-looking UI with modern CSS frameworks.</li>
        </ul>
        <p>
            This project exemplifies my ability to work with a modern tech stack, ensuring a high-quality and scalable application.
        </p>
    </div>

    <div class="section" id="saas-websites">
        <h2>SaaS Websites I Admire</h2>
        <p>
            Here are a few SaaS websites that I believe exemplify how brand identity and tone-of-voice translate into modern, user-centered web design:
        </p>
        <p>
            <strong><a href="https://slack.com/" target="_blank">Slack</a>:</strong> Slack’s website reflects its collaborative and approachable brand identity through clean design, intuitive navigation, and a friendly, professional tone.
        </p>
        <p>
            <strong><a href="https://www.dropbox.com/" target="_blank">Dropbox</a>:</strong> Dropbox uses simplicity and clarity to convey its reliable and user-friendly brand. The design is straightforward, making it easy for users to understand and engage with the platform.
        </p>
        <p>
            <strong><a href="https://www.notion.so/" target="_blank">Notion</a>:</strong> Notion’s website balances minimalism with visual engagement, reflecting the brand’s identity as a flexible and creative productivity tool. The empowering tone encourages users to explore and customize their experience.
        </p>
    </div>

    <div class="skills" id="skills">
        <h2>Skills & Proficiency</h2>
        <div class="skill">
            <span>5/5</span> Brand Identity, Color Theory, Typography
        </div>
        <div class="skill">
            <span>3/5</span> UX Design
        </div>
        <div class="skill">
            <span>2/5</span> Figma
        </div>
        <div class="skill">
            <span>4/5</span> HTML/CSS
        </div>
        <div class="skill">
            <span>3/5</span> TailwindCSS
        </div>
        <div class="skill">
            <span>5/5</span> Basic JavaScript
        </div>
        <div class="skill">
            <span>4/5</span> Git
        </div>
        <div class="skill">
            <span>5/5</span> Remote Team Collaboration
        </div>
    </div>

    <div class="joyful-element" id="motivation">
        <h2>What Keeps Me Motivated</h2>
        <p>
            The song "Champion" by Zach Diamond is a huge source of motivation for me. The lyrics remind me of the importance of resilience, hard work, and staying focused on my goals, no matter the challenges that come my way. It’s a constant reminder to push forward and strive for excellence in everything I do.
        </p>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/U3dR3hJ-mL0?autoplay=1" frameborder="0" allow="encrypted-media" allowfullscreen></iframe>
    </div>
</body>
</html>
