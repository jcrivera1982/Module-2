<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        .container {
            width: 960px;
            margin: 0 auto;
            height: 500px;
        }
        .box {
            display: inline-block;
            width: 300px;
            height: 200px;
            margin-right: 30px; 
            background-color: gray; 
            border: 2px solid black; 
            color: white; 
            text-align: top right; 
            line-height: 200px; 
        }
        .box1 { background-color: gray; text-align: top right;}
        .box2 { background-color: gray; text-align: top right;}
        .box3 { background-color: gray; margin-right: 0; text-align: top right;}
    </style>
</head>
<body>
    <h1>Our Menu</h1>
    <div class="container">
        <div class="box box1">Chicken</div>
        <div class="box box2">Beef</div>
        <div class="box box3">Sushi</div>
    </div>
</body>
</html>
