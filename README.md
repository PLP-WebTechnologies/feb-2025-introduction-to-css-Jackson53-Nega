
📌 index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Webpage</title>
    <link rel="stylesheet" href="style.css"> <!-- Linking external CSS -->
</head>
<body>

    <header id="main-header">
        <h1>Welcome to My Styled Page</h1>
    </header>

    <section class="content">
        <p class="intro">This is a sample webpage with external CSS styling.</p>
        <img src="image.jpg" alt="Sample Image" class="styled-image">
    </section>

    <footer>
        <p>&copy; 2025 My Website</p>
    </footer>

</body>
</html>

🎨 style.css

/* 1. Styling using an ID selector */
#main-header {
    background-color: #3498db;
    color: white;
    text-align: center;
    padding: 20px;
    font-family: Arial, sans-serif;
}

/* 2. Styling using a class selector */
.intro {
    font-size: 18px;
    color: #2c3e50;
    margin: 20px;
    padding: 10px;
    border-left: 5px solid #3498db;
}

/* 3. Styling an image */
.styled-image {
    width: 300px;
    height: auto;
    border: 5px solid #2ecc71;
    padding: 10px;
    display: block;
    margin: 20px auto;
    border-radius: 10px;
}

/* General styling for better readability */
body {
    font-family: "Georgia", serif;
    background-color: #ecf0f1;
    margin: 0;
    padding: 0;
    text-align: center;
}

footer {
    background-color: #2c3e50;
    color: white;
    padding: 10px;
    margin-top: 20px;
}

