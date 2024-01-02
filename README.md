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
            display: flex;
            flex-direction: column;
            align-items: flex-start;
            flex-wrap: wrap; /* Allow items to wrap to the next line */
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
    <label for="textInput">Enter Text:</label>
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
