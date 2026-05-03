---
layout: post
title: "Guía de Facturación Electrónica en Odoo para empresas en Quito"
subtitle: "Todo lo que necesitas saber para emitir comprobantes electrónicos válidos ante el SRI desde Odoo."
date: 2024-01-15
categories: [odoo, ecuador, sri]
image: /img/mountain-hero.jpg
author: Accioma
show_sidebar: false
---

La **Facturación Electrónica** es obligatoria en Ecuador para la gran mayoría de contribuyentes. Implementarla correctamente en Odoo requiere conocer los requisitos del SRI y configurar el módulo de contabilidad de manera adecuada.

## ¿Qué exige el SRI?

El Servicio de Rentas Internas (SRI) requiere que los comprobantes electrónicos:

- Sean firmados con un certificado digital válido.
- Se envíen en formato XML siguiendo el esquema oficial.
- Reciban autorización vía webservice antes de entregarse al receptor.

## Odoo y la Facturación Electrónica

Odoo, con la localización ecuatoriana, cubre todos estos requisitos. El módulo genera el XML, lo firma con tu certificado `.p12` y consulta el webservice del SRI automáticamente al validar una factura.

### Pasos clave de configuración

1. **Instala la localización de Ecuador** (`l10n_ec`).
2. **Carga tu certificado digital** en `Contabilidad > Configuración > Empresa`.
3. **Configura los diarios** de venta y compra con el tipo de comprobante correcto.
4. **Activa el entorno de pruebas** del SRI antes de ir a producción.

```python
# Ejemplo: verificar estado de un comprobante
from odoo import api, models

class AccountMove(models.Model):
    _inherit = 'account.move'

    def check_sri_state(self):
        for move in self:
            # lógica de consulta al webservice SRI
            pass
```

## Conclusión

Con Odoo y la configuración correcta, la Facturación Electrónica se convierte en un proceso transparente. Si necesitas ayuda para implementarlo en tu empresa en Quito o en cualquier ciudad del Ecuador, [contáctanos](/contacto/).
