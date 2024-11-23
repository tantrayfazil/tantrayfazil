<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Before Kashmir - News Articles</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>Before Kashmir</h1>
            <p>Your Source for Authentic News</p>
        </div>
        <nav>
            <ul class="navbar">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#articles">Articles</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <div class="container">
            <h2>Welcome to Before Kashmir</h2>
            <p>Stay informed with the latest and most reliable news updates from Jammu & Kashmir and beyond.</p>
        </div>
    </section>

    <section id="about">
        <div class="container">
            <h2>About Us</h2>
            <p>Before Kashmir is an independent news platform committed to delivering unbiased and authentic news articles. Our mission is to amplify voices from the region and promote journalistic integrity.</p>
        </div>
    </section>

    <section id="articles">
        <div class="container">
            <h2>Latest Articles</h2>
            <div class="article">
                <h3>Breaking: Key Developments in South Kashmir</h3>
                <p>A detailed report on recent events shaping the political and social landscape of South Kashmir.</p>
                <a href="#">Read More</a>
            </div>
            <div class="article">
                <h3>Community Voices: Stories That Matter</h3>
                <p>Highlighting the challenges and triumphs of local communities in Jammu & Kashmir.</p>
                <a href="#">Read More</a>
            </div>
            <div class="article">
                <h3>Opinion: The Role of Youth in Journalism</h3>
                <p>An insightful analysis of how young journalists are transforming the media landscape in the region.</p>
                <a href="#">Read More</a>
            </div>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" placeholder="Your Name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" placeholder="Your Email" required>
                
                <label for="message">Message:</label>
                <textarea id="message" name="message" placeholder="Your Message" required></textarea>
                
                <button type="submit">Submit</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Before Kashmir. All Rights Reserved.</p>
        </div>
    </footer>
</body>
</html>
/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    color: #333;
    line-height: 1.6;
    background-color: #f9f9f9;
}

.container {
    width: 80%;
    margin: auto;
    overflow: hidden;
}

/* Header Styles */
header {
    background: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 2.5rem;
}

header p {
    font-size: 1rem;
}

.navbar {
    display: flex;
    justify-content: center;
    list-style: none;
    padding: 10px 0;
    background: #444;
    margin: 0;
}

.navbar li {
    margin: 0 15px;
}

.navbar a {
    color: #fff;
    text-decoration: none;
    font-size: 1rem;
}

.navbar a:hover {
    color: #00bcd4;
}

/* Section Styles */
section {
    padding: 20px 0;
}

section h2 {
    font-size: 1.8rem;
    text-align: center;
    margin-bottom: 20px;
}

.article {
    background: #fff;
    border: 1px solid #ddd;
    padding: 15px;
    margin-bottom: 20px;
    border-radius: 5px;
}

.article h3 {
    margin: 0 0 10px;
}

.article a {
    color: #00bcd4;
    text-decoration: none;
}

.article a:hover {
    text-decoration: underline;
}

/* Form Styles */
form {
    max-width: 500px;
    margin: auto;
    display: flex;
    flex-direction: column;
}

form label {
    margin: 10px 0 5px;
}

form input, form textarea, form button {
    padding: 10px;
    margin-bottom: 15px;
}

form input, form textarea {
    width: 100%;
    border: 1px solid #ccc;
    border-radius: 5px;
}

form button {
    background: #00bcd4;
    color: #fff;
    border: none;
    cursor: pointer;
}

form button:hover {
    background: #019bab;
}

/* Footer */
footer {
    text-align: center;
    padding: 10px;
    background: #333;
    color: #fff;
}
