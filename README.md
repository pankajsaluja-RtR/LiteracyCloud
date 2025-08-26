<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Scan & Read</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: #fefefe;
      font-family: Arial, sans-serif;
      overflow: hidden;
    }

    .container {
      position: relative;
      z-index: 10;
      background: #fff8e7;
      padding: 20px 40px;
      border-radius: 12px;
      text-align: center;
      box-shadow: 0 4px 15px rgba(0,0,0,0.2);
    }

    h1 { margin: 0; font-size: 24px; }
    p { margin: 8px 0; }
    button {
      background: #ff6600;
      border: none;
      padding: 10px 20px;
      color: #fff;
      font-size: 16px;
      border-radius: 6px;
      cursor: pointer;
    }
    footer {
      margin-top: 10px;
      font-size: 12px;
      color: #666;
    }

    /* Floating Books Wrappers */
    .books-left, .books-right {
      position: absolute;
      top: 0;
      bottom: 0;
      width: 160px; /* adjust width of book strip */
      display: flex;
      justify-content: center;
      z-index: 1;
      pointer-events: none;
      overflow: hidden;
    }

    .books-left { left: 0; }
    .books-right { right: 0; }

    .column {
      display: flex;
      flex-direction: column;
      animation: floatUp 25s linear infinite;
    }

    .column img {
      width: 120px;
      margin: 15px 0;
      border-radius: 6px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.2);
    }

    /* Infinite loop upwards */
    @keyframes floatUp {
      0% { transform: translateY(0); }
      100% { transform: translateY(-50%); }
    }
  </style>
</head>
<body>

  <!-- Floating Books Left -->
  <div class="books-left">
    <div class="column">
      <!-- repeat set twice for seamless loop -->
      <img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7919/cover_thumbnail/size1/Fri_Jul_25_2025_12_27_29_GMT_0530_%28India_Standard_Time%29.webp?1753426650">
      <img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7863/cover_thumbnail/size1/page-0-1751522275.webp?1751522280">
      <img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7856/cover_thumbnail/size1/Wed_Jul_02_2025_16_37_15_GMT_0530_%28India_Standard_Time%29.webp?1751454435">
      <img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7853/cover_thumbnail/size1/Wed_Jul_02_2025_14_59_56_GMT_0530_%28India_Standard_Time%29.webp?1751448596">
      <img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7658/cover_thumbnail/size1/Sun_Apr_06_2025_14_14_14_GMT_0530_%28India_Standard_Time%29.webp?1743929054">
      <!-- duplicate again -->
      <img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7919/cover_thumbnail/size1/Fri_Jul_25_2025_12_27_29_GMT_0530_%28India_Standard_Time%29.webp?1753426650">
      <img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7863/cover_thumbnail/size1/page-0-1751522275.webp?1751522280">
      <img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7856/cover_thumbnail/size1/Wed_Jul_02_2025_16_37_15_GMT_0530_%28India_Standard_Time%29.webp?1751454435">
      <img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7853/cover_thumbnail/size1/Wed_Jul_02_2025_14_59_56_GMT_0530_%28India_Standard_Time%29.webp?1751448596">
      <img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7658/cover_thumbnail/size1/Sun_Apr_06_2025_14_14_14_GMT_0530_%28India_Standard_Time%29.webp?1743929054">
    </div>
  </div>

  <!-- Floating Books Right -->
  <div class="books-right">
    <div class="column">
      <!-- same covers as left (or you can mix other set) -->
      <img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7919/cover_thumbnail/size1/Fri_Jul_25_2025_12_27_29_GMT_0530_%28India_Standard_Time%29.webp?1753426650">
      <img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7863/cover_thumbnail/size1/page-0-1751522275.webp?1751522280">
      <img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7856/cover_thumbnail/size1/Wed_Jul_02_2025_16_37_15_GMT_0530_%28India_Standard_Time%29.webp?1751454435">
      <img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7853/cover_thumbnail/size1/Wed_Jul_02_2025_14_59_56_GMT_0530_%28India_Standard_Time%29.webp?1751448596">
      <img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7658/cover_thumbnail/size1/Sun_Apr_06_2025_14_14_14_GMT_0530_%28India_Standard_Time%29.webp?1743929054">
      <!-- duplicate again -->
      <img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7919/cover_thumbnail/size1/Fri_Jul_25_2025_12_27_29_GMT_0530_%28India_Standard_Time%29.webp?1753426650">
      <img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7863/cover_thumbnail/size1/page-0-1751522275.webp?1751522280">
      <img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7856/cover_thumbnail/size1/Wed_Jul_02_2025_16_37_15_GMT_0530_%28India_Standard_Time%29.webp?1751454435">
      <img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7853/cover_thumbnail/size1/Wed_Jul_02_2025_14_59_56_GMT_0530_%28India_Standard_Time%29.webp?1751448596">
      <img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7658/cover_thumbnail/size1/Sun_Apr_06_2025_14_14_14_GMT_0530_%28India_Standard_Time%29.webp?1743929054">
    </div>
  </div>

  <!-- Main Content -->
  <div class="container">
    <h1>📖 Scan & Read</h1>
    <p>कहानी पढ़ने के लिए क्लिक करें!</p>
    <button onclick="openRandomURL()">Click Here</button>
    <footer>Powered by Literacy Cloud</footer>
  </div>

  <script>
    function openRandomURL() {
      const urls = [
      	'https://literacycloud.org/stories/5635-it-is-back/',
'https://literacycloud.org/stories/5383-muna-and-milan-s-game/',
'https://literacycloud.org/stories/5640-my-elastical-fantastical-bubble/',
'https://literacycloud.org/stories/5644-the-butterfly-and-the-rainbow/',

'https://literacycloud.org/stories/7919',
    'https://literacycloud.org/stories/7863',
    'https://literacycloud.org/stories/7856',
    'https://literacycloud.org/stories/7853',
    'https://literacycloud.org/stories/7658',
    'https://literacycloud.org/stories/7337',
    'https://literacycloud.org/stories/7326',
    'https://literacycloud.org/stories/7323',
    'https://literacycloud.org/stories/7298',
    'https://literacycloud.org/stories/7296'
		
		
      ];
      const randomUrl = urls[Math.floor(Math.random() * urls.length)];
      window.open(randomUrl, "_blank");
    }
  </script>

</body>
</html>
