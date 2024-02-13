<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Will You Be My Valentine?</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
            background-size: cover;
            background-position: center;
            transition: background-image 0.5s ease;
            overflow: hidden;
        }
        h1 {
            color: #e60000;
            margin-top: 100px;
        }
        p {
            font-size: 18px;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            background-color: #e60000;
            color: #fff;
            border: none;
            cursor: pointer;
            border-radius: 5px;
            margin: 10px;
        }
    </style>
</head>
<body>
    <h1>Dear Thin Yanant Thu,</h1>
    <p>Will you be my Valentine?</p>
    <button onclick="celebrate('yes')">Yes</button>
    <button onclick="commiserate('no')">No</button>

    <script>
        function celebrate(choice) {
            if (choice === 'yes') {
                document.body.style.backgroundImage = "url('C:/Users/ASUS/OneDrive/Pictures/gif/heart.gif')";
            }
        }

        function commiserate(choice) {
            if (choice === 'no') {
                document.body.style.backgroundImage = "url('C:/Users/ASUS/OneDrive/Pictures/gif/mud.gif')";
            }
        }
    </script>
</body>
</html>
