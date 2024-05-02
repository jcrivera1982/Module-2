<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <title>Our Menu</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            margin: 2%;
            justify-content: center;
            overflow: hidden;
        }
        .box-wrapper {
            height: 95vh;
            width: 100%;
            display: flex;
            flex-direction: column;
            text-align: center;
        }
        .box {
            padding: 10px;
            border: solid 1px green;
        }
    </style>
</head>
<body>
    <div class="box-wrapper">
        <div class="box" id="box1">Box 1</div>
        <div class="box" id="box2">Box 2</div>
        <div class="box" id="box3">
            <div id="box4">Box 4</div>
            <div class="middle-column">
                <div id="box5">Box 5</div>
                <div id="box6">Box 6</div>
                <div id="box7">Box 7</div>
            </div>
            <div id="box8">Box 8</div>
        </div>
    </div>
</body>
</html>
