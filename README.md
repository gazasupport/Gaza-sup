<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Help Gaza - Charity Organization</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: Arial, sans-serif; }
    body { line-height: 1.6; background-color: #f4f4f4; color: #333; }
    header { background-color: #005555; color: white; padding: 1rem 0; text-align: center; position: relative; }
    nav ul { list-style: none; display: flex; justify-content: center; gap: 20px; margin-top: 10px; }
    nav a { color: white; text-decoration: none; font-weight: bold; }
    #lang-toggle { position: absolute; top: 20px; right: 20px; background: #fff; border: 1px solid #ccc; padding: 5px 10px; border-radius: 5px; cursor: pointer; }
    section { padding: 2rem; text-align: center; }
    .btn { display: inline-block; background-color: #009999; color: white; padding: 0.75rem 1.5rem; margin-top: 1rem; border: none; text-decoration: none; border-radius: 5px; transition: background-color 0.3s; }
    .btn:hover { background-color: #007777; }
    form { max-width: 500px; margin: 0 auto; display: flex; flex-direction: column; gap: 1rem; }
    input, textarea { padding: 0.75rem; border: 1px solid #ccc; border-radius: 5px; width: 100%; }
    button { padding: 0.75rem; background-color: #009999; color: white; border: none; border-radius: 5px; cursor: pointer; }
    button:hover { background-color: #007777; }
    footer { background-color: #003333; color: white; text-align: center; padding: 1rem 0; }
    .gallery { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 15px; margin-top: 20px; }
    .gallery img { width: 100%; border-radius: 10px; }
    .progress-bar { width: 80%; margin: 20px auto; background-color: #ccc; border-radius: 10px; overflow: hidden; height: 25px; }
    .progress-bar-fill { height: 100%; background-color: #009999; width: 65%; color: white; display: flex; align-items: center; justify-content: center; font-weight: bold; }
    .blog-post { text-align: left; background: white; margin: 10px auto; max-width: 700px; padding: 20px; border-radius: 10px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
    [dir="rtl"] { direction: rtl; text-align: right; }
    @media (max-width: 768px) { nav ul { flex-direction: column; } }
  </style>
</head>
<body>
  <button id="lang-toggle">AR</button>
  <header>
    <h1 data-en="Help Gaza" data-ar="ساعدوا غزة">Help Gaza</h1>
    <nav>
      <ul>
        <li><a href="#home" data-en="Home" data-ar="الرئيسية">Home</a></li>
        <li><a href="#about" data-en="About" data-ar="من نحن">About</a></li>
        <li><a href="#donate" data-en="Donate" data-ar="تبرع">Donate</a></li>
        <li><a href="#gallery" data-en="Gallery" data-ar="معرض الصور">Gallery</a></li>
        <li><a href="#blog" data-en="News" data-ar="الأخبار">News</a></li>
        <li><a href="#contact" data-en="Contact" data-ar="اتصل بنا">Contact</a></li>
      </ul>
    </nav>
  </header>  <section id="home">
    <h2 data-en="Support Gaza, Support Humanity" data-ar="ادعموا غزة، ادعموا الإنسانية">Support Gaza, Support Humanity</h2>
    <p data-en="Your donations provide food, medical care, and shelter to those in need." data-ar="تبرعاتكم توفر الغذاء والرعاية الطبية والمأوى للمحتاجين.">Your donations provide food, medical care, and shelter to those in need.</p>
    <img src="https://via.placeholder.com/800x300?text=Support+Gaza" alt="Support Gaza" style="width:100%;margin:20px 0;border-radius:10px;">
    <a href="#donate" class="btn" data-en="Donate Now" data-ar="تبرع الآن">Donate Now</a>
  </section>  <section id="about">
    <h2 data-en="About Us" data-ar="من نحن">About Us</h2>
    <p data-en="We are a non-profit dedicated to delivering aid and support to Gaza. Every donation goes directly to families in urgent need."
       data-ar="نحن منظمة غير ربحية مكرسة لتقديم المساعدة والدعم لغزة. كل تبرع يذهب مباشرةً للعائلات المحتاجة.">
       We are a non-profit dedicated to delivering aid and support to Gaza. Every donation goes directly to families in urgent need.
    </p>
    <img src="https://via.placeholder.com/600x200?text=Our+Mission" alt="Our Mission" style="width:100%;margin-top:20px;border-radius:10px;">
  </section>  <section id="donate">
    <h2 data-en="Make a Donation" data-ar="قدم تبرعًا">Make a Donation</h2>
    <p data-en="Select your preferred payment method:" data-ar="اختر وسيلة الدفع المفضلة:">Select your preferred payment method:</p>
    <div class="payments">
      <a href="https://www.paypal.com/donate" target="_blank" class="btn" data-en="Donate via PayPal" data-ar="تبرع عبر بايبال">Donate via PayPal</a>
      <a href="https://stripe.com/donate" target="_blank" class="btn" data-en="Donate via Stripe" data-ar="تبرع عبر سترايب">Donate via Stripe</a>
    </div>
    <div class="progress-bar">
      <div class="progress-bar-fill" style="width: 65%;">$6,500 / $10,000</div>
    </div>
  </section>  <section id="gallery">
    <h2 data-en="Photo Gallery" data-ar="معرض الصور">Photo Gallery</h2>
    <div class="gallery">
      <img src="https://via.placeholder.com/300x200?text=Relief+1" alt="Relief">
      <img src="https://via.placeholder.com/300x200?text=Relief+2" alt="Relief">
      <img src="https://via.placeholder.com/300x200?text=Relief+3" alt="Relief">
      <img src="https://via.placeholder.com/300x200?text=Relief+4" alt="Relief">
    </div>
  </section>  <section id="blog">
    <h2 data-en="Latest News" data-ar="آخر الأخبار">Latest News</h2>
    <div class="blog-post">
      <h3 data-en="Food Delivered to 100 Families" data-ar="تم توصيل الغذاء إلى 100 عائلة">Food Delivered to 100 Families</h3>
      <p data-en="This week, we distributed essential food packages to 100 families in Gaza." data-ar="هذا الأسبوع، قمنا بتوزيع حزم غذائية أساسية على 100 عائلة في غزة.">This week, we distributed essential food packages to 100 families in Gaza.</p>
    </div>
    <div class="blog-post">
      <h3 data-en="Emergency Medical Aid Provided" data-ar="توفير مساعدات طبية طارئة">Emergency Medical Aid Provided</h3>
      <p data-en="Medical teams have reached remote areas to deliver urgent care." data-ar="وصلت الفرق الطبية إلى المناطق النائية لتقديم الرعاية العاجلة.">Medical teams have reached remote areas to deliver urgent care.</p>
    </div>
  </section>  <section id="contact">
    <h2 data-en="Contact Us" data-ar="اتصل بنا">Contact Us</h2>
    <form action="mailto:yourcharity@email.com" method="post" enctype="text/plain">
      <input type="text" name="name" placeholder="Your Name">
      <input type="email" name="email" placeholder="Your Email">
      <textarea name="message" placeholder="Your Message"></textarea>
      <button type="submit" data-en="Send Message" data-ar="أرسل الرسالة">Send Message</button>
    </form>
  </section>  <footer>
    <p data-en="© 2025 Help Gaza. All rights reserved." data-ar="© 2025 ساعدوا غزة. جميع الحقوق محفوظة.">&copy; 2025 Help Gaza. All rights reserved.</p>
  </footer>  <script>
    const toggle = document.getElementById('lang-toggle');
    let isArabic = false;

    toggle.addEventListener('click', () => {
      isArabic = !isArabic;
      document.body.dir = isArabic ? 'rtl' : 'ltr';
      toggle.textContent = isArabic ? 'EN' : 'AR';
      document.querySelectorAll('[data-en]').forEach(el => {
        el.textContent = isArabic ? el.getAttribute('data-ar') : el.getAttribute('data-en');
      });
    });
  </script></body>
</html>
