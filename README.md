<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>MCQ Quiz — 15s Timer</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <main class="container">
    <header>
      <h1>MCQ Quiz</h1>
      <div class="meta">
        <div id="score">Score: 0</div>
        <button id="restartBtn">Restart</button>
      </div>
    </header>

    <section id="quiz" class="card">
      <div id="questionArea">
        <div id="timerBarWrap">
          <div id="timerBar"></div>
        </div>
        <div id="countdown">15</div>
        <h2 id="question">Question will appear here</h2>
      </div>

      <div id="choices" class="choices">
        <!-- Buttons injected here -->
      </div>

      <div class="controls">
        <button id="nextBtn" disabled>Next</button>
        <div id="feedback" aria-live="polite"></div>
      </div>
    </section>

    <section id="results" class="card hidden">
      <h2>Quiz finished</h2>
      <p id="finalScore">Your score: 0 / 0</p>
      <button id="playAgainBtn">Play again</button>
    </section>

    <footer>
      <small>15 second timer per question. Questions randomized each run.</small>
    </footer>
  </main>

  <script src="app.js"></script>
</body>
</html>
