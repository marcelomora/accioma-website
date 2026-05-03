# Project: Accioma Website Refinement
**Role:** Senior UI/UX Designer & B2B Conversion Expert
**Context:** accioma.com is a digital transformation agency in Quito, Ecuador, specializing in Odoo ERP, custom Python development, and professional training.

---

## 1. Visual Identity & Design System
Refine the current Bulma-based theme to transition from a "template" look to a premium consultancy aesthetic.

### Typography
- **Primary Headings:** Use **Inter** or **Montserrat** (Bold/Extra-Bold) for a modern, trustworthy feel.
- **Body Text:** Use **Inter** (Regular) at 16px-18px for high readability.
- **Technical Accents:** Use **JetBrains Mono** for code snippets, version numbers, or "Developer-First" labels to highlight Python/Postgres expertise.

### Color Palette
- **Primary (Trust):** Deep Navy (`#1A202C`)
- **Action (Energy):** Electric Indigo (`#4F46E5`)
- **Secondary (Clean):** Slate Gray (`#64748B`)
- **Background:** Pure White (`#FFFFFF`) with subtle Light Gray (`#F8FAFC`) section breaks.

### UI Style
- **Glassmorphism:** Use semi-transparent white backgrounds with subtle blurs for navigation and cards.
- **Borders:** Soft rounded corners (`border-radius: 12px`) for a friendly yet professional tech feel.
- **Whitespace:** Increase padding between sections by 20% to reduce visual clutter.

---

## 2. Information Architecture (Sitemap)
Consolidate the current "Example Pages" and "Docs" into a high-conversion business structure.

* **Home:** Hero -> 3 Solution Pillars -> Process -> Local Trust -> CTA.
* **Services:**
    * Odoo Implementation (Accounting, Inventory, CRM).
    * Software Factory (Python, n8n, Custom API).
    * Ecuador Compliance (Electronic Invoicing/SRI).
* **Blog:** Focus on "Odoo in Ecuador" and "Automation for SMEs."
* **Contact:** Direct form + WhatsApp integration for the local market.

---

## 3. Messaging & Copywriting Strategy
The tone must be **Expert, Local, and Solution-Oriented.**

* **Main Value Prop:** "Digitalizamos tu empresa en Ecuador. Expertos en Odoo y desarrollo a medida para automatizar tu crecimiento."
* **Key Differentiator:** Mention deep knowledge of local regulations (Facturación Electrónica) and technical proficiency (Python/Postgres).

---

## 4. Content Pivot (Blog)
Archive old "Bulma Theme" technical posts. Replace with:
1. "Guía de Facturación Electrónica en Odoo para empresas en Quito."
2. "Cómo migrar de Excel a un ERP sin morir en el intento."
3. "Casos de uso: Automatización de flujos con n8n y Odoo."

---

## 5. Technical Constraints for AI
- **Framework:** Bulma CSS (Jekyll static site).
- **Hosting:** GitHub Pages.
- **Dev Environment:** Local Docker-compose (Ruby 3.2) on port 4001.
- **Target Audience:** Business owners in Ecuador and CTOs looking for reliable Odoo partners.

---

**Instruction to AI Agent:** *Analyze the current `_sass/` and `_layouts/` in the linked repository. Provide the specific CSS overrides and Liquid template changes required to implement this vision.*
