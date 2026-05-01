<!DOCTYPE html>
<html>
<head>
  <title>Mary Says Yes</title>
  <style>
    body { text-align:center; font-family:Arial; background:#fff0f5; }
    h1 { margin-top:50px; }
    button { padding:10px 20px; margin:10px; font-size:16px; }
    #quiz, #reveal { display:none; margin-top:30px; }
    #reveal { color:#d6336c; font-size:24px; }
  </style>
</head>
<body>
  <h1>I have something important to tell you...</h1>
  <button onclick="document.getElementById('quiz').style.display='block'">Start the challenge</button>

  <div id="quiz">
    <p>Kelan kita pinayagan na ligawan ako?</p>
    <button onclick="next()">Kahapon</button>
    <button onclick="next()">Kaarawan ko</button>
    <button onclick="next()">Kanina</button>
  </div>

  <div id="reveal">
    <h2>Ulol lupit mo na alala mo yun? 💖</h2>
  </div>

  <script>
    function next() {
      document.getElementById('quiz').style.display='none';
      document.getElementById('reveal').style.display='block';
    }
  </script>
</body>
</html>
