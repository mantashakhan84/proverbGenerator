<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>proverb Generator</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Proverb Generator</h1>
        
        <div class="proverb-buttons">
            <a href="#proverb1" class="proverb-button">Proverb 1</a>
            <a href="#proverb2" class="proverb-button">Proverb 2</a>
            <a href="#proverb3" class="proverb-button">Proverb 3</a>
            <a href="#proverb4" class="proverb-button">Proverb 4</a>
            <a href="#proverb5" class="proverb-button">Proverb 5</a>
        </div>

        <div id="proverb1" class="proverb">Actions speak louder than words</div>
        <div id="proverb2" class="proverb">Don’t judge a book by its cover</div>
        <div id="proverb3" class="proverb">The grass is always greener on the other side</div>
        <div id="proverb4" class="proverb">	Practice makes perfect</div>
        <div id="proverb5" class="proverb">Don’t put all of your eggs in one basket</div>
    </div>
</body>
</html>



*css*

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
    text-align: center;
}

.container {
    margin: 50px auto;
    padding: 20px;
    background: white;
    border-radius: 8px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    max-width: 400px;
}

h1 {
    font-size: 24px;
    margin-bottom: 20px;
}

.proverb-buttons {
    margin-bottom: 20px;
}

.proverb-button {
    padding: 10px 15px;
    margin: 5px;
    border: none;
    border-radius: 5px;
    background-color: #007BFF;
    color: white;
    text-decoration: none;
    cursor: pointer;
    display: inline-block;
    transition: background 0.3s;
}

.proverb-button:hover {
    background-color: #0056b3;
}

.proverb {
    display: none;
    font-size: 18px;
    margin-top: 20px;
}

.proverb:target {
    display: block;
}

