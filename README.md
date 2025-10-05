<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Unblocked Games - Play 10 Free Games!</title>
  <style>
    body {
      background: #222;
      color: #fff;
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background: #444;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
    }
    #searchInput {
      width: 80%;
      max-width: 400px;
      padding: 10px;
      margin: 20px auto;
      display: block;
      border-radius: 5px;
      border: none;
      font-size: 16px;
    }
    .game-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 15px;
      padding: 20px;
    }
    .game {
      background: #333;
      border-radius: 10px;
      padding: 10px;
      text-align: center;
      transition: transform 0.2s;
    }
    .game:hover {
      transform: scale(1.05);
      background: #555;
    }
    .game img {
      width: 100%;
      border-radius: 5px;
    }
    .game a {
      color: #0ff;
      text-decoration: none;
      display: block;
      margin-top: 10px;
    }
    footer {
      background: #444;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Unblocked Games</h1>
    <p>Play 10 fun games for free — no blocks, no restrictions!</p>
  </header>

  <input type="text" id="searchInput" placeholder="Search games...">

  <div class="game-grid" id="gameGrid">
    <div class="game" data-name="Game 1">
      <img src="https://via.placeholder.com/200x120.png alt="Game 1">
      <a href="https://scratch.mit.edu/projects/10128407/" target="_blank">Play Game 1</a>
    </div>
    <div class="game" data-name="Game 2">
      <img src="https://via.placeholder.com/200x120.png?text=Game+2" alt="Game 2">
      <a href="https://scratch.mit.edu/projects/146468643/" target="_blank">Play Game 2</a>
    </div>
    <div class="game" data-name="Game 3">
      <img src="https://via.placeholder.com/200x120.png?text=Game+3" alt="Game 3">
      <a href="https://scratch.mit.edu/projects/17358777/" target="_blank">Play Game 3</a>
    </div>
    <div class="game" data-name="Game 4">
      <img src="https://via.placeholder.com/200x120.png?text=Game+4" alt="Game 4">
      <a href="https://scratch.mit.edu/projects/56907851/" target="_blank">Play Game 4</a>
    </div>
    <div class="game" data-name="Game 5">
      <img src="https://via.placeholder.com/200x120.png?text=Game+5" alt="Game 5">
      <a href="https://example.com/game5" target="_blank">Play Game 5</a>
    </div>
    <div class="game" data-name="Game 6">
      <img src="https://via.placeholder.com/200x120.png?text=Game+6" alt="Game 6">
      <a href="https://example.com/game6" target="_blank">Play Game 6</a>
    </div>
    <div class="game" data-name="Game 7">
      <img src="https://via.placeholder.com/200x120.png?text=Game+7" alt="Game 7">
      <a href="https://example.com/game7" target="_blank">Play Game 7</a>
    </div>
    <div class="game" data-name="Game 8">
      <img src="https://via.placeholder.com/200x120.png?text=Game+8" alt="Game 8">
      <a href="https://example.com/game8" target="_blank">Play Game 8</a>
    </div>
    <div class="game" data-name="Game 9">
      <img src="https://via.placeholder.com/200x120.png?text=Game+9" alt="Game 9">
      <a href="https://example.com/game9" target="_blank">Play Game 9</a>
    </div>
    <div class="game" data-name="Game 10">
      <img src="https://via.placeholder.com/200x120.png?text=Game+10" alt="Game 10">
      <a href="https://example.com/game10" target="_blank">Play Game 10</a>
    </div>
  </div>

  <footer>
    &copy; 2025 Unblocked Games.teacher-proof games website😄
  </footer>

  <script>
    const searchInput = document.getElementById("searchInput");
    const games = document.querySelectorAll(".game");

    searchInput.addEventListener("input", function() {
      const query = this.value.toLowerCase();
      games.forEach(game => {
        const name = game.getAttribute("data-name").toLowerCase();
        if (name.includes(query)) {
          game.style.display = "block";
        } else {
          game.style.display = "none";
        }
      });
    });
  </script>
</body>
</html>
