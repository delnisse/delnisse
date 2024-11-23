import math - 👋 Hi, I’m @delnisse
import turtle
- configuracion inicial
- turtle.bgcolor black
- turtle.shape
- turtle.speed 0
  turtle.fillcolor bronw
- dibuja el tallo
- turtle.penup
- turtle.goto 0-200
- turtle.pedown
- turtle.begin_fill
- turtle.left 90
- turtle.forward 200
- tyrtle.left
- turtle.forward
- turtle.end_fill
- Código HTML:
html
Copiar código
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Girasol</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="sunflower">
    <div class="center"></div>
    <div class="petals">
      <div class="petal"></div>
      <div class="petal"></div>
      <div class="petal"></div>
      <div class="petal"></div>
      <div class="petal"></div>
      <div class="petal"></div>
      <div class="petal"></div>
      <div class="petal"></div>
    </div>
  </div>
</body>
</html>
Código CSS (styles.css):
css
Copiar código
body {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background-color: #87CEEB;
  margin: 0;
}

.sunflower {
  position: relative;
  width: 150px;
  height: 150px;
}

.center {
  width: 50px;
  height: 50px;
  background-color: #8B4513;
  border-radius: 50%;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.petals {
  position: absolute;
  width: 100%;
  height: 100%;
}

.petal {
  position: absolute;
  width: 40px;
  height: 20px;
  background-color: #FFD700;
  border-radius: 20px 20px 0 0;
  top: 0;
  left: 50%;
  transform-origin: bottom;
  animation: spin 10s linear infinite;
}

.petal:nth-child(1) { transform: rotate(0deg) translateY(-50%); }
.petal:nth-child(2) { transform: rotate(45deg) translateY(-50%); }
.petal:nth-child(3) { transform: rotate(90deg) translateY(-50%); }
.petal:nth-child(4) { transform: rotate(135deg) translateY(-50%); }
.petal:nth-child(5) { transform: rotate(180deg) translateY(-50%); }
.petal:nth-child(6) { transform: rotate(225deg) translateY(-50%); }
.petal:nth-child(7) { transform: rotate(270deg) translateY(-50%); }
.petal:nth-child(8) { transform: rotate(315deg) translateY(-50%); }

@keyframes spin {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(360deg);
  }
}

for i in range 160 40
r= 40 math.sqrt
turtle.goto
turtle.pendow
if i< turtle.stamp
else:
turtle.fillcolor
turtle. right
turtle.foward
turtle.end_fill
turtle.penup
turtle.goto Ajustar la posicion vertical segun sea necesario
<!---turtle.writer
turtle.hideturtle
turtle.click

delnisse/delnisse is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
