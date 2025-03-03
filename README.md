# Ex01 Portfolio
## Date: 03/03/2025

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Multi-Page Resume</title>
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap');
        
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: #f4f4f4;
        }
        .resume {
            width: 800px;
            background: white;
            margin: 20px auto;
            box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.2);
            border-radius: 10px;
            padding: 20px;
            page-break-after: always;
            display: flex;
        }
        .left {
            width: 30%;
            background: #2a5298;
            color: white;
            padding: 20px;
            text-align: center;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .right {
            width: 70%;
            padding: 20px;
        }
        .left img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            border: 3px solid white;
            margin-bottom: 10px;
        }
        .section {
            margin-bottom: 20px;
        }
        .section h2 {
            color: #2a5298;
            border-bottom: 2px solid #2a5298;
            padding-bottom: 5px;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <div class="resume">
        <div class="left">
            <img src="WhatsApp Image 2025-03-03 at 10.25.50_2e3c2ef0.jpg" alt="Profile Image">
            <h2>Rahul Krishna</h2>
            <p>Web Developer</p>
            <h3>Contact</h3>
            <ul>
                <li>Email: RahulKrishna@example.com</li>
                <li>Phone: (123) 456-7890</li>
                <li>Website: RahulKrishna.com</li>
            </ul>
        </div>
        <div class="right">
            <div class="section">
                <h2>Summary</h2>
                <p>Experienced Web Developer with expertise in front-end and back-end development. Passionate about creating efficient, scalable, and user-friendly web applications. Adept at integrating modern technologies and frameworks to enhance application functionality and performance. Strong problem-solving skills, teamwork, and a commitment to continuous learning to stay ahead in the rapidly evolving tech industry. Skilled in leveraging cloud computing, database management, and responsive design principles to deliver seamless digital experiences.</p>
            </div>
        </div>
    </div>
    
    <div class="resume">
        <div class="section">
            <h2>Experience</h2>
            <p><strong>Software Engineer</strong> - ABC Corp (2020 - Present)</p>
            <p>Developed scalable web applications and implemented new UI/UX designs. Optimized backend systems for performance and efficiency, while also integrating cloud-based solutions to improve scalability.</p>
            <p><strong>Intern - XYZ Tech</strong> (2019 - 2020)</p>
            <p>Assisted in backend development, worked with RESTful APIs, and contributed to AI model training for predictive analytics.</p>
        </div>
    </div>
    
    <div class="resume">
        <div class="section">
            <h2>Education</h2>
            <p><strong>Bachelor of IT</strong> - XYZ University (2016 - 2020)</p>
            <p>Studied core computer science concepts, software development, data structures, and cybersecurity.</p>
            <p><strong>Master's in Computer Science</strong> - ABC University (2021 - 2023)</p>
            <p>Specialized in AI and cloud computing, conducting research on automation and data-driven decision-making.</p>
        </div>
    </div>
    
    <div class="resume">
        <div class="section">
            <h2>Projects</h2>
            <p><strong>AI Chatbot</strong> - Built a chatbot with NLP and machine learning for automated customer support.</p>
            <p><strong>Portfolio Website</strong> - Designed a responsive portfolio showcasing skills and projects.</p>
            <p><strong>E-commerce Platform</strong> - Developed a full-stack e-commerce application with secure payment integration.</p>
            <p><strong>Cloud-Based CRM</strong> - Created a CRM system deployed on AWS with automation tools.</p>
        </div>
    </div>
    
    <div class="resume">
        <div class="section">
            <h2>Certifications</h2>
            <ul>
                <li>Certified Web Developer - Google</li>
                <li>Advanced JavaScript Certification - Udemy</li>
                <li>Machine Learning Specialization - Coursera</li>
                <li>AWS Certified Cloud Practitioner</li>
            </ul>
        </div>
        <div class="section">
            <h2>References</h2>
            <p><strong>John Doe</strong> - Senior Developer at ABC Corp (johndoe@example.com)</p>
            <p><strong>Jane Smith</strong> - Manager at XYZ Tech (janesmith@example.com)</p>
        </div>
    </div>
</body>
</html>
```
## OUTPUT

![Screenshot 2025-03-03 113840](https://github.com/user-attachments/assets/5ef41c4f-e1c2-44b1-ade9-911734f30d00)
![Screenshot 2025-03-03 113856](https://github.com/user-attachments/assets/48310f7f-3c64-4d45-8918-8136204a18bd)
![Screenshot 2025-03-03 113912](https://github.com/user-attachments/assets/3e019c73-a38f-4634-99d5-fde65626365d)


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
