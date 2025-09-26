# Informe Digitalización (Procesos, Software e IoT) — Proyecto: Empresa de Muñecos de Crochet
---
**INSTITUCIÓN:** Servicio Nacional de Aprendizaje – SENA / Centro de Biotecnología  
**PROGRAMA:** Análisis y Desarrollo de Software  
**APRENDIZ:** Laura Fonseca, Juan Jose Bocanegra, Karen gonzalez
**INSTRUCTOR:** Esteban Hernandez  
**FICHA:** 3203082  
---

## 1. Contexto

La empresa se dedica al diseño, producción artesanal y venta de muñecos tejidos en crochet. Sus procesos principales tienen la adquisición de materias primas que son hilos, relleno y accesorios, la producción artesanal, la gestión de pedidos, la comercialización y la logística de distribución.

## 2. Inventario de Procesos 

* **Ventas y marketing digital**: Tienda online, redes sociales, pasarelas de pago.
* **Gestión de inventario y materias primas**: Control de stock, alertas de reabastecimiento.
* **Producción artesanal**: Planificación de pedidos, seguimiento de avance, digitalización de patrones.
* **Atención al cliente y CRM**: Registro de clientes, automatización de respuestas, fidelización.
* **Logística y envíos**: Generación de guías, integración con transportadoras, seguimiento de pedidos.
* **Contabilidad y facturación**: Facturación electrónica, reportes fiscales.

## 3. Análisis por Proceso

### 3.1 Ventas y marketing digital

**Rol:** Exponer catálogo y concretar ventas.

**Digitalización:** Implementar tienda online (Shopify/WooCommerce) integrada con redes sociales y pasarelas de pago.

**Software propuesto:** Shopify (Liquid) o WooCommerce (WordPress + PHP). Framework alterno: Next.js (React) para frontend moderno.

**IoT/Hardware:** No requerido.

**Justificación técnica:** SaaS como Shopify ofrecen escalabilidad y rapidez, mientras WooCommerce brinda control total en entornos económicos.

---
### 3.2 Gestión de inventario y materias primas

*Rol:* Controlar stock de insumos y productos terminados.

*Digitalización:* ERP modular (Odoo, Zoho Inventory) con alertas automáticas.

*Software propuesto:* Odoo ERP (Python, PostgreSQL).

*IoT/Hardware:* Sensores de peso (celda de carga + ESP32) en estantes de hilos para automatizar inventario.

*Justificación técnica:* Integración directa con el ERP permite mantener inventario actualizado y reducir quiebres de stock.

---

### 3.3 Producción artesanal

*Rol:* Organización del flujo de pedidos y asignación a artesanos.

*Digitalización:* Uso de tableros digitales (Trello, Notion) y módulo de producción en ERP.

*Software propuesto:* Odoo (módulo de fabricación) o Notion/Trello para planificación.

*IoT/Hardware:* No requerido.

*Justificación técnica:* Herramientas visuales de gestión reducen tiempos muertos y permiten trazabilidad.

---

### 3.4 Atención al cliente y CRM

*Rol:* Comunicación y fidelización de clientes.

*Digitalización:* WhatsApp Business + CRM (HubSpot, Zoho CRM).

*Software propuesto:* HubSpot CRM (SaaS, integraciones nativas) + ManyChat (chatbot).

*IoT/Hardware:* No requerido.

*Justificación técnica:* CRM permite segmentar y automatizar campañas, mejorando retención.

---

