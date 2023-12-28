<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cultural Events</title>
    <style>
        /* Your styles go here */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }

        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1em;
            position: relative;
        }

        header img {
            max-width: 80px; /* Adjust the size as needed for passport size */
            height: auto;
            position: absolute;
            left: 1em;
            top: 50%;
            transform: translateY(-50%);
        }

        nav {
            background-color: #444;
            padding: 1em;
            text-align: center;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            padding: 1em;
            margin: 0 1em;
            transition: color 0.3s ease-in-out;
        }

        nav a:hover {
            color: #57a0d3;
        }

        main {
            padding: 2em;
        }

        .event {
            border: 1px solid #ddd;
            margin-bottom: 1em;
            padding: 1em;
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: #333;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1em;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>

<body>
    <header>
        <img src="your-logo.png" alt="Logo">
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
            <h2>Event Title 1</h2>
            <p>Date: January 1, 2024</p>
            <p>Location: City, Country</p>
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
