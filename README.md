# Nice-
About app
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Age Calculator</title>
</head>
<body>
    <div class="container">
        <h1>Age Calculator</h1>
        <form id="age-form">
            <label for="birthdate">Enter your birthdate:</label>
            <input type="date" id="birthdate" name="birthdate" required>
            <button type="submit">Calculate Age</button>
        </form>
        <div id="result"></div>
    </div>
    <script src="script.js"></script>
</body>
</html>


css
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
}

.container {
    background-color: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    text-align: center;
}

h1 {
    margin-bottom: 20px;
}

form {
    margin-bottom: 20px;
}

label {
    display: block;
    margin-bottom: 10px;
}

input[type="date"] {
    padding: 10px;
    width: 100%;
    box-sizing: border-box;
    margin-bottom: 20px;
}

button {
    padding: 10px 20px;
    background-color: #007BFF;
    color: #fff;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

button:hover {
    background-color: #0056b3;
}

#result {
    font-size: 1.2em;
    font-weight: bold;
}
