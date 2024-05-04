<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <style>
        .container {
            width: 960px;
            margin: 0 auto;
            height: 200px;
            text-align: center; 
        }
        .box {
            float: left; 
            width: 300px;
            height: 200px;
            margin-right: 0px;
            background-color: gray;
            border: 2px solid black;
            color: black;
            line-height: 200px; 
            padding: 10px
            text-align: top center;
        }
    @media (min-width: 768px) (max-width: 991px)
    @media (max-width: 767px) {.box {width: 100%;}
    </style>
</head>
<body>
     <h1 style="text-align: center;">Our Menu</h1>
    <div class="container">
        <div class="box">Chicken Lorem ipsum dolor sit amet, consectetur adipiscing elit.</div>
        <div class="box">Beef Lorem ipsum dolor sit amet, consectetur adipiscing elit.</div>
        <div class="box">Sushi Lorem ipsum dolor sit amet, consectetur adipiscing elit.</div>
    </div>
</body>
</html>
