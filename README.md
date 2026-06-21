<h1 align="center">🧠 Python Tkinter Quiz Game (Full Interactive Project)</h1>

<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&duration=3000&pause=500&color=00C2FF&center=true&vCenter=true&width=800&lines=Welcome+to+Python+Quiz+Game;Interactive+MCQ+Based+Learning+App;Built+with+Tkinter+GUI;Science+%2B+GK+Questions+Included;Beginner+Friendly+Python+Project" />
</p>

---

<h2>🏠 HOME / PROJECT OVERVIEW</h2>

<p>
This project is a <b>Python-based Quiz Application</b> built using <b>Tkinter GUI</b>.  
It is designed to simulate an interactive exam system where users answer multiple-choice questions one by one.
</p>

<p>
The quiz includes science, general knowledge, space, biology, physics, geography, and logical questions.  
It is built for beginners to understand how GUI applications and logic-based programs work in Python.
</p>

<p>
👉 The main idea of this project is to make learning Python fun and interactive.
</p>

---

<h2>🎯 PROJECT OBJECTIVE</h2>

<ul>
  <li>To create an interactive quiz system using Python GUI</li>
  <li>To practice conditional logic and loops</li>
  <li>To understand user input handling in Tkinter</li>
  <li>To improve problem-solving skills</li>
  <li>To simulate a real-world exam experience</li>
</ul>

---

<h2>⚙️ HOW THE SYSTEM WORKS (DETAILED FLOW)</h2>

<ol>
  <li><b>Program Starts</b> → Tkinter window is created (hidden main window)</li>
  <li><b>Welcome Message</b> → User is greeted with a popup</li>
  <li><b>Start Input</b> → User must type “start” to begin quiz</li>
  <li><b>Validation</b> → If wrong input → error message appears</li>
  <li><b>Question Loop Begins</b> → Each question appears in sequence</li>
  <li><b>User Input</b> → Answer entered using dialog box</li>
  <li><b>Answer Check</b> → System compares with correct answer</li>
  <li><b>Retry System</b> → Wrong answers repeat until correct</li>
  <li><b>Progression</b> → Only correct answer moves to next question</li>
  <li><b>Completion</b> → Final message shows “Test Completed”</li>
</ol>

---

<h2>🧠 FEATURES (DETAILED)</h2>

<ul>
  <li>🧠 30+ Educational Questions</li>
  <li>🎮 Interactive GUI using Tkinter</li>
  <li>🔁 Retry system until correct answer</li>
  <li>💬 Popup-based question system</li>
  <li>📚 Covers Science, GK, Space, Biology, Physics</li>
  <li>🎯 Simple keyboard input system</li>
  <li>🚀 Beginner-friendly structure</li>
  <li>🧩 Easy to extend with more questions</li>
</ul>

---

<h2>📌 QUESTION CATEGORIES INCLUDED</h2>

<ul>
  <li>🌌 Space & Astronomy (Black holes, planets, galaxies)</li>
  <li>🌍 Geography (Countries, continents, capitals)</li>
  <li>🧪 Science (Physics, chemistry basics)</li>
  <li>🧬 Biology (Human body, animals, vitamins)</li>
  <li>📚 General Knowledge</li>
</ul>

---

<h2>🛠️ TECHNOLOGY STACK</h2>

<p>
<img src="https://img.shields.io/badge/Python-3.10-blue">
<img src="https://img.shields.io/badge/Tkinter-GUI-yellow">
<img src="https://img.shields.io/badge/Beginner-Friendly-green">
</p>

---

<h2>📂 PROJECT STRUCTURE</h2>

<pre>
Quiz-Game/
│
├── quiz.py
└── README.md
</pre>

---

<h2>▶️ HOW TO RUN THE PROJECT</h2>

<pre>
1. Install Python (if not installed)
2. Save file as quiz.py
3. Run command:
   python quiz.py
4. Start quiz by typing "start"
</pre>

---

<h2>📊 LOGIC EXPLANATION (IMPORTANT)</h2>

<p>
The project is based on:
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Python Quiz Game</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: linear-gradient(120deg, #0f2027, #203a43, #2c5364);
    color: white;
}

header {
    text-align: center;
    padding: 40px;
    background: rgba(0,0,0,0.4);
    animation: fadeIn 2s ease-in-out;
}

h1 {
    font-size: 40px;
    color: #00e6ff;
}

.typing {
    font-size: 18px;
    color: #fff;
    border-right: 2px solid white;
    width: fit-content;
    margin: auto;
    white-space: nowrap;
    overflow: hidden;
    animation: typing 4s steps(40) infinite alternate;
}

@keyframes typing {
    from { width: 0 }
    to { width: 100% }
}

@keyframes fadeIn {
    from { opacity: 0 }
    to { opacity: 1 }
}

.container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
    padding: 30px;
}

.card {
    background: rgba(255,255,255,0.1);
    padding: 20px;
    border-radius: 15px;
    box-shadow: 0 0 20px rgba(0,255,255,0.2);
    transition: 0.3s;
}

.card:hover {
    transform: scale(1.05);
    background: rgba(0,255,255,0.1);
}

button {
    padding: 10px 20px;
    border: none;
    background: #00e6ff;
    color: black;
    border-radius: 10px;
    cursor: pointer;
    transition: 0.3s;
}

button:hover {
    background: #00ffaa;
}

footer {
    text-align: center;
    padding: 20px;
    background: rgba(0,0,0,0.5);
    margin-top: 20px;
}
</style>
</head>

<body>

<header>
    <h1>🧠 Python Quiz Game</h1>
    <div class="typing">Interactive MCQ Learning System • Built with Tkinter Logic • 30+ Questions</div>
</header>

<div class="container">

    <div class="card">
        <h2>🏠 HOME</h2>
        <p>Welcome to Quiz Game Project. This is a Python-based interactive MCQ system.</p>
        <button>Start Quiz</button>
    </div>

    <div class="card">
        <h2>⚙️ FEATURES</h2>
        <ul>
            <li>30+ Questions</li>
            <li>Retry System</li>
            <li>MCQ Format</li>
            <li>Beginner Friendly</li>
        </ul>
    </div>

    <div class="card">
        <h2>🧠 HOW IT WORKS</h2>
        <p>Start → Answer Questions → Validation → Next Question → Final Result</p>
    </div>

    <div class="card">
        <h2>📊 MODULES</h2>
        <p>Science, GK, Space, Biology, Physics, Geography</p>
    </div>

    <div class="card">
        <h2>🚀 FUTURE</h2>
        <ul>
            <li>Score System</li>
            <li>JSON Storage</li>
            <li>Timer Mode</li>
            <li>Leaderboard</li>
        </ul>
    </div>

    <div class="card">
        <h2>👨‍💻 AUTHOR</h2>
        <p>Built using Python + Tkinter for learning purposes.</p>
        <button>GitHub Project</button>
    </div>

</div>

<footer>
    🔥 Python Quiz Game • Ultimate Learning Project • UI Version 🔥
</footer>

</body>
</html>
