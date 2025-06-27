# Perkenalan-Diri
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Perkenalan Diri</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to right, #000000, #013220);
      color: #fff;
      overflow-x: hidden;
      animation: fadeIn 2s ease-in;
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    header {
      text-align: center;
      padding: 50px 20px 20px;
    }

    .typing {
      font-size: 2.2em;
      font-weight: bold;
      white-space: nowrap;
      overflow: hidden;
      border-right: 4px solid #00ff88;
      width: 0;
      animation: typing 4s steps(40, end) forwards, blink .75s step-end infinite;
    }

    @keyframes typing {
      from { width: 0 }
      to { width: 100% }
    }

    @keyframes blink {
      50% { border-color: transparent; }
    }

    .content {
      padding: 30px 10%;
      animation: slideUp 1.5s ease-out;
    }

    @keyframes slideUp {
      from { transform: translateY(50px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }

    h2 {
      color: #00ff88;
      font-size: 1.8em;
      margin-top: 40px;
      position: relative;
      animation: fadeIn 2s ease-in;
    }

    p {
      font-size: 1.2em;
      line-height: 1.6;
      animation: fadeIn 2.5s ease-in;
    }

    .hobbies {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }

    .hobby-card {
      background: rgba(0, 255, 136, 0.1);
      border: 1px solid #00ff88;
      padding: 20px;
      border-radius: 15px;
      text-align: center;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      cursor: pointer;
    }

    .hobby-card:hover {
      transform: scale(1.1) rotate(2deg);
      box-shadow: 0 0 20px #00ff88;
    }

    .button {
      display: inline-block;
      margin-top: 40px;
      padding: 15px 30px;
      background-color: #00ff88;
      color: #000;
      border: none;
      border-radius: 30px;
      font-size: 1.2em;
      cursor: pointer;
      animation: pulse 2s infinite;
      transition: background 0.3s;
    }

    .button:hover {
      background-color: #00cc70;
    }

    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.05); }
      100% { transform: scale(1); }
    }

    footer {
      text-align: center;
      padding: 30px;
      font-size: 0.9em;
      color: #aaa;
    }
  </style>
</head>
<body>
  <header>
    <div class="typing" id="typing-text"></div>
  </header>

  <div class="content">
    <h2>Sebelum itu, makasih banyak buat kalian yang udah berkunjung ke website ini😋</h2>
    <h2>Oke, jadi disini aku mau intro dulu yaa</h2>
    <p>Assalamualaikum👋. Hello my name is <strong>Novel Mubariz Abdillah</strong>. Maybe some people who was know more about me said " why you put that 'Abdillah' on your name, are you lie?"
Bro/sis, im not gonna lie, Abdillah is mean that im the servant of Allah, so when i put it on my name, im not lie, because im muslim, and every muslim is Abdillah/Abdullah (the servant of Allah 'ajja wa jalla).
And what? You wanna know more about me? Tch I'm just an ordinary boy, not very famous, and I.. sometimes prefer to be alone and secluded.
Talent? Ahh not very impressive, don't put too much expectation on me, haha.
The fact is, i'm just an ordinary boy, with an ordinary life, and im so grateful about this.</p>
    <h2>Izin spill sedikit hobi boleh lah yaa:</h2>
    <div class="hobbies">
      <div class="hobby-card">Bola basket</div>
      <div class="hobby-card">Jogging</div>
      <div class="hobby-card">Fotografi</div>
      <div class="hobby-card">Main game kadang² banget</div>
      <div class="hobby-card">Kadang buat syair atau poetry</div>
      <div class="hobby-card">Kadang writing random</div>
      <div class="hobby-card">Sepak Bola</div>
    </div>

    <button class="button" onclick="alert('Terima kasih sudah berkunjung!👋')">Goodbye..👋</button>
  </div>

  <footer>
    &copy; Sekian terimakasih
  </footer>

  <script>
    const text = "Selamat datang";
    let i = 0;
    const speed = 50;

    function typeWriter() {
      if (i < text.length) {
        document.getElementById("typing-text").innerHTML += text.charAt(i);
        i++;
        setTimeout(typeWriter, speed);
      }
    }
    window.onload = typeWriter;
  </script>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=Edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <title>HTML</title>
  
  <!-- HTML -->
  

  <!-- Custom Styles -->
  <link rel="stylesheet" href="style.css">
</head>
  <p></p>
  <!-- Project -->
  <script src="main.js"></script>
