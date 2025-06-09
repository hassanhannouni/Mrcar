<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mr. Car - Car Dispatching Service</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#vehicles">Vehicles</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h1>Welcome to Mr. Car</h1>
        <p>Your trusted partner for car dispatching services across Morocco.</p>
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <ul>
            <li>Door-to-Door Delivery</li>
            <li>Vehicle Transport</li>
        </ul>
    </section>

    <section id="vehicles">
        <h2>Vehicle Types</h2>
        <p>We specialize in transporting small cars such as sedans, hatchbacks, and compact SUVs.</p>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form action="submit_form.php" method="POST">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Mr. Car. All rights reserved.</p>
    </footer>
</body>
</html># Mr. Car 🚗

**Mr. Car** is a car dispatching service based in Morocco, offering reliable and professional door-to-door vehicle transport.

## 🌟 Features

- 🚙 Door-to-door car delivery
- 🚐 Small vehicle transport (sedans, hatchbacks, compact SUVs)
- 📨 Contact form for customer inquiries

## 🛠️ Technologies Used

- HTML5
- CSS3
- PHP (for contact form submission)

## 📂 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/hassanhannouni/Mrcar.git
