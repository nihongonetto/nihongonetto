<title>Nihongonetto - Impara il Giapponese con un Tutor Italiano</title> <style> * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        line-height: 1.6;
        color: #333;
        background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    }

    .container {
        max-width: 1200px;
        margin: 0 auto;
        padding: 0 20px;
    }

    /* Header */
    header {
        background: rgba(255, 255, 255, 0.95);
        backdrop-filter: blur(10px);
        padding: 1rem 0;
        position: fixed;
        width: 100%;
        top: 0;
        z-index: 1000;
        box-shadow: 0 2px 20px rgba(0, 0, 0, 0.1);
    }

    .header-content {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .logo {
        font-size: 1.8rem;
        font-weight: bold;
        color: #e74c3c;
        text-decoration: none;
        display: flex;
        align-items: center;
        gap: 10px;
    }

    .logo::before {
        content: "🇯🇵";
        font-size: 1.5rem;
    }

    .nav-links {
        display: flex;
        list-style: none;
        gap: 2rem;
    }

    .nav-links a {
        color: #333;
        text-decoration: none;
        font-weight: 500;
        transition: color 0.3s;
    }

    .nav-links a:hover {
        color: #e74c3c;
    }

    /* Hero Section */
    .hero {
        background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        color: white;
        padding: 120px 0 80px;
        text-align: center;
        min-height: 100vh;
        display: flex;
        align-items: center;
    }

    .hero-content h1 {
        font-size: 3.5rem;
        margin-bottom: 1rem;
        font-weight: 700;
        text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
    }

    .hero-content p {
        font-size: 1.3rem;
        margin-bottom: 2rem;
        max-width: 600px;
        margin-left: auto;
        margin-right: auto;
        opacity: 0.9;
    }

    .cta-button {
        display: inline-block;
        background: #e74c3c;
        color: white;
        padding: 15px 40px;
        text-decoration: none;
        border-radius: 50px;
        font-weight: bold;
        font-size: 1.1rem;
        transition: all 0.3s;
        box-shadow: 0 4px 15px rgba(231, 76, 60, 0.4);
    }

    .cta-button:hover {
        background: #c0392b;
        transform: translateY(-2px);
        box-shadow: 0 6px 20px rgba(231, 76, 60, 0.6);
    }

    /* About Section */
    .about {
        background: white;
        padding: 80px 0;
    }

    .about-content {
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 4rem;
        align-items: center;
    }

    .about-text h2 {
        font-size: 2.5rem;
        margin-bottom: 1.5rem;
        color: #2c3e50;
    }

    .about-text p {
        margin-bottom: 1.5rem;
        color: #555;
        font-size: 1.1rem;
    }

    .about-image {
        text-align: center;
        font-size: 8rem;
        color: #e74c3c;
        opacity: 0.8;
    }

    /* Features Section */
    .features {
        background: #f8f9fa;
        padding: 80px 0;
    }

    .features h2 {
        text-align: center;
        font-size: 2.5rem;
        margin-bottom: 3rem;
        color: #2c3e50;
    }

    .features-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        gap: 2rem;
        margin-top: 3rem;
    }

    .feature-card {
        background: white;
        padding: 2rem;
        border-radius: 10px;
        text-align: center;
        box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        transition: transform 0.3s;
    }

    .feature-card:hover {
        transform: translateY(-5px);
    }

    .feature-icon {
        font-size: 3rem;
        margin-bottom: 1rem;
    }

    .feature-card h3 {
        font-size: 1.5rem;
        margin-bottom: 1rem;
        color: #2c3e50;
    }

    .feature-card p {
        color: #666;
        line-height: 1.6;
    }

    /* Courses Section */
    .courses {
        background: white;
        padding: 80px 0;
    }

    .courses h2 {
        text-align: center;
        font-size: 2.5rem;
        margin-bottom: 3rem;
        color: #2c3e50;
    }

    .course-levels {
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 3rem;
        margin-top: 3rem;
    }

    .level-card {
        background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        color: white;
        padding: 2.5rem;
        border-radius: 15px;
        text-align: center;
        box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
    }

    .level-card h3 {
        font-size: 2rem;
        margin-bottom: 1rem;
    }

    .level-card p {
        font-size: 1.1rem;
        margin-bottom: 1.5rem;
        opacity: 0.9;
    }

    .level-features {
        list-style: none;
        text-align: left;
        margin-bottom: 2rem;
    }

    .level-features li {
        padding: 0.5rem 0;
        position: relative;
        padding-left: 2rem;
    }

    .level-features li::before {
        content: "✓";
        position: absolute;
        left: 0;
        color: #2ecc71;
        font-weight: bold;
    }

    /* CTA Section */
    .cta-section {
        background: #2c3e50;
        color: white;
        padding: 80px 0;
        text-align: center;
    }

    .cta-section h2 {
        font-size: 2.5rem;
        margin-bottom: 1rem;
    }

    .cta-section p {
        font-size: 1.2rem;
        margin-bottom: 2rem;
        opacity: 0.9;
    }

    /* Footer */
    footer {
        background: #1a252f;
        color: white;
        padding: 40px 0;
        text-align: center;
    }

    .footer-content {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 2rem;
        margin-bottom: 2rem;
    }

    .footer-section h3 {
        margin-bottom: 1rem;
        color: #e74c3c;
    }

    .footer-section p, .footer-section a {
        color: #bdc3c7;
        text-decoration: none;
    }

    .footer-section a:hover {
        color: #e74c3c;
    }

    /* Responsive Design */
    @media (max-width: 768px) {
        .nav-links {
            display: none;
        }

        .hero-content h1 {
            font-size: 2.5rem;
        }

        .about-content {
            grid-template-columns: 1fr;
            text-align: center;
        }

        .course-levels {
            grid-template-columns: 1fr;
        }

        .about-image {
            font-size: 4rem;
        }
    }
</style>
Nihongonetto
Home
Chi Sono
Corsi
Contatti
<section id="home" class="hero">
    <div class="container">
        <div class="hero-content">
            <h1>Impara il Giapponese con Nihongonetto</h1>
            <p>Il tuo tutor italiano per l'apprendimento della lingua giapponese. 30 anni di esperienza e vita in Giappone al tuo servizio.</p>
            <a href="#" class="cta-button">Inizia Ora</a>
        </div>
    </div>
</section>

<section id="about" class="about">
    <div class="container">
        <div class="about-content">
            <div class="about-text">
                <h2>Chi Sono</h2>
                <p>Ciao e grazie per essere qui! Sono Nihongonetto, il tuo tutor italiano per l'apprendimento della lingua giapponese. Studio questa lingua da 30 anni e vivo in Giappone, nel 2019 ho deciso di aiutare chi desidera imparare la lingua giapponese.</p>
                
                <p>Hai sempre desiderato imparare questa lingua, ma non sai da dove cominciare? I libri spesso sono in inglese o in giapponese e perdi subito interesse? Nihongonetto ti dà la possibilità di studiare con un tutor italiano esperto della lingua giapponese.</p>
                
                <p><strong>La mia missione è aiutare sempre più persone a imparare il giapponese in modo naturale, semplice e divertente.</strong> È con la leggerezza e il sorriso che si impara di più e più in fretta.</p>
            </div>
            <div class="about-image">
                🎌
            </div>
        </div>
    </div>
</section>

<section class="features">
    <div class="container">
        <h2>Cosa Troverai</h2>
        <div class="features-grid">
            <div class="feature-card">
                <div class="feature-icon">📚</div>
                <h3>Materiali Completi</h3>
                <p>Trascrizioni dei podcast con esercizi interattivi di lessico e attività per espandere il tuo vocabolario giapponese.</p>
            </div>
            <div class="feature-card">
                <div class="feature-icon">✍️</div>
                <h3>Scrittura Giapponese</h3>
                <p>Esercizi guidati per imparare hiragana, katakana e kanji in modo progressivo e sistematico.</p>
            </div>
            <div class="feature-card">
                <div class="feature-icon">🏯</div>
                <h3>Cultura Giapponese</h3>
                <p>Spiegazioni culturali approfondite per comprendere meglio il Giappone e il contesto della lingua.</p>
            </div>
            <div class="feature-card">
                <div class="feature-icon">🎯</div>
                <h3>Preparazione JFT-Basic</h3>
                <p>Materiali specifici per prepararti al Japan Foundation Test for Basic Japanese.</p>
            </div>
        </div>
    </div>
</section>

<section id="courses" class="courses">
    <div class="container">
        <h2>I Corsi</h2>
        <p style="text-align: center; font-size: 1.2rem; color: #666; margin-bottom: 3rem;">
            Nihongonetto ti aiuterà a sviluppare le competenze comunicative di base in giapponese, necessarie per affrontare situazioni quotidiane o per prepararti a un futuro viaggio in Giappone.
        </p>
        
        <div class="course-levels">
            <div class="level-card">
                <h3>Livello A1 - Principiante</h3>
                <p>Perfetto per chi si avvicina al giapponese per la prima volta</p>
                <ul class="level-features">
                    <li>Hiragana e Katakana</li>
                    <li>Saluti e presentazioni</li>
                    <li>Numeri e tempo</li>
                    <li>Frasi di base per la vita quotidiana</li>
                    <li>Grammatica fondamentale</li>
                </ul>
            </div>
            <div class="level-card">
                <h3>Livello A2 - Elementare</h3>
                <p>Sviluppa competenze per interagire nella vita quotidiana</p>
                <ul class="level-features">
                    <li>Kanji di base</li>
                    <li>Conversazioni quotidiane</li>
                    <li>Shopping e ristoranti</li>
                    <li>Trasporti e direzioni</li>
                    <li>Preparazione mondo del lavoro</li>
                </ul>
            </div>
        </div>
        
        <div style="text-align: center; margin-top: 3rem;">
            <p style="font-size: 1.1rem; color: #666; margin-bottom: 2rem;">
                L'apprendimento delle regole grammaticali sarà integrato passo dopo passo con l'uso pratico della lingua, sviluppando le quattro abilità linguistiche: comprensione orale, comprensione scritta, produzione orale e produzione scritta.
            </p>
        </div>
    </div>
</section>

<section class="cta-section">
    <div class="container">
        <h2>Inizia il Tuo Viaggio</h2>
        <p>Ti basteranno pochi minuti al giorno per apprendere senza fatica e senza lo stress di dover imparare tutto in una volta.</p>
        <a href="#" class="cta-button">Accedi ai Corsi</a>
        <p style="margin-top: 2rem; font-size: 1.1rem; opacity: 0.9;">
            Buon apprendimento e buon divertimento!
        </p>
    </div>
</section>

<footer id="contact">
    <div class="container">
        <div class="footer-content">
            <div class="footer-section">
                <h3>Nihongonetto</h3>
                <p>Il tuo tutor italiano per l'apprendimento della lingua giapponese</p>
            </div>
            <div class="footer-section">
                <h3>Contatti</h3>
                <p>Email: info@nihongonetto.com</p>
                <p>Social: @nihongonetto</p>
            </div>
            <div class="footer-section">
                <h3>Supporto</h3>
                <p>Il tuo supporto permetterà a Nihongonetto di aiutare sempre più studenti in tutto il mondo a imparare e migliorare il loro giapponese.</p>
            </div>
        </div>
        <p>&copy; 2024 Nihongonetto. Tutti i diritti riservati.</p>
    </div>
</footer>
