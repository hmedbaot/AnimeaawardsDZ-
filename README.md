<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <title>جائزة أفضل أنمي لعام 2025</title>
  <style>
    body {
      background-color: #f2f2f2;
      font-family: 'Tahoma', sans-serif;
      text-align: center;
      padding: 30px;
    }
    .anime {
      margin: 30px auto;
      background: white;
      border-radius: 12px;
      padding: 20px;
      width: 80%;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    .anime img {
      width: 250px;
      border-radius: 8px;
    }
    .button {
      margin-top: 15px;
      padding: 10px 30px;
      font-size: 18px;
      background-color: #004080;
      color: white;
      border: none;
      border-radius: 6px;
      cursor: pointer;
    }
    .results, .reveal, iframe {
      display: none;
      margin-top: 20px;
    }
    .results p {
      font-size: 20px;
    }
    .reveal {
      font-size: 30px;
      color: red;
      font-weight: bold;
      margin-top: 50px;
    }
  </style>
</head>
<body>

  <h1>🇩🇿 وزارة الثقافة الجزائرية - استبيان رسمي لأفضل أنمي لعام 2025</h1>

  <div class="anime">
    <h2>Attack on Titan</h2>
    <img src="https://upload.wikimedia.org/wikipedia/en/f/f5/Attack_on_Titan_S4.jpg" alt="Attack on Titan">
    <br>
    <button class="button" onclick="vote('aot')">صوّت الآن</button>
  </div>

  <div class="anime">
    <h2>One Piece</h2>
    <img src="https://upload.wikimedia.org/wikipedia/en/2/2f/OnePieceVolume61Cover.png" alt="One Piece">
    <br>
    <button class="button" onclick="vote('onepiece')">صوّت الآن</button>
  </div>

  <div class="anime">
    <h2>Steins;Gate</h2>
    <img src="https://upload.wikimedia.org/wikipedia/en/3/3e/SteinsGate.jpg" alt="Steins Gate">
    <br>
    <button class="button" onclick="vote('steins')">صوّت الآن</button>
  </div>

  <div class="results" id="results">
    <p>🔸 Attack on Titan: 45%</p>
    <p>🔸 One Piece: 35%</p>
    <p>🔸 Steins;Gate: 20%</p>
  </div>

  <div class="reveal" id="reveal">
    😂 تم خداعك مجددًا يا صاحب العقل الصغير!<br>
    <span style="font-size: 24px;">- أيــزن (فعلتها بالمناسبة)</span>
    <br><br>
    <img src="https://media.tenor.com/D3YgZl6APaEAAAAC/aizen-sosuke.gif" alt="Aizen Laughing" width="300">
    <br>
    <iframe src="https://www.youtube.com/embed/5xvbE3zdtmE?autoplay=1" width="300" height="200" allow="autoplay"></iframe>
  </div>

  <!-- المقال -->
  <div style="text-align: right; direction: rtl; margin-top: 60px; background: #ffffff; padding: 20px; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.1); font-family: 'Tahoma', sans-serif; font-size: 16px; line-height: 1.9;">
    <h2 style="color: #004080;">🔍 نبذة عن أنمي "Attack on Titan"</h2>
    <p>
      يُعد أنمي "هجوم العمالقة" من أبرز الأعمال الفنية اليابانية التي حققت صدىً عالميًا واسعًا، لما يحمله من عمق درامي وإسقاطات سياسية واجتماعية جريئة، وأسلوب بصري مذهل.
    </p>
    <p>
      تدور القصة في عالم يعيش فيه البشر داخل أسوار ضخمة تحميهم من تهديد خارجي مرعب: العمالقة. تبدأ القصة باختراق أحد الأسوار، حيث يشهد "إيرين" مقتل والدته، ما يدفعه لبدء رحلته الانتقامية.
    </p>
    <p>
      تتطور القصة لاحقًا بشكل مفاجئ، لتتحول إلى صراع بين الأيديولوجيات، وتكشف عن مؤامرات دولية وحقائق مخفية حول أصل العمالقة والحضارات المختلفة.
    </p>
    <p>
      تتميز السلسلة بموسيقاها التصويرية الملحمية مثل "Treachery" و"Call of Silence"، وبشخصيات معقدة تقود القصة مثل ليفاي، زيك، وأرمين.
    </p>
    <p>
      يعتبره الكثيرون أعظم أنمي في التاريخ، لما فيه من واقعية قاتمة وطرح فلسفي عميق.
    </p>
    <p style="font-weight: bold; margin-top: 30px; font-size: 18px;">🚨 ملاحظة: التصويت حقيقي ويتم اعتماده من قبل لجنة الأنمي الوطنية.</p>
  </div>

  <script>
    function vote(choice) {
      if (choice === 'aot') {
        document.getElementById('results').style.display = 'block';
        setTimeout(() => {
          document.getElementById('reveal').style.display = 'block';
          document.querySelector('iframe').style.display = 'block';
        }, 2500);
      } else {
        // عرض النتائج فقط بدون خدعة
        document.getElementById('results').style.display = 'block';
      }
    }
  </script>

</body>
</html>