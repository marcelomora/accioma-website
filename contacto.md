---
title: Contacto
subtitle: Hablemos sobre cómo podemos ayudarte a digitalizar tu empresa.
layout: page
hero_height: is-medium
show_sidebar: false
---

## Estamos en Quito, Ecuador

Atendemos empresas en todo el país de manera remota y en Quito de manera presencial.

**Email:** [marcelo.mora@accioma.com](mailto:marcelo.mora@accioma.com)

**WhatsApp:** [Escríbenos ahora](https://wa.me/593000000000){:target="_blank" .button .is-success}

---

## Cuéntanos tu proyecto

Completa el formulario y te contactamos en menos de 24 horas hábiles.

<div class="notification is-success is-light" data-fs-success style="display:none;">
  ¡Gracias! Hemos recibido tu mensaje y te contactaremos pronto.
</div>
<div class="notification is-danger is-light" data-fs-error style="display:none;">
  Ups, hubo un error. Por favor intenta de nuevo o escríbenos por WhatsApp.
</div>

<form id="contact-form" style="max-width:600px">
  <input type="text" name="_gotcha" style="display:none" />
  <div class="field">
    <label class="label">Nombre</label>
    <div class="control">
      <input class="input" type="text" name="nombre" placeholder="Tu nombre completo" required data-fs-field>
    </div>
    <p class="help is-danger" data-fs-error="nombre"></p>
  </div>
  <div class="field">
    <label class="label">Empresa</label>
    <div class="control">
      <input class="input" type="text" name="empresa" placeholder="Nombre de tu empresa" data-fs-field>
    </div>
    <p class="help is-danger" data-fs-error="empresa"></p>
  </div>
  <div class="field">
    <label class="label">Email</label>
    <div class="control">
      <input class="input" type="email" name="email" placeholder="tu@empresa.com" required data-fs-field>
    </div>
    <p class="help is-danger" data-fs-error="email"></p>
  </div>
  <div class="field">
    <label class="label">Servicio de interés</label>
    <div class="control">
      <div class="select is-fullwidth">
        <select name="servicio" data-fs-field>
          <option value="">Selecciona un servicio</option>
          <option value="odoo">Implementación Odoo ERP</option>
          <option value="software">Desarrollo de software a medida</option>
          <option value="sri">Facturación Electrónica SRI</option>
          <option value="otro">Otro</option>
        </select>
      </div>
    </div>
    <p class="help is-danger" data-fs-error="servicio"></p>
  </div>
  <div class="field">
    <label class="label">Mensaje</label>
    <div class="control">
      <textarea class="textarea" name="mensaje" placeholder="Cuéntanos brevemente qué necesitas..." rows="4" data-fs-field></textarea>
    </div>
    <p class="help is-danger" data-fs-error="mensaje"></p>
  </div>
  <div class="field">
    <div class="control">
      <button type="submit" class="button is-primary" data-fs-submit-btn>Enviar mensaje</button>
    </div>
  </div>
</form>

<script>
  window.formspree = window.formspree || function () { (formspree.q = formspree.q || []).push(arguments); };
  formspree('initForm', { 
    formElement: '#contact-form', 
    formId: 'mwvylpwy',
    onSuccess: function() {
      document.getElementById('contact-form').style.display = 'none';
    }
  });
</script>
<script src="https://unpkg.com/@formspree/ajax@1" defer></script>
