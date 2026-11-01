# Practical-16-Theme-Based-Webpage-Using-CSS-Variables

<!DOCTYPE html>
<html>
<head>
    <title>CSS Variables</title>
    <style>
        :root {
            --primary: navy;
            --secondary: lightblue;
            --space: 20px;
            --radius: 12px;
        }

        body {
            font-family: Arial;
            background: var(--secondary);
        }

        .card {
            background: white;
            padding: var(--space);
            margin: var(--space);
            border-radius: var(--radius);
            border: 2px solid var(--primary);
        }

        h1 {
            color: var(--primary);
        }

        button {
            background: var(--primary);
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: var(--radius);
        }
    </style>
</head>
<body>
    <div class="card">
        <h1>My College</h1>
        <p>Welcome to our college website.</p>
        <button>Learn More</button>
    </div>
</body>
</html>
