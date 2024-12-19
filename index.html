<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ตรรกศาสตร์</title>
<style>
  body {
    font-family: Arial, sans-serif;
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-top: 50px;
  }
  #question {
    font-size: 1.5em;
    margin-bottom: 20px;
  }
  #feedback {
    font-size: 1.2em;
    margin-top: 20px;
  }
  button {
    padding: 10px 20px;
    font-size: 1em;
    background-color: #4CAF50;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: transform 0.2s, background-color 0.2s;
    margin-top: 20px;
  }
  button:hover {
    background-color: #45a049;
  }
  button:active {
    transform: scale(0.95);
  }
  .correct {
    color: green;
  }
  .incorrect {
    color: red;
  }
</style>
</head>
<body>
<h1>ทดสอบตรรกศาสตร์</h1>
<div id="question">กดปุ่มเพื่อสุ่มโจทย์ตรรกศาสตร์</div>
<button onclick="generateQuestion()">สุ่มโจทย์</button>
<label for="answer">คำตอบของคุณ (จริง/เท็จ):</label>
<input type="text" id="answer">
<button onclick="checkAnswer()">ตรวจคำตอบ</button>
<div id="feedback"></div>
<div id="score">คะแนนของคุณ: <span id="scoreCount">0</span></div>
<script>
  let score = 0;
  const questions = [
    { text: "p เป็นจริง, q เป็นเท็จ, r เป็นเท็จ, p ∧ q ↔ r", answer: "เท็จ" },
    { text: "p เป็นจริง, q เป็นจริง, r เป็นเท็จ, p ∨ q", answer: "จริง" },
    { text: "p เป็นเท็จ, q เป็นจริง, r เป็นจริง, ~ p ∧ q", answer: "จริง" },
    { text: "p เป็นเท็จ, q เป็นเท็จ, r เป็นจริง, p ∧ q ↔ r", answer: "เท็จ" },
    { text: "p เป็นจริง, q เป็นจริง, r เป็นจริง, p ∧ (q ∨ r)", answer: "จริง" },
    { text: "p เป็นจริง, q เป็นจริง, p ↔ q", answer: "จริง" },
    { text: "p เป็นจริง, q เป็นเท็จ, p ↔ q", answer: "เท็จ" },
    { text: "p เป็นจริง, q เป็นจริง, p → q", answer: "จริง" },
    { text: "p เป็นจริง, q เป็นเท็จ, p → q", answer: "เท็จ" },
    { text: "p เป็นเท็จ, q เป็นจริง, p → q", answer: "จริง" },
    { text: "p เป็นเท็จ, q เป็นเท็จ, p → q", answer: "จริง" }
  ];

  let currentQuestion = null;

  function updateScore(isCorrect) {
    if (isCorrect) {
      score++;
    } else {
      score--;
    }
    document.getElementById("scoreCount").textContent = score;
  }

  function generateQuestion() {
    const randomIndex = Math.floor(Math.random() * questions.length);
    currentQuestion = questions[randomIndex];
    document.getElementById("question").textContent = currentQuestion.text;
    document.getElementById("feedback").textContent = "";
    document.getElementById("answer").value = "";
  }

  function checkAnswer() {
    const userAnswer = document.getElementById("answer").value.trim();
    const feedback = document.getElementById("feedback");
    if (currentQuestion) {
      if (userAnswer === currentQuestion.answer) {
        feedback.textContent = "คำตอบถูกต้อง!";
        feedback.className = "correct";
        updateScore(true);
      } else {
        feedback.textContent = "คำตอบไม่ถูกต้อง ลองใหม่อีกครั้ง!";
        feedback.className = "incorrect";
        updateScore(false);
      }
    } else {
      feedback.textContent = "กรุณาสุ่มโจทย์ก่อน";
      feedback.className = "incorrect";
    }
  }
</script>
</body>
</html>