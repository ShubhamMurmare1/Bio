<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Shubham</h1>
        <p>Cloud/DevOps Engineer</p>
    </header>
    <section id="bio">
        <h2>Linux Associate with 3 years of experience in system administration. Currently, I'm upskilling in AWS and DevOps practices to enhance my cloud and automation skills.

</h2>
        <p>Brief introduction about yourself.</p>
    </section>
    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>AWS</li>
            <li>DevOps Tools</li>
            <li>Linux</li>
            <!-- Add more skills as needed -->
        </ul>
    </section>
    <section id="projects">
        <h2>Projects</h2>
        <ul>
            <li><a href="https://github.com/ShubhamMurmare1/project1">Project 1</a></li>
            <li><a href="https://github.com/ShubhamMurmare1/project2">Project 2</a></li>
            <!-- Add more projects as needed -->
        </ul>
    </section>
    <section id="contact">
        <h2>7887476477</h2>
        <p>Email: shubhammurmare1997@gmail.com</p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/shubham-murmare-a071a51b2">linkedin-profile</a></p>
    </section>
    <footer>
        <p>&copy; 2025 Shubham</p>
    </footer>

    <script>
    document.addEventListener('DOMContentLoaded', () => {
        const greeting = document.createElement('p');
        const hour = new Date().getHours();
        if (hour < 12) {
            greeting.textContent = 'Good Morning!';
        } else if (hour < 18) {
            greeting.textContent = 'Good Afternoon!';
        } else {
            greeting.textContent = 'Good Evening!';
        }
        document.querySelector('header').appendChild(greeting);
    });
</script>

</body>
</html>
