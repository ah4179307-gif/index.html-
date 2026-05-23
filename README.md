<! DOCTYPE html>
HTML.lang="ar" dir="rtl">
<رئيس.>
 <ميتا.charset="UTF-8"> 
    <العنوان.>منجم الذكاء الاصطناعي | المنصة الفلكية الاحترافية </العنوان.> 
 <ميتا.اسم="viewport" content="العرض=عرض على الجهاز, النطاق الأولي=1"> 
 <رابط.href="https://googleapis.com" rel="stylesheet"> 
 <السيناريو.src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></السيناريو.> 
   <أسلوب.> 
 الجسم.{الخلفية: خط التدرج (120deg، #181533 60٪، #422b5c 100٪) ؛ عائلة الخط: 'القاهرة'، سان-سيريف؛ الهامش:0؛ حشو:0؛ اللون: #fff؛ مين الارتفاع: 100vh؛}       
 رأس، تذييل. {الخلفية:#20183e;اللون:#ffe490;text-align:center;padding:1.2em 0 1em 0;font-size:2em;letter-spacing:.04em;box-shadow:0 2px 12px #0002;}
 تذييل. {الهامش أعلى:2em; الخلفية:#241a39;الحجم الأمامي:1em;اللون:#ffd700;}
 ناف. 
 عرض:مرن؛ تبرير المحتوى: المركز؛ فليكس التفاف: التفاف؛ الفجوة: 9px؛ 
 خلفية:#2d214b; حشو: .7em .1em 0 .1em; 
 مربع الظل: 0.7px 28px #23103b24; 
 } 
 زر الملاحة { 
 الخلفية: التدرج الخطي (90deg،#291c47 60٪، #b8954f4a) ؛ 
 الحدود: لا شيء؛ اللون:#ffda7c؛ 
 حجم الخط: 1.13em; 
 المؤشر: نقطة. 
 الحشو:.6EM 1.2EM. 
 الحدود-راديوس:9px; 
 وزن الخط: جريء. 
 الانتقال:.19s؛ 
 ترجمة الرسائل:.04em؛ 
 الهامش السفلي: .3EM؛ 
      box-shadow: 0 2px 13px #18133736;
    }
    nav button.active,nav button:hover {
      background:#ffe08c; color: #2d214b;
      box-shadow: 0 0 20px #ffd70050;
    }
    main {
      max-width:950px;
      margin:2.3em auto 2.2em auto;
      background:#2c003ed9;
      border-radius:22px;
      box-shadow:0 8px 32px #0005;
      padding:2.1em 1.6em 2.5em 1.6em;
      min-width:0;
      border:1.7px solid #bc9f64ad;
    }
    section{display:none;}
    section.active{display:block;}
    h2{color:#ffd700e0;border-bottom:2px solid #d4af3740;margin-bottom:0.38em;padding-bottom:0.14em;margin-top:.45em;}
    label {display:block;margin:.54em 0 0.3em 0;font-size:1.02em;}
    input,select,textarea{
      width:100%;padding:.75em;border-radius:7px;
      border:1.5px solid #361d43;font-size:1em;margin-bottom:.33em;
      background:#191028;color:#faebd3;
      font-family:inherit;box-sizing: border-width;
    }
    textarea{resize:vertical;}
    button.submit-btn {
      background: linear-gradient(90deg,#ffd700 89%,#ad8829 100%);
      color:#29213d;font-weight:bold;
      border:none;
      padding:.71em 1.18em;
      margin:.35em 0 .24em 0;
      border-radius:10px;
      cursor:pointer;
      font-size: 1.01em;
      box-shadow:0 2px 10px #ffd70030;
      transition:.15s;
      letter-spacing:.03em;
    }
    button.submit-btn:hover{background:#502b7c; color:#ffe08c;}
    .result-box, .ai-card {
      border-radius:11px;
      background:#1d12348e;
      padding:1.14em 1em 1em 1.21em;
      color:#fff;
      margin:.7em 0 .7em 0;
      box-shadow:0 2px 20px #ffedc226;
      border:1px solid #ad88293c;
    }
    .zod-list {display:flex;flex-wrap:wrap;gap:.8em;}
    .zod-chip {
      background:linear-gradient(90deg,#502b7c 53%,#ffe08c30);
      color:#ffe99b;
      padding:.44em 1.11em;
      border-radius:14px;
      font-size:1.03em;
      margin-bottom:.4em;
      font-weight:bold;
      border: none;
      box-shadow:0 2px 7px #ffd90019;
      cursor:pointer;
      transition:.13s;
    }
    .zod-chip.active{
      background:#ffd700ab; color:#30123c;
      box-shadow: 0 0 20px #ffd70070;
    }
    .moon-table{
      width:100%;margin-top:.71em;border-collapse:collapse;
      background:#150c24e6;font-size:1em;
    }
    .moon-table th,.moon-table td{
      border:1px solid #d4af3748; padding:.33em;
      text-align:center;
    }
    .moon-table th{background:#7b3fbfce;color:#fff;}
    .chat-box{
      background:#4227573d;
      border-radius:13px;
      min-height:150px;max-height:300px;overflow-y:auto;
      padding:.6em 1.08em;margin-bottom:.55em;
    }
    .chat-message {
      margin:.51em 0; padding:.7em 1.1em; border-radius:17px;
      max-width:83%; word-wrap:break-word;
    }
    .user-msg{background:#ffe699;color:#3a142a;float:left;clear:both;}
    .ai-msg{background:#502b7c;color:#fff;float:right;clear:both;}
    #export-pdf{
      margin-top:.8em; background:linear-gradient(90deg,#c3930e 80%,#fff69b 100%);
    }
    @media(max-width:770px){
      main{padding:.65em;}
      h2{font-size:1.17em;}
      .zod-chip{font-size:.92em;}
      nav button{font-size:1em;padding:.33em;}
    }
  </style>
</head>
<body>
  <header>منجم الذكاء الاصطناعي • منصة التنجيم والفلك العربية</header>
  <nav>
    <button class="active" data-section="home">الرئيسية</button>
    <button data-section="today">برج اليوم</button>
    <button data-section="birth">خريطة الميلاد</button>
    <button data-section="compat">توافق</button>
    <button data-section="number">الكود الكوني</button>
    <button data-section="allah">الأسماء الحسنى</button>
    <button data-section="surah">سورة قرآنية</button>
    <button data-section="palm">الكف</button>
    <button data-section="cup">الفنجان</button>
    <button data-section="moon">القمر</button>
    <button data-section="dream">الأحلام</button>
    <button data-section="chat">الدردشة الذكية</button>
  </nav>
  
  <main>
    <section id="home" class="active">
      <h2>مرحباً بك في منجم الذكاء الاصطناعي</h2>
      <p>بوابتك الفلكية والروحية المتكاملة المدمجة بأحدث تقنيات المحاكاة الذكية. استكشف الأقسام في الأعلى لاستخراج التقارير وقراءة الطالع بصيغة رقمية فورية.</p>
    </section>

    <section id="today">
       <h2>توقعات برجك اليوم الفلكية</h2> 
      <p>اختر برجك لقراءة الطالع الحالي:</p>
      <div class="zod-list" id="today-zod-list"></div>
      <div id="today-result" class="result-box" style="display:none;"></div>
    </section>

    <section id="birth">
      <h2>خريطة الميلاد الفلكية</h2>
      <label>الاسم بالكامل:</label><input type="text" id="b-name">
      <label>تاريخ الميلاد:</label><input type="date" id="b-date">
      <label>مكان الميلاد:</label><input type="text" id="b-place" placeholder="المدينة/الدولة">
      <button class="submit-btn" onclick="genBirthChart()">استخراج الخريطة</button>
      <div id="birth-result" class="result-box" style="display:none;"></div>
    </section>

    <section id="compat">
      <h2>تحليل التوافق بين البرجين</h2>
      <label>برج الطرف الأول:</label><select id="comp-z1"></select>
      <label>برج الطرف الثاني:</label><select id="comp-z2"></select>
      <button class="submit-btn" onclick="genCompat()">احسب التوافق</button>
      <div id="compat-result" class="result-box" style="display:none;"></div>
    </section>

    <section id="number">
      <h2>حساب الكود الكوني والعددي</h2>
      <label>اسمك واسم الأم (اختياري):</label><input type="text" id="num-name">
      <label>تاريخ ميلادك:</label><input type="date" id="num-date">
      <button class="submit-btn" onclick="genCosmicCode()">استخراج الكود</button>
      <div id="number-result" class="result-box" style="display:none;"></div>
    </section>

    <section id="allah">
      <h2>الورد الفلكي والأسماء الحسنى المناسبة لبرجك</h2>
      <label>أدخل اسمك:</label><input type="text" id="allah-name">
      <button class="submit-btn" onclick="genAllahNames()">استخراج الورد</button>
      <div id="allah-result" class="result-box" style="display:none;"></div>
    </section>

    <section id="surah">
        <h2>السورة القرآنية المناسبة لطاقتك الحالية</h2>  
      <label>بماذا تشعر اليوم؟</label>
      <select id="surah-mood">
         <option value="قلق">قلق أو خوف</option> 
        <option value="ضيق">ضيق في الرزق</option>
         <option value="حزن">حزن أو هم</option> 
        <option value="تشتت">تشتت وعدم توفيق</option>
      </select>
       <button class="submit-btn" onclick="genSurah()">معرفة السورة والورد</button> 
      <div id="surah-result" class="result-box" style="display:none;"></div>
    </section>

    <section id="palm">
          <h2>تحليل خطوط الكف بالذكاء الاصطناعي</h2>    
          <p>أجب عن شكل خط الحياة الرئيسي في كفك الأيمن:</p>    
      <select id="palm-line">
           <option value="طويل">طويل وعميق وممتد</option>   
           <option value="قصير">قصير ومتفرع</option>   
            <option value="متقطع">متقطع أو باهت</option>    
     </اختيار> 
         <button class="submit-btn" onclick="genPalm()">تحليل الكف</button>   
     <div id="palm-result" Class="Reult-box" Style="العرض:لا شيء";"></div> 
    </القسم>

    <القسم id="كوب">
         <h2>قراءة الفنجان الافتراضية</h2>   
         <p>تخيل أنك شربت فنجانك، ما الرمز الأبرز المفترض ظهوره في مخيلتك؟</p>   
        <حدد ID="شكل الكأس">    
            <option value="طائر">طائر أو حمامة</option>    
            <option value="شجرة">شجرة أو نخلة</option>    
            <option value="طريق">طريق ممتد أو أفعى</option>    
            <option value="خاتم">خاتم أو قفل</option>    
     <اختيار> 
          <button class="submit-btn" onclick="genCup()">تبصير الفنجان</button>    
     <div id="كوب نتيجة" class="Reult-box" style="عرض: لا شيء;"></div> 
    </القسم>

    <القسم ID="القمر">
            <h2>مرازل القمر الحالية وتأثيرها الطاقي</h2>      
            <p>جدول الطاقات القمرية المحدث:</p>      
          <فئة الجدول ="الطاولة القمرية">      
         الرأس>     
               <tr><th>المنزلة القمرية</th><th>الحالة الطاقية</th><th>النصيحة الفلكية اليومية</th></tr>     
     <thead> 
         الجسم>     
               <tr><td>البدر الافتراضي</td><td>طاقة مكتملة وتجلي</td><td>مناسب للتأمل وتجنب القرارات الانفعالية.</td></tr>     
               <tr><td>الهلال المتزايد</td><td>بدايات جديدة وشحن</td><td>ابدأ بتنفيذ خططك المهنية والمالية الآن.</td></tr>     
         /الجسم>     
         </الجدول>     
    </القسم>

    <القسم id="الحلم">
           <h2>تفسير الأحلام الرمزي الفوري</h2>     
           <label>اكتب حلمك أو الرمز الأساسي فيه باختصار:</label>     
     <textarea id="dream-text" Rows="3" placeholder="مثال: رؤية البحر، "...></textarea> 
            <button class="submit-btn" onclick="genDream()">تفسير الحلم</button>      
 <div id=""الحلم-النتيجة" Class="صندوق النتائج" style="عرض: لا شيء;"></div> 
    </القسم>

    <القسم id="دردشة">
        <h2>المستشار الفلكي والروحي الذكي</h2>  
# index.html-
علم التنجيم horscope.ai مجانا.
