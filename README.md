<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Tiago Rodrigues - Web Developer passionate about AI, Quantum Computing, Cybersecurity, and more.">
    <meta name="author" content="Tiago Rodrigues">
    <meta name="keywords" content="Web Developer, AI, Quantum Computing, Cybersecurity, E-Commerce">
    <meta property="og:title" content="Tiago Rodrigues - My Career in Tech">
    <title>Tiago Rodrigues - My Career in Tech</title>

    <!-- Link to external CSS file -->
    <link rel="stylesheet" href="styles.css">

    <!-- Google Analytics -->
    <script async src="https://www.googletagmanager.com/gtag/js?id=G-C0QKL2DHTM"></script>
    <script>
        window.dataLayer = window.dataLayer || [];
        function gtag(){dataLayer.push(arguments);}
        gtag('js', new Date());
        gtag('config', 'G-C0QKL2DHTM');
    </script>
</head>
<body>

    <header>
        <h1>Welcome.</h1>
    </header>

    <nav>
        <ul>
            <li><a href="#about">About Me</a></li>
            <li><a href="#languages">Languages</a></li>
            <li><a href="#interests">Interests</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- English Content Block -->
    <section id="english">
        <h2>About Me</h2>
        <p>With the aim of becoming a Java software developer, I am investing my resources to learn Java 21SE and plan to pursue the Oracle Java Professional Certification in the upcoming months.</p>

        <h2>Languages</h2>
        <p>English: B2</p>
        <p>German: B2</p>
        <p>Spanish: Basic</p>
        <p>Japanese: Basic</p>

        <h2>Interests</h2>
        <p>Currently, I am focused on mastering the Java 21 language and its new features, integrating with modern Front-End technologies to build robust backends, AI and Machine Learning integration through libraries like Deeplearning4j, Weka, and Apache Spark, writing energy-efficient code, and becoming more active in the Java community through forums or even Open Source Projects.</p>

        <h2>Contact</h2>
        <p>Email: <a href="mailto:tiago.rodrigues2@yahoo.com">tiago.rodrigues2@yahoo.com</a></p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/tiago-r-074105226/" target="_blank" rel="noopener noreferrer">Tiago Rodrigues</a></p>

        <h3>Contact Form</h3>
        <form id="contact-form">
            <label for="name">Your Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Your Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="4" required></textarea>

            <p>If you’ve come to my website, feel free to leave a "Hi" along with your LinkedIn link. Let’s connect!</p>

            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>Powered by Google Analytics to collect information on page views, scrolls, outbound clicks, form interactions, and more. For more details, check our Privacy Policy.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
