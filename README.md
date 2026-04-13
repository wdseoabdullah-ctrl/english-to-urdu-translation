<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>English to Urdu Translator</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #e9f0ff, #f7f9fc);
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .card {
      width: 320px;
      padding: 30px;
      background: #fff;
      border-radius: 14px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.1);
      text-align: center;
    }

    h1 {
      font-size: 22px;
      margin-bottom: 10px;
      color: #111;
    }

    p {
      font-size: 13px;
      color: #666;
      margin-bottom: 20px;
    }

    button {
      width: 100%;
      padding: 12px;
      margin-bottom: 10px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      font-size: 14px;
      font-weight: bold;
    }

    .primary {
      background: #1a73e8;
      color: white;
    }

    .secondary {
      background: #222;
      color: white;
    }

    .footer {
      margin-top: 15px;
      font-size: 11px;
      color: #999;
    }

    .footer a {
      color: #1a73e8;
      text-decoration: none;
      font-weight: bold;
    }

    .footer a:hover {
      text-decoration: underline;
    }

    button:hover {
      opacity: 0.9;
    }
  </style>
</head>
<body>

  <div class="card">
    <h1>English to Urdu Translator</h1>
    <p>Fast, simple and accurate translation tool</p>

    <button class="primary" onclick="openTranslate()">
      Translate Now
    </button>

    <button class="secondary" onclick="openSite()">
      Visit Website
    </button>

    <div class="footer">
      Powered by 
      <a href="https://www.translation.pk/" target="_blank">
        Translation.pk
      </a>
    </div>
  </div>

  <script>
    function openTranslate() {
      window.open(
        "https://www.translation.pk/english-to-urdu-translation/",
        "_blank"
      );
    }

    function openSite() {
      window.open("https://www.translation.pk/", "_blank");
    }
  </script>

</body>
</html>
