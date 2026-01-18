# Advanced-GPS-agritech-website
It detects pits and muddy road and provides safe roots
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Advanced GPS Agritech System</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f4f7f6;
            color: #333;
        }

        header {
            background: linear-gradient(135deg, #2e8b57, #4CAF50);
            color: white;
            padding: 50px 20px;
            text-align: center;
        }

        nav {
            background: #1f6f43;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        section {
            padding: 40px 20px;
            max-width: 1000px;
            margin: auto;
        }

        h2 {
            color: #2e8b57;
            text-align: center;
        }

        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            text-align: center;
        }

        #map {
            width: 100%;
            height: 400px;
            background: #ccc;
            border-radius: 10px;
        }

        .alert {
            background: #fff3cd;
            border-left: 5px solid #ffc107;
            padding: 15px;
            margin-top: 20px;
            border-radius: 5px;
        }

        footer {
            background: #1f6f43;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 40px;
        }

        @media (max-width: 600px) {
            header h1 {
                font-size: 1.8em;
            }
        }
    </style>
</head>

<body>

<header>
    <h1>Advanced GPS Agritech System</h1>
    <p>Smart Navigation & Road Safety for Rural and Agricultural Areas</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#features">Features</a>
    <a href="#map-section">Live Map</a>
    <a href="#alerts">Alerts</a>
    <a href="#contact">Contact</a>
</nav>

<section id="home">
    <h2>About the Project</h2>
    <p>
        The Advanced GPS Agritech System is designed to improve rural road safety
        and agricultural transportation using GPS technology. It detects road
        issues such as pits and rough surfaces and alerts drivers in advance.
    </p>
</section>

<section id="features">
    <h2>Key Features</h2>
    <div class="features">
        <div class="card">
            <h3>Live GPS Tracking</h3>
            <p>Track vehicles and farm equipment in real time.</p>
        </div>
        <div class="card">
            <h3>Pothole Detection</h3>
            <p>Detect road pits and damaged rural roads.</p>
        </div>
        <div class="card">
            <h3>Smart Alerts</h3>
            <p>Get instant notifications on mobile or web.</p>
        </div>
        <div class="card">
            <h3>Rural Development</h3>
            <p>Helps authorities plan road maintenance efficiently.</p>
        </div>
    </div>
</section>

<section id="map-section">
    <h2>Live GPS Map</h2>
    <div id="map">
        <p style="text-align:center; padding-top:180px;">
            Map will load here (Google Maps API)
        </p>
    </div>
</section>

<section id="alerts">
    <h2>Recent Alerts</h2>
    <div class="alert">
        ⚠️ Pothole detected 500m ahead on rural road.
    </div>
    <div class="alert">
        ⚠️ Rough road condition reported near farm area.
    </div>
</section>

<section id="contact">
    <h2>Contact</h2>
    <p style="text-align:center;">
        Email: agrigps@gmail.com <br>
        Phone: +91 98765 43210
    </p>
</section>

<footer>
    <p>© 2026 Advanced GPS Agritech Project | Student Innovation</p>
</footer>

</body>
</html>
