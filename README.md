<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>INSPIREEZ Magazine</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f7f7f7;
      color: #222;
    }

    header {
      background: linear-gradient(90deg, #ff7b00, #ffca28);
      padding: 20px;
      text-align: center;
      color: white;
      font-size: 32px;
      font-weight: bold;
      letter-spacing: 2px;
    }

    nav {
      background: #fff;
      padding: 15px;
      display: flex;
      justify-content: center;
      gap: 25px;
      border-bottom: 2px solid #eee;
    }

    nav a {
      text-decoration: none;
      color: #444;
      font-weight: 600;
      font-size: 18px;
    }

    nav a:hover {
      color: #ff7b00;
    }

    .hero {
      background: url('https://images.unsplash.com/photo-1516534775068-ba3e7458af70') center/cover;
      height: 350px;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: white;
      font-size: 40px;
      font-weight: bold;
      text-shadow: 2px 2px 6px #000;
    }

    .section {
      padding: 40px;
      text-align: center;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 25px;
      padding: 20px;
    }

    .card {
      background: white;
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      transition: 0.3s;
    }

    .card:hover {
      transform: scale(1.05);
    }

    footer {
      margin-top: 40px;
      background: #222;
      padding: 20px;
      text-align: center;
      color: white;
    }

    button {
      background: #ff7b00;
      border: none;
      padding: 12px 22px;
      color: white;
      font-size: 18px;
      border-radius: 10px;
      cursor: pointer;
      margin-top: 15px;
    }

    button:hover {
      background: #e66800;
    }
  </style>
</head>
<body>

<header>INSPIREEZ – Kids Magazine</header>

<nav>
  <a href="#home">Home</a>
  <a href="#stories">Stories</a>
  <a href="#comics">Comics</a>
  <a href="#puzzles">Puzzles</a>
  <a href="#contact">Contact</a>
</nav>

<div class="hero" id="home">Where Imagination Comes Alive ✨</div>

<div class="section" id="stories">
  <h2>Featured Stories</h2>
  <div class="cards">
    <div class="card">
      <h3>The Brave Little Star</h3>
      <p>A magical adventure of a star who falls to Earth!</p>
    </div>
    <div class="card">
      <h3>Mittu & the Mystery Box</h3>
      <p>An exciting Inspireez original story!</p>
    </div>
    <div class="card">
      <h3>Benny’s Big Lesson</h3>
      <p>A heart-touching school tale.</p>
    </div>
  </div>
</div>

<div class="section" id="comics">
  <h2>Comic Zone</h2>
  <p>Colorful, funny and inspiring comic strips every month!</p>
</div>

<div class="section" id="puzzles">
  <h2>Puzzles & Activities</h2>
  <p>Mazes, sudoku, spot-the-difference and more.</p>
</div>

<div class="section" id="contact">
  <h2>Contact Us</h2>
  <p>Follow us on Instagram: <strong>inspireez._.official</strong></p>
  <button onclick="followMsg()">Click Me</button>
</div>

<footer>
  © 2025 Inspireez Magazine – All Rights Reserved
</footer>

<script>
  function followMsg() {
    alert("Thanks for supporting INSPIREEZ! 🎉");
  }
</script>

</body>
</html>
