---
title: Facturación Electrónica SRI
subtitle: Cumplimiento total con la normativa del Servicio de Rentas Internas.
layout: page
hero_height: is-medium
show_sidebar: false
---

## Comprobantes electrónicos que emitimos

- Facturas de venta
- Notas de crédito y débito
- Retenciones en la fuente e IVA
- Guías de remisión
- Liquidaciones de compra

## Cómo funciona en Axyrion

Axyrion —nuestra implementación de Odoo Community con localización ecuatoriana (`l10n_ec`)— se comunica directamente con el webservice del SRI para:

1. Generar el XML firmado con tu certificado digital.
2. Enviar el comprobante al SRI y obtener la autorización.
3. Almacenar el RIDE (representación impresa) para envío al cliente.

Todo esto ocurre automáticamente al validar un documento en Axyrion — sin intervención manual.

## Requisitos

- Certificado digital vigente (Banco Central, Security Data, ANF Ecuador, etc.)
- RUC activo y en estado "activo" en el SRI
- Una instancia de Axyrion (Odoo 16 o superior, recomendado 17)

[Consultar disponibilidad](/contacto/){:.button.is-primary}
