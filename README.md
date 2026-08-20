# HTML-CSS-real-projects-4
HTML
<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alisher Usmonov — Full-Stack Dasturchi Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>

    <!-- Header & Navigatsiya -->
    <header class="header">
        <div class="container nav-container">
            <a href="#" class="logo">Portfolio<span>.</span></a>
            <nav class="nav">
                <a href="#hero">Bosh sahifa</a>
                <a href="#about">Men haqimda</a>
                <a href="#projects">Loyihalar</a>
                <a href="#skills">Ko'nikmalar</a>
                <a href="#contact" class="btn-nav">Aloqa</a>
            </nav>
        </div>
    </header>

    <!-- 1. Hero Qism -->
    <section id="hero" class="hero">
        <div class="container hero-container">
            <div class="hero-content">
                <span class="greeting">Salom, men</span>
                <h1>Alisher Usmonov</h1>
                <h2>Senior Full-Stack Dasturchi</h2>
                <p>Foydalanuvchilarga qulay, tezkor va zamonaviy veb-ilovalarni yaratishga ixtisoslashganman.</p>
                <div class="hero-btns">
                    <a href="#contact" class="btn btn-primary">Bog'lanish</a>
                    <a href="#" class="btn btn-outline"><i class="fa-solid fa-download"></i> CV Yuklab olish</a>
                </div>
            </div>
            <div class="hero-image">
                <div class="avatar-glow"></div>
                <img src="https://images.unsplash.com/photo-1534528741775-53994a69daeb?auto=format&fit=crop&w=500&q=80" alt="Avatar">
            </div>
        </div>
    </section>

    <!-- 2. About Qism -->
    <section id="about" class="about">
        <div class="container">
            <h2 class="section-title">Men Haqimda</h2>
            <div class="about-grid">
                <div class="about-img">
                    <img src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?auto=format&fit=crop&w=500&q=80" alt="Workspace">
                </div>
                <div class="about-text">
                    <h3>Raqamli olamda o'z izingizni qoldiring</h3>
                    <p>Men 5 yildan ortiq tajribaga ega dasturchiman. Murakkab arxitekturaga ega tizimlar, zamonaviy interfeyslar va servislar yaratishni yaxshi ko'raman. Har bir loyiha ustida ishlashda sifat va tezkorlikka alohida e'tibor qarataman.</p>
                    <div class="stats">
                        <div class="stat-box">
                            <h4>5+</h4>
                            <p>Tajriba yillari</p>
                        </div>
                        <div class="stat-box">
                            <h4>40+</h4>
                            <p>Muvaffaqiyatli loyihalar</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 3. Loyihalar Grid -->
    <section id="projects" class="projects">
        <div class="container">
            <h2 class="section-title">So'nggi Loyihalarim</h2>
            <div class="projects-grid">
                <!-- Loyiha 1 -->
                <div class="project-card">
                    <img src="https://images.unsplash.com/photo-1551288049-bebda4e38f71?auto=format&fit=crop&w=600&q=80" alt="E-Commerce">
                    <div class="project-info">
                        <h3>E-Commerce Platformasi</h3>
                        <p>Onlayn savdo uchun mo'ljallangan to'liq funksional internet do'kon tizimi.</p>
                        <div class="tags">
                            <span>React</span><span>Node.js</span><span>MongoDB</span>
                        </div>
                        <a href="#" class="project-link">Ko'rish <i class="fa-solid fa-arrow-right"></i></a>
                    </div>
                </div>
                <!-- Loyiha 2 -->
                <div class="project-card">
                    <img src="https://images.unsplash.com/photo-1460925895917-afdab827c52f?auto=format&fit=crop&w=600&q=80" alt="Task Manager">
                    <div class="project-info">
                        <h3>Task Manager App</h3>
                        <p>Jamoalar uchun vazifalarni taqsimlash va kuzatib borish veb-ilovasi.</p>
                        <div class="tags">
                            <span>Vue.js</span><span>Firebase</span><span>Tailwind</span>
                        </div>
                        <a href="#" class="project-link">Ko'rish <i class="fa-solid fa-arrow-right"></i></a>
                    </div>
                </div>
                <!-- Loyiha 3 -->
                <div class="project-card">
                    <img src="https://images.unsplash.com/photo-1504868584819-f8e8b4b6d7e3?auto=format&fit=crop&w=600&q=80" alt="Analytics Dashboard">
                    <div class="project-info">
                        <h3>Analytics Dashboard</h3>
                        <p>Real vaqt rejimida statistik ma'lumotlarni tahlil qilish va vizualizatsiya paneli.</p>
                        <div class="tags">
                            <span>React</span><span>Chart.js</span><span>API</span>
                        </div>
                        <a href="#" class="project-link">Ko'rish <i class="fa-solid fa-arrow-right"></i></a>
                    </div>
                </div>
                <!-- Loyiha 4 -->
                <div class="project-card">
                    <img src="https://images.unsplash.com/photo-1522542550221-31fd19575a2d?auto=format&fit=crop&w=600&q=80" alt="AI Copywriter">
                    <div class="project-info">
                        <h3>AI Content Generator</h3>
                        <p>Sun'iy intellekt yordamida tezkor matnlar va maqolalar tayyorlovchi platforma.</p>
                        <div class="tags">
                            <span>Python</span><span>OpenAI API</span><span>FastAPI</span>
                        </div>
                        <a href="#" class="project-link">Ko'rish <i class="fa-solid fa-arrow-right"></i></a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 4. Ko'nikmalar -->
    <section id="skills" class="skills">
        <div class="container">
            <h2 class="section-title">Texnik Ko'nikmalar</h2>
            <div class="skills-grid">
                <div class="skill-category">
                    <h3>Frontend</h3>
                    <div class="skill-item">
                        <span>HTML / CSS</span> <span>95%</span>
                    </div>
                    <div class="progress-bar"><div class="progress" style="width: 95%;"></div></div>
                    
                    <div class="skill-item">
                        <span>JavaScript (ES6+)</span> <span>90%</span>
                    </div>
                    <div class="progress-bar"><div class="progress" style="width: 90%;"></div></div>

                    <div class="skill-item">
                        <span>React.js</span> <span>85%</span>
                    </div>
                    <div class="progress-bar"><div class="progress" style="width: 85%;"></div></div>
                </div>

                <div class="skill-category">
                    <h3>Backend & Baza</h3>
                    <div class="skill-item">
                        <span>Node.js / Express</span> <span>80%</span>
                    </div>
                    <div class="progress-bar"><div class="progress" style="width: 80%;"></div></div>
                    
                    <div class="skill-item">
                        <span>Python / FastAPI</span> <span>75%</span>
                    </div>
                    <div class="progress-bar"><div class="progress" style="width: 75%;"></div></div>

                    <div class="skill-item">
                        <span>MongoDB / PostgreSQL</span> <span>85%</span>
                    </div>
                    <div class="progress-bar"><div class="progress" style="width: 85%;"></div></div>
                </div>
            </div>
            <!-- Badge alternativasi -->
            <div class="badges">
                <span class="badge">Git & GitHub</span>
                <span class="badge">Docker</span>
                <span class="badge">REST API</span>
                <span class="badge">Tailwind CSS</span>
                <span class="badge">TypeScript</span>
                <span class="badge">UI/UX Design</span>
            </div>
        </div>
    </section>

    <!-- 5. Aloqa Shakli -->
    <section id="contact" class="contact">
        <div class="container">
            <h2 class="section-title">Bog'lanish</h2>
            <div class="contact-wrapper">
                <form class="contact-form">
                    <div class="form-group">
                        <input type="text" placeholder="Ismingiz" required>
                    </div>
                    <div class="form-group">
                        <input type="email" placeholder="Email manzilingiz" required>
                    </div>
                    <div class="form-group">
                        <textarea rows="5" placeholder="Xabaringiz..." required></textarea>
                    </div>
                    <button type="submit" class="btn btn-primary btn-full">Xabarni yuborish</button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container footer-container">
            <p>&copy; 2026 Alisher Usmonov. Barcha huquqlar himoyalangan.</p>
            <div class="social-icons">
                <a href="#"><i class="fa-brands fa-github"></i></a>
                <a href="#"><i class="fa-brands fa-telegram"></i></a>
                <a href="#"><i class="fa-brands fa-linkedin"></i></a>
            </div>
        </div>
    </footer>

</body>
</html>

CSS
/* Umumiy sozlamalar */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Inter', sans-serif;
}

html {
    scroll-behavior: smooth; /* 6. Silliq scroll talabi */
}

body {
    background-color: #0b0f19;
    color: #f1f5f9;
    line-height: 1.6;
}

.container {
    max-width: 1100px;
    margin: 0 auto;
    padding: 0 20px;
}

section {
    padding: 90px 0;
}

.section-title {
    text-align: center;
    font-size: 2.5rem;
    margin-bottom: 50px;
    color: #ffffff;
    font-weight: 700;
}

.section-title::after {
    content: '';
    display: block;
    width: 60px;
    height: 4px;
    background-color: #3b82f6;
    margin: 10px auto 0;
    border-radius: 2px;
}

/* Header & Nav */
.header {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    background-color: rgba(11, 15, 25, 0.9);
    backdrop-filter: blur(10px);
    z-index: 1000;
    border-bottom: 1px solid #1e293b;
}

.nav-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 70px;
}

.logo {
    font-size: 1.5rem;
    font-weight: 700;
    color: #ffffff;
    text-decoration: none;
}

.logo span {
    color: #3b82f6;
}

.nav {
    display: flex;
    gap: 30px;
    align-items: center;
}

.nav a {
    text-decoration: none;
    color: #94a3b8;
    font-weight: 500;
    transition: color 0.3s;
}

.nav a:hover {
    color: #3b82f6;
}

.btn-nav {
    background-color: #3b82f6;
    color: #fff !important;
    padding: 8px 18px;
    border-radius: 6px;
    transition: background 0.3s !important;
}

.btn-nav:hover {
    background-color: #2563eb !important;
}

/* 1. Hero Qism */
.hero {
    padding-top: 160px;
    min-height: 100vh;
    display: flex;
    align-items: center;
}

.hero-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 40px;
    width: 100%;
}

.hero-content {
    flex: 1;
}

.greeting {
    color: #3b82f6;
    font-weight: 600;
    font-size: 1.2rem;
}

.hero-content h1 {
    font-size: 3.5rem;
    font-weight: 700;
    margin: 10px 0;
    color: #ffffff;
}

.hero-content h2 {
    font-size: 1.8rem;
    color: #94a3b8;
    margin-bottom: 20px;
}

.hero-content p {
    color: #94a3b8;
    margin-bottom: 30px;
    font-size: 1.1rem;
}

.hero-btns {
    display: flex;
    gap: 15px;
}

.btn {
    padding: 12px 24px;
    border-radius: 6px;
    font-weight: 600;
    text-decoration: none;
    display: inline-flex;
    align-items: center;
    gap: 8px;
    cursor: pointer;
    transition: all 0.3s;
}

.btn-primary {
    background-color: #3b82f6;
    color: #fff;
}

.btn-primary:hover {
    background-color: #2563eb;
}

.btn-outline {
    border: 1px solid #334155;
    color: #f1f5f9;
}

.btn-outline:hover {
    border-color: #3b82f6;
    color: #3b82f6;
}

.hero-image {
    position: relative;
    display: flex;
    justify-content: center;
}

.hero-image img {
    width: 300px;
    height: 300px;
    object-fit: cover;
    border-radius: 50%;
    border: 4px solid #1e293b;
    position: relative;
    z-index: 2;
}

/* 2. About Qism */
.about-grid {
    display: grid;
    grid-template-columns: 1fr 1.2fr;
    gap: 50px;
    align-items: center;
}

.about-img img {
    width: 100%;
    border-radius: 12px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.5);
}

.about-text h3 {
    font-size: 1.8rem;
    margin-bottom: 20px;
    color: #ffffff;
}

.about-text p {
    color: #94a3b8;
    margin-bottom: 30px;
}

.stats {
    display: flex;
    gap: 30px;
}

.stat-box h4 {
    font-size: 2rem;
    color: #3b82f6;
}

.stat-box p {
    font-size: 0.9rem;
    color: #64748b;
    margin: 0;
}

/* 3. Loyihalar Grid */
.projects {
    background-color: #0f172a;
}

.projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    gap: 25px;
}

.project-card {
    background-color: #1e293b;
    border-radius: 12px;
    overflow: hidden;
    border: 1px solid #334155;
    transition: transform 0.3s;
}

.project-card:hover {
    transform: translateY(-5px);
}

.project-card img {
    width: 100%;
    height: 180px;
    object-fit: cover;
}

.project-info {
    padding: 20px;
}

.project-info h3 {
    font-size: 1.2rem;
    margin-bottom: 10px;
    color: #ffffff;
}

.project-info p {
    color: #94a3b8;
    font-size: 0.9rem;
    margin-bottom: 15px;
}

.tags {
    display: flex;
    gap: 8px;
    flex-wrap: wrap;
    margin-bottom: 15px;
}

.tags span {
    background-color: #0f172a;
    color: #3b82f6;
    font-size: 0.75rem;
    padding: 4px 8px;
    border-radius: 4px;
}

.project-link {
    color: #3b82f6;
    text-decoration: none;
    font-weight: 600;
    font-size: 0.9rem;
    display: inline-flex;
    align-items: center;
    gap: 5px;
}

/* 4. Ko'nikmalar */
.skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 40px;
    margin-bottom: 40px;
}

.skill-category h3 {
    margin-bottom: 20px;
    color: #ffffff;
}

.skill-item {
    display: flex;
    justify-content: space-between;
    margin-bottom: 8px;
    font-size: 0.9rem;
    color: #94a3b8;
}

.progress-bar {
    width: 100%;
    height: 8px;
    background-color: #1e293b;
    border-radius: 4px;
    margin-bottom: 20px;
    overflow: hidden;
}

.progress {
    height: 100%;
    background-color: #3b82f6;
    border-radius: 4px;
}

.badges {
    display: flex;
    gap: 10px;
    flex-wrap: wrap;
    justify-content: center;
}

.badge {
    background-color: #1e293b;
    border: 1px solid #334155;
    color: #f1f5f9;
    padding: 8px 16px;
    border-radius: 20px;
    font-size: 0.9rem;
}

/* 5. Aloqa Shakli */
.contact {
    background-color: #0f172a;
}

.contact-wrapper {
    max-width: 600px;
    margin: 0 auto;
    background-color: #1e293b;
    padding: 40px;
    border-radius: 12px;
    border: 1px solid #334155;
}

.form-group {
    margin-bottom: 20px;
}

.form-group input,
.form-group textarea {
    width: 100%;
    padding: 12px 16px;
    background-color: #0f172a;
    border: 1px solid #334155;
    border-radius: 6px;
    color: #fff;
    outline: none;
    font-size: 1rem;
    transition: border-color 0.3s;
}

.form-group input:focus,
.form-group textarea:focus {
    border-color: #3b82f6;
}

.btn-full {
    width: 100%;
    justify-content: center;
}

/* Footer */
footer {
    padding: 30px 0;
    border-top: 1px solid #1e293b;
    text-align: center;
}

.footer-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.footer-container p {
    color: #64748b;
    font-size: 0.9rem;
}

.social-icons {
    display: flex;
    gap: 15px;
}

.social-icons a {
    color: #94a3b8;
    font-size: 1.2rem;
    transition: color 0.3s;
}

.social-icons a:hover {
    color: #3b82f6;
}

/* Responsivlik */
@media (max-width: 768px) {
    .hero-container, .about-grid, .footer-container {
        flex-direction: column;
        text-align: center;
    }
    .hero-content h1 {
        font-size: 2.5rem;
    }
    .nav {
        display: none; /* Mobilda menyu yashiriladi, istasa JS bilan ochiladigan qilish mumkin */
    }
    .stats {
        justify-content: center;
    }
}
