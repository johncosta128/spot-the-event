<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Find Events Near You</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Find Events Near You</h1>
    </header>

    <main>
        <div id="location-container">
            <button onclick="getLocation()">Find Events Near Me</button>
            <p id="location-info"></p>
        </div>
        
        <div id="events-list">
            <!-- Events will be displayed here -->
        </div>
    </main>

    <footer>
        <p>Powered by Event API</p>
    </footer>

    <script src="app.js"></script>
</body>
</html>
