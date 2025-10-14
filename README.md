
    body {
      margin: 0;
      padding: 0;
      background-color: #000;
      font-family: 'Poppins', sans-serif;
      color: #fff;
      text-align: center;
      min-height: 140vh;
    }

    .container {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: flex-start;
      padding: 60px 20px;
      gap: 25px;
    }

    .logo {
      width: 320px;
      height: auto;
      margin-bottom: 35px;
      filter: drop-shadow(0 0 25px rgba(255, 0, 0, 0.6));
      animation: pulse 3s infinite alternate;
    }

    @keyframes pulse {
      0% { filter: drop-shadow(0 0 10px rgba(255, 0, 0, 0.3)); }
      100% { filter: drop-shadow(0 0 30px rgba(255, 0, 0, 0.7)); }
    }

    h1 {
      font-size: 3.2rem;
      color: #ff3b3b;
      text-shadow: 0 0 10px rgba(255, 0, 0, 0.6);
      margin-bottom: 10px;
    }

    .tagline {
      font-size: 1.25rem;
      color: #ff5555;
      margin-bottom: 30px;
      font-weight: 600;
      text-shadow: 0 0 15px rgba(255, 0, 0, 0.4);
      line-height: 1.5;
    }

    .download-btn {
      background: linear-gradient(90deg, #ff0000, #cc0000);
      color: white;
      font-size: 1.4rem;
      font-weight: 600;
      padding: 18px 45px;
      border: none;
      border-radius: 12px;
      cursor: pointer;
      box-shadow: 0 0 25px rgba(255, 0, 0, 0.5);
      transition: all 0.3s ease;
      text-decoration: none;
      margin-bottom: 40px;
    }

    .download-btn:hover {
      box-shadow: 0 0 35px rgba(255, 0, 0, 0.8);
      transform: scale(1.07);
    }

    .features {
      display: flex;
      flex-direction: column;
      gap: 30px;
      width: 90%;
      max-width: 480px;
    }

    .feature-box {
      background-color: #111;
      border-radius: 16px;
      padding: 28px;
      box-shadow: 0 0 22px rgba(255, 0, 0, 0.35);
      transition: 0.3s;
    }

    .feature-box:hover {
      transform: scale(1.04);
      box-shadow: 0 0 30px rgba(255, 0, 0, 0.6);
    }

    .feature-box h3 {
      color: #ff3b3b;
      margin-bottom: 12px;
      font-size: 1.25rem;
    }

    .feature-box p {
      color: #ccc;
      margin: 0;
      font-size: 1rem;
      line-height: 1.5;
    }

    footer {
      margin-top: 70px;
      font-size: 0.9rem;
      color: #777;
    }
  </style>
</head>
<body>
  <div class="container">
    <img src="warclash_logo.png" alt="WarClash Logo" class="logo" />
    <h1>WarClash</h1>

    <div class="tagline">
      Join India's Best Free Fire Tournament • Compete Daily, Win Cash Instantly 💥
    </div>

    <!-- ✅ Download Button -->
    <a class="download-btn" href="https://ga-fs.primexop.com/11521/androidBuilds/warclashV1.apk" target="_blank">
      ⚔️ Download App (APK)
    </a>

    <div class="features">
      <div class="feature-box">
        <h3>🎯 Free Tournaments</h3>
        <p>Free Tournament Every Week With Big Prize Pools 🔥</p>
      </div>

      <div class="feature-box">
        <h3>⚡ Fastest Withdrawal</h3>
        <p>Withdrawals In Just 30 Mins, No Delays 💸</p>
      </div>

      <div class="feature-box">
        <h3>🚀 Fastest Support</h3>
        <p>Issues Solved in 30 Mins Via Super Speedy Support System</p>
      </div>

      <div class="feature-box">
        <h3>💰 Fastest Reward System</h3>
        <p>Results Updated Instantly Within Seconds ⚡</p>
      </div>

      <div class="feature-box">
        <h3>🛡️ Secure & Fair</h3>
        <p>Advanced Anti-Cheat System For Fair Tournament Play</p>
      </div>

      <div class="feature-box">
        <h3>🔥 Fastest Growing & Trusted</h3>
        <p>WarClash Is One Of India's Most Trusted Gaming Apps</p>
      </div>
    </div>

    <footer>© 2025 WarClash. All Rights Reserved.</footer>
  </div>
</body>
</html>
