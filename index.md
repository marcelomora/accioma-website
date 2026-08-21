---
title: No solo digitalizamos tu empresa
subtitle: Te acompañamos hasta que tu operación funcione sola
layout: home
show_sidebar: false
---

<section class="home-hero">
  <div class="home-hero__field" aria-hidden="true">
    {% for n in (1..32) %}<span class="home-hero__node"></span>{% endfor %}
  </div>
  <div class="container home-hero__grid home-hero__grid--single">
    <div class="home-hero__copy">
      <h1 class="home-hero__title">{{ page.title }}</h1>
      <p class="home-hero__subtitle">{{ page.subtitle }}</p>
      <div class="home-hero__actions">
        <a href="{{ '/servicios/presencia-digital/' | relative_url }}" class="button is-primary is-medium">Optimizar mi presencia digital →</a>
        <a href="{{ '/servicios/axyrion/' | relative_url }}" class="button is-outlined is-medium">Explorar Axyrion →</a>
      </div>
    </div>
    <!--
      Illustrative status panel — disabled 2026-08-20: even labeled "ejemplo
      ilustrativo", a mock business/status/sync panel risked reading as real
      live data to leads. Re-enable only with real data, or keep it explicit
      and unmistakably a mockup if reinstated.
    <div class="home-hero__panel">
      <div class="home-hero__panel-header">
        <span class="label-mono">Ejemplo ilustrativo</span>
      </div>
      <div class="home-hero__panel-body">
        <div class="home-hero__panel-row">
          <span class="home-hero__panel-key">Negocio</span>
          <span class="home-hero__panel-val">Tu empresa en Quito</span>
        </div>
        <div class="home-hero__panel-row">
          <span class="home-hero__panel-key">Estado</span>
          <span class="home-hero__panel-badge">EN OPTIMIZACIÓN</span>
        </div>
        <div class="home-hero__panel-row">
          <span class="home-hero__panel-key">Sincronización</span>
          <span class="home-hero__panel-val">Maps · WhatsApp · Axyrion</span>
        </div>
      </div>
    </div>
    -->
  </div>
</section>

<section class="pillar-grid-section">
  <div class="pillar-grid">
    <article class="pillar">
      <p class="pillar__number">01</p>
      <h2 class="pillar__title">Presencia Digital</h2>
      <ul class="pillar__list">
        <li>Optimización de Google Maps y Perfil de Negocio</li>
        <li>Tarjetas NFC de reseña automática</li>
        <li>Sitios de enlace (bio-link)</li>
      </ul>
      <a href="{{ '/servicios/presencia-digital/' | relative_url }}" class="pillar__cta">Auditar mi presencia en Google Maps →</a>
    </article>
    <article class="pillar">
      <p class="pillar__number">02</p>
      <h2 class="pillar__title">Operaciones</h2>
      <ul class="pillar__list">
        <li>Axyrion — Odoo Community con localización ecuatoriana</li>
        <li>CRM y pipeline de ventas</li>
        <li>Facturación Electrónica SRI</li>
      </ul>
      <a href="{{ '/servicios/axyrion/' | relative_url }}" class="pillar__cta">Configurar mi instancia de Axyrion →</a>
    </article>
    <article class="pillar">
      <p class="pillar__number">03</p>
      <h2 class="pillar__title">Automatización &amp; IA</h2>
      <ul class="pillar__list">
        <li>Integraciones con n8n</li>
        <li>APIs a medida en Python</li>
        <li>Agentes de IA aplicados</li>
      </ul>
      <a href="{{ '/servicios/automatizacion-ia/' | relative_url }}" class="pillar__cta">Automatizar mi flujo de trabajo →</a>
    </article>
  </div>
</section>

<section class="proof-strip-section">
  <div class="proof-strip">
    <div class="proof-strip__item">
      <p class="proof-strip__value">2x</p>
      <p class="proof-strip__label">Confianza del Consumidor</p>
    </div>
    <div class="proof-strip__item">
      <p class="proof-strip__value">+20</p>
      <p class="proof-strip__label">Empresas implementadas</p>
    </div>
    <div class="proof-strip__item">
      <p class="proof-strip__value"><span class="label-mono">Python</span> <span class="label-mono">PostgreSQL</span></p>
      <p class="proof-strip__label">Stack técnico</p>
    </div>
  </div>
</section>

<section class="home-context">
  <div class="container">
    <div class="home-context__grid">
      <h2>¿Por qué Accioma?</h2>
      <p>Somos una consultora técnica con sede en Quito, Ecuador. Entendemos los procesos locales, <strong>las necesidades de las pymes ecuatorianas</strong> y los retos de crecer con tecnología. No vendemos licencias: construimos soluciones que funcionan.</p>
    </div>
  </div>
</section>
