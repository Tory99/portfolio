<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <title>Main</title>
        <link rel="stylesheet" href="./main.css">
    </head>
    <body>
        <h1>황정우</h1>
        <div id="txt_welcome">
            다시 시작하는 프로그래머 황정우입니다.<br>
            아직 모르는게 많지만 하고싶은게 많습니다.
        </div>
        <div style="display:grid; grid-template-columns: 1fr 1fr 1fr;">
            <div class="card">
                <img class="card_img" src="./img/map.png">
                <p class="card_title"> Red Racket </p>
                <input class="card_button" type="button" value="프로젝트 가기" onclick="location.href='./FirstProject'">
            </div>
            <div class="card">
                <img class="card_img" src="./img/trip.jpg">
                <p class="card_title"> Blue Racket </p>
                <input class="card_button" type="button" value="프로젝트 가기" onclick="location.href='./SecondProject'">
            </div>
            <div class="card">
                <img class="card_img" src="./img/pinball.jpg">
                <p class="card_title"> Black Racket </p>
                <input class="card_button" type="button" value="프로젝트 가기" onclick="location.href='./ThirdProject'">
            </div>
        </div>
    </body>
</html>
