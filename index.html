<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>AMRAX v1.0 — Institutional EA</title>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400&family=Outfit:wght@300;400;500;600;700&family=DM+Mono:wght@400;500&display=swap" rel="stylesheet" />
  <style>
    /* ============================================
       CSS VARIABLES — Edit colors/theme here
    ============================================ */
    :root {
      --gold: #c9a84c;
      --gold-light: #e8c97a;
      --gold-dim: #8a6d2a;
      --obsidian: #09090b;
      --obsidian-2: #0f0f12;
      --surface: #141418;
      --surface-2: #1c1c22;
      --surface-3: #242430;
      --border: rgba(201,168,76,0.15);
      --border-strong: rgba(201,168,76,0.35);
      --text-primary: #f0ece0;
      --text-secondary: #a09880;
      --text-muted: #5a5448;
      --profit: #4caf7d;
      --profit-dim: #2d7a54;
    }

    /* ============================================
       BASE RESET
    ============================================ */
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
    html { scroll-behavior: smooth; }
    body {
      background: var(--obsidian);
      color: var(--text-primary);
      font-family: 'Outfit', sans-serif;
      font-weight: 300;
      -webkit-font-smoothing: antialiased;
      overflow-x: hidden;
    }
    body::before {
      content: "";
      pointer-events: none;
      z-index: 9999;
      opacity: 0.4;
      background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)' opacity='0.04'/%3E%3C/svg%3E");
      position: fixed;
      inset: 0;
    }
    a { color: inherit; text-decoration: none; }
    img, svg { display: block; }
    ul, ol { list-style: none; }
    button { background: none; border: none; cursor: pointer; font: inherit; color: inherit; }

    /* ============================================
       TYPOGRAPHY HELPERS
    ============================================ */
    .font-display { font-family: 'Cormorant Garamond', serif; }
    .font-mono    { font-family: 'DM Mono', monospace; }
    .text-gold    { color: var(--gold); }
    .text-gold-gradient {
      background: linear-gradient(135deg, var(--gold-light) 0%, var(--gold) 50%, var(--gold-dim) 100%);
      -webkit-text-fill-color: transparent;
      -webkit-background-clip: text;
      background-clip: text;
    }
    .uppercase { text-transform: uppercase; }
    .tracking-widest { letter-spacing: 0.1em; }

    /* ============================================
       LAYOUT UTILITIES
    ============================================ */
    .container { max-width: 1280px; margin: 0 auto; }
    .section-pad { padding: 96px 24px; }
    @media (min-width: 768px) { .section-pad { padding: 96px 48px; } }
    @media (min-width: 1024px) { .section-pad { padding: 96px 96px; } }

    /* ============================================
       COMPONENTS
    ============================================ */

    /* Gold border card */
    .gold-border {
      border: 1px solid var(--border);
      box-shadow: 0 0 0 1px rgba(201,168,76,0.05), inset 0 1px rgba(201,168,76,0.08);
    }
    .gold-border:hover {
      border-color: var(--border-strong);
      box-shadow: 0 0 24px rgba(201,168,76,0.08), inset 0 1px rgba(201,168,76,0.12);
    }

    /* Gold button */
    .btn-gold {
      background: linear-gradient(135deg, var(--gold-light) 0%, var(--gold) 60%, var(--gold-dim) 100%);
      color: #0a0804;
      letter-spacing: 0.04em;
      font-weight: 600;
      transition: filter 0.2s, transform 0.15s, box-shadow 0.2s;
      box-shadow: 0 4px 20px rgba(201,168,76,0.3);
      display: inline-flex;
      align-items: center;
      gap: 10px;
      padding: 14px 32px;
      border-radius: 12px;
      font-size: 0.8rem;
      text-transform: uppercase;
      border: none;
      cursor: pointer;
    }
    .btn-gold:hover { filter: brightness(1.12); transform: translateY(-1px); box-shadow: 0 8px 32px rgba(201,168,76,0.4); }
    .btn-gold:active { filter: brightness(0.95); transform: translateY(0); }

    /* Gold divider */
    .divider-gold {
      background: linear-gradient(90deg, transparent, var(--gold-dim), transparent);
      height: 1px;
      max-width: 1000px;
      margin: 0 auto;
    }

    /* Scroll reveal animations */
    .reveal {
      opacity: 0;
      transform: translateY(32px);
      transition: opacity 0.8s cubic-bezier(0.16,1,0.3,1), transform 0.8s cubic-bezier(0.16,1,0.3,1);
    }
    .reveal.visible { opacity: 1; transform: translateY(0); }
    .delay-100 { transition-delay: 0.1s; }
    .delay-200 { transition-delay: 0.2s; }
    .delay-300 { transition-delay: 0.3s; }
    .delay-400 { transition-delay: 0.4s; }
    .delay-500 { transition-delay: 0.5s; }

    /* Shimmer line */
    @keyframes shimmer { 0% { background-position: -200%; } 100% { background-position: 200%; } }
    .shimmer-line {
      background: linear-gradient(90deg, transparent, rgba(201,168,76,0.15), transparent) 0 0 / 200%;
      animation: shimmer 3s linear infinite;
      height: 1px;
      width: 100%;
      border-radius: 9999px;
    }

    /* Pulse dot */
    @keyframes pulse-dot { 0%,100% { opacity:1; transform:scale(1); } 50% { opacity:0.5; transform:scale(0.85); } }
    .pulse-dot { animation: pulse-dot 2s ease-in-out infinite; }

    /* ============================================
       NAVBAR
    ============================================ */
    nav {
      position: fixed; top: 0; left: 0; right: 0; z-index: 50;
      display: flex; align-items: center; justify-content: space-between;
      padding: 16px 24px;
      background: rgba(9,9,11,0.85);
      backdrop-filter: blur(24px);
      border-bottom: 1px solid rgba(201,168,76,0.08);
    }
    @media (min-width: 768px) { nav { padding: 16px 48px; } }

    .nav-logo { display: flex; align-items: center; gap: 10px; }
    .nav-logo-text {
      font-family: 'Cormorant Garamond', serif;
      font-weight: 600;
      font-size: 1.2rem;
      letter-spacing: 0.15em;
      color: var(--gold);
    }
    .nav-badge {
      font-family: 'DM Mono', monospace;
      font-size: 0.7rem;
      padding: 2px 8px;
      border-radius: 4px;
      background: rgba(201,168,76,0.1);
      color: var(--gold-dim);
      border: 1px solid rgba(201,168,76,0.15);
    }
    .nav-links { display: none; gap: 32px; }
    @media (min-width: 768px) { .nav-links { display: flex; align-items: center; } }
    .nav-links a {
      font-size: 0.875rem;
      color: var(--text-secondary);
      transition: color 0.2s;
    }
    .nav-links a:hover { color: var(--gold); }
    .nav-cta { display: none; }
    @media (min-width: 768px) { .nav-cta { display: inline-flex; } }

    /* Mobile menu */
    .mobile-menu-btn { display: flex; padding: 8px; color: var(--gold); }
    @media (min-width: 768px) { .mobile-menu-btn { display: none; } }
    .mobile-menu {
      display: none;
      position: fixed; top: 65px; left: 0; right: 0; z-index: 40;
      padding: 24px;
      background: rgba(9,9,11,0.97);
      backdrop-filter: blur(24px);
      border-bottom: 1px solid rgba(201,168,76,0.1);
    }
    .mobile-menu.open { display: block; }
    .mobile-menu a {
      display: block; padding: 16px 0;
      font-size: 0.875rem; color: var(--text-secondary);
      border-bottom: 1px solid rgba(201,168,76,0.06);
    }
    .mobile-menu .btn-gold { display: flex; justify-content: center; margin-top: 20px; padding: 12px; width: 100%; }

    /* ============================================
       HERO SECTION
    ============================================ */
    #hero {
      position: relative;
      min-height: 100vh;
      display: flex; flex-direction: column; align-items: center; justify-content: center;
      text-align: center;
      padding: 96px 24px 80px;
      overflow: hidden;
    }
    .hero-glow {
      position: absolute; inset: 0; pointer-events: none;
      background: radial-gradient(ellipse 80% 50% at 50% 60%, rgba(201,168,76,0.07) 0%, transparent 70%);
    }
    .hero-grid {
      position: absolute; inset: 0; pointer-events: none; opacity: 0.2;
      background-image: linear-gradient(rgba(201,168,76,0.08) 1px, transparent 1px), linear-gradient(90deg, rgba(201,168,76,0.08) 1px, transparent 1px);
      background-size: 80px 80px;
      mask-image: radial-gradient(ellipse 70% 60% at 50% 50%, black 30%, transparent 80%);
    }

    /* ---- EDITABLE: Hero badge text ---- */
    .hero-badge {
      display: inline-flex; align-items: center; gap: 10px;
      padding: 8px 20px;
      border-radius: 9999px;
      font-family: 'DM Mono', monospace;
      font-size: 0.7rem; letter-spacing: 0.15em; text-transform: uppercase;
      background: rgba(201,168,76,0.06); border: 1px solid rgba(201,168,76,0.18); color: var(--gold);
      margin-bottom: 32px;
    }

    /* ---- EDITABLE: Hero title ---- */
    .hero-title {
      font-family: 'Cormorant Garamond', serif;
      font-size: clamp(4rem, 12vw, 9rem);
      font-weight: 600;
      letter-spacing: 0.08em;
      line-height: 0.9;
      background: linear-gradient(135deg, var(--gold-light) 0%, var(--gold) 50%, var(--gold-dim) 100%);
      -webkit-text-fill-color: transparent;
      -webkit-background-clip: text;
      background-clip: text;
      margin-bottom: 12px;
    }
    .hero-version {
      font-family: 'DM Mono', monospace;
      font-size: 0.8rem; letter-spacing: 0.5em; text-transform: uppercase;
      color: var(--text-muted); margin-bottom: 24px;
    }

    /* ---- EDITABLE: Hero tagline ---- */
    .hero-tagline {
      font-family: 'Cormorant Garamond', serif;
      font-size: clamp(1.1rem, 2vw, 1.4rem);
      font-weight: 300; font-style: italic;
      color: var(--text-secondary);
      max-width: 640px; line-height: 1.6; margin-bottom: 16px;
    }

    /* ---- EDITABLE: Hero description ---- */
    .hero-desc {
      font-size: 0.9rem; color: var(--text-muted);
      max-width: 560px; line-height: 1.8; margin-bottom: 48px;
    }

    /* Hero stats */
    .hero-stats { display: flex; flex-wrap: wrap; justify-content: center; gap: 32px; margin-bottom: 48px; }
    .hero-stat-value { font-family: 'Cormorant Garamond', serif; font-size: clamp(1.5rem, 3vw, 1.9rem); font-weight: 600; color: var(--gold-light); }
    .hero-stat-label { font-family: 'DM Mono', monospace; font-size: 0.65rem; letter-spacing: 0.12em; text-transform: uppercase; color: var(--text-muted); margin-top: 4px; }

    /* Hero CTA buttons */
    .hero-ctas { display: flex; flex-direction: column; gap: 16px; align-items: center; }
    @media (min-width: 576px) { .hero-ctas { flex-direction: row; } }
    .btn-outline {
      display: inline-flex; align-items: center; gap: 10px;
      padding: 16px 32px; border-radius: 16px;
      font-size: 0.875rem; font-weight: 400; letter-spacing: 0.06em;
      color: var(--text-secondary);
      border: 1px solid var(--border);
      background: var(--surface);
      transition: all 0.2s;
    }
    .btn-outline:hover { border-color: var(--border-strong); color: var(--gold); }

    /* Scroll indicator */
    .scroll-hint { position: absolute; bottom: 32px; left: 50%; transform: translateX(-50%); display: flex; flex-direction: column; align-items: center; gap: 8px; opacity: 0.4; }
    .scroll-hint span { font-family: 'DM Mono', monospace; font-size: 0.65rem; letter-spacing: 0.2em; color: var(--text-muted); }

    /* ============================================
       PERFORMANCE SECTION
    ============================================ */
    #performance { max-width: 1280px; margin: 0 auto; }

    .section-label { font-family: 'DM Mono', monospace; font-size: 0.65rem; letter-spacing: 0.2em; text-transform: uppercase; color: var(--gold-dim); margin-bottom: 16px; }
    .section-title { font-family: 'Cormorant Garamond', serif; font-size: clamp(2rem, 5vw, 3.75rem); font-weight: 600; color: var(--text-primary); margin-bottom: 24px; }
    .section-desc { font-size: 0.95rem; color: var(--text-secondary); line-height: 1.8; max-width: 640px; margin: 0 auto; }

    /* Metric cards grid */
    .metrics-grid { display: grid; grid-template-columns: repeat(2, 1fr); gap: 16px; margin-bottom: 32px; }
    @media (min-width: 1024px) { .metrics-grid { grid-template-columns: repeat(3, 1fr); } }

    .metric-card {
      background: var(--surface);
      border-radius: 16px; padding: 24px;
      display: flex; flex-direction: column; gap: 12px;
      cursor: default;
      transition: transform 0.3s;
    }
    .metric-card:hover { transform: translateY(-4px); }
    .metric-card-top { display: flex; align-items: center; justify-content: space-between; }
    .metric-icon {
      width: 36px; height: 36px; border-radius: 8px;
      display: flex; align-items: center; justify-content: center;
    }
    .metric-icon.gold { background: rgba(201,168,76,0.08); color: var(--gold); border: 1px solid rgba(201,168,76,0.15); }
    .metric-icon.green { background: rgba(76,175,125,0.1); color: var(--profit); border: 1px solid rgba(76,175,125,0.2); }
    .metric-value { font-family: 'Cormorant Garamond', serif; font-size: 1.9rem; font-weight: 600; line-height: 1; margin-bottom: 4px; }
    .metric-value.gold { color: var(--gold-light); }
    .metric-value.green { color: var(--profit); }
    .metric-suffix { font-size: 1.1rem; }
    .metric-label { font-family: 'DM Mono', monospace; font-size: 0.62rem; letter-spacing: 0.12em; text-transform: uppercase; color: var(--text-muted); margin-top: 8px; }

    /* Insight block */
    .insight-block {
      border-radius: 16px; padding: 24px 32px;
      display: flex; align-items: flex-start; gap: 24px;
      background: linear-gradient(135deg, rgba(201,168,76,0.06) 0%, rgba(76,175,125,0.04) 100%);
      margin-bottom: 32px;
    }
    .insight-icon {
      flex-shrink: 0; width: 48px; height: 48px; border-radius: 12px;
      display: flex; align-items: center; justify-content: center;
      font-family: 'Cormorant Garamond', serif; font-size: 1.4rem; font-weight: 700;
      background: rgba(201,168,76,0.12); color: var(--gold); border: 1px solid rgba(201,168,76,0.25);
    }
    .insight-eyebrow { font-family: 'DM Mono', monospace; font-size: 0.65rem; letter-spacing: 0.2em; text-transform: uppercase; color: var(--gold-dim); margin-bottom: 8px; }
    .insight-text { font-family: 'Cormorant Garamond', serif; font-size: clamp(1rem, 1.5vw, 1.15rem); font-style: italic; color: var(--text-primary); line-height: 1.7; }

    /* Equity curve card */
    .equity-card { background: var(--surface); border-radius: 16px; padding: 32px; }
    .equity-label { font-family: 'DM Mono', monospace; font-size: 0.65rem; letter-spacing: 0.15em; text-transform: uppercase; color: var(--text-muted); margin-bottom: 24px; }
    .equity-footer { display: flex; align-items: center; gap: 16px; margin-top: 16px; font-family: 'DM Mono', monospace; font-size: 0.7rem; color: var(--text-muted); }
    .equity-footer .line { flex: 1; height: 1px; background: rgba(201,168,76,0.08); }

    /* ============================================
       DEPLOYMENT SECTION
    ============================================ */
    #deployment { max-width: 1000px; margin: 0 auto; }

    /* Accordion */
    .accordion { margin-bottom: 16px; background: var(--surface); border-radius: 16px; overflow: hidden; }
    .accordion-btn {
      width: 100%; display: flex; align-items: center; gap: 20px;
      padding: 24px 28px; text-align: left; cursor: pointer; background: none; border: none;
    }
    .accordion-step-icon {
      flex-shrink: 0; width: 40px; height: 40px; border-radius: 10px;
      display: flex; align-items: center; justify-content: center;
      color: var(--gold); border: 1px solid rgba(201,168,76,0.2);
      transition: background 0.3s;
      background: rgba(201,168,76,0.06);
    }
    .accordion.open .accordion-step-icon { background: rgba(201,168,76,0.15); }
    .accordion-step-num { font-family: 'DM Mono', monospace; font-size: 0.65rem; letter-spacing: 0.2em; text-transform: uppercase; color: var(--gold-dim); margin-bottom: 4px; }
    .accordion-title { font-size: 0.95rem; font-weight: 500; color: var(--text-primary); }
    .accordion-chevron { margin-left: auto; color: var(--gold); opacity: 0.7; transition: transform 0.4s ease; }
    .accordion.open .accordion-chevron { transform: rotate(180deg); }
    .accordion-body { max-height: 0; overflow: hidden; transition: max-height 0.5s cubic-bezier(0.16,1,0.3,1); }
    .accordion.open .accordion-body { max-height: 700px; }
    .accordion-content-inner {
      padding: 0 28px 28px;
      color: var(--text-secondary); font-size: 0.875rem; line-height: 1.8;
    }
    .accordion-divider { height: 1px; background: rgba(201,168,76,0.08); margin-bottom: 24px; }

    /* Step list */
    .step-list { background: var(--surface-2); border: 1px solid var(--border); border-radius: 12px; padding: 20px; margin: 16px 0; }
    .step-item { display: flex; align-items: flex-start; gap: 12px; margin-bottom: 12px; }
    .step-item:last-child { margin-bottom: 0; }
    .step-num {
      flex-shrink: 0; width: 24px; height: 24px; border-radius: 50%;
      display: flex; align-items: center; justify-content: center;
      font-size: 0.7rem; font-weight: 700;
      background: rgba(201,168,76,0.15); color: var(--gold);
    }
    .step-text { padding-top: 2px; }

    /* Tip box */
    .tip-box { border-radius: 10px; padding: 12px 16px; font-size: 0.8rem; background: rgba(76,175,125,0.06); border: 1px solid rgba(76,175,125,0.15); color: var(--profit); }
    .tip-box.gold-tip { background: rgba(201,168,76,0.06); border-color: rgba(201,168,76,0.15); color: var(--gold); }

    /* Video section */
    .video-card {
      background: var(--surface); border: 1px solid var(--border);
      border-radius: 24px; overflow: hidden;
      aspect-ratio: 16/9; position: relative;
    }
    .video-card::after { content: ""; background: linear-gradient(135deg, rgba(201,168,76,0.05), transparent 60%); position: absolute; inset: 0; }
    .video-inner {
      width: 100%; height: 100%;
      display: flex; flex-direction: column; align-items: center; justify-content: center; gap: 24px;
      position: relative; z-index: 1;
    }
    .video-scanlines {
      position: absolute; inset: 0; opacity: 0.05;
      background-image: repeating-linear-gradient(0deg, rgba(201,168,76,0.3) 0px, rgba(201,168,76,0.3) 1px, transparent 1px, transparent 60px);
    }
    .play-btn {
      width: 80px; height: 80px; border-radius: 50%;
      display: flex; align-items: center; justify-content: center;
      background: linear-gradient(135deg, rgba(201,168,76,0.2), rgba(201,168,76,0.08));
      border: 2px solid rgba(201,168,76,0.4); color: var(--gold);
      box-shadow: 0 0 40px rgba(201,168,76,0.15);
      transition: all 0.3s; cursor: pointer;
    }
    .play-btn:hover { box-shadow: 0 0 60px rgba(201,168,76,0.3); transform: scale(1.08); }
    .video-title { font-family: 'Cormorant Garamond', serif; font-size: 1.2rem; font-weight: 500; color: var(--text-primary); text-align: center; }
    .video-sub { font-family: 'DM Mono', monospace; font-size: 0.65rem; letter-spacing: 0.2em; text-transform: uppercase; color: var(--gold-dim); text-align: center; }

    /* ============================================
       PRICING SECTION
    ============================================ */
    #pricing { max-width: 1280px; margin: 0 auto; }

    .pricing-grid { display: grid; grid-template-columns: 1fr; gap: 24px; }
    @media (min-width: 768px) { .pricing-grid { grid-template-columns: repeat(3, 1fr); } }

    .pricing-card {
      background: var(--surface); border-radius: 24px;
      padding: 32px; display: flex; flex-direction: column;
      position: relative; overflow: hidden;
      transition: transform 0.4s cubic-bezier(0.16,1,0.3,1), box-shadow 0.4s;
    }
    .pricing-card:hover { transform: translateY(-8px); }
    .pricing-card.featured {
      background: linear-gradient(145deg, #1a1a22, #1e1c18);
      box-shadow: 0 0 60px rgba(201,168,76,0.12), 0 20px 40px rgba(0,0,0,0.5);
      border-color: var(--gold) !important;
    }
    .pricing-card.featured:hover { box-shadow: 0 0 80px rgba(201,168,76,0.2), 0 28px 56px rgba(0,0,0,0.55); }
    .featured-top-line { position: absolute; top: 0; left: 0; right: 0; height: 2px; background: linear-gradient(90deg, transparent, var(--gold), transparent); }
    .featured-badge {
      position: absolute; top: -1px; left: 50%; transform: translateX(-50%);
      padding: 4px 16px; border-radius: 0 0 8px 8px;
      font-family: 'DM Mono', monospace; font-size: 0.65rem; letter-spacing: 0.15em; text-transform: uppercase; font-weight: 500;
      background: var(--gold); color: #0a0804;
    }
    .pricing-tier { font-family: 'DM Mono', monospace; font-size: 0.65rem; letter-spacing: 0.15em; text-transform: uppercase; color: var(--gold-dim); margin-bottom: 12px; }
    .pricing-price { font-family: 'Cormorant Garamond', serif; font-size: 3rem; font-weight: 600; line-height: 1; margin-bottom: 12px; }
    .pricing-price.featured-price { color: var(--gold-light); }
    .pricing-price-usd { font-size: 0.85rem; color: var(--text-muted); font-family: 'Outfit', sans-serif; font-weight: 300; }
    .pricing-desc { font-size: 0.875rem; color: var(--text-secondary); line-height: 1.6; margin-bottom: 24px; }
    .pricing-accounts {
      display: flex; align-items: center; gap: 8px;
      padding: 10px 16px; border-radius: 10px; margin-bottom: 24px;
      background: rgba(201,168,76,0.06); border: 1px solid rgba(201,168,76,0.1);
      font-size: 0.875rem; font-weight: 500; color: var(--gold);
    }
    .pricing-features { list-style: none; margin-bottom: 32px; flex: 1; }
    .pricing-features li { display: flex; align-items: flex-start; gap: 10px; font-size: 0.875rem; color: var(--text-secondary); margin-bottom: 12px; }
    .pricing-features li .check { flex-shrink: 0; margin-top: 2px; color: var(--profit); }
    .pricing-cta {
      display: flex; align-items: center; justify-content: center; gap: 8px;
      width: 100%; padding: 16px; border-radius: 12px;
      font-size: 0.75rem; font-weight: 600; letter-spacing: 0.1em; text-transform: uppercase;
      transition: all 0.2s;
    }
    .pricing-cta.cta-gold {
      background: linear-gradient(135deg, var(--gold-light) 0%, var(--gold) 60%, var(--gold-dim) 100%);
      color: #0a0804; box-shadow: 0 4px 20px rgba(201,168,76,0.3);
    }
    .pricing-cta.cta-gold:hover { filter: brightness(1.1); transform: translateY(-1px); }
    .pricing-cta.cta-outline { background: var(--surface-3); color: var(--gold); border: 1px solid var(--border-strong); }
    .pricing-cta.cta-outline:hover { border-color: var(--gold); background: rgba(201,168,76,0.08); }

    /* Trust badges under pricing */
    .trust-grid {
      display: grid; grid-template-columns: repeat(2, 1fr); gap: 24px;
      background: var(--surface); border: 1px solid var(--border);
      border-radius: 16px; padding: 24px 32px;
      margin-top: 48px; text-align: center;
    }
    @media (min-width: 768px) { .trust-grid { grid-template-columns: repeat(4, 1fr); } }
    .trust-item { display: flex; flex-direction: column; align-items: center; gap: 12px; }
    .trust-icon { width: 40px; height: 40px; border-radius: 10px; display: flex; align-items: center; justify-content: center; background: rgba(201,168,76,0.08); color: var(--gold); border: 1px solid rgba(201,168,76,0.12); }
    .trust-label { font-size: 0.875rem; font-weight: 500; color: var(--text-primary); }
    .trust-sub { font-size: 0.75rem; color: var(--text-muted); }

    /* ============================================
       TESTIMONIALS
    ============================================ */
    #testimonials { background: var(--surface); border-top: 1px solid var(--border); border-bottom: 1px solid var(--border); padding: 64px 24px; }
    @media (min-width: 768px) { #testimonials { padding: 64px 48px; } }
    .testimonials-grid { display: grid; grid-template-columns: 1fr; gap: 24px; max-width: 1280px; margin: 0 auto; }
    @media (min-width: 768px) { .testimonials-grid { grid-template-columns: repeat(3, 1fr); } }
    .testimonial-card { background: var(--surface-2); border-radius: 16px; padding: 24px; }
    .stars { display: flex; gap: 4px; margin-bottom: 16px; color: var(--gold); }
    .testimonial-text { font-family: 'Cormorant Garamond', serif; font-size: 0.975rem; font-style: italic; font-weight: 300; color: var(--text-secondary); line-height: 1.7; margin-bottom: 20px; }
    .testimonial-author { display: flex; align-items: center; gap: 12px; }
    .author-avatar { width: 36px; height: 36px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 0.875rem; font-weight: 600; background: rgba(201,168,76,0.12); color: var(--gold); }
    .author-name { font-size: 0.875rem; font-weight: 500; color: var(--text-primary); }
    .author-role { font-size: 0.75rem; color: var(--text-muted); }

    /* ============================================
       CTA SECTION
    ============================================ */
    #cta { padding: 112px 24px; text-align: center; position: relative; overflow: hidden; }
    .cta-glow { position: absolute; inset: 0; pointer-events: none; background: radial-gradient(ellipse 60% 80% at 50% 50%, rgba(201,168,76,0.06) 0%, transparent 70%); }
    .cta-title { font-family: 'Cormorant Garamond', serif; font-size: clamp(2.5rem, 7vw, 4.5rem); font-weight: 600; line-height: 1.1; color: var(--text-primary); max-width: 760px; margin: 0 auto 24px; }
    .cta-desc { font-size: 0.975rem; color: var(--text-secondary); max-width: 560px; margin: 0 auto 48px; line-height: 1.8; }
    .cta-buttons { display: flex; flex-direction: column; gap: 16px; align-items: center; justify-content: center; }
    @media (min-width: 576px) { .cta-buttons { flex-direction: row; } }

    /* ============================================
       FOOTER
    ============================================ */
    footer {
      padding: 40px 24px; border-top: 1px solid var(--border);
      background: var(--obsidian-2);
    }
    @media (min-width: 768px) { footer { padding: 40px 48px; } }
    .footer-inner { max-width: 1280px; margin: 0 auto; display: flex; flex-direction: column; align-items: center; gap: 24px; }
    @media (min-width: 768px) { .footer-inner { flex-direction: row; justify-content: space-between; } }
    .footer-logo { display: flex; align-items: center; gap: 10px; }
    .footer-disclaimer { font-size: 0.72rem; color: var(--text-muted); line-height: 1.8; text-align: center; }
    .footer-socials { display: flex; align-items: center; gap: 12px; }
    .social-btn {
      width: 36px; height: 36px; border-radius: 10px;
      display: flex; align-items: center; justify-content: center;
      transition: all 0.2s;
    }
    .social-btn.tiktok { background: rgba(201,168,76,0.08); color: rgba(201,168,76,0.6); border: 1px solid var(--border); }
    .social-btn.tiktok:hover { background: rgba(201,168,76,0.15); color: var(--gold); }
    .social-btn.whatsapp { background: rgba(37,211,102,0.08); color: rgba(37,211,102,0.6); border: 1px solid rgba(37,211,102,0.15); }
    .social-btn.whatsapp:hover { background: rgba(37,211,102,0.15); color: rgb(37,211,102); }

    /* ============================================
       WHATSAPP FLOAT
    ============================================ */
    .whatsapp-float {
      position: fixed; bottom: 28px; right: 28px; z-index: 1000;
      display: flex; align-items: center; gap: 10px;
      padding: 12px 20px 12px 16px; border-radius: 9999px;
      background: linear-gradient(135deg, #25d366, #128c7e);
      color: #fff; box-shadow: 0 8px 32px rgba(37,211,102,0.35);
      transition: transform 0.3s cubic-bezier(0.34,1.56,0.64,1);
      font-weight: 600; font-size: 0.875rem;
    }
    .whatsapp-float:hover { transform: scale(1.1) translateY(-3px); }
    .whatsapp-label { display: none; }
    @media (min-width: 576px) { .whatsapp-label { display: inline; } }
    @media (max-width: 768px) { .whatsapp-float { bottom: 20px; right: 20px; } }

    /* ============================================
       SVG ICON HELPERS
    ============================================ */
    svg { flex-shrink: 0; }
  </style>
</head>
<body>

  <!-- ============================================
       NAVBAR — Edit links/brand here
  ============================================ -->
  <nav>
    <div class="nav-logo">
      <span class="nav-logo-text">AMRAX</span>
      <span class="nav-badge">v1.0</span>
    </div>
    <div class="nav-links">
      <a href="#performance">Performance</a>
      <a href="#deployment">Deployment</a>
      <a href="#pricing">Pricing</a>
    </div>
    <a href="https://wa.link/sxp9ss" target="_blank" rel="noopener noreferrer" class="btn-gold nav-cta" style="padding:10px 20px;font-size:0.72rem;">
      Get Access
      <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><line x1="5" y1="12" x2="19" y2="12"/><polyline points="12 5 19 12 12 19"/></svg>
    </a>
    <button class="mobile-menu-btn" onclick="document.getElementById('mobileMenu').classList.toggle('open')" aria-label="Toggle menu">
      <svg id="menuIcon" width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
        <line x1="3" y1="12" x2="21" y2="12"/><line x1="3" y1="6" x2="21" y2="6"/><line x1="3" y1="18" x2="21" y2="18"/>
      </svg>
    </button>
  </nav>

  <!-- Mobile Menu -->
  <div id="mobileMenu" class="mobile-menu">
    <a href="#performance" onclick="document.getElementById('mobileMenu').classList.remove('open')">Performance</a>
    <a href="#deployment" onclick="document.getElementById('mobileMenu').classList.remove('open')">Deployment</a>
    <a href="#pricing" onclick="document.getElementById('mobileMenu').classList.remove('open')">Pricing</a>
    <a href="https://wa.link/sxp9ss" target="_blank" rel="noopener noreferrer" class="btn-gold" onclick="document.getElementById('mobileMenu').classList.remove('open')">
      Get Access
      <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><line x1="5" y1="12" x2="19" y2="12"/><polyline points="12 5 19 12 12 19"/></svg>
    </a>
  </div>

  <!-- ============================================
       HERO SECTION
       Edit: badge text, title, tagline, description, stats, CTA links
  ============================================ -->
  <section id="hero">
    <div class="hero-glow"></div>
    <div class="hero-grid"></div>

    <!-- EDIT: Badge text -->
    <div class="hero-badge reveal">
      <span class="pulse-dot" style="width:6px;height:6px;border-radius:50%;background:var(--profit);display:inline-block;"></span>
      Live Performance · MT5 Expert Advisor
      <span class="pulse-dot" style="width:6px;height:6px;border-radius:50%;background:var(--profit);display:inline-block;"></span>
    </div>

    <!-- EDIT: Main title -->
    <div class="reveal delay-100" style="margin-bottom:24px;">
      <h1 class="hero-title">AMRAX</h1>
      <!-- EDIT: Subtitle below title -->
      <p class="hero-version">version 1.0 · institutional ea</p>
    </div>

    <!-- EDIT: Tagline -->
    <p class="hero-tagline reveal delay-200">
      Engineered for capital preservation. Designed for consistent alpha.
    </p>

    <!-- EDIT: Description -->
    <p class="hero-desc reveal delay-300">
      A fully-automated trading system built for sophisticated investors who demand
      institutional-grade precision without institutional overhead.
    </p>

    <!-- EDIT: Hero stats — change values and labels here -->
    <div class="hero-stats reveal delay-400">
      <div>
        <div class="hero-stat-value">$23,872</div>
        <div class="hero-stat-label">Net Profit</div>
      </div>
      <div>
        <div class="hero-stat-value">73%</div>
        <div class="hero-stat-label">Win Rate</div>
      </div>
      <div>
        <div class="hero-stat-value">1.59</div>
        <div class="hero-stat-label">Profit Factor</div>
      </div>
      <div>
        <div class="hero-stat-value">5.60%</div>
        <div class="hero-stat-label">Max Drawdown</div>
      </div>
    </div>

    <!-- EDIT: CTA button links -->
    <div class="hero-ctas reveal delay-500">
      <a href="https://wa.link/sxp9ss" target="_blank" rel="noopener noreferrer" class="btn-gold" style="padding:16px 32px;border-radius:16px;">
        <svg width="22" height="22" viewBox="0 0 24 24" fill="currentColor"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"/></svg>
        Acquire License
      </a>
      <a href="#performance" class="btn-outline">
        View Performance Data
        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="5" y1="12" x2="19" y2="12"/><polyline points="12 5 19 12 12 19"/></svg>
      </a>
    </div>

    <!-- Scroll hint -->
    <div class="scroll-hint">
      <span>scroll</span>
      <svg width="16" height="24" viewBox="0 0 16 24" fill="none" stroke="rgba(201,168,76,0.5)" stroke-width="1.5">
        <rect x="1" y="1" width="14" height="22" rx="7"/>
        <circle cx="8" cy="7" r="2" fill="rgba(201,168,76,0.5)">
          <animate attributeName="cy" values="7;15;7" dur="2s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="1;0.3;1" dur="2s" repeatCount="indefinite"/>
        </circle>
      </svg>
    </div>
  </section>

  <!-- ============================================
       PERFORMANCE SECTION
       Edit: section title, metric values, insight text
  ============================================ -->
  <section id="performance" class="section-pad">
    <div class="container">
      <div style="text-align:center;margin-bottom:64px;">
        <!-- EDIT: Section label -->
        <p class="section-label reveal">Verified Backtested Metrics</p>
        <!-- EDIT: Section title -->
        <h2 class="section-title reveal delay-100">Performance <span class="text-gold-gradient">Dashboard</span></h2>
        <!-- EDIT: Section description -->
        <p class="section-desc reveal delay-200">Every metric independently verified. No curve-fitting. No overfitted backtests. Raw results from live-condition historical data.</p>
      </div>

      <!-- EDIT: Metric cards — change values, labels, colors (gold/green) -->
      <div class="metrics-grid">

        <div class="metric-card gold-border reveal">
          <div class="metric-card-top">
            <div class="metric-icon green">
              <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"><polyline points="23 6 13.5 15.5 8.5 10.5 1 18"/><polyline points="17 6 23 6 23 12"/></svg>
            </div>
            <div class="pulse-dot" style="width:8px;height:8px;border-radius:50%;background:var(--profit);"></div>
          </div>
          <div>
            <div class="metric-value green">$23,872<span class="metric-suffix" style="color:var(--profit-dim);">.60</span></div>
            <div class="metric-label">Net Profit</div>
          </div>
          <div class="shimmer-line"></div>
        </div>

        <div class="metric-card gold-border reveal delay-100">
          <div class="metric-card-top">
            <div class="metric-icon gold">
              <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"/><circle cx="12" cy="12" r="6"/><circle cx="12" cy="12" r="2"/></svg>
            </div>
            <div class="pulse-dot" style="width:8px;height:8px;border-radius:50%;background:var(--gold);"></div>
          </div>
          <div>
            <div class="metric-value gold">73<span class="metric-suffix" style="color:var(--gold-dim);">%</span></div>
            <div class="metric-label">Win Rate</div>
          </div>
          <div class="shimmer-line"></div>
        </div>

        <div class="metric-card gold-border reveal delay-200">
          <div class="metric-card-top">
            <div class="metric-icon gold">
              <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"><line x1="18" y1="20" x2="18" y2="10"/><line x1="12" y1="20" x2="12" y2="4"/><line x1="6" y1="20" x2="6" y2="14"/></svg>
            </div>
            <div class="pulse-dot" style="width:8px;height:8px;border-radius:50%;background:var(--gold);"></div>
          </div>
          <div>
            <div class="metric-value gold">1.59</div>
            <div class="metric-label">Profit Factor</div>
          </div>
          <div class="shimmer-line"></div>
        </div>

        <div class="metric-card gold-border reveal delay-300">
          <div class="metric-card-top">
            <div class="metric-icon green">
              <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"><polyline points="23 4 23 10 17 10"/><polyline points="1 20 1 14 7 14"/><path d="M3.51 9a9 9 0 0 1 14.85-3.36L23 10M1 14l4.64 4.36A9 9 0 0 0 20.49 15"/></svg>
            </div>
            <div class="pulse-dot" style="width:8px;height:8px;border-radius:50%;background:var(--profit);"></div>
          </div>
          <div>
            <div class="metric-value green">3.63</div>
            <div class="metric-label">Recovery Factor</div>
          </div>
          <div class="shimmer-line"></div>
        </div>

        <div class="metric-card gold-border reveal delay-400">
          <div class="metric-card-top">
            <div class="metric-icon gold">
              <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/></svg>
            </div>
            <div class="pulse-dot" style="width:8px;height:8px;border-radius:50%;background:var(--gold);"></div>
          </div>
          <div>
            <div class="metric-value gold">5.60<span class="metric-suffix" style="color:var(--gold-dim);">%</span></div>
            <div class="metric-label">Max Drawdown</div>
          </div>
          <div class="shimmer-line"></div>
        </div>

        <div class="metric-card gold-border reveal delay-500">
          <div class="metric-card-top">
            <div class="metric-icon gold">
              <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"><polygon points="13 2 3 14 12 14 11 22 21 10 12 10 13 2"/></svg>
            </div>
            <div class="pulse-dot" style="width:8px;height:8px;border-radius:50%;background:var(--gold);"></div>
          </div>
          <div>
            <div class="metric-value gold" style="font-size:1.6rem;">LIVE</div>
            <div class="metric-label">System Status</div>
          </div>
          <div class="shimmer-line"></div>
        </div>

      </div>

      <!-- EDIT: Insight quote -->
      <div class="insight-block gold-border reveal">
        <div class="insight-icon">✦</div>
        <div>
          <p class="insight-eyebrow">Institutional Insight</p>
          <p class="insight-text">
            A <span style="color:var(--gold);">3.63 Recovery Factor</span> demonstrates that AMRAX generates profit
            <strong style="color:var(--gold-light);">3.6× faster</strong> than its maximum drawdown — a hallmark of institutional-grade capital efficiency.
          </p>
        </div>
      </div>

      <!-- Equity curve -->
      <div class="equity-card gold-border reveal">
        <p class="equity-label">Equity Curve · Simulated Growth Trajectory</p>
        <svg viewBox="0 0 800 180" style="width:100%;height:180px;">
          <defs>
            <linearGradient id="equityGrad" x1="0" y1="0" x2="0" y2="1">
              <stop offset="0%" stop-color="rgba(201,168,76,0.3)"/>
              <stop offset="100%" stop-color="rgba(201,168,76,0)"/>
            </linearGradient>
            <linearGradient id="lineGrad" x1="0" y1="0" x2="1" y2="0">
              <stop offset="0%" stop-color="#8a6d2a"/>
              <stop offset="60%" stop-color="#c9a84c"/>
              <stop offset="100%" stop-color="#e8c97a"/>
            </linearGradient>
          </defs>
          <line x1="0" y1="40" x2="800" y2="40" stroke="rgba(201,168,76,0.06)" stroke-width="1"/>
          <line x1="0" y1="80" x2="800" y2="80" stroke="rgba(201,168,76,0.06)" stroke-width="1"/>
          <line x1="0" y1="120" x2="800" y2="120" stroke="rgba(201,168,76,0.06)" stroke-width="1"/>
          <line x1="0" y1="160" x2="800" y2="160" stroke="rgba(201,168,76,0.06)" stroke-width="1"/>
          <path d="M0,160 C50,155 80,148 120,140 C160,132 180,128 220,118 C260,108 280,115 310,105 C340,95 360,90 390,78 C420,66 440,72 470,60 C500,48 520,54 550,40 C580,26 600,32 630,20 C660,8 700,15 730,10 C750,7 770,5 800,2"
            fill="none" stroke="url(#lineGrad)" stroke-width="2.5" stroke-linecap="round"/>
          <path d="M0,160 C50,155 80,148 120,140 C160,132 180,128 220,118 C260,108 280,115 310,105 C340,95 360,90 390,78 C420,66 440,72 470,60 C500,48 520,54 550,40 C580,26 600,32 630,20 C660,8 700,15 730,10 C750,7 770,5 800,2 L800,180 L0,180 Z"
            fill="url(#equityGrad)"/>
          <circle cx="280" cy="115" r="4" fill="rgba(220,80,80,0.7)"/>
          <text x="268" y="132" font-size="8" fill="rgba(220,80,80,0.6)" font-family="DM Mono, monospace">DD 5.6%</text>
          <circle cx="800" cy="2" r="5" fill="#c9a84c"/>
          <text x="720" y="18" font-size="9" fill="#e8c97a" font-family="DM Mono, monospace">$23,872.60</text>
        </svg>
        <div class="equity-footer">
          <span>START</span>
          <div class="line"></div>
          <span>NET +$23,872.60</span>
        </div>
      </div>
    </div>
  </section>

  <div class="divider-gold"></div>

  <!-- ============================================
       DEPLOYMENT SECTION
       Edit: step titles, step content
  ============================================ -->
  <section id="deployment" class="section-pad">
    <div class="container" style="max-width:1000px;">
      <div style="text-align:center;margin-bottom:64px;">
        <p class="section-label reveal">Operational Handbook</p>
        <h2 class="section-title reveal delay-100">Deployment <span class="text-gold-gradient">Protocol</span></h2>
        <p class="section-desc reveal delay-200">From zero to live trading in three structured steps. No technical background required.</p>
      </div>

      <!-- EDIT: Accordion Step 1 -->
      <div class="accordion gold-border open reveal" id="acc1">
        <button class="accordion-btn" onclick="toggleAccordion('acc1')">
          <div class="accordion-step-icon">
            <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"><path d="M18 10h-1.26A8 8 0 1 0 9 20h9a5 5 0 0 0 0-10z"/></svg>
          </div>
          <div>
            <p class="accordion-step-num">Step 01</p>
            <p class="accordion-title">Cloud VPS Setup — Oracle Free Tier</p>
          </div>
          <svg class="accordion-chevron" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="6 9 12 15 18 9"/></svg>
        </button>
        <div class="accordion-body">
          <div class="accordion-content-inner">
            <div class="accordion-divider"></div>
            <p>Deploy AMRAX on a <strong style="color:var(--text-primary);">24/7 cloud server</strong> using Oracle's Always-Free VPS — zero hosting cost, enterprise-grade uptime. This eliminates PC dependency and ensures your EA never misses a trade signal.</p>
            <div class="step-list">
              <div class="step-item"><div class="step-num">1</div><div class="step-text">Register at <span style="color:var(--gold);">cloud.oracle.com</span> — select <strong style="color:var(--text-primary);">Pakistan</strong> as billing territory</div></div>
              <div class="step-item"><div class="step-num">2</div><div class="step-text">Create instance in <strong style="color:var(--text-primary);">UK South (London)</strong> region — optimal latency to Exness servers</div></div>
              <div class="step-item"><div class="step-num">3</div><div class="step-text">Select Windows Server image — minimum 2 vCPU / 4GB RAM</div></div>
              <div class="step-item"><div class="step-num">4</div><div class="step-text">Note your public IP and RDP credentials from Oracle console</div></div>
            </div>
            <div class="tip-box">✦ London region provides sub-10ms latency to major Exness execution nodes — critical for order accuracy.</div>
          </div>
        </div>
      </div>

      <!-- EDIT: Accordion Step 2 -->
      <div class="accordion gold-border reveal delay-100" id="acc2">
        <button class="accordion-btn" onclick="toggleAccordion('acc2')">
          <div class="accordion-step-icon">
            <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"><rect x="2" y="3" width="20" height="14" rx="2" ry="2"/><line x1="8" y1="21" x2="16" y2="21"/><line x1="12" y1="17" x2="12" y2="21"/></svg>
          </div>
          <div>
            <p class="accordion-step-num">Step 02</p>
            <p class="accordion-title">MetaTrader 5 Installation via RDP</p>
          </div>
          <svg class="accordion-chevron" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="6 9 12 15 18 9"/></svg>
        </button>
        <div class="accordion-body">
          <div class="accordion-content-inner">
            <div class="accordion-divider"></div>
            <p>Connect to your VPS via Remote Desktop Protocol and install the <strong style="color:var(--text-primary);">Exness MT5 Terminal</strong> — the designated broker for AMRAX's calibrated execution parameters.</p>
            <div class="step-list">
              <div class="step-item"><div class="step-num">1</div><div class="step-text">Open Remote Desktop Connection (Windows key → type "mstsc")</div></div>
              <div class="step-item"><div class="step-num">2</div><div class="step-text">Enter your Oracle VPS IP address and login credentials</div></div>
              <div class="step-item"><div class="step-num">3</div><div class="step-text">Inside VPS: download MT5 from exness.com/trading/platforms</div></div>
              <div class="step-item"><div class="step-num">4</div><div class="step-text">Install and launch — log in with your Exness live account</div></div>
              <div class="step-item"><div class="step-num">5</div><div class="step-text">Confirm server connection: green status bar in the bottom-right</div></div>
            </div>
          </div>
        </div>
      </div>

      <!-- EDIT: Accordion Step 3 -->
      <div class="accordion gold-border reveal delay-200" id="acc3">
        <button class="accordion-btn" onclick="toggleAccordion('acc3')">
          <div class="accordion-step-icon">
            <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"><polygon points="13 2 3 14 12 14 11 22 21 10 12 10 13 2"/></svg>
          </div>
          <div>
            <p class="accordion-step-num">Step 03</p>
            <p class="accordion-title">EA Activation & Smiley Face Confirmation</p>
          </div>
          <svg class="accordion-chevron" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="6 9 12 15 18 9"/></svg>
        </button>
        <div class="accordion-body">
          <div class="accordion-content-inner">
            <div class="accordion-divider"></div>
            <p>Install the AMRAX EA file and configure MT5 to grant algorithmic trading permissions. The <strong style="color:var(--gold);">"Smiley Face"</strong> icon confirms your EA is live and trading autonomously.</p>
            <div class="step-list">
              <div class="step-item"><div class="step-num">1</div><div class="step-text">Place AMRAX.ex5 file in: MetaTrader 5 → MQL5 → Experts folder</div></div>
              <div class="step-item"><div class="step-num">2</div><div class="step-text">In MT5: Tools → Options → Expert Advisors → Enable Algorithmic Trading</div></div>
              <div class="step-item"><div class="step-num">3</div><div class="step-text">Drag AMRAX from Navigator panel onto your chart (XAUUSD or configured pair)</div></div>
              <div class="step-item"><div class="step-num">4</div><div class="step-text">In EA properties: confirm "Allow Algo Trading" is checked → OK</div></div>
              <div class="step-item"><div class="step-num">5</div><div class="step-text">Verify the Smiley Face (😊) appears on the chart — EA is active and running</div></div>
            </div>
            <div class="tip-box gold-tip">
              <span style="font-size:18px;">✦</span>
              The smiley face icon is your final confirmation. Frowning face = algo trading disabled. Confirm before stepping away from the terminal.
            </div>
          </div>
        </div>
      </div>

      <!-- EDIT: Video link -->
      <div style="max-width:900px;margin:64px auto 0;">
        <div class="video-card gold-border">
          <div class="video-scanlines"></div>
          <div class="video-inner">
            <a href="https://www.tiktok.com/@ahmadkaamrax" target="_blank" rel="noopener noreferrer" style="display:flex;flex-direction:column;align-items:center;gap:20px;z-index:1;">
              <div class="play-btn">
                <svg width="28" height="28" viewBox="0 0 24 24" fill="currentColor"><polygon points="5 3 19 12 5 21 5 3"/></svg>
              </div>
              <div>
                <p class="video-title">Watch The Complete Deployment Video</p>
                <p class="video-sub">TikTok · Ahmad Ka AMRAX</p>
              </div>
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <div class="divider-gold"></div>

  <!-- ============================================
       PRICING SECTION
       Edit: tier names, prices, descriptions, features, links
  ============================================ -->
  <section id="pricing" class="section-pad">
    <div class="container">
      <div style="text-align:center;margin-bottom:64px;">
        <p class="section-label reveal">License Acquisition</p>
        <h2 class="section-title reveal delay-100">Select Your <span class="text-gold-gradient">Access Tier</span></h2>
        <p class="section-desc reveal delay-200">One-time license fee. Lifetime access. No subscriptions, no hidden costs. Contact via WhatsApp for immediate activation.</p>
      </div>

      <div class="pricing-grid">

        <!-- EDIT: Standard plan -->
        <div class="pricing-card gold-border reveal delay-100">
          <p class="pricing-tier">Standard License</p>
          <p class="pricing-price">$99 <span class="pricing-price-usd">USD</span></p>
          <p class="pricing-desc">Entry point for individual traders testing AMRAX on a single account.</p>
          <div class="pricing-accounts">
            <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="11" width="18" height="11" rx="2" ry="2"/><path d="M7 11V7a5 5 0 0 1 10 0v4"/></svg>
            1 MT5 Account Lock
          </div>
          <ul class="pricing-features">
            <li><span class="check"><svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg></span>Full AMRAX v1.0 EA file</li>
            <li><span class="check"><svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg></span>1 MT5 account activation</li>
            <li><span class="check"><svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg></span>Deployment support via WhatsApp</li>
            <li><span class="check"><svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg></span>Default parameter set</li>
            <li><span class="check"><svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg></span>Lifetime access, no subscription</li>
          </ul>
          <!-- EDIT: Link -->
          <a href="https://wa.link/wzbt23" target="_blank" rel="noopener noreferrer" class="pricing-cta cta-outline">
            <svg width="22" height="22" viewBox="0 0 24 24" fill="currentColor"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"/></svg>
            Acquire License
            <svg width="13" height="13" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/><polyline points="15 3 21 3 21 9"/><line x1="10" y1="14" x2="21" y2="3"/></svg>
          </a>
        </div>

        <!-- EDIT: Professional plan (featured) -->
        <div class="pricing-card gold-border featured reveal delay-200">
          <div class="featured-top-line"></div>
          <div class="featured-badge">Most Popular</div>
          <p class="pricing-tier">Professional Bundle</p>
          <p class="pricing-price featured-price">$249 <span class="pricing-price-usd">USD</span></p>
          <p class="pricing-desc">The institutional trader's choice — scale across three independent accounts.</p>
          <div class="pricing-accounts">
            <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="11" width="18" height="11" rx="2" ry="2"/><path d="M7 11V7a5 5 0 0 1 10 0v4"/></svg>
            3 MT5 Account Locks
          </div>
          <ul class="pricing-features">
            <li><span class="check"><svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg></span>Full AMRAX v1.0 EA file</li>
            <li><span class="check"><svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg></span>3 MT5 account activations</li>
            <li><span class="check"><svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg></span>Priority WhatsApp support</li>
            <li><span class="check"><svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg></span>Advanced parameter guidance</li>
            <li><span class="check"><svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg></span>Lifetime access, no subscription</li>
            <li><span class="check"><svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg></span>Multi-account strategy consultation</li>
          </ul>
          <!-- EDIT: Link -->
          <a href="https://wa.link/sxp9ss" target="_blank" rel="noopener noreferrer" class="pricing-cta cta-gold">
            <svg width="22" height="22" viewBox="0 0 24 24" fill="currentColor"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"/></svg>
            Acquire License
            <svg width="13" height="13" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/><polyline points="15 3 21 3 21 9"/><line x1="10" y1="14" x2="21" y2="3"/></svg>
          </a>
        </div>

        <!-- EDIT: Institutional plan -->
        <div class="pricing-card gold-border reveal delay-300">
          <p class="pricing-tier">Institutional Access</p>
          <p class="pricing-price">$999 <span class="pricing-price-usd">USD</span></p>
          <p class="pricing-desc">Built for fund managers, prop firms, and multi-account operations.</p>
          <div class="pricing-accounts">
            <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="11" width="18" height="11" rx="2" ry="2"/><path d="M7 11V7a5 5 0 0 1 10 0v4"/></svg>
            Unlimited Account Locks
          </div>
          <ul class="pricing-features">
            <li><span class="check"><svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg></span>Full AMRAX v1.0 EA file</li>
            <li><span class="check"><svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg></span>Unlimited MT5 activations</li>
            <li><span class="check"><svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg></span>VIP WhatsApp direct line</li>
            <li><span class="check"><svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg></span>Custom parameter calibration</li>
            <li><span class="check"><svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg></span>Lifetime access, no subscription</li>
            <li><span class="check"><svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg></span>Dedicated institutional onboarding</li>
            <li><span class="check"><svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg></span>Priority feature updates</li>
          </ul>
          <!-- EDIT: Link -->
          <a href="https://wa.link/r98nem" target="_blank" rel="noopener noreferrer" class="pricing-cta cta-outline">
            <svg width="22" height="22" viewBox="0 0 24 24" fill="currentColor"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"/></svg>
            Acquire License
            <svg width="13" height="13" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/><polyline points="15 3 21 3 21 9"/><line x1="10" y1="14" x2="21" y2="3"/></svg>
          </a>
        </div>

      </div>

      <!-- Trust badges -->
      <div class="trust-grid reveal">
        <div class="trust-item">
          <div class="trust-icon"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/></svg></div>
          <div class="trust-label">Verified Metrics</div>
          <div class="trust-sub">Backtested & documented</div>
        </div>
        <div class="trust-item">
          <div class="trust-icon"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"><polyline points="23 6 13.5 15.5 8.5 10.5 1 18"/><polyline points="17 6 23 6 23 12"/></svg></div>
          <div class="trust-label">Consistent Alpha</div>
          <div class="trust-sub">73% win rate sustained</div>
        </div>
        <div class="trust-item">
          <div class="trust-icon"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"><polyline points="23 4 23 10 17 10"/><polyline points="1 20 1 14 7 14"/><path d="M3.51 9a9 9 0 0 1 14.85-3.36L23 10M1 14l4.64 4.36A9 9 0 0 0 20.49 15"/></svg></div>
          <div class="trust-label">Rapid Recovery</div>
          <div class="trust-sub">3.63 recovery factor</div>
        </div>
        <div class="trust-item">
          <div class="trust-icon"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"/><circle cx="12" cy="12" r="6"/><circle cx="12" cy="12" r="2"/></svg></div>
          <div class="trust-label">Low Drawdown</div>
          <div class="trust-sub">5.60% max drawdown</div>
        </div>
      </div>
    </div>
  </section>

  <!-- ============================================
       TESTIMONIALS
       Edit: names, roles, testimonial text
  ============================================ -->
  <section id="testimonials">
    <p class="section-label" style="text-align:center;margin-bottom:40px;">What Traders Are Saying</p>
    <div class="testimonials-grid">

      <!-- EDIT: Testimonial 1 -->
      <div class="testimonial-card gold-border reveal delay-100">
        <div class="stars">
          <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
          <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
          <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
          <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
          <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
        </div>
        <p class="testimonial-text">"The 3.63 recovery factor alone justified the investment. AMRAX bounced back from its max drawdown in days, not weeks."</p>
        <div class="testimonial-author">
          <div class="author-avatar">K</div>
          <div>
            <p class="author-name">Khalid M.</p>
            <p class="author-role">Proprietary Trader, Dubai</p>
          </div>
        </div>
      </div>

      <!-- EDIT: Testimonial 2 -->
      <div class="testimonial-card gold-border reveal delay-200">
        <div class="stars">
          <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
          <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
          <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
          <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
          <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
        </div>
        <p class="testimonial-text">"I run it on three accounts with the Professional Bundle. Consistent, disciplined, and predictable — exactly what institutional capital requires."</p>
        <div class="testimonial-author">
          <div class="author-avatar">U</div>
          <div>
            <p class="author-name">Usman R.</p>
            <p class="author-role">Fund Manager, Karachi</p>
          </div>
        </div>
      </div>

      <!-- EDIT: Testimonial 3 -->
      <div class="testimonial-card gold-border reveal delay-300">
        <div class="stars">
          <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
          <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
          <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
          <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
          <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
        </div>
        <p class="testimonial-text">"I was skeptical at first. After seeing the 73% win rate hold across 6 months, I upgraded to the institutional tier."</p>
        <div class="testimonial-author">
          <div class="author-avatar">F</div>
          <div>
            <p class="author-name">Fahad A.</p>
            <p class="author-role">Retail Investor, Lahore</p>
          </div>
        </div>
      </div>

    </div>
  </section>

  <!-- ============================================
       FINAL CTA SECTION
       Edit: headline, description, button links
  ============================================ -->
  <section id="cta">
    <div class="cta-glow"></div>
    <p class="section-label reveal" style="margin-bottom:24px;">Ready to Deploy</p>
    <h2 class="cta-title reveal delay-100">
      Your Edge Starts <span class="text-gold-gradient">Today</span>
    </h2>
    <p class="cta-desc reveal delay-200">
      Join a select group of traders running institutional-grade automation on every timeframe, every session, every opportunity.
    </p>
    <div class="cta-buttons reveal delay-300">
      <!-- EDIT: CTA WhatsApp link -->
      <a href="https://wa.link/sxp9ss" target="_blank" rel="noopener noreferrer" class="btn-gold" style="padding:20px 40px;border-radius:16px;font-size:0.8rem;">
        <svg width="22" height="22" viewBox="0 0 24 24" fill="currentColor"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"/></svg>
        Acquire License Now
      </a>
      <!-- EDIT: TikTok link -->
      <a href="https://www.tiktok.com/@ahmadkaamrax" target="_blank" rel="noopener noreferrer" class="btn-outline" style="padding:20px 40px;">
        <svg width="18" height="18" viewBox="0 0 24 24" fill="currentColor"><path d="M19.59 6.69a4.83 4.83 0 01-3.77-4.25V2h-3.45v13.67a2.89 2.89 0 01-2.88 2.5 2.89 2.89 0 01-2.89-2.89 2.89 2.89 0 012.89-2.89c.28 0 .54.04.79.1V9.01a6.33 6.33 0 00-.79-.05 6.34 6.34 0 00-6.34 6.34 6.34 6.34 0 006.34 6.34 6.34 6.34 0 006.33-6.34V8.67a8.18 8.18 0 004.78 1.52V6.72a4.85 4.85 0 01-1.01-.03z"/></svg>
        TikTok: Ahmad Ka AMRAX
        <svg width="13" height="13" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/><polyline points="15 3 21 3 21 9"/><line x1="10" y1="14" x2="21" y2="3"/></svg>
      </a>
    </div>
  </section>

  <!-- ============================================
       FOOTER
       Edit: disclaimer text, social links
  ============================================ -->
  <footer>
    <div class="footer-inner">
      <div class="footer-logo">
        <span class="nav-logo-text">AMRAX</span>
        <span class="nav-badge">v1.0</span>
      </div>
      <!-- EDIT: Disclaimer -->
      <p class="footer-disclaimer">
        Trading involves substantial risk of loss. Past performance is not indicative of future results.<br>
        AMRAX is a software tool, not financial advice. Trade at your own discretion.
      </p>
      <div class="footer-socials">
        <!-- EDIT: TikTok link -->
        <a href="https://www.tiktok.com/@ahmadkaamrax" target="_blank" rel="noopener noreferrer" class="social-btn tiktok" title="TikTok">
          <svg width="15" height="15" viewBox="0 0 24 24" fill="currentColor"><path d="M19.59 6.69a4.83 4.83 0 01-3.77-4.25V2h-3.45v13.67a2.89 2.89 0 01-2.88 2.5 2.89 2.89 0 01-2.89-2.89 2.89 2.89 0 012.89-2.89c.28 0 .54.04.79.1V9.01a6.33 6.33 0 00-.79-.05 6.34 6.34 0 00-6.34 6.34 6.34 6.34 0 006.34 6.34 6.34 6.34 0 006.33-6.34V8.67a8.18 8.18 0 004.78 1.52V6.72a4.85 4.85 0 01-1.01-.03z"/></svg>
        </a>
        <!-- EDIT: WhatsApp number -->
        <a href="https://wa.me/923179897517" target="_blank" rel="noopener noreferrer" class="social-btn whatsapp" title="WhatsApp">
          <svg width="15" height="15" viewBox="0 0 24 24" fill="currentColor"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/></svg>
        </a>
      </div>
    </div>
  </footer>

  <!-- ============================================
       WHATSAPP FLOATING BUTTON
       Edit: WhatsApp number link
  ============================================ -->
  <a href="https://wa.me/923179897517" target="_blank" rel="noopener noreferrer" class="whatsapp-float">
    <svg width="22" height="22" viewBox="0 0 24 24" fill="white"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/></svg>
    <span class="whatsapp-label">Chat on WhatsApp</span>
  </a>

  <!-- ============================================
       JAVASCRIPT — Scroll reveal + Accordion
  ============================================ -->
  <script>
    // Scroll reveal
    const revealEls = document.querySelectorAll('.reveal');
    const observer = new IntersectionObserver((entries) => {
      entries.forEach(e => { if (e.isIntersecting) e.target.classList.add('visible'); });
    }, { threshold: 0.1, rootMargin: '0px 0px -40px 0px' });
    revealEls.forEach(el => observer.observe(el));

    // Accordion toggle
    function toggleAccordion(id) {
      const el = document.getElementById(id);
      el.classList.toggle('open');
    }

    // Scrollbar style
    document.documentElement.style.setProperty('--scrollbar-thumb', '#8a6d2a');
  </script>
  <style>
    ::-webkit-scrollbar { width: 6px; }
    ::-webkit-scrollbar-track { background: var(--obsidian-2); }
    ::-webkit-scrollbar-thumb { background: var(--gold-dim); border-radius: 3px; }
    ::-webkit-scrollbar-thumb:hover { background: var(--gold); }
  </style>
</body>
</html>
