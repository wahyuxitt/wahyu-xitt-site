<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>WAHYU X XITT Ultra Settings</title>
  <style>
    body {
      font-family: 'Arial Black', sans-serif;
      background: #fff;
      color: #000;
      text-align: center;
      padding: 30px;
    }

    .header {
      font-size: 32px;
      font-weight: bold;
      text-shadow: 2px 2px #000;
    }

    .subheader {
      font-size: 22px;
      font-weight: bold;
      text-shadow: 2px 2px #000;
      margin-bottom: 40px;
    }

    .setting {
      border: 3px solid black;
      border-radius: 10px;
      margin: 20px auto;
      width: 400px;
      padding: 15px 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      font-size: 20px;
      font-weight: bold;
      background-color: white;
      text-shadow: 1.5px 1.5px #000;
    }

    .toggle-btn {
      background-color: black;
      color: white;
      border: none;
      padding: 10px 25px;
      cursor: pointer;
      font-weight: bold;
      border-radius: 8px;
      font-size: 16px;
      transition: background-color 0.3s;
    }

    .toggle-btn.off {
      background-color: gray;
    }

    .footer {
      margin-top: 40px;
      font-size: 14px;
      font-weight: bold;
    }

    .footer span {
      margin: 0 20px;
    }
  </style>
</head>
<body>

  <div class="header">WAHYU X XITT</div>
  <div class="subheader">ULTRA SETTINGS</div>

  <div class="setting">
    <span>AIM SENSITIVITY+</span>
    <button class="toggle-btn" onclick="toggle(this)">ON</button>
  </div>

  <div class="setting">
    <span>SMOOTH DISPLAY</span>
    <button class="toggle-btn" onclick="toggle(this)">ON</button>
  </div>

  <div class="setting">
    <span>ADVANCED AIM</span>
    <button class="toggle-btn" onclick="toggle(this)">ON</button>
  </div>

  <div class="footer">
    <span>©wahyustore</span>
    <span>FULL VIP FEATURES</span>
  </div>

  <script>
    function toggle(button) {
      if (button.textContent === "ON") {
        button.textContent = "OFF";
        button.classList.add("off");
      } else {
        button.textContent = "ON";
        button.classList.remove("off");
      }
    }
  </script>

</body>
</html>

