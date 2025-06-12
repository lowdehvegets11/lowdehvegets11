## Hi , I am you :)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Click the Vegetable 🥦</title>
  <style>
    body { text-align: center; font-family: sans-serif; background: #f0fff0; }
    h1 { color: #2e7d32; }
    #veg { width: 100px; cursor: pointer; position: absolute; }
  </style>
</head>
<body>
  <h1>🥦 Click the Vegetable!</h1>
  <p>Score: <span id="score">0</span></p>
  <img id="veg" src="https://i.ibb.co/0fnLspS/broccoli.png" alt="vegetable" />

  <script>
    const veg = document.getElementById("veg");
    const scoreDisplay = document.getElementById("score");
    let score = 0;

    function moveVeg() {
      const x = Math.random() * (window.innerWidth - 100);
      const y = Math.random() * (window.innerHeight - 100);
      veg.style.left = `${x}px`;
      veg.style.top = `${y}px`;
    }

    veg.addEventListener("click", () => {
      score++;
      scoreDisplay.textContent = score;
      moveVeg();
    });

    moveVeg();
  </script>
</body>
</html>


<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=lowdehvegets11&show_icons=true&theme=radical" alt="GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=lowdehvegets11&theme=radical" alt="GitHub Streak" />
</p>





