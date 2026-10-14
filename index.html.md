```
birthday.html

```
<!DOCTYPE html>  
<html lang="th">  
<head>  
  <meta charset="UTF-8">  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">  
  <title>Happy Birthday **คุณแม่** 🎂❤️</title>  
  <style>  
    @import url('https://fonts.googleapis.com/css2?family=Mitr:wght@300;400;600&family=Sarabun:wght@400;600&display=swap');  
  
    body {  
      margin: 0;  
      padding: 20px;  
      background: linear-gradient(135deg, #ffd1dc 0%, #ffe6e8 100%);  
      font-family: 'Mitr', sans-serif;  
      display: flex;  
      flex-direction: column;  
      align-items: center;  
      justify-content: center;  
      min-height: 100vh;  
      box-sizing: border-box;  
      text-align: center;  
      color: #5a3d48;  
    }  
  
    .container {  
      background: rgba(255, 255, 255, 0.9);  
      padding: 30px 20px;  
      border-radius: 25px;  
      box-shadow: 0 10px 25px rgba(220, 120, 150, 0.2);  
      max-width: 450px;  
      width: 100%;  
    }  
  
    /* Cake Styling */  
    .cake-container {  
      position: relative;  
      margin: 30px auto;  
      width: 150px;  
      height: 120px;  
    }  
  
    .flame {  
      width: 16px;  
      height: 26px;  
      background: #ff9d00;  
      border-radius: 50% 50% 50% 50% / 60% 60% 40% 40%;  
      position: absolute;  
      top: -25px;  
      left: 50%;  
      transform: translateX(-50%);  
      box-shadow: 0 0 15px #ff9d00, 0 0 25px #ffbd59;  
      animation: flicker 0.6s infinite alternate;  
      transition: all 0.5s ease;  
    }  
  
    @keyframes flicker {  
      0% { transform: translateX(-50%) scale(1); }  
      100% { transform: translateX(-50%) scale(1.15); }  
    }  
  
    .flame.off {  
      opacity: 0;  
      transform: translateX(-50%) scale(0);  
    }  
  
    .candle {  
      width: 12px;  
      height: 35px;  
      background: linear-gradient(to bottom, #ff9a9e, #fecfef);  
      position: absolute;  
      top: 0;  
      left: 50%;  
      transform: translateX(-50%);  
      border-radius: 4px;  
    }  
  
    .cake {  
      width: 140px;  
      height: 80px;  
      background: #ffb6c1;  
      position: absolute;  
      bottom: 0;  
      left: 50%;  
      transform: translateX(-50%);  
      border-radius: 15px 15px 10px 10px;  
      box-shadow: inset 0 -10px 0 #f67280;  
    }  
  
    .cake::before {  
      content: '';  
      position: absolute;  
      top: 0;  
      left: 0;  
      width: 100%;  
      height: 25px;  
      background: #fff;  
      border-radius: 15px 15px 10px 10px;  
    }  
  
    /* Button */  
    .blow-btn {  
      background: #ff6b81;  
      color: white;  
      border: none;  
      padding: 12px 25px;  
      font-size: 1.1rem;  
      font-family: 'Mitr', sans-serif;  
      border-radius: 50px;  
      cursor: pointer;  
      box-shadow: 0 5px 15px rgba(255, 107, 129, 0.4);  
      transition: all 0.3s ease;  
      margin-top: 10px;  
    }  
  
    .blow-btn:hover {  
      background: #ff4757;  
      transform: scale(1.05);  
    }  
  
    /* Message Box */  
    .message-card {  
      display: none;  
      opacity: 0;  
      transition: opacity 1s ease;  
      margin-top: 20px;  
      font-family: 'Sarabun', sans-serif;  
      line-height: 1.8;  
      font-size: 1.05rem;  
      color: #4a4a4a;  
      text-align: left;  
      background: #fff5f6;  
      padding: 20px;  
      border-radius: 15px;  
      border: 2px dashed #ffb6c1;  
    }  
  
    .message-card.show {  
      display: block;  
      opacity: 1;  
    }  
  
    .highlight {  
      font-weight: bold;  
      color: #ff4757;  
      font-size: 1.2rem;  
      text-align: center;  
      margin-bottom: 15px;  
      display: block;  
    }  
  </style>  
</head>  
<body>  
  
  <div class="container">  
    <h2 id="title">🎂 **สุขสันต์วันเกิดนะแม่** 🎂</h2>  
      
    <div class="cake-container">  
      <div class="flame" id="flame"></div>  
      <div class="candle"></div>  
      <div class="cake"></div>  
    </div>  
  
    <button class="blow-btn" id="blowBtn" onclick="blowCandle()">**เป่าเทียนตรงนี้เลยแม่** 💨</button>  
  
    <div class="message-card" id="messageCard">  
      <span class="highlight">Happy Birthday to my mom 🎉</span>  
      **หนูขอให้เป็นอายุวัย**50**ที่ดีของแม่** **หนูรักแม่มากๆนะจ้ะ** **รักแม่ที่สุดในโลกเลย** **หนูขอบคุณที่แม่เกิดมาขอบคุณที่แม่เป็นแม่ที่เก่งมากๆๆๆๆๆทนกับลูกนิสัยไม่ดีแบบหนูได้ตลอดขอบคุณที่แม่ส่งหนูเรียนจนถึงตอนนี้เลี้ยงดูหนูสอนหนูให้เป็นคนเก่งของแม่ของทุกคน** **ละก็สุดท้ายหนูไม่เคยมีเค้กให้แม่เลยแต่ว่าสักวันหนึ่งหนูจะเอาเค้กวันเกิดให้แม่ให้ได้หนูสัญญาตอนนี้แม่เอาแต่คำอวยพรกากๆไปก่อนนะ**55555**หนูรักแม่ที่สุดในโลกเลย**❤️❤️🎂🎂  
    </div>  
  </div>  
  
  <script>  
    function blowCandle() {  
      // **ดับไฟเทียน**  
      document.getElementById('flame').classList.add('off');  
        
      // **ซ่อนปุ่มเป่า**  
      document.getElementById('blowBtn').style.display = 'none';  
        
      // **เปลี่ยนหัวข้อ**  
      document.getElementById('title').innerText = "❤️ **คำอวยพรจากใจลูก** ❤️";  
  
      // **แสดงการ์ดข้อความ**  
      setTimeout(() => {  
        document.getElementById('messageCard').classList.add('show');  
      }, 500);  
    }  
  </script>  
</body>  
</html>  
