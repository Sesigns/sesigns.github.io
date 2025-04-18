<!DOCTYPE html><html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>مصمم جرافيك</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f5f5f5;
      color: #333;
    }
    header {
      background-color: #444;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      background-color: #666;
    }
    nav a {
      color: white;
      text-decoration: none;
      padding: 1rem;
      display: block;
    }
    nav a:hover {
      background-color: #888;
    }
    section {
      padding: 2rem;
    }
    .services, .portfolio {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1rem;
    }
    .service, .work {
      background-color: white;
      padding: 1rem;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      text-align: center;
    }
    form {
      max-width: 400px;
      margin: auto;
      display: flex;
      flex-direction: column;
    }
    input, textarea {
      margin-bottom: 1rem;
      padding: 0.75rem;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      background-color: #444;
      color: white;
      padding: 0.75rem;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background-color: #333;
    }
  </style>
</head>
<body>
  <header>
    <h1>مصمم جرافيك</h1>
    <p>أعرض خدماتي وأعمالي في التصميم</p>
  </header>
  <nav>
    <a href="#about">من نحن</a>
    <a href="#services">خدماتنا</a>
    <a href="#portfolio">معرض الأعمال</a>
    <a href="#contact">تواصل معنا</a>
  </nav>  <section id="about">
    <h2>من نحن</h2>
    <p>أنا مصمم جرافيك محترف، أقدم حلول تصميم إبداعية للعلامات التجارية، الإعلانات، والهوية البصرية.</p>
  </section>  <section id="services">
    <h2>خدماتنا</h2>
    <div class="services">
      <div class="service">
        <h3>تصميم شعارات</h3>
        <p>تصميم احترافي يعبر عن هوية العلامة التجارية.</p>
      </div>
      <div class="service">
        <h3>تصميم سوشيال ميديا</h3>
        <p>تصاميم جذابة لمنصات التواصل.</p>
      </div>
      <div class="service">
        <h3>تصميم مطبوعات</h3>
        <p>كروت، بروشورات، بوسترات والمزيد.</p>
      </div>
    </div>
  </section>  <section id="portfolio">
    <h2>معرض الأعمال</h2>
    <div class="portfolio">
      <div class="work">صورة 1</div>
      <div class="work">صورة 2</div>
      <div class="work">صورة 3</div>
    </div>
  </section>  <section id="contact">
    <h2>تواصل معنا</h2>
    <form>
      <input type="text" placeholder="الاسم" required>
      <input type="email" placeholder="البريد الإلكتروني" required>
      <textarea rows="4" placeholder="رسالتك" required></textarea>
      <button type="submit">إرسال</button>
    </form>
  </section>
</body>
</html>
