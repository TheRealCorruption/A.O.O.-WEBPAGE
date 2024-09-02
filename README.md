<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Agency Of Order (AOO) - Home</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to external CSS file -->
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #1e1e1e; /* Dark background for the page */
            color: #e0e0e0; /* Light text color */
            transition: background-color 1s;
        }
        .header {
            background-color: #121212; /* Darker header background */
            color: #ffffff; /* White text color in header */
            padding: 1rem 0;
            text-align: center;
        }
        .nav {
            text-align: center;
            margin-top: 1rem;
            background-color: #333333; /* Dark background for navigation */
            padding: 0.5rem 0;
        }
        .nav a {
            color: #ffffff; /* White text color for navigation links */
            margin: 0 1rem;
            text-decoration: none;
            font-weight: bold;
        }
        .nav a:hover {
            text-decoration: underline; /* Underline on hover */
        }
        .main-content {
            padding: 2rem;
            text-align: center;
        }
        .section {
            margin: 2rem 0;
            background-color: #2a2a2a; /* Dark background for sections */
            padding: 1rem;
            border-radius: 8px; /* Rounded corners for sections */
        }
        .footer {
            background-color: #121212; /* Darker footer background */
            color: #ffffff; /* White text color in footer */
            text-align: center;
            padding: 1rem 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .footer p {
            margin: 0;
        }
        .secret-text {
            color: white;
            font-size: 2em;
            display: none;
        }
        .glitch {
            display: inline-block;
            position: relative;
            font-weight: bold;
            color: #e0e0e0;
        }
        .glitch:before, .glitch:after {
            content: attr(data-text);
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            color: #ff0000;
            background: black;
            overflow: hidden;
            clip: rect(0, 900px, 0, 0);
        }
        .glitch:after {
            color: #0000ff;
            z-index: -1;
        }
        .input-container {
            margin-top: 20px;
            display: none;
        }
        #name-input {
            padding: 10px;
            font-size: 1.2em;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        #submit-button {
            padding: 10px 20px;
            font-size: 1.2em;
            background-color: #333;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        #submit-button:hover {
            background-color: #555;
        }
        #user-name-display {
            font-size: 2.5em;
            color: white;
            margin-top: 50px;
            display: none;
            text-align: center;
        }
    </style>
</head>
<body>
    <header class="header">
        <h1>Welcome to the Agency Of Order (AOO)</h1>
    </header>
    <nav class="nav">
        <a href="#about">About Us</a>
        <a href="#roles">Roles</a>
        <a href="#events">Events</a>
        <a href="#updates">Updates</a>
        <a href="#contact">Contact</a>
        <a href="https://docs.google.com/forms/d/e/1FAIpQLSeddokVRnRPZlgCl7QTDr-1BNHJhC5BXp4neeCvSi3a-r8_sg/viewform" target="_blank">Sign Up</a>
        <a href="https://therealcorruption.github.io/A.O.O.-TOS/" target="_blank">Terms Of Service</a>
    </nav>
    <div class="main-content">
        <section id="about" class="section">
            <h2>About Us</h2>
            <p>The Agency Of Order (AOO) is dedicated to maintaining peace and order within our community. Our unique approach combines transparency with discretion to create a harmonious environment for all members.</p>
        </section>
        <section id="roles" class="section">
            <h2>Roles and Structure</h2>
            <ul>
                <li><strong>Founders:</strong> Andrew, Alex B, Jaidyn Hopkins (Karma)</li>
                <li><strong>Secretaries:</strong> 4 Positions Available</li>
                <li><strong>Double Agents:</strong> 3 Positions</li>
                <li><strong>Members:</strong> Infinite Membership</li>
                <li><strong>Guards:</strong> 2 Positions</li>
                <li><strong>Headmasters:</strong> 2 Positions</li>
                <li><strong>Staff:</strong> 1-2 Positions</li>
            </ul>
        </section>
        <section id="events" class="section">
            <h2>Upcoming Events</h2>
            <ul>
                <li><strong>Training:</strong> Enhance skills and knowledge.</li>
                <li><strong>Field Day/Park-Day:</strong> Fun and interactive activities.</li>
                <li><strong>Gathering:</strong> Social and networking opportunities.</li>
            </ul>
        </section>
        <section id="updates" class="section">
            <h2>Update List</h2>
            <ul>
                <li><strong>August 2024:</strong> Launched the new member sign-up system.</li>
                <li><strong>August 2024:</strong> Updated the Terms Of Service with new policies.</li>
                <li><strong>August 2024:</strong> Introduced new event types for increased engagement.</li>
                <li><strong>August 2024:</strong> Created Invitations With Letters.</li>
                <li><strong>August 2024:</strong> Created a Discord server</li>
            </ul>
        </section>
        <section id="contact" class="section">
            <h2>Contact Us</h2>
            <p>For any inquiries or to get involved, please contact:</p>
            <p>Email: <a href="pumkintrue@gmail.com" style="color: #e0e0e0;">pumkintrue@gmail.com</a></p>
            <p>Phone: <a href="tel:+19713496861" style="color: #e0e0e0;">1+(971) 349-6861</a></p>
        </section>
    </div>
    <footer class="footer">
        <p>&copy; 2024 Agency Of Order (AOO). All rights reserved.</p>
    </footer>

    <!-- Hidden elements for secret event -->
    <div id="secret" class="secret-text">Hello, I am <span class="glitch" data-text="Nexi">Nexi</span>, Who are you?</div>
    <div class="input-container">
        <input type="text" id="name-input" placeholder="Enter your name">
        <button id="submit-button">Submit</button>
    </div>

    <div id="user-name-display"></div> <!-- Element to display the user's name -->

    <!-- Background music -->
    <audio id="bg-music" loop>
        <source src="https://www.youtube.com/embed/Bv5XwI5O7BQ?si=Jq2Xt0AAd0qwTIaO" type="audio/mp3">
        Your browser does not support the audio element.
    </audio>

    <script>
        // Function to trigger the secret event
        function triggerSecret() {
            document.body.style.backgroundColor = 'black';
            document.querySelector('.main-content').style.display = 'none';
            document.getElementById('secret').style.display = 'block';

            setTimeout(() => {
                document.querySelector('.input-container').style.display = 'block';
            }, 10000);

            document.getElementById('bg-music').volume = 0.15;
            document.getElementById('bg-music').play();

            glitchEffect();
            setInterval(glitchEffect, 3000);
        }

        // Function for the glitch effect on Nexi's name
        function glitchEffect() {
            const glitch = document.querySelector('.glitch');
            const originalText = glitch.getAttribute('data-text');
            const glitchChars = 'ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789';

            const randomizeText = () => {
                glitch.textContent = originalText.split('').map(letter => glitchChars.charAt(Math.floor(Math.random() * glitchChars.length))).join('');
            };

            const resetText = () => {
                glitch.textContent = originalText;
            };

            randomizeText();
            setTimeout(resetText, 500);
        }

        // Event listener for user input
        document.getElementById('submit-button').addEventListener('click', () => {
            const userName = document.getElementById('name-input').value.trim();
            if (userName) {
                document.getElementById('user-name-display').textContent = `Nice to meet you, ${userName}!`;
                document.getElementById('user-name-display').style.display = 'block';
            }
        });

        // Add your desired event to trigger the secret, e.g., click a specific area
        document.addEventListener('click', triggerSecret);
    </script>
</body>
</html>
