# dafero753.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Presentation</title>
    <link href="https://fonts.googleapis.com/css?family=Pacifico&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Indie+Flower&display=swap" rel="stylesheet">
    <style>
        .body{
            background-color: black;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .position{
            width: 80%;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;
            background-image: url("https://images.pexels.com/photos/1330218/pexels-photo-1330218.jpeg?cs=srgb&dl=body-of-water-1330218.jpg&fm=jpg");
            background-size: 100%;
            background-repeat: no-repeat;
            overflow: hidden;   
        }

        .name, .location{
            color: green
        }
        .image{
            
            width: 200px;
            height: 200px;
            border-radius:150px;
            border: solid 5px white;
        }
        .name{
            color: whitesmoke;
            font-family: 'Pacifico', cursive;
        }
        .location{
            color: whitesmoke;
            font-family: 'Indie Flower', cursive;
        }
    </style>
</head>
<body class="body">
    <div class="position">
        <img class="image" src="mineBW.jpeg" />
        <div class="name">
            <h1>Daniel Romero</h1>
        </div>
        <div class="location">
            <h3>Envigado, Antioquia, Colombia</h3>
        </div>
    </div>
</body>
</html>
