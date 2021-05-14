<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
    <title>Avengers</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Girassol&display=swap');
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body:not(h1) {
            height: 100vh;
            font-family: 'Girassol', cursive;
            background-color: #d8d8d8;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        
        .cards {
            display: flex;
            flex-direction: row;
            justify-content: space-between;
            flex-wrap: wrap;
        }
        
        .card {
            height: 270px;
            min-width: 250px;
            width: 470px;
            background: linear-gradient(45deg, #0c0200, #2f3131);
            box-shadow: rgba(0, 0, 0, 0.15) 0px 5px 15px 0px;
            position: relative;
            border-radius: 20px;
            padding-left: 20px;
            color: rgb(228, 187, 5);
            border: 0;
            transition: all 0.2s;
            margin-right: 120px;
        }
        
        .card img {
            height: 370px;
            max-width: 100%;
            position: absolute;
            top: 30%;
            left: 59%;
            transform: translate(-50%, -50%);
            transition: all 0.2s;
        }
        
        .card h2 {
            margin-top: 20px;
            color: #e5aa1d;
            transition: all 0.2s;
        }
        
        .card a {
            font-family: Arial;
            text-decoration: none;
            text-transform: uppercase;
            color: #0c0200;
            background-color: #e5aa1d;
            padding: 5px 10px;
            border-radius: 5px;
            font-weight: bold;
            cursor: pointer;
            transition: all 0.2s;
            opacity: 0;
        }
        
        .card a:hover {
            color: #0c0200;
            background-color: #fff;
        }
        
        .card p {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            width: 200px;
            margin-bottom: 25px;
            color: #fff;
            transition: all 0.2s;
            opacity: 0;
        }
        
        .card:hover img {
            left: 82%;
            height: 400px;
            top: 40%;
        }
        
        .card:hover h2 {
            font-size: 40px;
            margin-bottom: 15px;
            letter-spacing: 2px;
        }
        
        .card:hover a,
        .card:hover p {
            opacity: 1;
        }
        
        .captain {
            background: linear-gradient(45deg, #212531, #3E4966);
        }
        
        .captain img {
            height: 360px;
            max-width: 100%;
            position: absolute;
            top: 40%;
            left: 78%;
            transform: translate(-50%, -50%);
            transition: all 0.2s;
        }
        
        .captain:hover img {
            left: 97%;
            height: 400px;
            top: 36%;
        }
        
        .Ironman {
            background: linear-gradient(45deg, #952528, #c84648);
        }
        
        .Ironman img {
            height: 370px;
            max-width: 100%;
            position: absolute;
            top: 30%;
            left: 52%;
            transform: translate(-50%, -50%);
            transition: all 0.2s;
        }
        
        .Ironman:hover img {
            left: 69%;
            height: 400px;
            top: 36%;
        }
    </style>
</head>

<body>
    <div class="cards">
        <div class="card">
            <div class="content">
                <h2>Black Panthar</h2>
                <p>We miss you, You will be always in our heart. Dolor sit amet, Consec incididunt ut aliqua.</p>
                <a href="#">Read more</a>
            </div>
            <img src="./Marvel-Black-Panther-PNG-Transparent-Images.png" alt=" ">
        </div>
        <div class="card captain">
            <div class="content">
                <h2 style="color:#fff">Captain America</h2>
                <p style="color:#f5da92">We miss you, You will be always in our heart. Dolor sit amet, Consec incididunt ut aliqua.</p>
                <a style="background-color: #fff" href="#">Read more</a>
            </div>
            <img src="./Captain.png" alt=" ">
        </div>
        <div class="card Ironman">
            <div class="content">
                <h2 style="color:#ffbb00">Iron man</h2>
                <p>We miss you, You will be always in our heart. Dolor sit amet, Consec incididunt ut aliqua.</p>
                <a href="#">Read more</a>
            </div>
            <img src="./IronMan.png" alt=" ">
        </div>
    </div>

    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js " integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN " crossorigin="anonymous "></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js " integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q " crossorigin="anonymous "></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js " integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl " crossorigin="anonymous "></script>
</body>

</html>
