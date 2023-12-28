<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cultural Events</title>
    <style>
        /* Reset some default styles */
        body, h1, h2, p {
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f8f8f8;
            color: #333;
            line-height: 1.6;
        }

        header {
            background-color: #2c3e50;
            color: #ecf0f1;
            text-align: center;
            padding: 2em 0;
            position: relative;
        }

        header img {
            max-width: 30px; /* Adjust the max-width as needed */
            height: auto;
            position: absolute;
            left: 1em;
            top: 50%;
            transform: translateY(-50%);
        }

        header h1 {
            font-size: 2.5em;
            margin-top: 0.5em;
        }

        nav {
            background-color: #34495e;
            padding: 1em 0;
            text-align: center;
        }

        nav a {
            color: #ecf0f1;
            text-decoration: none;
            padding: 1em;
            margin: 0 1em;
            font-size: 1.2em;
            transition: color 0.3s ease-in-out;
        }

        nav a:hover {
            color: #3498db;
        }

        main {
            padding: 2em;
        }

        .event {
            border: 1px solid #bdc3c7;
            margin-bottom: 1.5em;
            padding: 1.5em;
            background-color: #ecf0f1;
            border-radius: 5px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: #2c3e50;
            font-size: 1.8em;
            margin-bottom: 0.5em;
        }

        footer {
            background-color: #2c3e50;
            color: #ecf0f1;
            text-align: center;
            padding: 1.5em 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>

<body>
    <header>
        <img src="cultural.jpg">
        <h1>Cultural Events</h1>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">Events</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
    </nav>

    <main>
        <div class="event">
            <h2>Alaap</h2>
            <p>Date: February 03-04, 2024</p>
            <p>Location: PJAB auditorium, Indian Statistical Institute, Kolkata</p>
            <p>Description: Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </div>

        <div class="event">
            <h2>Event Title 2</h2>
            <p>Date: February 15, 2024</p>
            <p>Location: Another City, Country</p>
            <p>Description: Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </div>

        <!-- Add more events as needed -->

    </main>

    <footer>
        &copy; 2023 Your Website Name. All rights reserved.
    </footer>
</body>

</html>
