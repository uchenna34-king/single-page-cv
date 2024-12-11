<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Single Page CV</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            color: #333;
            background-color: #fff;
        }

        .container {
            max-width: 600px;
            margin: 2rem auto;
            padding: 1.5rem;
            border: 1px solid #ddd;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            background-color: #fff;
        }

        h1 {
            font-size: 1.8rem;
            font-weight: bold;
            margin-bottom: 0.3rem;
        }

        .job-title {
            font-size: 1.1rem;
            color: #4CAF50;
            margin-bottom: 1rem;
        }

        .contact {
            margin-bottom: 1.5rem;
            font-size: 0.9rem;
        }

        .contact p {
            margin: 0.2rem 0;
        }

        .section {
            margin-bottom: 2rem;
        }

        .section h2 {
            font-size: 1.2rem;
            color: #4CAF50;
            border-bottom: 1px solid #4CAF50;
            padding-bottom: 0.2rem;
            margin-bottom: 1rem;
        }

        ul {
            margin: 0;
            padding: 0 0 0 1rem;
            list-style: disc;
        }

        .skills {
            font-size: 0.9rem;
        }

        .across-internet {
            margin-top: 2rem;
            font-style: italic;
            font-size: 0.9rem;
        }

        .across-internet a {
            color: #007BFF;
            text-decoration: none;
        }

        .across-internet a:hover {
            text-decoration: underline;
        }

        .title-line {
            border-top: 2px solid #333;
            margin: 1rem 0;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Your Name</h1>
        <div class="job-title">Junior Frontend Developer</div>

        <div class="contact">
            <p>123 Your Street</p>
            <p>Your City, ST 12345</p>
            <p>(123) 456-7890</p>
            <p>no_reply@example.com</p>
        </div>

        <div class="title-line"></div>

        <div class="section">
            <h2>Skills</h2>
            <p class="skills">HTML, CSS, JavaScript, Accessibility, Figma to Design, Responsive Web Design, Technical Writing, Presentation</p>
        </div>

        <div class="section">
            <h2>Education</h2>
            <p><strong>School Name, Location - Degree</strong></p>
            <p>Month 20xx to Month 20xx</p>
            <p>List of exciting things you did at university</p>
        </div>

        <div class="section">
            <h2>Experience</h2>
            <p><strong>Company Name, Location - Job Title</strong></p>
            <p>Month 20xx to Month 20xx</p>
            <ul>
                <li>List of achievements</li>
                <li>List of achievements</li>
                <li>List of achievements</li>
            </ul>
            <p><strong>Skills:</strong> List of skills used or gained at this company</p>

            <p><strong>Company Name, Location - Job Title</strong></p>
            <p>Month 20xx to Month 20xx</p>
            <ul>
                <li>List of achievements</li>
                <li>List of achievements</li>
                <li>List of achievements</li>
            </ul>
            <p><strong>Skills:</strong> List of skills used or gained at this company</p>
        </div>

        <div class="across-internet">
            <p>Add your <a href="#">LinkedIn</a>, <a href="#">GitHub</a> profile links</p>
        </div>
    </div>
</body>
</html>
