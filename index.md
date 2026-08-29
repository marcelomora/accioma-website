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
        <a href="{{ '/servicios/axyrion/' | relative_url }}" class="button is-outlined is-medium">Controlar mi operación con Axyrion →</a>
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
      <h2 class="pillar__title">Negocio Visible</h2>
      <ul class="pillar__list">
        <li>Google Maps y Perfil de Negocio</li>
        <li>Sistema de reseñas (NFC/QR)</li>
        <li>WhatsApp y Landing Page</li>
      </ul>
      <a href="{{ '/servicios/presencia-digital/' | relative_url }}" class="pillar__cta">Descubrir Presencia Digital →</a>
    </article>
    <article class="pillar">
      <p class="pillar__number">02</p>
      <h2 class="pillar__title">Negocio Conectado</h2>
      <ul class="pillar__list">
        <li>Automatización de procesos (CRM/ERP)</li>
        <li>WhatsApp automatizado 24/7</li>
        <li>Agentes de IA para ventas y soporte</li>
      </ul>
      <a href="{{ '/servicios/automatizacion-ia/' | relative_url }}" class="pillar__cta">Explorar Automatización e IA →</a>
    </article>
    <article class="pillar">
      <p class="pillar__number">03</p>
      <h2 class="pillar__title">Negocio Controlado</h2>
      <ul class="pillar__list">
        <li>Axyrion para pymes y tiendas</li>
        <li>Control de ventas, inventario y operaciones</li>
        <li>Desarrollo y aplicaciones a medida</li>
      </ul>
      <a href="{{ '/servicios/axyrion/' | relative_url }}" class="pillar__cta">Conocer Axyrion para empresas →</a>
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
