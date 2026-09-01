<!DOCTYPE html>
<html>
<head>
  <title>Pratik की Funny Website 😂</title>
  <style>
    body {
      text-align: center;
      background: linear-gradient(135deg, #ffeb3b, #ff5722);
      font-family: Arial;
      padding-top: 60px;
    }

    h1 {
      font-size: 45px;
    }

    button {
      padding: 15px 25px;
      font-size: 20px;
      border: none;
      border-radius: 15px;
      cursor: pointer;
      background: #00ff88;
    }

    #joke {
      font-size: 25px;
      margin: 30px;
      font-weight: bold;
    }
  </style>
</head>

<body>

  <h1>😂 Welcome Pratik 😂</h1>

  <p id="joke">नीचे वाला बटन दबाओ 😎</p>

  <button onclick="funny()">😂 दबाओ मुझे 😂</button>

  <script>
    function funny() {
      let jokes = [
        "🤣 Error 404: दिमाग नहीं मिला!",
        "😂 Pratik आज पढ़ाई करेगा... शायद!",
        "🐒 Warning! एक बंदर वेबसाइट पर आ गया!",
        "🍕 Homework से ज्यादा जरूरी Pizza है!",
        "😎 Pratik = Coding का बादशाह!",
        "🤯 Computer भी Pratik से डरता है!",
        "😂 मम्मी: पढ़ाई कर! Pratik: Website बना रहा हूँ!",
        "🚀 99% Coding... 1% समझ!"
      ];

      let random = Math.floor(Math.random() * jokes.length);

      document.getElementById("joke").innerHTML = jokes[random];
    }
  </script>

</body>
</html>
