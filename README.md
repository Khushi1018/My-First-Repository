# My First Repository

This is my first repository where I am experimenting with HTML and CSS.

## Project Description

This project demonstrates how to use a custom font from Google Fonts and apply it to a simple webpage.

## Files

1. **index.html**: Contains the structure of the webpage.
2. **styles.css**: Contains the styling for the webpage including the custom font.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repository-name.git

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Linking Google Font (Roboto) -->
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>Welcome to My First Repository</h1>
    <p>This is a simple example of how to use a custom font in your project.</p>
</body>
</html>

/* Apply Google Font to the whole body */
body {
    font-family: 'Roboto', sans-serif;
    background-color: #f4f4f9;
    margin: 0;
    padding: 20px;
}

h1 {
    color: #333;
    font-weight: 700;  /* Bold font weight */
    text-align: center;
}

p {
    color: #555;
    font-weight: 400;  /* Normal font weight */
    font-size: 1.2em;
    text-align: center;
}

