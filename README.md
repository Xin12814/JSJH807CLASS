<html lang="zh-Hant">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>JSJH 807 班級網站</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+TC&display=swap');

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: "DFKai-SB", "Noto Sans TC", sans-serif;
      background: linear-gradient(to bottom right, #FFD580, #FF8C42);
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: flex-start;
      min-height: 100vh;
      padding: 30px;
    }

    header {
      background: rgba(255, 255, 255, 0.2);
      backdrop-filter: blur(10px);
      border-radius: 20px;
      padding: 20px 40px;
      margin-bottom: 30px;
      text-align: center;
      color: #fff;
      font-size: 2.5em;
      font-weight: bold;
      animation: fadeIn 1.5s ease-out;
    }

    section {
      background: rgba(255, 255, 255, 0.2);
      backdrop-filter: blur(10px);
      border-radius: 20px;
      padding: 20px 40px;
      width: 90%;
      max-width: 700px;
      margin-bottom: 20px;
      text-align: center;
      color: #000;
      animation: slideUp 1s ease-out;
    }

    h2 {
      color: #2E6FA7;
      margin-bottom: 10px;
    }

    ul {
      list-style-type: none;
      padding-left: 0;
    }

    li {
      margin: 8px 0;
    }

    @keyframes slideUp {
      from {
        transform: translateY(30px);
        opacity: 0;
      }
      to {
        transform: translateY(0);
        opacity: 1;
      }
    }

    @keyframes fadeIn {
      from {
        opacity: 0;
        transform: scale(0.9);
      }
      to {
        opacity: 1;
        transform: scale(1);
      }
    }
  </style>
</head>
<body>
  <header>
    JSJH 807 班級網站
  </header>

  <section>
    <h2>班級幹部 / Class Officers</h2>
    <ul>
      <li>班長 / Class President: 8號</li>
      <li>副班長 / Vice Class President: 2號</li>
      <li>風紀股長 / Class Monitor: not yet</li>
      <li>副風紀股長 / Vice Class Monitor: not yet</li>
      <li>學藝股長 / Class Secretary: 27號</li>
      <li>副學藝股長 / Vice Class Secretary: 3號</li>
      <li>總務股長 / Class Treasurer: 23號</li>
    </ul>
  </section>

  <section>
    <h2>班級公告 / Class Announcements</h2>
    <p>日後將隨更新推出 / Will be released in future updates</p>
  </section>

  <section>
    <h2>學校行事曆 / School Calendar</h2>
    <p>日後將隨更新推出 / Will be released in future updates</p>
  </section>

  <section>
    <h2>照片專區 / Photo Gallery</h2>
    <p>目前無內容 / No content yet</p>
  </section>

</body>
</html>
