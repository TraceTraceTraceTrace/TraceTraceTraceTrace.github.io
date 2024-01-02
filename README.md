<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Text Processing Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            align-items: flex-start; /* Align items to the start (top) 
        }

        input {
            padding: 10px;
            width: 500px; /* Set width to 500px */
            height: 500px; /* Set height to 500px */
            margin-right: 10px;
        }

        button {
            padding: 10px;
            cursor: pointer;
        }
    </style>
</head>

<body>
    <label for="textInput">Paste table from Order History, start from Transaction Number and end with the last Total:</label>
    </br>
    <input type="text" id="textInput" placeholder="Type something...">
    <button onclick="processText()">Process Text</button>
    <div id="output"></div>

    <script>
        function processText() {
            // Get the input value
            var inputValue = document.getElementById("textInput").value;

            // Process the input (you can replace this with your own processing logic)
            var processedOutput = "Processed: " + inputValue.toUpperCase();

            // Display the processed output
            document.getElementById("output").innerText = processedOutput;
        }
    </script>
</body>

</html>
