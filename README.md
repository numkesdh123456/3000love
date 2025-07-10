<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>I love you</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: black;
    }
    .heart {
      font-size: 5rem;
      color: pink;
      animation: pulse 1s infinite;
    }
    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.2); color: red; }
      100% { transform: scale(1); }
    }
  </style>
</head>
<body>
  <div class="heart">I love you 💖</div>
</body>
</html>
