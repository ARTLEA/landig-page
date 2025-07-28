
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>MADE BY ME - اشترك الآن!</title>
  <link href="https://fonts.googleapis.com/css?family=Cairo:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Cairo', sans-serif;
      background: linear-gradient(135deg, #f2f4ff 0%, #e0e7ff 100%);
      margin: 0;
      padding: 0;
      color: #222;
    }
    .container {
      max-width: 900px;
      margin: 0 auto;
      padding: 40px 20px;
      background: #fff;
      border-radius: 16px;
      box-shadow: 0 6px 32px rgba(99, 102, 241, 0.06);
      margin-top: 40px;
    }
    h1 {
      color: #3730a3;
      font-size: 2.5rem;
      margin-bottom: 12px;
      text-align: center;
    }
    .subtitle {
      color: #6366f1;
      font-size: 1.3rem;
      text-align: center;
      margin-bottom: 32px;
    }
    .features {
      display: flex;
      flex-wrap: wrap;
      gap: 24px;
      margin-bottom: 32px;
      justify-content: center;
    }
    .feature {
      flex: 1 1 280px;
      background: #f5f6fa;
      border-radius: 12px;
      padding: 20px;
      min-width: 260px;
      box-shadow: 0 2px 8px rgba(99,102,241,0.04);
      margin-bottom: 15px;
    }
    .feature h3 {
      color: #3730a3;
      margin-top: 0;
      margin-bottom: 8px;
    }
    .offer {
      background: #6366f1;
      color: #fff;
      padding: 16px 24px;
      border-radius: 12px;
      font-size: 1.2rem;
      margin-bottom: 24px;
      text-align: center;
      font-weight: bold;
      letter-spacing: 1px;
      box-shadow: 0 4px 16px rgba(99,102,241,0.12);
    }
    .timer {
      font-size: 2rem;
      color: #3730a3;
      text-align: center;
      margin-bottom: 32px;
      font-weight: bold;
      letter-spacing: 2px;
    }
    form {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 16px;
      margin-bottom: 24px;
    }
    input[type="text"], input[type="email"] {
      padding: 12px 18px;
      border-radius: 8px;
      border: 1px solid #d1d5db;
      font-size: 1rem;
      width: 300px;
      transition: border-color 0.2s;
    }
    input[type="text"]:focus, input[type="email"]:focus {
      border-color: #6366f1;
      outline: none;
    }
    button {
      background: linear-gradient(90deg, #6366f1 0%, #3730a3 100%);
      color: #fff;
      font-size: 1.1rem;
      font-weight: bold;
      padding: 12px 36px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      transition: background 0.2s;
    }
    button:hover {
      background: linear-gradient(90deg, #3730a3 0%, #6366f1 100%);
    }
    .success-message {
      color: #16a34a;
      text-align: center;
      margin-top: 10px;
      font-weight: bold;
    }
    @media (max-width: 600px) {
      .features {
        flex-direction: column;
      }
      input[type="text"], input[type="email"] {
        width: 98%;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>MADE BY ME</h1>
    <div class="subtitle">أنشئ متجرك، بيع تصاميمك، تواصل مع مجتمعك، وحقق دخلك من أي مكان!</div>
    
    <div class="offer">
      ⭐ عرض خاص: شهر مجاني للمستخدمين الأوائل على MADE BY ME! ⭐
    </div>
    <div class="timer" id="timer">
      15 يوم 00:00:00
    </div>

    <form id="signup-form" autocomplete="off">
      <input type="text" id="name" name="name" placeholder="الاسم الكامل" required>
      <input type="email" id="email" name="email" placeholder="البريد الإلكتروني" required>
      <button type="submit">اشترك الآن واحصل على شهر مجاني</button>
    </form>
    <div class="success-message" id="successMessage" style="display:none;">
      شكراً لانضمامك إلى MADE BY ME! سنتواصل معك قريباً 🎉
    </div>

    <h2 style="color:#6366f1; text-align:center; margin-top:30px;">خصائص منصة MADE BY ME</h2>
    <div class="features">
      <div class="feature">
        <h3>متاجر شخصية للمصممين</h3>
        <p>أنشئ متجرك الخاص، اعرض وبيع منتجاتك الرقمية بسهولة واحترافية عبر MADE BY ME.</p>
      </div>
      <div class="feature">
        <h3>تكامل مع Figma وCanva</h3>
        <p>استورد وصدر تصاميمك مباشرة من وإلى أدواتك المفضلة بضغطة زر عبر MADE BY ME.</p>
      </div>
      <div class="feature">
        <h3>تحليل سلوك المستخدم بالذكاء الاصطناعي</h3>
        <p>احصل على توصيات مخصصة لتحسين أعمالك ومسارك المهني وحتى اقتراحات للسفر والعمل عن بعد.</p>
      </div>
      <div class="feature">
        <h3>مجتمع تفاعلي حقيقي</h3>
        <p>غرف دردشة ولقاءات حية تجمعك مع مصممين من مدينتك أو حول العالم عبر MADE BY ME.</p>
      </div>
      <div class="feature">
        <h3>تسويق تلقائي لمنتجاتك</h3>
        <p>المنصة تروج تلقائياً لتصاميمك لجمهور واسع وتساعدك على زيادة مبيعاتك.</p>
      </div>
      <div class="feature">
        <h3>أمان وحماية</h3>
        <p>حماية بياناتك وحقوق تصاميمك أولوية قصوى لدينا في MADE BY ME.</p>
      </div>
      <div class="feature">
        <h3>نموذج ربحي عادل</h3>
        <p>عمولة منخفضة واشتراكات اختيارية لمزايا متقدمة تناسب جميع الاحتياجات.</p>
      </div>
    </div>
  </div>

  <script>
    // عداد زمني تنازلي لمدة 15 يوم
    var countDownDate = new Date().getTime() + 15*24*60*60*1000; // 15 يوم

    var timer = setInterval(function() {
      var now = new Date().getTime();
      var distance = countDownDate - now;

      var days = Math.floor(distance / (1000 * 60 * 60 * 24));
      var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
      var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
      var seconds = Math.floor((distance % (1000 * 60)) / 1000);

      document.getElementById("timer").innerHTML = 
        days + " يوم " + 
        (hours < 10 ? "0" : "") + hours + ":" + 
        (minutes < 10 ? "0" : "") + minutes + ":" + 
        (seconds < 10 ? "0" : "") + seconds;

      if (distance < 0) {
        clearInterval(timer);
        document.getElementById("timer").innerHTML = "انتهى العرض";
      }
    }, 1000);

    // معالجة نموذج الاشتراك
    document.getElementById('signup-form').addEventListener('submit', function(e) {
      e.preventDefault();
      // يمكنك هنا ربط النموذج بخدمة مثل Mailchimp أو Google Sheets
      document.getElementById('successMessage').style.display = 'block';
      document.getElementById('signup-form').reset();
    });
  </script>
</body>
</html>
