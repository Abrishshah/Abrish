# Abrish
Guest post,backlinks
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Guest Posting & Link Insertion Services</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Guest Posting & Link Insertion Services</h1>
        <p>Boost your SEO with high-quality backlinks</p>
    </header>

    <section id="services">
        <h2>Our Services</h2>
        <ul>
            <li>Guest Posting on High DA Websites</li>
            <li>Link Insertion in Existing Articles</li>
            <li>High-Quality Backlinks</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form id="contact-form">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            
            <button type="submit">Submit</button>
        </form>
        <div id="form-message"></div>
    </section>

    <footer>
        <p>&copy; 2024 Guest Posting & Link Insertion Services</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    color: #333;
}

header {
    background: #333;
    color: #fff;
    padding: 1em 0;
    text-align: center;
}

header h1 {
    margin: 0;
}

section {
    padding: 2em;
    margin: 2em 0;
    border-bottom: 1px solid #ccc;
}

h2 {
    color: #333;
}

ul {
    list-style-type: none;
    padding: 0;
}

ul li {
    background: #f4f4f4;
    margin: 0.5em 0;
    padding: 0.5em;
}

form {
    display: flex;
    flex-direction: column;
}

form label {
    margin: 0.5em 0 0.2em;
}

form input,
form textarea {
    padding: 0.5em;
    margin-bottom: 1em;
    border: 1px solid #ccc;
    border-radius: 4px;
}

form button {
    padding: 0.7em;
    background: #333;
    color: #fff;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

form button:hover {
    background: #555;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1em 0;
}
document.getElementById('contact-form').addEventListener('submit', function(event) {
    event.preventDefault();
    
    const name = document.getElementById('name').value;
    const email = document.getElementById('email').value;
    const message = document.getElementById('message').value;
    
    const formMessage = document.getElementById('form-message');
    
    formMessage.innerHTML = `<p>Thank you, ${name}. We have received your message and will get back to you at ${email} soon.</p>`;
    
    // Clear the form
    document.getElementById('contact-form').reset();
});
