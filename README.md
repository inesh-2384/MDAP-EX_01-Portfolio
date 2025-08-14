# MDAP-EX_01-Portfolio
## Date:

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
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>Inesh K | Portfolio</title>
    <link rel="stylesheet" href="2.css" />
</head>
<body>
    <header>
        <h1>Inesh K</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#internship">Internship</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <img src="inn.jpg" alt="Inesh K's Photo" />
        <div>
            <h2>About Me</h2>
            <p>Hi, I'm Inesh K! A 3rd-year Information Technology student with a passion for building intelligent systems and scalable applications. My expertise lies in Full-Stack Java Development and Data Science, enabling me to craft efficient, data-driven solutions.</p>
        </div>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Enhancing SAR Image Interpretation</h3>
            <p>A deep learning-based SAR image colorization project designed to improve data interpretation and analysis for better decision-making in remote sensing. Built using Python, TensorFlow, and OpenCV.</p>
        </div>
        <div class="project">
            <h3>Predictive Hiring with Data Science</h3>
            <p>An AI-driven recruitment system utilizing predictive analytics and machine learning to improve hiring decisions, reduce bias, and enhance candidate selection.</p>
        </div>
        <div class="project">
            <h3>Full-Stack Web Application for Data Analytics</h3>
            <p>Developed a full-stack web platform integrating Spring Boot and React.js for interactive data visualization and real-time analytics.</p>
        </div>
        <div class="project">
            <h3>AI-Powered Chatbot for Customer Support</h3>
            <p>Designed an NLP-based chatbot for automated customer support, built using Python, Flask, and Dialogflow.</p>
        </div>
    </section>

    <section id="internship">
        <h2>Internship Experience</h2>
        <p><strong>Arjun Vision Tech Solutions | 2024</strong></p>
        <p>Gained hands-on experience in data science, focusing on predictive modeling, machine learning algorithms, and SAR image colorization using deep learning.</p>
    </section>

    <section id="education">
        <h2>Education</h2>
        <p><strong>B.Tech in Information Technology</strong><br>Saveetha Engineering College (2023–2027)<br>CGPA: 8.5/10</p>
        <p><strong>Higher Secondary Education</strong><br>DAV School (2020–2023)<br>Percentage: 85%</p>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <h3>Technical Skills</h3>
        <ul>
            <li>Programming: Java, Python, SQL, JavaScript</li>
            <li>Web Development: HTML, CSS, React.js, Spring Boot</li>
            <li>Data Science: Machine Learning, Deep Learning, Data Analysis</li>
            <li>Computer Vision: SAR Image Processing, Image Colorization</li>
        </ul>
        <h3>Soft Skills</h3>
        <ul>
            <li>Communication, Teamwork, Problem-Solving, Leadership</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Email: inesh2010nj@gmail.com</p>
        <p>Address: Chennai, India</p>
        <p>Phone: 8939744434</p>
        <p>GitHub: <a href="#">github.com/inesh-2384</a></p>
        <p>LinkedIn: <a href="#">linkedin.com/in/ineshnj</a></p>
    </section>

    <footer>
        <p>&copy; 2027 Inesh K. All Rights Reserved.</p>
    </footer>
</body>
</html>
```
## Style.css
```
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0;
    background-color: #f4f4f4;
    color: #333;
    line-height: 1.6;
}

header {
    background-color: #0d47a1;
    color: white;
    padding: 20px 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
    margin-top: 10px;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

nav ul li a:hover {
    text-decoration: underline;
}

section {
    padding: 40px 20px;
    max-width: 900px;
    margin: auto;
    background-color: white;
    margin-bottom: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
}

#about {
    display: flex;
    align-items: center;
    gap: 30px;
    flex-wrap: wrap;
}

#about img {
    border-radius: 50%;
    width: 150px;
    height: 150px;
    object-fit: cover;
    box-shadow: 0 2px 8px rgba(0,0,0,0.2);
}

.project {
    margin-bottom: 20px;
}

footer {
    background-color: #0d47a1;
    color: white;
    text-align: center;
    padding: 15px 0;
}

h1, h2, h3 {
    color: #0d47a1;
}

a {
    color: #0d47a1;
}

@media (max-width: 600px) {
    #about {
        flex-direction: column;
        text-align: center;
    }
}

```

## OUTPUT
<img width="1912" height="692" alt="image" src="https://github.com/user-attachments/assets/eee6841d-cad1-49bb-bbf1-9543a5aeac23" />
<img width="1911" height="886" alt="image" src="https://github.com/user-attachments/assets/fabfd6f1-2e24-4b6a-af67-4fd3552aae8b" />
<img width="1906" height="881" alt="image" src="https://github.com/user-attachments/assets/806df6f9-8ede-49ee-a123-75ad3f7cd5d2" />
<img width="1905" height="881" alt="image" src="https://github.com/user-attachments/assets/45564bfb-cac2-4149-a89a-85c957fdb862" />
<img width="1919" height="877" alt="image" src="https://github.com/user-attachments/assets/85d7fc6c-55d9-4d27-848e-cc678f49d14e" />

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
