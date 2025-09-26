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
### 3.5 Logística y envíos

*Rol:* Gestionar despachos y seguimiento de pedidos.

*Digitalización:* Integración con APIs de transportadoras (ShipStation, Envíame).

*Software propuesto:* Middleware en Node.js (Express/NestJS) o Python (FastAPI) para conectar tienda y transportadoras.

*IoT/Hardware:* Etiquetas QR para trazabilidad en almacén.

*Justificación técnica:* Integraciones API automatizan procesos, reducen errores y aumentan confianza del cliente.

---

### 3.6 Contabilidad y facturación

*Rol:* Cumplir normatividad y generar reportes.

*Digitalización:* Facturación electrónica y contabilidad automatizada.

*Software propuesto:* Alegra (SaaS, facturación electrónica en LATAM) o QuickBooks.

*IoT/Hardware:* No requerido.

*Justificación técnica:* SaaS contables locales cumplen legislación y simplifican reportes.

---

## 4. Justificación técnica global

Las herramientas elegidas combinan *SaaS escalables* (Shopify, HubSpot, Alegra) con *ERP modular open-source* (Odoo), lo que ofrece:

* *Escalabilidad:* Crece con la empresa sin reestructurar sistemas.
* *Costo-eficiencia:* Inicia con SaaS básicos y evoluciona hacia integraciones avanzadas.
* *Integraciones seguras:* APIs estandarizadas y middleware en Node.js/Python.
* *Protección de la producción artesanal:* IoT en inventario y ambiente cuida materias primas críticas.

En conclusión, la digitalización con este stack potencia la *eficiencia operativa, la trazabilidad y la experiencia del cliente*, manteniendo la esencia artesanal del crochet.


