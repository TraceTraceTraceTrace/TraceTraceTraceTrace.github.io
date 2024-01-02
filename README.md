<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Text Processing Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }

        input {
            padding: 10px;
            margin-right: 10px;
        }

        button {
            padding: 10px;
            cursor: pointer;
        }
    </style>
</head>

<body>
    <h1>Text Processing Website</h1>
    <label for="textInput">Paste table from Order History, start from Transaction Number and end with the last Total:</label>
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
