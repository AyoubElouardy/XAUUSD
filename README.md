

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

    /* Nueva sección de estrategias */
    .strategy-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 2.2rem;
      margin: 2.8rem 0 3.5rem;
    }
    .strategy-card {
      background: white;
      border-radius: 28px;
      padding: 2rem 1.8rem;
      border: 1px solid #e2eaf2;
      box-shadow: 0 4px 12px rgba(0,0,0,0.02);
      transition: 0.2s;
    }
    .strategy-card:hover {
      border-color: #d4af37;
      transform: translateY(-4px);
      box-shadow: 0 12px 28px rgba(0,0,0,0.04);
    }
    .strategy-card h4 {
      font-size: 1.3rem;
      margin-bottom: 0.6rem;
      color: #0b1a2e;
    }
    .strategy-card h4 i {
      color: #d4af37;
      margin-right: 10px;
    }
    .strategy-card .meta {
      display: inline-block;
      background: #f0f5fb;
      padding: 0.15rem 1rem;
      border-radius: 40px;
      font-size: 0.8rem;
      font-weight: 500;
      color: #1e3a5f;
      margin: 0.5rem 0 0.8rem 0;
    }
    .strategy-card ul {
      list-style: none;
      padding-left: 0;
    }
    .strategy-card ul li {
      padding: 0.3rem 0;
      display: flex;
      gap: 8px;
      align-items: baseline;
      font-size: 0.95rem;
      color: #1f344a;
    }
    .strategy-card ul li i {
      color: #b8860b;
      width: 18px;
      font-size: 0.9rem;
    }
    .badge-gold {
      background: #d4af37;
      color: #0b1a2e;
      padding: 0.1rem 0.9rem;
      border-radius: 30px;
      font-weight: 600;
      font-size: 0.8rem;
      display: inline-block;
      margin-top: 0.8rem;
    }
  </style>
</head>
<body>

<div class="container">

  <!-- Header -->
  <header class="header">
    <div class="logo">
      <h1><i class="fas fa-coins" style="color:#d4af37; background: none; -webkit-background-clip: unset; background-clip: unset;"></i> Oro<span>vs</span>Dollar</h1>
      <div style="font-size:0.9rem; color:#2f4a62; font-weight: 400;">XAUUSD · tácticas y estrategias 2026</div>
    </div>
    <div class="tag">
      <i class="fas fa-chart-line"></i> Análisis técnico · Gestión de riesgo
    </div>
  </header>

  <!-- Hero principal -->
  <div class="hero">
    <div class="hero-text">
      <h2><i class="fas fa-arrow-trend-up"></i> Invertir en XAUUSD</h2>
      <p>Descubre las tácticas esenciales para operar el par oro/dólar. Desde fundamentos hasta gestión de riesgo, todo lo que necesitas para empezar con confianza.</p>
      <a href="#" class="btn-gold"><i class="fas fa-gem" style="margin-right: 10px;"></i>Comienza ahora</a>
    </div>
    <div class="hero-image">
      <img src="https://images.unsplash.com/photo-1611974789855-9c2a0a7236a3?w=600&h=400&fit=crop&crop=center&auto=format" alt="Gráfico de oro y lingotes" loading="lazy">
    </div>
  </div>

  <!-- Tácticas principales (cards) -->
  <div style="margin-top: 1rem;">
    <div class="section-title">
      <i class="fas fa-bullseye"></i> Tácticas clave para operar oro
    </div>
    <div class="subhead">
      Estrategias fundamentales y técnicas de análisis para el trading de XAUUSD.
    </div>
  </div>

  <div class="cards-grid">
    <div class="card">
      <div class="card-icon"><i class="fas fa-flag-checkered"></i></div>
      <h3>Análisis fundamental</h3>
      <p>El oro reacciona con fuerza a los datos de empleo, inflación y decisiones de la FED. La relación inversa con el dólar (DXY) es clave, aunque en 2026 se ha vuelto menos predecible debido a la acumulación de oro por parte de bancos centrales [citation:2].</p>
      <span class="badge"><i class="far fa-clock"></i> Macroeconomía</span>
    </div>
    <div class="card">
      <div class="card-icon"><i class="fas fa-chart-simple"></i></div>
      <h3>Soporte y resistencia</h3>
      <p>Identifica zonas clave en el gráfico diario. Los niveles psicológicos (ej. 4000, 4500) son puntos de inflexión habituales. La capacidad de identificar estructuras significativas es clave para un análisis efectivo del oro [citation:5].</p>
      <span class="badge"><i class="fas fa-ruler"></i> Niveles clave</span>
    </div>
    <div class="card">
      <div class="card-icon"><i class="fas fa-wave-square"></i></div>
      <h3>Medias móviles y ATR</h3>
      <p>Usa EMAs de 20 y 50 periodos para seguir la tendencia. En 2026, con rangos diarios de $150-$200, el ATR (Average True Range) es el indicador más crítico para ajustar los stops [citation:4].</p>
      <span class="badge"><i class="fas fa-filter"></i> Trend following</span>
    </div>
    <div class="card">
      <div class="card-icon"><i class="fas fa-shield-halved"></i></div>
      <h3>Gestión de riesgo</h3>
      <p>Nunca arriesgues más del 1-2% por operación. Usa stops basados en ATR (ej. 1.5x ATR) y relación riesgo/beneficio mínima 1:2. La disciplina es más valiosa que cualquier indicador [citation:1].</p>
      <span class="badge"><i class="fas fa-scale-balanced"></i> Protección</span>
    </div>
  </div>

  <!-- Sección de estrategias detalladas (NUEVO) -->
  <div style="margin-top: 3rem;">
    <div class="section-title">
      <i class="fas fa-chess-queen"></i> Estrategias de inversión 2026
    </div>
    <div class="subhead">
      Enfoques probados para diferentes condiciones del mercado, adaptados a la alta volatilidad actual.
    </div>
  </div>

  <div class="strategy-grid">
    <!-- Estrategia 1: London Open Breakout -->
    <div class="strategy-card">
      <h4><i class="fas fa-city"></i> London Open Breakout</h4>
      <span class="meta"><i class="far fa-clock"></i> Day trading · 08:00-12:00 GMT</span>
      <ul>
        <li><i class="fas fa-check-circle"></i> <strong>Definir rango:</strong> Dibuja el rango de la sesión asiática (hasta las 08:00 GMT).</li>
        <li><i class="fas fa-check-circle"></i> <strong>Confirmar ruptura:</strong> Espera un cierre de vela de 30-60min fuera del rango con volumen.</li>
        <li><i class="fas fa-check-circle"></i> <strong>Entrada y stop:</strong> Entra en dirección de la ruptura; stop a 1.5x ATR por debajo/encima del mínimo/máximo de la vela de ruptura [citation:4].</li>
        <li><i class="fas fa-check-circle"></i> <strong>Objetivo:</strong> Próximo nivel de soporte/resistencia o ratio R:R 1:2/1:3.</li>
      </ul>
      <span class="badge-gold"><i class="fas fa-bolt"></i> Alta probabilidad</span>
    </div>

    <!-- Estrategia 2: Trend Following con Pullback -->
    <div class="strategy-card">
      <h4><i class="fas fa-trend-up"></i> Pullback a EMA</h4>
      <span class="meta"><i class="fas fa-chart-line"></i> Seguimiento de tendencia</span>
      <ul>
        <li><i class="fas fa-check-circle"></i> <strong>Identificar tendencia:</strong> Precio por encima de EMA de 50 periodos en gráfico H4/D1.</li>
        <li><i class="fas fa-check-circle"></i> <strong>Esperar pullback:</strong> El precio retrocede hasta la EMA de 20 o 50 periodos.</li>
        <li><i class="fas fa-check-circle"></i> <strong>Entrada:</strong> Tras confirmación de soporte (vela de rechazo o patrón de precio).</li>
        <li><i class="fas fa-check-circle"></i> <strong>Stop loss:</strong> Debajo del mínimo del pullback o 1.5x ATR. Objetivo: siguiente nivel de estructura [citation:10].</li>
      </ul>
      <span class="badge-gold"><i class="fas fa-arrow-up"></i> Tendencia alcista</span>
    </div>

    <!-- Estrategia 3: RSI Divergencia -->
    <div class="strategy-card">
      <h4><i class="fas fa-arrows-spin"></i> RSI Divergencia</h4>
      <span class="meta"><i class="fas fa-wave-square"></i> Reversión · 5-15 min</span>
      <ul>
        <li><i class="fas fa-check-circle"></i> <strong>Identificar divergencia:</strong> El precio hace un nuevo máximo/mínimo, pero el RSI no lo confirma.</li>
        <li><i class="fas fa-check-circle"></i> <strong>Confirmación:</strong> Espera un cambio de estructura (quiebre de tendencia) o patrón de reversión.</li>
        <li><i class="fas fa-check-circle"></i> <strong>Entrada:</strong> En la dirección de la reversión anticipada.</li>
        <li><i class="fas fa-check-circle"></i> <strong>Stop y objetivo:</strong> Stop en el extremo de la divergencia; objetivo en el siguiente soporte/resistencia [citation:10].</li>
      </ul>
      <span class="badge-gold"><i class="fas fa-arrows-left-right"></i> Rango / Reversión</span>
    </div>
  </div>

  <!-- Sección de fundamentos extendida (NUEVO) -->
  <div style="background: #ffffff; border-radius: 32px; padding: 2rem 2.5rem; margin: 2.5rem 0; border: 1px solid #ebf0f6;">
    <h3 style="display: flex; align-items: center; gap: 12px; font-size: 1.8rem;"><i class="fas fa-database" style="color:#d4af37;"></i> Factores clave que mueven el oro en 2026</h3>
    <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(210px,1fr)); gap: 1.8rem; margin-top: 1.5rem;">
      <div>
        <h4><i class="fas fa-dollar-sign" style="color:#b8860b;"></i> Dólar y tipos reales</h4>
        <p style="font-size:0.95rem; color: #1e3349;">El oro no genera interés. Cuando los rendimientos reales (bonos - inflación) caen, el oro sube. Sin embargo, en 2026 la acumulación de bancos centrales ha roto esta relación en momentos clave [citation:2][citation:4].</p>
      </div>
      <div>
        <h4><i class="fas fa-building-columns" style="color:#b8860b;"></i> Bancos centrales</h4>
        <p style="font-size:0.95rem; color: #1e3349;">China, India, Turquía y Polonia han comprado oro de forma agresiva (297 toneladas hasta nov 2025). Esta demanda estructural apuntala el precio incluso cuando el dólar se fortalece [citation:4][citation:11].</p>
      </div>
      <div>
        <h4><i class="fas fa-globe" style="color:#b8860b;"></i> Geopolítica</h4>
        <p style="font-size:0.95rem; color: #1e3349;">Conflictos como el de Oriente Medio generan oleadas de compras de refugio. El oro reacciona con fuerza a las noticias, pero los retrocesos pueden ser rápidos si la tensión disminuye [citation:8][citation:9].</p>
      </div>
      <div>
        <h4><i class="fas fa-flag" style="color:#b8860b;"></i> Ratio Oro/Plata</h4>
        <p style="font-size:0.95rem; color: #1e3349;">Actualmente en la zona media-baja de los 60. Un ratio >80 señala posible agotamiento alcista del oro; <50 puede indicar infravaloración [citation:4].</p>
      </div>
    </div>
  </div>

  <!-- Pasos para empezar a invertir -->
  <div class="step-section">
    <div class="step-content">
      <h3><i class="fas fa-list-check"></i> Primeros pasos en XAUUSD</h3>
      <ul class="step-list">
        <li><i class="fas fa-circle-check"></i> <span><strong>Elige un bróker</strong> — regulado, con bajos spreads en XAUUSD y ejecución rápida [citation:3].</span></li>
        <li><i class="fas fa-circle-check"></i> <span><strong>Practica en demo</strong> — al menos 2-4 semanas para conocer la volatilidad y probar estrategias [citation:5].</span></li>
        <li><i class="fas fa-circle-check"></i> <span><strong>Define tu perfil</strong> — intradía, swing o posición. Cada uno requiere tácticas distintas y marcos temporales específicos [citation:5].</span></li>
        <li><i class="fas fa-circle-check"></i> <span><strong>Plan de trading</strong> — define horarios (mejor NYLON: 08:00-12:00 EST), noticias a seguir y reglas de entrada/salida [citation:4].</span></li>
        <li><i class="fas fa-circle-check"></i> <span><strong>Gestión de riesgo</strong> — riesgo máximo 1-2% por operación, usa stops dinámicos con ATR y no sobreapalanques [citation:1].</span></li>
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
      “El oro no es para quienes hacen muchas operaciones, sino para quienes operan en el momento adecuado, en el lugar adecuado y con la disciplina correcta. Menos órdenes = más dinero.” [citation:1]
      <br><cite>— TradingView · 2026</cite>
    </blockquote>
  </div>

  <!-- Foto extra (tercera imagen) con contexto de mercado -->
  <div style="display: flex; flex-wrap: wrap; gap: 2rem; background: #ffffff; border-radius: 32px; padding: 1.2rem 1.8rem; align-items: center; border:1px solid #ebf0f6; margin: 2.8rem 0;">
    <div style="flex: 1 1 200px;">
      <img src="https://images.unsplash.com/photo-1589883661923-6476cb0ae9f2?w=400&h=280&fit=crop&crop=center&auto=format" alt="Lingotes de oro" style="width:100%; border-radius: 20px; box-shadow: 0 6px 16px rgba(0,0,0,0.04);">
    </div>
    <div style="flex: 2 1 240px;">
      <h3 style="display: flex; align-items: center; gap: 12px; font-size: 1.7rem;"><i class="fas fa-arrow-right" style="color:#d4af37;"></i>¿Por qué XAUUSD en 2026?</h3>
      <p style="color: #1e3349;">El oro ha superado los $5000 por onza, con rangos diarios de $150-$200. La demanda de bancos centrales y la geopolítica lo han convertido en un activo de alta volatilidad. Aprender a leer el contexto es más importante que nunca [citation:4][citation:11].</p>
      <div style="margin-top: 14px; display: flex; gap: 16px; flex-wrap: wrap;">
        <span style="background:#ecf3fa; padding: 0.2rem 1.2rem; border-radius: 40px; font-size:0.9rem;"><i class="fas fa-clock" style="color:#b8860b;"></i> 24h / 5d</span>
        <span style="background:#ecf3fa; padding: 0.2rem 1.2rem; border-radius: 40px; font-size:0.9rem;"><i class="fas fa-bolt" style="color:#b8860b;"></i> Alta liquidez</span>
        <span style="background:#ecf3fa; padding: 0.2rem 1.2rem; border-radius: 40px; font-size:0.9rem;"><i class="fas fa-arrow-trend-up" style="color:#b8860b;"></i> Tendencia alcista</span>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="footer">
    <div>
      <i class="fas fa-crown"></i> XAUUSD · Tácticas y estrategias · 2026
    </div>
    <div>
      <i class="fas fa-share-nodes"></i> Análisis · <i class="fas fa-chart-pie"></i> Riesgo
      <span style="margin-left: 1rem; opacity:0.6;">|</span>
      <a href="#"><i class="fab fa-twitter"></i></a>
      <a href="#" style="margin-left: 12px;"><i class="fab fa-linkedin-in"></i></a>
    </div>
  </footer>

</div>
<!-- fin container -->
</body>
</html>
