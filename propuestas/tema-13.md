---
layout: default
title: 13. SocioUnido
nav_order: 14
---

# SocioUnido: Plataforma Inteligente de Gestión y Fidelización Deportiva

## 🎯 Necesidad u oportunidad detectada

Los clubes, gimnasios y centros deportivos sufren dos grandes pérdidas económicas invisibles: la rotación de socios (abandono) y el fraude en los accesos (préstamo de carnets o capturas de pantalla de códigos QR estáticos). Además, destinan una cantidad desproporcionada de horas-hombre en tareas administrativas repetitivas, como responder consultas de horarios o gestionar reservas de canchas por teléfono.

## 💡 Solución planteada

Desarrollo de una plataforma SaaS (Software as a Service) B2B que centraliza la gestión administrativa del club (abonos, cuotas, actividades) y la potencia con herramientas de fidelización activa y seguridad perimetral.

**Estrategia del producto:**
1. **Prevención y Fidelización:** Pasar de un modelo reactivo (dar de baja al socio que no paga) a un modelo proactivo, detectando patrones de ausentismo para incentivar el regreso antes de que el usuario abandone la institución.
2. **Seguridad y Autogestión:** Eliminar el fraude en molinetes y automatizar la atención al socio mediante canales conversacionales.

## 👥 Clientes objetivos

* **Clubes Medianos y Grandes / Megagimnasios:** Instituciones deportivas que manejan un alto volumen de socios y sufren cuellos de botella en la atención presencial y en el control de accesos.
* **Usuarios Decisores (Decision Makers):** Gerentes Generales, Tesoreros o Directores de Operaciones del club, cuya motivación principal es maximizar la recaudación, evitar la fuga de socios y modernizar la imagen de la institución.

## 📱 Medios de uso

* **Plataforma Web (Dashboard B2B):** Panel de control para la administración del club (finanzas, métricas de retención, gestión de actividades).
* **App Móvil / PWA del Socio:** Billetera digital del usuario donde reside su credencial dinámica, estado de cuenta y cartelera de eventos.
* **Integración WhatsApp:** Canal de atención automatizado 24/7.
* **Integración de Hardware:** APIs diseñadas para conectar la validación de tokens directamente con los molinetes de acceso físico.

## 🤖 Uso de IA y Alta Ingeniería

* **Motor Predictivo de Abandono (Machine Learning):** Un algoritmo que analiza la frecuencia de asistencia y el historial de pagos para detectar socios en "riesgo de fuga". Dispara automáticamente promociones o beneficios para re-engancharlos antes de que dejen de pagar.
* **Asistente Transaccional (NLP / RAG):** Un bot de WhatsApp integrado a la base de datos que entiende lenguaje natural. Permite al socio enviar un audio preguntando "¿Hay cancha de tenis libre hoy a las 20hs?" y el bot responde, reserva y descuenta el saldo automáticamente.
* **Smart Access (Criptografía):** Sistema Anti-Fraude mediante códigos QR dinámicos (Tokens TOTP) que se regeneran cada 15 segundos y funcionan de manera offline, procesados por un *backend* preparado para ráfagas de alta concurrencia (ej. días de partido).

## Análisis de las 5Cs

### 1. Compañía

* **Descripción:** Startup de tecnología deportiva (SportTech) que ofrece una plataforma integral de gestión y fidelización para clubes y centros deportivos, combinando administración eficiente, prevención de abandono y seguridad avanzada mediante inteligencia artificial y arquitecturas de alta concurrencia. Nuestra solución no solo optimiza la operación interna del club, sino que también transforma la experiencia del socio, fomentando una relación más cercana y personalizada con su institución deportiva. Con un enfoque en la innovación tecnológica aplicada al deporte, buscamos ser el aliado estratégico de los clubes en su camino hacia la modernización y la excelencia operativa.
* **Visión:** Ser el sistema operativo estándar para clubes y centros deportivos en Latinoamérica, erradicando el fraude y transformando la retención de socios mediante datos.
* **Misión:** Proveer a los gestores deportivos una herramienta inteligente que automatice la administración, blinde los accesos y fidelice a los usuarios mediante inteligencia artificial.

### 2. Colaboradores

1. **Proveedores de Infraestructura Cloud:** AWS, Google Cloud o Azure para garantizar escalabilidad, seguridad y alta disponibilidad.
2. **Empresas de Hardware de Control de Acceso:** Para integrar nuestra solución con molinetes y sistemas de validación física.
3. **Agencias de Marketing Deportivo:** Para la creación de campañas de fidelización y promociones personalizadas.
4. **Asociaciones Deportivas y Federaciones:** Para la promoción y adopción de la plataforma entre sus miembros y afiliados.

### 3. Clientes

1. **Segmento B2B Principal:** Clubes de barrio grandes, clubes que compiten en ligas de ascenso o regionales, y cadenas de gimnasios que buscan optimizar su rentabilidad eliminando el fraude en la puerta y reduciendo la morosidad.
2. **Organizadores de Eventos Deportivos:** Clientes secundarios que requieran validación de entradas dinámicas masivas con alta tolerancia a fallos de red.

### 4. Competidores

1. **El "Status Quo" (Competencia Directa):** La administración basada en papel, planillas de Excel desactualizadas y carnets físicos de plástico fácilmente falsificables.
2. **Sistemas de Gestión de Clubes Legacy:** Herramientas locales tradicionales (como SocioPlus o TurnosWeb) que resuelven la parte contable básica (facturación y alta de socios), pero que carecen de arquitecturas de alta concurrencia, motores predictivos de IA o QRs criptográficos dinámicos.

### 5. Contexto

| Categoría | Corto Plazo (1-2 años) | Mediano Plazo (3-5 años) | Largo Plazo (+5 años) |
| :--- | :---: | :---: | :---: |
| **Económico** | 🟡 | 🟢 | 🟢 |
| **Regulatorio** | 🟢 | 🟢 | 🟢 |
| **Social / Cultural** | 🟡 | 🟢 | 🟢 |
| **Tecnológico** | 🟡 | 🟢 | 🟢 |
| **Político / Ambiental** | 🟢 | 🟢 | 🟢 |

> **Guía de colores**
> * 🟢 **Verde:** Bueno / Favorable.
> * 🟡 **Amarillo:** Intermedio / Neutral.
> * 🔴 **Rojo:** Malo / Riesgoso.

## Análisis de las 4Ps

### Producto

SocioUnido es una plataforma SaaS B2B modular orientada a la gestión y fidelización de entidades deportivas. No es un simple CRM, sino un ecosistema compuesto por cuatro pilares:

* **Dashboard Administrativo (Web):** Centro de comando para la gerencia, con métricas financieras y operativas en tiempo real.
* **Aplicación del Socio (PWA/Mobile):** Interfaz de autogestión para el usuario final, con credencial digital y acceso a beneficios. También podrá adquerir servicios adicionales (clases, alquiler de canchas) directamente desde la app.
* **Módulo de Inteligencia y Seguridad:** Generación de Tokens TOTP (QR dinámico anti-fraude) y motor predictivo de abandono (Machine Learning).
* **Canal Conversacional:** Integración de un bot de WhatsApp con NLP para atención automatizada y transaccional.  

### Plaza

Al ser un producto digital (Cloud-based), la distribución principal carece de barreras físicas. 

* **Despliegue de Software:** Se comercializa mediante acceso web (navegadores) para la administración, y a través de tiendas de aplicaciones (Google Play / App Store) o PWA para los socios.
* **Implementación Física (On-site):** La única instancia "física" de la plaza es la etapa de *onboarding* técnico, donde nuestro equipo (o *partners* integradores) conecta las APIs del sistema con el hardware preexistente del club (molinetes, lectoras ópticas y barreras de estacionamiento).

<p align="center">
  <img src="../assets/images/formula-ingresos_t13.png" alt="Fórmula de Proyección de Ingresos">
</p>

* **Expansión del Ecosistema y Marketplace Deportivo (Canal B2B2C)**: Más allá de la provisión del software administrativo al club, la "Plaza" se expande al transformar la aplicación móvil del socio en un canal de distribución dirigido y altamente segmentado. A través de alianzas comerciales con marcas de indumentaria, tiendas de suplementación, sponsors del club o clínicas de medicina deportiva, la plataforma actúa como un puente transaccional. Estos actores de terceros pueden desplegar campañas de beneficios dinámicos (Por ejemplo, habilitar automáticamente un 20% de descuento en botines o indumentaria deportiva presentando la credencial digital en días de partido). Esta estrategia convierte a la app en un punto de encuentro entre una demanda cautiva y perfilada (Los miembros del club) y la oferta del retail deportivo, fidelizando al usuario final con beneficios tangibles y abriendo la puerta a esquemas de monetización indirecta (Modelos de CPA o revenue share) sin costo adicional para la institución.

### Precio

La estrategia de monetización se basa en el "Pricing basado en el Valor" y consta de dos componentes:

* **Setup Fee (Pago Único):** Cobro inicial por la configuración de la cuenta, migración de la base de datos de socios anterior y la integración de las APIs con los molinetes del club.
* **Suscripción Mensual (SaaS B2B):** Modelo escalonado basado en el volumen de socios activos. A medida que el club crece, el plan se ajusta.
**Justificación estratégica:** El precio se presenta a los directivos no como un gasto, sino como una inversión con ROI inmediato. El costo mensual de la plataforma se paga solo al tapar la fuga de capital que genera el fraude en la puerta (QR estático) y al retener socios mediante la IA predictiva antes de que dejen de pagar.

### Promoción

Al apuntar a *Decision Makers* (Gerentes y Presidentes de clubes), la estrategia de captación se aleja del marketing masivo B2C y se enfoca en ventas corporativas:

* **Venta Consultiva (Outbound B2B):** Contacto directo y perfilado a través de LinkedIn y correo electrónico con gerentes deportivos, ofreciendo una "Auditoría de Pérdidas por Fraude".
* **Marketing de Demostración:** Ofrecer calculadoras de ROI en la página web donde un gerente pueda ingresar sus datos (ej. "Tengo 5.000 socios") y el sistema le calcule cuánta plata está perdiendo por mes debido a tecnología obsoleta.
* **Presencia en Nichos Estratégicos:** Participación y sponsoreo en congresos de *Sports Management* y alianzas con federaciones deportivas regionales para que actúen como recomendadores oficiales del sistema ante sus clubes afiliados.