<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Nishanthan Suseekaran | Personal Website</title>
<meta name="description" content="Nishanthan Suseekaran's personal profile, education, work experience, family and life journey.">

<style>
*{margin:0;padding:0;box-sizing:border-box}
html{scroll-behavior:smooth}
body{font-family:Arial,sans-serif;background:#f1f5fa;color:#172033;line-height:1.7}

/* Header & Navigation */
header{background:#071b35;color:white;padding:15px 5%;display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:10px}
.logo{font-size:18px;font-weight:bold}
nav{display:flex;flex-wrap:wrap;gap:10px;justify-content:center}
nav a{color:white;text-decoration:none;font-size:13px}
nav a:hover{color:#8ddfff}

/* Hero Section - Dark Maroon Background */
.hero{
  position:relative;
  background:linear-gradient(135deg, #3a0007, #5c0f18);
  color:white;
  padding:40px 6%;
  padding-left:190px;
  min-height:360px;
}

/* Profile Photo */
.profile{
  position:absolute;
  top:35px;
  left:6%;
  width:130px;
  height:130px;
  object-fit:cover;
  object-position:center;
  border-radius:12px;
  border:3px solid white;
  background:#dceeff;
}

/* Hero Content Area */
.hero-content {
  margin-left: 10px;
}

.hero h1{
  font-size:clamp(22px, 4vw, 36px);
  margin-bottom: 5px;
}

.name-line {
  width: 100%;
  max-width: 400px;
  height: 2px;
  background-color: #8ddfff;
  margin-bottom: 12px;
}

/* Contact Details with Symbols/Icons */
.contact-mini{
  margin-bottom: 15px;
  font-size: 14px;
  display: flex;
  flex-direction: column;
  gap: 8px;
  overflow-wrap: anywhere;
}

.contact-item {
  display: flex;
  align-items: center;
  gap: 10px;
}

.contact-icon {
  display: inline-flex;
  justify-content: center;
  align-items: center;
  width: 28px;
  height: 28px;
  border-radius: 50%;
  font-size: 13px;
  color: white;
  box-shadow: 0 2px 4px rgba(0,0,0,0.2);
}

.email-icon { background: #ea4335; }    /* Red */
.phone-icon { background: #34a853; }    /* Green */
.whatsapp-icon { background: #25d366; } /* WhatsApp Green */
.map-icon { background: #1a73e8; }      /* Blue for Maps */

.contact-mini a{
  color: #d5f4ff;
  text-decoration: none;
}
.contact-mini a:hover {
  text-decoration: underline;
}

/* CV Button placed below Profile Photo on the left */
.cv-container {
  margin-top: 15px;
}
.button{
  display:inline-block;
  background:white;
  color:#071b35;
  text-decoration:none;
  padding:9px 15px;
  border-radius:8px;
  font-weight:bold;
  font-size: 14px;
}
.cv-button{background:#8ddfff}

/* Main Content & Sections */
main{max-width:1000px;margin:auto;padding:25px 16px}
section{background:white;padding:25px;margin:22px 0;border-radius:14px;box-shadow:0 4px 15px rgba(0,0,0,.05);scroll-margin-top:20px}
section h2{color:#104a76;margin-bottom:12px;font-size:24px}
.card{border-left:4px solid #7a28b8;padding:14px 16px;margin-top:15px;background:#f5f9fd;border-radius:5px}
.lovestory-link,.family-link,.footer-link{color:#075b91;font-weight:bold;overflow-wrap:anywhere}
ul{padding-left:22px}
footer{text-align:center;background:#071b35;color:white;padding:30px 15px;margin-top:25px;line-height:1.8}
.footer-box{max-width:600px;margin:0 auto 20px auto;text-align:left;background:rgba(255,255,255,0.08);padding:20px;border-radius:10px}

/* Mobile Responsive Adjustments */
@media(max-width:768px){
  header{flex-direction:column;text-align:center;padding:15px}
  nav{justify-content:center;gap:8px}
  .hero{
    padding:25px 20px;
    padding-left:20px;
    text-align:left;
  }
  .profile{
    position:static;
    display:block;
    width:110px;
    height:110px;
    margin:0 0 15px 0;
  }
  .hero-content {
    margin-left: 0;
  }
  .name-line {
    max-width: 100%;
  }
}
</style>
</head>

<body>

<header>
  <div class="logo">Nishanthan Suseekaran</div>
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About Me</a>
    <a href="#education">Education</a>
    <a href="#work">Work</a>
    <a href="#lovestory">Love Story</a>
    <a href="#family">My Family</a>
  </nav>
</header>

<div class="hero" id="home">

  <!-- Profile Photo (Left Side) -->
  <img class="profile"
       src="IMG_20260924_071849.jpg"
       alt="Nishanthan Suseekaran profile photo"
       onerror="this.alt='Profile photo file not found'">

  <!-- Download CV Button placed below Profile Photo -->
  <div class="cv-container">
    <a class="button cv-button" href="CV_Nishan.pdf" download>Download My CV ↓</a>
  </div>

  <!-- Hero Content (Right Side) -->
  <div class="hero-content">
    <h1>Nishanthan Suseekaran</h1>
    <div class="name-line"></div>

    <div class="contact-mini">
      <div class="contact-item">
        <span class="contact-icon email-icon">✉️</span>
        <a href="mailto:nishanthan200102@gmail.com">nishanthan200102@gmail.com</a>
      </div>
      <div class="contact-item">
        <span class="contact-icon phone-icon">📞</span>
        <a href="tel:+94756652873">+94756652873</a>
      </div>
      <div class="contact-item">
        <span class="contact-icon whatsapp-icon">💬</span>
        <a href="https://wa.me/+94756652873" target="_blank">Chat on WhatsApp</a>
      </div>
      <div class="contact-item">
        <span class="contact-icon map-icon">📍</span>
        <a href="https://www.google.com/maps/search/?api=1&query=Vendikulam%2C+Sri+Lanka" target="_blank" rel="noopener noreferrer">My Location (Open Google Maps)</a>
      </div>
    </div>
  </div>

</div>

<main>

<section id="about">
  <h2>About Me</h2>
  <p>Hello! I am <strong>Nishanthan Suseekaran</strong>, and I am from Vendikulam, Sri Lanka. I am 25 years old. From a young age, I have had a strong passion for becoming an Electrical Engineer. Although circumstances made it difficult to complete that specific path at the time, my dedication to learning and growing has never stopped.</p>
  <p>Currently, I am working as a Driver in Qatar, where I manage my responsibilities with hard work and discipline. Beyond my job, I possess a wide range of practical skills, including electrical works, IT-related knowledge, and creative artistic talents.</p>
  <p>This website is a reflection of my life journey, hard work, experiences, and my continuous drive toward a brighter future.</p>
</section>

<section id="education">
  <h2>Education</h2>

  <div class="card">
    <h3>🏫 Basic Education – Primary School</h3>
    
    <div style="display: flex; align-items: flex-start; justify-content: space-between; gap: 20px; flex-wrap: wrap;">
      <!-- School Details -->
      <div style="flex: 1; min-width: 220px;">
        <p><strong>School:</strong> Kannapuram Primary School</p>
        <p><strong>Address:</strong> 35 Village, Kannapuram, Vaikala</p>
        <p><strong>Years:</strong> 2003–2006</p>
        <p style="margin-top: 8px;">From 2003 to 2006, I completed my primary education at Kannapuram Primary School, where I studied basic subjects and explored foundational arts and early learning skills.</p>
      </div>
      
      <!-- A4 Size / Portrait Photos Section (2 Photos) -->
      <div style="display: flex; gap: 10px; flex-shrink: 0; align-items: center;">
        <img src="primary_photo1.jpg" alt="Primary School Document/Photo 1" onclick="openModal(this.src)" style="width: 90px; height: 125px; object-fit: cover; border-radius: 4px; border: 1px solid #ccc; cursor: pointer;" onerror="this.style.display='none'">
        <img src="primary_photo2.jpg" alt="Primary School Document/Photo 2" onclick="openModal(this.src)" style="width: 90px; height: 125px; object-fit: cover; border-radius: 4px; border: 1px solid #ccc; cursor: pointer;" onerror="this.style.display='none'">
      </div>
    </div>
  </div>

  <div class="card">
    <h3>🏫 General Education</h3>
    <p><strong>School:</strong> Kannagipuram Vinayahar Vidiyalayam</p>
    <p><strong>Location:</strong> Mahiloor, Kaluwanchikudy, Sri Lanka</p>
    <p><strong>Years:</strong> 2006–2011 (Extended through 2017)</p>
    <p style="margin-top: 8px;">From 2006 to 2011, I completely studied my general education at Kannagipuram Vinayahar Vidiyalayam, continuing my studies here until completing my G.C.E. O/L Examination in 2017.</p>

    <div style="display: flex; gap: 10px; margin: 15px 0; justify-content: start; flex-wrap: wrap;">
      <img src="photo1.jpg" alt="Photo 1" onclick="openModal(this.src)" style="width: 80px; height: 100px; object-fit: cover; border-radius: 4px; border: 1px solid #ccc; cursor: pointer;" onerror="this.style.display='none'">
      <img src="photo2.jpg" alt="Photo 2" onclick="openModal(this.src)" style="width: 80px; height: 100px; object-fit: cover; border-radius: 4px; border: 1px solid #ccc; cursor: pointer;" onerror="this.style.display='none'">
      <img src="photo3.jpg" alt="Photo 3" onclick="openModal(this.src)" style="width: 80px; height: 100px; object-fit: cover; border-radius: 4px; border: 1px solid #ccc; cursor: pointer;" onerror="this.style.display='none'">
      <img src="photo4.jpg" alt="Photo 4" onclick="openModal(this.src)" style="width: 80px; height: 100px; object-fit: cover; border-radius: 4px; border: 1px solid #ccc; cursor: pointer;" onerror="this.style.display='none'">
    </div>

    <div id="imgModal" onclick="closeModal()" style="display: none; position: fixed; z-index: 9999; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(0,0,0,0.8); justify-content: center; align-items: center; cursor: pointer;">
      <img id="modalImage" style="max-width: 90%; max-height: 90%; border-radius: 8px;">
    </div>

    <script>
    function openModal(src) {
        document.getElementById('modalImage').src = src;
        document.getElementById('imgModal').style.display = 'flex';
    }
    function closeModal() {
        document.getElementById('imgModal').style.display = 'none';
    }
    </script>

    <p><strong>Subjects studied:</strong></p>
    <ul>
      <li>Tamil</li>
      <li>Mathematics</li>
      <li>English</li>
      <li>Science</li>
      <li>History</li>
      <li>Art</li>
      <li>Geography</li>
      <li>Drama</li>
    </ul>
    <p><strong>Examination:</strong> G.C.E. O/L Examination</p>

    <p style="margin-top: 12px; font-style: italic; color: #334155;">
      Leaving this school in 2017 after my O/L exams filled me with deep emotion. I gained countless valuable experiences, good habits, and strong foundational knowledge here. I heartfeltly thank all my teachers who guided and shaped me with great care. I truly miss my school, my teachers, and my friends dearly.
    </p>
  </div>

  <div class="card">
    <h3>🏫 Higher Education – National Vocational Training Institute</h3>
    <p>National Vocational Training Institute - Vantharumoolai - Batticaloa</p>

    <!-- 5 to 6 A4 Size / Portrait Photos Section for Training Center -->
    <div style="display: flex; gap: 10px; margin: 15px 0; justify-content: start; flex-wrap: wrap;">
      <img src="tech_photo1.jpg" alt="Technical Training Photo 1" onclick="openModal(this.src)" style="width: 90px; height: 125px; object-fit: cover; border-radius: 4px; border: 1px solid #ccc; cursor: pointer;" onerror="this.style.display='none'">
      <img src="tech_photo2.jpg" alt="Technical Training Photo 2" onclick="openModal(this.src)" style="width: 90px; height: 125px; object-fit: cover; border-radius: 4px; border: 1px solid #ccc; cursor: pointer;" onerror="this.style.display='none'">
      <img src="tech_photo3.jpg" alt="Technical Training Photo 3" onclick="openModal(this.src)" style="width: 90px; height: 125px; object-fit: cover; border-radius: 4px; border: 1px solid #ccc; cursor: pointer;" onerror="this.style.display='none'">
      <img src="tech_photo4.jpg" alt="Technical Training Photo 4" onclick="openModal(this.src)" style="width: 90px; height: 125px; object-fit: cover; border-radius: 4px; border: 1px solid #ccc; cursor: pointer;" onerror="this.style.display='none'">
      <img src="tech_photo5.jpg" alt="Technical Training Photo 5" onclick="openModal(this.src)" style="width: 90px; height: 125px; object-fit: cover; border-radius: 4px; border: 1px solid #ccc; cursor: pointer;" onerror="this.style.display='none'">
      <img src="tech_photo6.jpg" alt="Technical Training Photo 6" onclick="openModal(this.src)" style="width: 90px; height: 125px; object-fit: cover; border-radius: 4px; border: 1px solid #ccc; cursor: pointer;" onerror="this.style.display='none'">
    </div>

    <p><strong>NVQ & Technical Training Subjects:</strong></p>
    <ul>
      <li>NVQ Level 4 & Level 5 (Electrician)</li>
      <li>Electrical & HVAC Training</li>
      <li>Graphic Design</li>
      <li>Information and Communication Technology (ICT)</li>
    </ul>
    <p style="margin-top: 12px; line-height: 1.6;">
      From 2019 to January 2020, I pursued my higher technical education through this institute, mastering all essential concepts related to Information and Communication Technology (ICT) and electrical engineering. During this period, I gained profound practical experiences and hands-on knowledge. When I left the institute in January 2020, I felt a deep sense of attachment, fondly missing my beloved instructors and friends who were an integral part of this remarkable journey.
    </p>
  </div>
</section>

<section id="work">
  <h2>Work Experience</h2>
  <div class="card">
    <h3>Work Experience in Qatar & Sri Lanka</h3>
    <p><strong>Company:</strong> Axona (HVAC Technician - 9 months)</p>
    <p><strong>Company:</strong> Mesure (Electrician Field)</p>
    <p>My work experience has helped me develop responsibility, discipline, practical skills and a strong work ethic.</p>
  </div>
</section>

<!-- My Love Story Section -->
<section id="lovestory">
  <h2>My Love Story ❤️</h2>
  <p>This section is dedicated to my special love story and beautiful memories.</p>
  
  <div class="card">
    <h3>Special Moments</h3>
    <!-- 2-3 A4 Size / Portrait Photos Section for Love Story -->
    <div style="display: flex; gap: 10px; margin: 15px 0; justify-content: start; flex-wrap: wrap;">
      <img src="love_photo1.jpg" alt="Love Story Photo 1" onclick="openModal(this.src)" style="width: 90px; height: 125px; object-fit: cover; border-radius: 4px; border: 1px solid #ccc; cursor: pointer;" onerror="this.style.display='none'">
      <img src="love_photo2.jpg" alt="Love Story Photo 2" onclick="openModal(this.src)" style="width: 90px; height: 125px; object-fit: cover; border-radius: 4px; border: 1px solid #ccc; cursor: pointer;" onerror="this.style.display='none'">
      <img src="love_photo3.jpg" alt="Love Story Photo 3" onclick="openModal(this.src)" style="width: 90px; height: 125px; object-fit: cover; border-radius: 4px; border: 1px solid #ccc; cursor: pointer;" onerror="this.style.display='none'">
    </div>
    
    <p style="margin-top: 10px; font-style: italic; color: #555;">[Your love story details will be updated here...]</p>
    <p style="margin-top: 15px;">
      <a class="lovestory-link" href="my-lovestory.html">Visit My Love Story Page →</a>
    </p>
  </div>
</section>

<section id="family">
  <h2>My Family</h2>
  <p>My family is an important part of my life. This page is dedicated to family love, photographs and special memories.</p>
  <a class="family-link" href="my-family.html">Visit My Family Page →</a>
</section>

</main>

<footer>
  <div class="footer-box">
    <p><strong>Email:</strong> <a href="mailto:nishanthan200102@gmail.com" style="color: #8ddfff; text-decoration: none;">nishanthan200102@gmail.com</a></p>
    <p><strong>Phone:</strong> <a href="tel:+94756652873" style="color: #8ddfff; text-decoration: none;">+94756652873</a></p>
    <p><strong>Website:</strong> <a class="footer-link" href="https://nishanthan-ur.github.io/nishanthan20012/" target="_blank" rel="noopener noreferrer" style="color: #8ddfff;">Visit My Website</a></p>
    <p style="margin-top: 8px;">
      <a href="https://wa.me/?text=Check%20out%20this%20amazing%20website:%20https://nishanthan-ur.github.io/nishanthan20012/" target="_blank" style="color: #8ddfff; text-decoration: underline;">Share My Website 💬</a>
    </p>
  </div>
  <p>🙏 Thank you for visiting my website!</p>
  <p>© 2026 Nishanthan Suseekaran</p>
  <p>My Life • My Journey • My Dreams ✈️</p>
</footer>

</body>
</html>
