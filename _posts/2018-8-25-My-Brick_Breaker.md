---
layout: post
title: My Brick Breaker
---
{% asset 8_25_18_a.png width="50%" %}
This is a simple brick breaker clone we made during the first year in Berkeley

When Elvis, Khang, Denny and I were in <a href="https://calhacks3.devpost.com/">CalHacks 3.0</a>, we came up an idea to
create a web game. At the time of 2016, we were but just transfer student from De Anza
College to Berkeley, and know nothing besides basic programming language. We even have no
experience in front-end development such as web game.

At first, the game is designed as just a simply brick breaker clone, but we soon got bored,
resulting in playing with some fun element to our game. Since we were hacking at October, which is
a month before the election, we ended up in making fun with Donal Trump's election rhetoric. We turned the
brick as Trump's great wall. Each time the ball hits the "wall", the game will play Trump's unforgettable
"Wrong!" voice instead of ordinary sound of ball bouncing.

Here is the <a href="https://github.com/tinhangchui/myBrickBreaker">link</a> to the Github.


For those of you that hate to download from github and figure out how to run this thing, I have already moved the game to here:
<body onload="init();">
{% asset createjs.min.js %}
<canvas id="PongStage" width="500" height="600"></canvas>
{% asset break_the_wall.js %}
<div></div>
</body>

Press space to start the game. Use arrow key(left and right) to move the platform.
<br/>

<a href="javascript:history.back()">Back</a>
