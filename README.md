# hello-world
//duniya ko mera namaskar ,, bangalore se
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hello Namaskar from Bangalore</title>
    <script>
        function displayMessage() {
            var userName = document.getElementById("username").value;
            var outputElement = document.getElementById("output");

            if (userName === "jujuii" || userName === "bubuii") {
                outputElement.innerHTML = "Namaskar kaise hai aap";
            } else if (userName === "jujuii") {
                outputElement.innerHTML = "I love you jujuii from bubuii";
            } else {
                outputElement.innerHTML = "Hello Namaskar from Bangalore";
            }
        }
    </script>
</head>
<body>
    <h1>Hello Namaskar from Bangalore</h1>
    <label for="username">Enter your username: </label>
    <input type="text" id="username" placeholder="Enter your username">
    <button onclick="displayMessage()">Submit</button>
    <p id="output"></p>
</body>
</html>
