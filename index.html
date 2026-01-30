<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
<title>Brainrot Steal</title>
<style>
  body {
    margin: 0;
    background: black;
    overflow: hidden;
    touch-action: none;
    font-family: monospace;
  }
  #player {
    width: 50px;
    height: 50px;
    background: lime;
    border-radius: 10px;
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
  }
  .brainrot {
    width: 35px;
    height: 35px;
    background: hotpink;
    border-radius: 50%;
    position: absolute;
  }
  #ui {
    position: fixed;
    top: 10px;
    left: 10px;
    color: white;
    font-size: 20px;
  }
</style>
</head>
<body>

<div id="ui">🧠 <span id="score">0</span></div>
<div id="player"></div>

<script>
const player = document.getElementById("player");
const scoreText = document.getElementById("score");

let score = 0;
let px = window.innerWidth / 2;
let py = window.innerHeight / 2;

function spawnBrainrot() {
  const b = document.createElement("div");
  b.className = "brainrot";
  b.style.left = Math.random() * (window.innerWidth - 40) + "px";
  b.style.top = Math.random() * (window.innerHeight - 40) + "px";
  document.body.appendChild(b);
  return b;
}

let brainrots = [];
for (let i = 0; i < 8; i++) brainrots.push(spawnBrainrot());

document.addEventListener("touchmove", e => {
  const t = e.touches[0];
  px = t.clientX;
  py = t.clientY;
  player.style.left = px + "px";
  player.style.top = py + "px";

  brainrots.forEach((b, i) => {
    const bx = b.offsetLeft;
    const by = b.offsetTop;
    if (Math.abs(bx - px) < 30 && Math.abs(by - py) < 30) {
      score++;
      scoreText.textContent = score;
      b.remove();
      brainrots.splice(i, 1);
      brainrots.push(spawnBrainrot());
    }
  });
});
</script>

</body>
</html>
