<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <title>Boner Birthday Wish 🎂</title>
  <style>
    body {
      text-align: center;
      background-color: #fff0f5;
      font-family: "Arial", sans-serif;
      padding-top: 100px;
    }
    .wish {
      display: none;
      font-size: 28px;
      color: #e91e63;
      margin-top: 20px;
      animation: fadeIn 2s ease-in-out;
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    a {
      font-size: 20px;
      text-decoration: none;
      color: white;
      background-color: #ff69b4;
      padding: 10px 20px;
      border-radius: 12px;
    }
    a:hover {
      background-color: #ff1493;
    }
  </style>
</head>
<body>

  <a href="#" onclick="showWish()">🎈 বার্থডে উইশ দেখুন 🎉</a>

  <div class="wish" id="wishBox">
    🎉🎂 শুভ জন্মদিন, প্রিয় বোন! 🎂🎉 <br>
    🌸 তুমি সবসময় সুখী থাকো, হাসিখুশি থাকো 🌸 <br>
    💖 তোমার প্রতিটি দিন হোক ভালোবাসা আর আনন্দে ভরা! 💖 <br>
    🥳🎁🍰🎀🎊🌟🌹
  </div>

  <script>
    function showWish() {
      document.getElementById('wishBox').style.display = 'block';
    }
  </script>

</body>
</html>
