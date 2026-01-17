# Utsab
It’s a event management company 
<!DOCTYPE html>
<html lang="bn">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>উৎসব - Event Management Company</title>
  <style>
    /* Reset and base */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Arial', sans-serif;
    }

    body {
      background-color: #fff7f0;
      color: #5a1f2a;
      line-height: 1.6;
    }

    header {
      background: #b3323f;
      color: #fff;
      padding: 20px 10%;
      display: flex;
      align-items: center;
      justify-content: space-between;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.15);
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    /* Logo with Bengali text */
    .logo {
      font-family: 'SolaimanLipi', Arial, sans-serif;
      font-size: 1.8rem;
      font-weight: bold;
      letter-spacing: 2px;
      color: #d94a30;
      cursor: default;
      user-select: none;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      margin-left: 25px;
      font-weight: 600;
      font-size: 1rem;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #f8c471;
    }

    main {
      max-width: 1200px;
      margin: 30px auto;
      padding: 0 20px;
    }

    section {
      margin-bottom: 60px;
    }

    h1, h2 {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      color: #a12f3b;
      margin-bottom: 15px;
    }

    p {
      margin-bottom: 20px;
      color: #452427;
      font-size: 1.1rem;
    }

    /* Home Section */
    .home-banner {
      background: linear-gradient(135deg, #d94a30, #7f2c37);
      color: #fff;
      padding: 100px 20px;
      text-align: center;
      border-radius: 15px;
      box-shadow: 0 10px 20px rgba(217, 74, 48, 0.5);
    }

    .home-banner h1 {
      font-size: 3rem;
      margin-bottom: 15px;
      letter-spacing: 3px;
    }

    .home-banner p {
      font-size: 1.5rem;
      font-weight: 600;
    }

    /* Services */
    .services-list {
      display: flex;
      flex-wrap: wrap;
      gap: 25px;
    }

    .service {
      background: #ffd6cc;
      border-radius: 12px;
      padding: 25px;
      flex: 1 1 280px;
      box-shadow: 0 5px 15px rgba(217, 74, 48, 0.3);
      transition: transform 0.3s ease;
    }

    .service:hover {
      transform: translateY(-10px);
    }

    .service h3 {
      margin-bottom: 12px;
      color: #a12f3b;
    }

    /* Events Gallery */
    .events-gallery {
      display: grid;
      gap: 20px;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    }

    .event-item {
      position: relative;
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 5px 15px rgba(217, 74, 48, 0.3);
    }

    .event-item img {
      width: 100%;
      display: block;
      height: 180px;
      object-fit: cover;
      transition: transform 0.3s ease;
    }

    .event-item:hover img {
      transform: scale(1.1);
    }

    .event-caption {
      position: absolute;
      bottom: 10px;
      left: 15px;
      color: #fff;
      background: rgba(163, 47, 50, 0.7);
      padding: 8px 12px;
      border-radius: 6px;
      font-weight: 600;
      font-size: 1rem;
    }

    /* Contact Form */
    form {
      max-width: 600px;
      margin: 0 auto;
      background: #f27f70;
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 6px 18px rgba(210, 71, 55, 0.5);
      color: #fff;
    }

    form label {
      display: block;
      margin-bottom: 8px;
      font-weight: 700;
    }

    form input,
    form textarea {
      width: 100%;
      padding: 12px 10px;
      margin-bottom: 20px;
      border: none;
      border-radius: 8px;
      font-size: 1rem;
      font-family: inherit;
    }

    form textarea {
      resize: vertical;
      min-height: 100px;
    }

    form button {
      cursor: pointer;
      background: #a4323a;
      border: none;
      padding: 14px 28px;
      font-size: 1.2rem;
      font-weight: 700;
      border-radius: 10px;
      color: #fff;
      transition: background 0.3s ease;
    }

    form button:hover {
      background: #7f2327;
    }

    footer {
      background: #7f2c37;
      color: #fff;
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
      letter-spacing: 1.1px;
    }

    /* Responsive Nav */
    @media (max-width: 700px) {
      nav {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        margin-top: 10px;
      }

      nav a {
        margin: 10px 15px 0 15px;
      }

      .services-list {
        flex-direction: column;
      }
    }
  </style>
</head>

<body>
  <header>
    <div class="logo">উৎসব</div>
    <nav>
      <a href="#home">হোম</a>
      <a href="#about">আমাদের সম্পর্কে</a>
      <a href="#services">সেবাসমূহ</a>
      <a href="#events">ইভেন্টস</a>
      <a href="#contact">যোগাযোগ</a>
    </nav>
  </header>

  <main>
    <!-- Home Section -->
    <section id="home" class="home-banner" aria-label="Welcome banner">
      <h1>উৎসব</h1>
      <p>আপনার সেরা ইভেন্ট ম্যানেজমেন্ট পার্টনার</p>
    </section>

    <!-- About Us -->
    <section id="about" aria-labelledby="about-title">
      <h2 id="about-title">আমাদের সম্পর্কে</h2>
      <p>
        উৎসব হলো এক বিশ্বস্ত ইভেন্ট ম্যানেজমেন্ট কোম্পানি, যা আপনাদের বিশেষ দিনগুলোকে স্মরণীয় করে তোলে।
        আমরা আপনার পারিবারিক অনুষ্ঠান থেকে কর্পোরেট ইভেন্ট পর্যন্ত সকল ধরণের আয়োজনের দায়িত্ব নিই।
      </p>
    </section>

    <!-- Services -->
    <section id="services" aria-labelledby="services-title">
      <h2 id="services-title">সেবাসমূহ</h2>
      <div class="services-list">
        <div class="service">
          <h3>বিবাহ উৎসব</h3>
          <p>আপনার বিশেষ দিনে মনোমুগ্ধকর সজ্জা ও ব্যবস্থাপনার মাধ্যমে স্মরণীয় মুহূর্ত তৈরি করি।</p>
        </div>
        <div class="service">
          <h3>কর্পোরেট ইভেন্টস</h3>
          <p>আপনার কোম্পানির বড় আয়োজনগুলো নিখুঁত পরিকল্পনা ও বাস্তবায়নে সহায়তা করি।</p>
        </div>
        <div class="service">
          <h3>সংস্কৃতিক অনুষ্ঠান</h3>
          <p>সাংস্কৃতিক ইভেন্টের জন্য প্রয়োজনীয় সকল ব্যবস্থা ও আয়োজন আমরা সম্পূর্ণ দক্ষতার সাথে পরিচালনা করি।</p>
        </div>
        <div class="service">
          <h3>পার্সোনাল পার্টি</h3>
          <p>আপনার ব্যক্তিগত উৎসবগুলো আরও জমকালো করতে আমাদের সেবাগুলো গ্রহণ করুন।</p>
        </div>
      </div>
    </section>

    <!-- Events -->
    <section id="events" aria-labelledby="events-title">
      <h2 id="events-title">ইভেন্টস গ্যালারি</h2>
      <div class="events-gallery">
        <div class="event-item" tabindex="0">
          <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=600&q=80" alt="বিবাহ অনুষ্ঠান সাজসজ্জা" />
          <div class="event-caption">বিবাহ অনুষ্ঠান</div>
        </div>
        <div class="event-item" tabindex="0">
          <img src="https://images.unsplash.com/photo-1556741533-f6acd647d2fb?auto=format&fit=crop&w=600&q=80" alt="কর্পোরেট সেমিনার" />
          <div class="event-caption">কর্পোরেট ইভেন্ট</div>
        </div>
        <div class="event-item" tabindex="0">
          <img src="https://images.unsplash.com/photo-1518609878373-06d740f60d8b?auto=format&fit=crop&w=600&q=80" alt="সাংস্কৃতিক অনুষ্ঠান" />
          <div class="event-caption">সাংস্কৃতিক অনুষ্ঠান</div>
        </div>
        <div class="event-item" tabindex="0">
          <img src="https://images.unsplash.com/photo-1504384308090-c894fdcc538d?auto=format&fit=crop&w=600&q=80" alt="পার্টি আয়োজন" />
          <div class="event-caption">পার্সোনাল পার্টি</div>
        </div>
      </div>
    </section>

    <!-- Contact -->
    <section id="contact" aria-labelledby="contact-title">
      <h2 id="contact-title">যোগাযোগ করুন</h2>
      <form>
        <label for="name">পূর্ণ নাম</label>
        <input type="text" id="name" name="name" placeholder="আপনার নাম লিখুন" required />

        <label for="email">ইমেইল</label>
        <input type="email" id="email" name="email" placeholder="আপনার ইমেইল লিখুন" required />

        <label for="message">বার্তা</label>
        <textarea id="message" name="message" placeholder="আপনার বার্তা লিখুন" required></textarea>

        <button type="submit">প্রেরণ করুন</button>
      </form>
    </section>
  </main>

  <footer>
    &copy; ২০২৪ উৎসব | ইভেন্ট ম্যানেজমেন্ট কোম্পানি | সর্বস্বত্ব সংরক্ষিত
  </footer>
</body>

</html>
