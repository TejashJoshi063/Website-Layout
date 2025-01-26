# Website-Layout
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Layout</title>
    <style>
        * {
            margin: 0;
            padding: 0;
        }
        .navbar {
            height: 70px;
            background-color: black;
            color: white;
        }
        .navbar ul {
            list-style-type: none;
            padding: 0;
            display: flex;
        }
        .navbar ul li {
            margin-right: 10px;
        }
        .navbar ul li a {
            color: white;
            text-decoration: none;
        }
        .container {
            display: flex;
        }
        .left, .right {
            height: 60vh;
            width: 50%;
        }
        .left {
            background-color: red;
            display: none;
        }
        .right {
            background-color: green;
        }
        header {
            font-family: cursive;
            background-color: black;
            color: white;
            text-align: center;
            padding: 10px;
        }
        footer {
            font-family: cursive;
            background-color: black;
            color: white;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>
    <div class="navbar">
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </div>
    <div class="container">
        <div class="left"></div>
        <div class="right"></div>
    </div>
    <footer>Copyright &copy; Website Layout - All rights reserved</footer>
</body>
</html>
