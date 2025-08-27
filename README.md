
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
      100% { transform: translateY(-100%); }
    }
  </style>
</head>
<body>

  <!-- Floating Books Left -->
  <div class="books-left">
    <div class="column">
      <!-- repeat set twice for seamless loop -->
	  
	  <img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7160/cover_thumbnail/size1/page-0-1752223773.webp?1752223778" alt="Image 1">
<img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7161/cover_thumbnail/size1/page-0-1752222783.webp?1752222787" alt="Image 2">
<img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7162/cover_thumbnail/size1/Fri_Jul_12_2024_17_30_41_GMT_0530_%28India_Standard_Time%29.webp?1720785641" alt="Image 3">
<img src="https://djuc8g2q9bu2u.cloudfront.net/stories/6492/cover_thumbnail/size1/Tue_Aug_01_2023_12_22_14_GMT_0530_%28India_Standard_Time%29.webp?1712126174" alt="Image 4">
<img src="https://djuc8g2q9bu2u.cloudfront.net/stories/6493/cover_thumbnail/size1/IN-LLP-14-0006_PeepalTree-HIN.webp?1712126152" alt="Image 5">
<img src="https://djuc8g2q9bu2u.cloudfront.net/stories/6462/cover_thumbnail/size1/Thu_Jul_18_2024_17_26_09_GMT_0530_%28India_Standard_Time%29.webp?1721303769" alt="Image 6">
<img src="https://djuc8g2q9bu2u.cloudfront.net/stories/6465/cover_thumbnail/size1/Mon_Jul_15_2024_13_41_46_GMT_0530_%28India_Standard_Time%29.webp?1721031106" alt="Image 7">
<img src="https://djuc8g2q9bu2u.cloudfront.net/stories/6422/cover_thumbnail/size1/Fri_Jul_14_2023_10_31_23_GMT_0530_%28India_Standard_Time%29.webp?1712127031" alt="Image 8">
<img src="https://djuc8g2q9bu2u.cloudfront.net/stories/6423/cover_thumbnail/size1/Fri_Jul_14_2023_10_40_59_GMT_0530_%28India_Standard_Time%29.webp?1712126993" alt="Image 9">
<img src="https://djuc8g2q9bu2u.cloudfront.net/stories/6309/cover_thumbnail/size1/Thu_Jul_18_2024_15_42_08_GMT_0530_%28India_Standard_Time%29.webp?1721297528" alt="Image 10">
<img src="https://djuc8g2q9bu2u.cloudfront.net/stories/6276/cover_thumbnail/size1/page-0-1686300737.webp?1712127348" alt="Image 11">
<img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7919/cover_thumbnail/size1/Fri_Jul_25_2025_12_27_29_GMT_0530_%28India_Standard_Time%29.webp?1753426650" alt="Image 12">

	  
	  
	  
	 
    </div>
  </div>

  <!-- Floating Books Right -->
  <div class="books-right">
    <div class="column">
      <!-- same covers as left (or you can mix other set) -->
     
	  
	  <!-- Floating Books New -->
	  
	 <img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7919/cover_thumbnail/size1/Fri_Jul_25_2025_12_27_29_GMT_0530_%28India_Standard_Time%29.webp?1753426650" alt="Image 1">
<img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7863/cover_thumbnail/size1/page-0-1751522275.webp?1751522280" alt="Image 2">
<img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7856/cover_thumbnail/size1/Wed_Jul_02_2025_16_37_15_GMT_0530_%28India_Standard_Time%29.webp?1751454435" alt="Image 3">
<img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7853/cover_thumbnail/size1/Wed_Jul_02_2025_14_59_56_GMT_0530_%28India_Standard_Time%29.webp?1751448596" alt="Image 4">
<img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7658/cover_thumbnail/size1/Sun_Apr_06_2025_14_14_14_GMT_0530_%28India_Standard_Time%29.webp?1743929054" alt="Image 5">
<img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7337/cover_thumbnail/size1/Wed_Oct_02_2024_17_40_22_GMT_0530_%28India_Standard_Time%29.webp?1727871022" alt="Image 6">
<img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7326/cover_thumbnail/size1/Sun_Sep_29_2024_16_42_41_GMT_0530_%28India_Standard_Time%29.webp?1727608362" alt="Image 7">
<img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7323/cover_thumbnail/size1/Sun_Sep_29_2024_15_08_59_GMT_0530_%28India_Standard_Time%29.webp?1727602739" alt="Image 8">
<img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7298/cover_thumbnail/size1/page-0-1726487616.webp?1726487624" alt="Image 9">
<img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7296/cover_thumbnail/size1/page-0-1726488001.webp?1726488006" alt="Image 10">
<img src="https://djuc8g2q9bu2u.cloudfront.net/stories/7221/cover_thumbnail/size1/Mon_Jul_22_2024_16_08_44_GMT_0530_%28India_Standard_Time%29.webp?1721644722" alt="Image 11">

	  
	  
	  
	  
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
