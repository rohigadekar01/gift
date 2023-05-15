
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=Edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Happy birthday project</title>
  <style>
    body {
      height: 100vh;
      background-color: yellow;
    }

    .body {
      display: flex;
      align-items: center;
      justify-content: center;
      margin-top: 100px;
    }

    h2 {
      animation: 1s blink linear infinite;
      display: flex;
      justify-content: center;
    }

    .birthdayCard {
      position: relative;
      width: 250px;
      height: 350px;
      cursor: pointer;
      transform-style: preserve-3d;
      transform: perspective(2500px);
      transition: 1s;
    }

    .cardFront {
      position: relative;
      background-color: #fff;
      width: 250px;
      height: 350px;
      overflow: hidden;
      transform-origin: left;
      box-shadow: inset 100px 20px 100px rgba(0, 0, 0, .2), 30px 0 50px rgba(0, 0, 0, 0.4);
      transition: .6s;
    }

    .happy {
      font-family: Tahoma, sans-serif;
      text-align: center;
      margin: 30px;
      background-image: linear-gradient(120deg, #f6d365 0%, #fda085 100%);
      transition: .1s;
    }

    .balloons {
      position: absolute;
    }

    .balloonOne,
    .balloonTwo,
    .balloonThree,
    .balloonFour {
      position: absolute;
      width: 85px;
      height: 95px;
      border-radius: 50%;
    }

    .balloonOne {
      background-color: rgba(239, 71, 111, 0.7);
      left: -10px;
      top: 50px;
    }

    .balloonTwo {
      background-color: rgba(6, 214, 160, 0.7);
      left: 50px;
      top: 20px;
    }

    .balloonThree {
      background-color: rgba(255, 209, 102, 0.7);
      left: 110px;
      top: 50px;
    }

    .balloonFour {
      background-color: rgba(17, 138, 178, 0.7);
      left: 170px;
      top: 20px;
    }

    .balloonOne:before,
    .balloonTwo:before,
    .balloonThree:before,
    .balloonFour:before {
      content: "";
      position: absolute;
      width: 1px;
      height: 155px;
      background-color: #ffd166;
      top: 95px;
      left: 43px;
    }

    .balloonOne:after,
    .balloonTwo:after,
    .balloonThree:after,
    .balloonFour:after {
      content: "";
      position: absolute;
      border-right: 7px solid transparent;
      border-left: 7px solid transparent;
      top: 94px;
      left: 37px;
    }

  .balloonOne:after { 
border-bottom: 10px solid #ef476f;
}
 .balloonTwo:after {
 border-bottom: 10px solid #06d6a0;
}
 .balloonThree:after { 
border-bottom: 10px solid #ffd166;
} 
.balloonFour:after {
 border-bottom: 10px solid #118ab2;
} 
.cardInside {
 position: absolute; 
background-color: #fff; 
border: 2px solid yellowgreen; 
width: 250px; 
height:350px; 
z-index:-1; 
left:0; 
top:0;
 box-shadow: inset 100px 20px 100px rgba(0,0,0,0.2);
}
 p 
{
 font-family: cursive; 
margin: 40px;
 color: #333;
} 
.name { 
position: absolute; 
left:150px; 
top:200px; 
color: #333; 
text-decoration: underline;
}
 .back { 
font-family: Tahoma, sans-serif; 
color: #333;
 text-align: center; 
margin:30px; 
outline-color:#333; 
outline-style: dotted;
}
 .birthdayCard:hover {	
transform: perspective(2500px) rotate(5deg);	box-shadow: inset 100px 20px 100px rgba(0,0,0,.2), 0 10px 100px rgba(0,0,0,0.5);
}
 .birthdayCard:hover .cardFront { 
transform:rotateY(-160deg);
 } 
.birthdayCard:hover .happy { 
visibility:hidden; 
} 
@keyframes blink { 
0% { 
color: white; 
} 
20% { 
color: yellow;
 } 
40% { 
color: greenyellow; 
} 
60% { 
color: red; 
}
 80% { 
color: hotpink;
 }
 100% { 
color: blue; 
}}

.p1{
  font-family:Arial;
}
.name{
  font-family: arial;
}
.music{
  display:flex;
   align-content:center;
  margin:50px;
  background-color:skyblue;
}



</style>
<body>
 <h2>Click this card</h2>
<div class="body">
 <div class="birthdayCard">
<div class="cardFront"><h3 class="happy">HAPPY BIRTHDAY!</h3>
<div class="balloons">
  <div class="balloonOne"></div>
  <div class="balloonTwo"></div>
  <div class="balloonThree"></div>
  <div class="balloonFour"></div>
</div>
</div>
<div class="cardInside">
    <h3 class="back">HAPPY BIRTHDAY!</h3>
    <p>My love</p> 
    <p class="p1">Happy birthday!! I hope your day is filled with lots of love and laughter! May all of your birthday wishes come true.</p>
    <p class="name">Prachi</p>
  </div>
</div>

</div>
<div class="music">
<iframe width="560" height="150"  src="https://www.youtube.com/embed/xV9R7MGhDbo?start=3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

</div>

  <script src="main.js"></script>
</body>
</html>
