---
layout: post
title: "Casos de uso: Automatización de flujos con n8n y Odoo"
subtitle: "Cómo conectar Odoo con tus otras herramientas (WhatsApp, correo, Google Sheets) usando n8n para eliminar el trabajo manual."
date: 2024-03-10
categories: [automatizacion, n8n, odoo, python]
image: /img/mountain-hero.jpg
author: Accioma
show_sidebar: false
---

`n8n` es una herramienta de automatización de flujos de trabajo open-source que se integra perfectamente con Odoo a través de su API REST. Juntos, permiten eliminar las tareas manuales repetitivas que consumen horas de trabajo cada semana.

## Caso 1: Notificación de pedido por WhatsApp

Cuando un cliente hace un pedido en Odoo, n8n captura el evento vía webhook y envía un mensaje automático de confirmación por WhatsApp Business API.

**Flujo:**
```
Odoo Webhook (Sale Order Confirmed)
  → n8n: Extraer datos del pedido
  → WhatsApp Business API: Enviar mensaje al cliente
  → Odoo: Actualizar campo "Notificación enviada"
```

## Caso 2: Sincronización de stock con Google Sheets

Para equipos comerciales que trabajan en campo, un Google Sheet actualizado en tiempo real con el stock de Odoo es un diferenciador clave.

**Flujo:**
```
n8n Schedule (cada hora)
  → Odoo API: GET /api/stock.quant
  → Google Sheets: Actualizar hoja "Stock Actual"
```

## Caso 3: Pipeline de leads desde formulario web

Un formulario en el sitio web crea automáticamente un lead en el CRM de Odoo, asigna un vendedor según la zona geográfica y envía un correo de bienvenida.

```python
# n8n Code Node — asignar vendedor por zona
const zonas = {
  "Quito": 5,       # ID del vendedor en Odoo
  "Guayaquil": 8,
  "Cuenca": 12,
};

const ciudad = $input.item.json.ciudad;
const vendedor_id = zonas[ciudad] || 1;  # default: admin

return [{ json: { vendedor_id, ...($input.item.json) } }];
```

## ¿Vale la pena?

La automatización con n8n + Odoo típicamente **amortiza su costo en menos de 3 meses** para empresas con más de 5 empleados administrativos. El ROI es claro: menos errores, más velocidad, equipo enfocado en tareas de valor.

¿Tienes un proceso manual que quieres automatizar? [Cuéntanos.](/contacto/)
