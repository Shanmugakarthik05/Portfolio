# Ex01 Portfolio
## Date:10/03/2025

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
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Resume</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="resume">
        <!-- Page 1 -->
        <section class="page">
            <header>
                <div class="header-content">
                    <div class="profile-image">
                        <img src="SK.png" alt="Profile Photo">
                    </div>
                    <div class="text-content">
                        <h1>SHANMUGAKARTHIK G</h1>
                        <p>Android Developer</p>
                        <p>Email: shanmugakarthik2005@gmail.com | Phone: 9445654236</p>
                        <p>LinkedIn: linkedin.com/in/shanmugakarthik | GitHub: github.com/shanmugakarthik05</p>
                    </div>
                </div>
            </header>
            <hr>
            <section>
                <h2>Skills</h2>
                <ul>
                    <li>Android Development</li>
                    <li>REST API Integration</li>
                    <li>UI/UX Design</li>
                </ul>
            </section>
            <section>
                <h2>Experience</h2>
                <h3>Android Developer | ABC Tech</h3>
                <p>MARCH 2025 - Present</p>
                <ul>
                    <li>Developed and maintained Android applications.</li>
                    <li>Implemented REST API integration.</li>
                    <li>Enhanced UI/UX for better user experience.</li>
                </ul>
                <h3>Intern | SK Solutions</h3>
                <p>Jan 2023 - May 2024</p>
                <ul>
                    <li>Worked on mobile app development projects.</li>
                    <li>Assisted in debugging and testing.</li>
                </ul>
            </section>
        </section>
        
        <!-- Page 2 -->
        <section class="page">
            <section>
                <h2>Projects</h2>
                <h3>Expense Tracker App</h3>
                <p>Built an Android app to track expenses with charts and analytics.</p>
               
            </section>
            <section>
                <h2>Education</h2>
                <h3>Bachelor of Technology - Information Technology</h3>
                <p>Saveetha University | 2023 - 2027</p>
            </section>
        </section>
    </div>
</body>
</html>

<style>
    body {
        font-family: 'Poppins', sans-serif;
        margin: 0;
        padding: 20px;
        background: url('BG.avif') no-repeat center center fixed;
        background-size: cover;
        color: #ffffff;
    }
    .resume {
        width: 800px;
        margin: auto;
        background: url('resume-bg.jpg') no-repeat center center;
        background-size: cover;
        padding: 20px;
        border-radius: 10px;
        box-shadow: 0px 0px 20px rgba(5, 5, 5, 0.1);
    }
    .page {
        border: 1px solid #ffffff;
        padding: 20px;
        margin-bottom: 20px;
        background: url('page-bg.jpg') no-repeat center center;
        background-size: cover;
        border-radius: 10px;
    }
    h1 {
        margin-bottom: 5px;
        font-size: 32px;
        color: #00d4ff;
    }
    hr {
        border: 1px solid #00d4ff;
    }
    ul {
        list-style-type: square;
    }
    .header-content {
        display: flex;
        align-items: center;
        justify-content: space-between;
        padding: 20px;
        background: #0e000000;
        border-radius: 10px;
        box-shadow: 0px 0px 15px rgba(244, 7, 7, 0.5);
    }
    .profile-image img {
        width: 120px;
        height: 120px;
        border-radius: 50%;
        border: 3px solid #ff0000;
    }
    .text-content {
        flex: 1;
        text-align: center;
    }
    h2 {
        color: #00fbff;
    }
</style>

~~~

## OUTPUT
![alt text](image.png)
![alt text](<image copy.png>)

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
