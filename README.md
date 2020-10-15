<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>
    <p style="font-size: xx-large;"></p>
    <button type="button" onclick="display()">Click Me</button>
    <script>
        function display() {
            console.log("ad")
            document.querySelector('p').innerText = "Hello World";
        }
    </script>
</body>

</html>
