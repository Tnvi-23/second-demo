# second-demo
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Quiz Game</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="quiz-container" id="quiz">
    <div class="quiz-header">
      <div id="scoreboard">Score: 0</div>
      <div id="timer">Time: 15</div>
    </div>
    <h2 id="question">Question text</h2>
    <ul>
      <li><button class="answer-btn" id="a"></button></li>
      <li><button class="answer-btn" id="b"></button></li>
      <li><button class="answer-btn" id="c"></button></li>
      <li><button class="answer-btn" id="d"></button></li>
    </ul>
    <button id="next">Next</button>
  </div>

  <script src="script.js"></script>
</body>
</html>
