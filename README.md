<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Invertir en XAUUSD · Guía profesional</title>
  <!-- Font Awesome (iconos) -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
      background: #f8fafc;
      color: #0b1a2e;
      line-height: 1.6;
    }

    .container {
      max-width: 1300px;
      margin: 0 auto;
      padding: 2rem 1.5rem;
    }

    /* Encabezado */
    .header {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 3rem;
      border-bottom: 1px solid #e9edf2;
      padding-bottom: 1.5rem;
    }

    .logo h1 {
      font-size: 2rem;
      font-weight: 700;
      letter-spacing: -0.02em;
      background: linear-gradient(145deg, #b8860b, #d4af37);
      -webkit-background-clip: text;
      background-clip: text;
      color: transparent;
      display: inline-block;
    }

    .logo span {
      font-weight: 300;
      color: #2c3e50;
      background: none;
      -webkit-background-clip: unset;
      background-clip: unset;
      color: #2c3e50;
    }

    .tag {
      background: #eef2f6;
      padding: 0.5rem 1.2rem;
      border-radius: 40px;
      font-weight: 500;
      font-size: 0.9rem;
      color: #1e2b3a;
      border: 1px solid #dce1e8;
    }

    .tag i {
      color: #d4af37;
      margin-right: 8px;
    }

    /* Hero / imagen principal */
    .hero {
      display: flex;
      flex-wrap: wrap;
      gap: 2.5rem;
      align-items: center;
      margin-bottom: 4rem;
      background: #ffffff;
      border-radius: 32px;
      padding: 2rem 2.5rem;
      box-shadow: 0 12px 30px rgba(0,0,0,0.04);
      border: 1px solid #eef2f6;
    }

    .hero-text {
      flex: 1 1 320px;
    }

    .hero-text h2 {
      font-size: 2.4rem;
      font-weight: 700;
      line-height: 1.2;
      margin-bottom: 1.2rem;
    }

    .hero-text h2 i {
      color: #d4af37;
      margin-right: 8px;
    }

    .hero-text p {
      font-size: 1.1rem;
      color: #33475b;
      margin-bottom: 1.8rem;
      max-width: 550px;
    }

    .btn-gold {
      background: #d4af37;
      border: none;
      padding: 0.9rem 2.4rem;
      border-radius: 60px;
      font-weight: 600;
      color: #0b1a2e;
      font-size: 1rem;
      box-shadow: 0 6px 14px rgba(212, 175, 55, 0.3);
      transition: all 0.2s;
      display: inline-block;
      text-decoration: none;
    }

    .btn-gold:hover {
      background: #c09c2e;
      transform: scale(1.02);
      box-shadow: 0 8px 18px rgba(212, 175, 55, 0.4);
    }

    .hero-image {
      flex: 1 1 300px;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .hero-image img {
      width: 100%;
      max-width: 420px;
      border-radius: 24px;
      box-shadow: 0 12px 28px rgba(0,0,0,0.08);
      object-fit: cover;
      background: #f1f5f9;
    }

    /* Tarjetas de tácticas */
    .section-title {
      font-size: 2rem;
      font-weight: 700;
      margin-bottom: 0.5rem;
      display: flex;
      align-items: center;
      gap: 12px;
    }

    .section-title i {
      color: #d4af37;
    }

    .subhead {
      color: #4a5b6e;
      margin-bottom: 2.5rem;
      font-size: 1.1rem;
      border-left: 4px solid #d4af37;
      padding-left: 1.2rem;
    }

    .cards-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 2rem;
      margin: 2.5rem 0 3.5rem;
    }

    .card {
      background: #ffffff;
      padding: 1.8rem 1.5rem;
      border-radius: 28px;
      border: 1px solid #e6ecf3;
      transition: 0.2s ease-in-out;
      box-shadow: 0 4px 12px rgba(0,0,0,0.02);
    }

    .card:hover {
      transform: translateY(-6px);
      border-color: #d4af37;
      box-shadow: 0 16px 30px rgba(0,0,0,0.04);
    }

    .card-icon {
      font-size: 2.2rem;
      color: #d4af37;
      margin-bottom: 1rem;
    }

    .card h3 {
      font-size: 1.4rem;
      font-weight: 600;
      margin-bottom: 0.8rem;
    }

    .card p {
      color: #2d4055;
      font-size: 0.98rem;
    }

    .card .badge {
      display: inline-block;
      margin-top: 1rem;
      background: #f0f4fa;
      padding: 0.25rem 1rem;
      border-radius: 40px;
      font-size: 0.8rem;
      font-weight: 500;
      color: #1e3a5f;
    }

    /* Sección de pasos / imagen extra */
    .step-section {
      display: flex;
      flex-wrap: wrap;
      gap: 2.8rem;
      background: #0b1a2e;
      color: #f0f6fd;
      border-radius: 36px;
      padding: 2.8rem 2.8rem;
      margin: 4rem 0;
      align-items: center;
    }

    .step-content {
      flex: 1 1 280px;
    }

    .step-content h3 {
      font-size: 2rem;
      font-weight: 600;
      margin-bottom: 1.5rem;
    }

    .step-content h3 i {
      color: #d4af37;
      margin-right: 10px;
    }

    .step-list {
      list-style: none;
    }

    .step-list li {
      display: flex;
      gap: 16px;
      align-items: flex-start;
      margin-bottom: 1.2rem;
    }

    .step-list li i {
      color: #d4af37;
      font-size: 1.4rem;
      min-width: 28px;
      margin-top: 4px;
    }

    .step-img {
      flex: 1 1 240px;
      display: flex;
      justify-content: center;
    }

    .step-img img {
      width: 100%;
      max-width: 300px;
      border-radius: 24px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.3);
      background: #1f3347;
    }

    /* Cita / frase */
    .quote-box {
      background: #f1f6fc;
      border-radius: 28px;
      padding: 2.2rem 2.5rem;
      margin: 3rem 0;
      border-left: 8px solid #d4af37;
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      gap: 1.5rem;
    }

    .quote-box i {
      font-size: 2.8rem;
      color: #b8860b;
      opacity: 0.5;
    }

    .quote-box blockquote {
      font-size: 1.3rem;
      font-weight: 400;
      color: #1b2e44;
      flex: 1;
    }

    .quote-box cite {
      font-style: normal;
      font-weight: 500;
      color: #3a5a7a;
    }

    /* Footer */
    .footer {
      margin-top: 4.5rem;
      border-top: 1px solid #dfe6ef;
      padding-top: 2rem;
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      align-items: center;
      color: #405b73;
      font-size: 0.95rem;
    }

    .footer i {
      color: #b8860b;
      margin: 0 4px;
    }

    .footer a {
      color: #1b2e44;
      text-decoration: none;
      font-weight: 500;
    }

    .footer a:hover {
      color: #d4af37;
    }

    /* Responsive */
    @media (max-width: 700px) {
      .hero {
        padding: 1.8rem;
      }
      .hero-text h2 {
        font-size: 2rem;
      }
      .step-section {
        padding: 2rem 1.8rem;
      }
      .quote-box {
        padding: 1.8rem;
      }
      .header {
        flex-direction: column;
        align-items: start;
        gap: 0.8rem;
      }
    }
  </style>
</head>
<body>

<div class="container">

  <!-- Header -->
  <header class="header">
    <div class="logo">
      <h1><i class="fas fa-coins" style="color:#d4af37; background: none; -webkit-background-clip: unset; background-clip: unset;"></i> Oro<span>vs</span>Dollar</h1>
      <div style="font-size:0.9rem; color:#2f4a62; font-weight: 400;">XAUUSD · guía profesional</div>
    </div>
    <div class="tag">
      <i class="fas fa-chart-line"></i> Tácticas 2026 · Análisis técnico
    </div>
  </header>

  <!-- Hero principal con imagen -->
  <div class="hero">
    <div class="hero-text">
      <h2><i class="fas fa-arrow-trend-up"></i> Invertir en XAUUSD</h2>
      <p>Descubre las tácticas esenciales para operar el par oro/dólar. Desde fundamentos hasta gestión de riesgo, todo lo que necesitas para empezar con confianza.</p>
      <a href="#" class="btn-gold"><i class="fas fa-gem" style="margin-right: 10px;"></i>Comienza ahora</a>
    </div>
    <div class="hero-image">
      <!-- foto de stock profesional: oro y gráficos -->
      <img src="https://images.unsplash.com/photo-1611974789855-9c2a0a7236a3?w=600&h=400&fit=crop&crop=center&auto=format" alt="Gráfico de oro y lingotes" loading="lazy">
    </div>
  </div>

  <!-- Tácticas principales (cards) -->
  <div style="margin-top: 1rem;">
    <div class="section-title">
      <i class="fas fa-bullseye"></i> Tácticas profesionales
    </div>
    <div class="subhead">
      Estrategias clave para operar XAUUSD con fundamentos y análisis técnico.
    </div>
  </div>

  <div class="cards-grid">
    <div class="card">
      <div class="card-icon"><i class="fas fa-flag-checkered"></i></div>
      <h3>Análisis fundamental</h3>
      <p>Sigue los datos de empleo, inflación y decisiones de la FED. El oro reacciona con fuerza a los tipos de interés y al dólar.</p>
      <span class="badge"><i class="far fa-clock"></i> Macroeconomía</span>
    </div>
    <div class="card">
      <div class="card-icon"><i class="fas fa-chart-simple"></i></div>
      <h3>Soporte y resistencia</h3>
      <p>Identifica zonas clave en el gráfico diario. Los niveles psicológicos (ej. 1900, 2000) son puntos de inflexión habituales.</p>
      <span class="badge"><i class="fas fa-ruler"></i> Niveles clave</span>
    </div>
    <div class="card">
      <div class="card-icon"><i class="fas fa-wave-square"></i></div>
      <h3>Medias móviles</h3>
      <p>Usa EMAs de 50 y 200 periodos para seguir la tendencia. Cruces y pendientes te dan señales de entrada/salida.</p>
      <span class="badge"><i class="fas fa-filter"></i> Trend following</span>
    </div>
    <div class="card">
      <div class="card-icon"><i class="fas fa-shield-halved"></i></div>
      <h3>Gestión de riesgo</h3>
      <p>Nunca arriesgues más del 1-2% por operación. Usa stops ajustados y relación riesgo/beneficio mínima 1:2.</p>
      <span class="badge"><i class="fas fa-scale-balanced"></i> Protección</span>
    </div>
  </div>

  <!-- Sección pasos + imagen extra (foto stock) -->
  <div class="step-section">
    <div class="step-content">
      <h3><i class="fas fa-list-check"></i> Primeros pasos</h3>
      <ul class="step-list">
        <li><i class="fas fa-circle-check"></i> <span><strong>Elige un bróker</strong> — regulado, con bajos spreads y ejecución rápida.</span></li>
        <li><i class="fas fa-circle-check"></i> <span><strong>Practica en demo</strong> — al menos 2 semanas para conocer la volatilidad del oro.</span></li>
        <li><i class="fas fa-circle-check"></i> <span><strong>Define tu perfil</strong> — intradía, swing o posición. Cada uno requiere tácticas distintas.</span></li>
        <li><i class="fas fa-circle-check"></i> <span><strong>Plan de trading</strong> — horarios, noticias, y reglas de entrada/salida.</span></li>
      </ul>
    </div>
    <div class="step-img">
      <img src="https://images.unsplash.com/photo-1611974789855-9c2a0a7236a3?w=400&h=300&fit=crop&crop=center&auto=format" alt="Análisis de gráfico XAUUSD" loading="lazy">
    </div>
  </div>

  <!-- Cita / inspiración -->
  <div class="quote-box">
    <i class="fas fa-quote-left"></i>
    <blockquote>
      “El oro es el dinero de los reyes. En XAUUSD, la paciencia y la disciplina son más valiosas que cualquier indicador.”
      <br><cite>— Traders Institute · 2026</cite>
    </blockquote>
  </div>

  <!-- Foto extra (tercera imagen) con contexto de mercado -->
  <div style="display: flex; flex-wrap: wrap; gap: 2rem; background: #ffffff; border-radius: 32px; padding: 1.2rem 1.8rem; align-items: center; border:1px solid #ebf0f6; margin: 2.8rem 0;">
    <div style="flex: 1 1 200px;">
      <img src="https://images.unsplash.com/photo-1589883661923-6476cb0ae9f2?w=400&h=280&fit=crop&crop=center&auto=format" alt="Lingotes de oro" style="width:100%; border-radius: 20px; box-shadow: 0 6px 16px rgba(0,0,0,0.04);">
    </div>
    <div style="flex: 2 1 240px;">
      <h3 style="display: flex; align-items: center; gap: 12px; font-size: 1.7rem;"><i class="fas fa-arrow-right" style="color:#d4af37;"></i>Por qué XAUUSD?</h3>
      <p style="color: #1e3349;">El oro es un activo refugio por excelencia. En un entorno de incertidumbre, la demanda de oro se dispara. Aprende a leer el mercado y aprovecha las oportunidades que ofrece el par más líquido del mundo.</p>
      <div style="margin-top: 14px; display: flex; gap: 16px; flex-wrap: wrap;">
        <span style="background:#ecf3fa; padding: 0.2rem 1.2rem; border-radius: 40px; font-size:0.9rem;"><i class="fas fa-clock" style="color:#b8860b;"></i> 24h / 5d</span>
        <span style="background:#ecf3fa; padding: 0.2rem 1.2rem; border-radius: 40px; font-size:0.9rem;"><i class="fas fa-bolt" style="color:#b8860b;"></i> Alta liquidez</span>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="footer">
    <div>
      <i class="fas fa-crown"></i> XAUUSD · Guía profesional · 2026
    </div>
    <div>
      <i class="fas fa-share-nodes"></i> Estrategias · <i class="fas fa-chart-pie"></i> Riesgo
      <span style="margin-left: 1rem; opacity:0.6;">|</span>
      <a href="#"><i class="fab fa-twitter"></i></a>
      <a href="#" style="margin-left: 12px;"><i class="fab fa-linkedin-in"></i></a>
    </div>
  </footer>

</div>
<!-- fin container -->
</body>
</html>
