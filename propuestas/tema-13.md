---
layout: default
title: 13. SocioUnido
nav_order: 14
---

# SocioUnido: Plataforma Inteligente de Gestión y Fidelización para Clubes de Fútbol

## 🎯 Necesidad u oportunidad detectada

Los clubes de fútbol en Argentina sufren tres grandes pérdidas económicas que muchas veces pasan desapercibidas:

- La rotación de socios (abandono o morosidad).
- La evasión en los accesos los días de partido (Préstamo de carnets o capturas de pantalla de códigos QR estáticos).
- Desaprovechamiento de los espacios de uso alquilables por los socios.

Además, las dirigencias y áreas administrativas destinan una cantidad desproporcionada de horas-hombre en tareas repetitivas, como responder consultas, gestionar cobros manuales o administrar el alta de nuevos hinchas.

## 💡 Solución planteada

Desarrollo de una plataforma SaaS (Software as a Service) B2B que centraliza la gestión administrativa del club de fútbol (Abonos, cuotas sociales, accesos al estadio, espacios compartidos) y la potencia con herramientas de fidelización activa y seguridad perimetral.

**Estrategia del producto:**

1. **Prevención y Fidelización:** Pasar de un modelo reactivo (Dar de baja al socio que no paga) a un modelo proactivo, detectando patrones de ausentismo o falta de pago para incentivar la retención antes de que el usuario abandone la institución.
2. **Seguridad y Autogestión:** Optimizar el control en molinetes los días de partido mediante tecnología dinámica offline y automatizar la atención al socio mediante canales conversacionales.
2. **Optimización de espacios:** Refinar el sistema mediante al que se alquilan espacios, o brindan servicios a los usuarios.

## 👥 Clientes objetivos

* **Clubes de Fútbol Argentino:** Instituciones deportivas de diversas categorías que manejan un alto volumen de socios e hinchas, y sufren cuellos de botella en la atención presencial y en el control de accesos al estadio.
* **Usuarios Decisores (Decision Makers):** Presidentes, Comisiones Directivas, Tesoreros o Gerentes Generales del club, cuya motivación principal es maximizar la recaudación, evitar la fuga de capitales por accesos indebidos y modernizar la imagen de la institución hacia el hincha.

## 📱 Medios de uso

* **Plataforma Web (Dashboard B2B):** Panel de control para la administración del club (Finanzas, métricas de retención, estado de la masa societaria).
* **App Móvil / PWA del Socio:** Billetera digital del hincha donde reside su carnet digital dinámico, estado de cuenta, cartelera de beneficios y alquiler de espacios/servicios.
* **Integración WhatsApp:** Canal de atención automatizado 24/7 para consultas de los hinchas.
* **Integración con sistemas existentes:** APIs diseñadas para conectar la validación de tokens directamente con los molinetes de acceso físico del estadio.

## 🤖 Uso de IA y Alta Ingeniería

* **Motor Predictivo de Morosidad (Machine Learning):** Un algoritmo que analiza la frecuencia de asistencia a la cancha y el historial de pagos para detectar socios en "riesgo de fuga". Dispara automáticamente promociones o recordatorios amistosos para re-engancharlos.
* **Asistente Transaccional (NLP / RAG):** Un bot de WhatsApp integrado a la base de datos que entiende lenguaje natural. Permite al socio enviar un audio preguntando "Quiero pagar la cuota de este mes" y el bot le genera el link de pago automáticamente.
* **Smart Access:** Sistema de control de accesos mediante códigos QR dinámicos (Tokens TOTP) que se regeneran cada 15 segundos y funcionan de manera offline. Crucial para estadios donde la conectividad a internet colapsa los días de partido.

## Análisis de las 5Cs

### 1. Compañía

* **Descripción:** Startup de tecnología deportiva que ofrece un ecosistema integral de gestión para clubes de fútbol, combinando administración eficiente, prevención de morosidad y control de socios.
* **Visión:** Ser el sistema operativo estándar para los clubes de fútbol en Argentina, transformando la relación entre el club y el hincha mediante innovación tecnológica.
* **Misión:** Proveer a las comisiones directivas una herramienta inteligente que optimice la administración, blinde los accesos al estadio y fidelice a los hinchas, brindando nuevas vías de monetización.

### 2. Colaboradores

1. **Empresas de Hardware de Control de Acceso:** Para integrar nuestra solución con molinetes y sistemas de validación física en los estadios.
2. **Agencias de Marketing y Sponsors:** Marcas que busquen pautar o generar activaciones directas con la masa societaria a través de la app del club.
3. **AFA y Ligas Regionales:** Entidades rectoras que pueden facilitar la adopción tecnológica en sus torneos.

### 3. Clientes

1. **Segmento B2B Principal:** Clubes de fútbol del ascenso y ligas metropolitanas que buscan profesionalizar su gestión, optimizar su rentabilidad controlando mejor los ingresos de los días de partido y reduciendo la morosidad.
2. **Segmento B2B Expansión:** Clubes de primera división (Liga Profesional y Primera Nacional) con necesidades de alta concurrencia y gestión masiva de socios.

### 4. Competidores

1. **El "Status Quo" (Competencia Directa):** La administración basada en papel, planillas de Excel y carnets físicos de plástico que se prestan o falsifican fácilmente.
2. **Sistemas de Gestión de Clubes Legacy:** Herramientas tradicionales que resuelven gestiones básicas, pero carecen de arquitecturas para alta concurrencia (días de partido), IA predictiva, entre otros features.
3. **Sistemas Informales y Dinámicas Internas:** Entendemos que los clubes de fútbol son instituciones políticas con funcionamientos complejos. Nuestro enfoque no es imponer una "transparencia disruptiva" que entorpezca los asuntos internos o perjudique a la institución. Por el contrario, nos posicionamos como una herramienta operativa orientada a dotar a la dirigencia de mejores mecanismos para **monetizar y controlar el funcionamiento general**, adaptándonos a la realidad de cada club sin forzar fricciones políticas.

### 5. Contexto

| Categoría | Corto Plazo (1-2 años) | Mediano Plazo (3-5 años) | Largo Plazo (+5 años) |
| :--- | :---: | :---: | :---: |
| **Económico** | 🟡 | 🟢 | 🟢 |
| **Regulatorio** | 🟢 | 🟢 | 🟢 |
| **Social / Cultural** | 🟡 | 🟢 | 🟢 |
| **Tecnológico** | 🟢 | 🟢 | 🟢 |
| **Político / Institucional** | 🟡 | 🟡 | 🟢 |

> **Justificación del análisis de contexto:**
> * **Económico:** La recuperación económica Post-pandemia y el aumento del interés en actividades deportivas generan un clima favorable para la adopción de soluciones que optimicen la gestión de clubes. Sin embargo, la inflación y los costos operativos pueden ser un desafío para algunos clubes, lo que hace que la propuesta de valor de SocioUnido (reducción de pérdidas por fraude y abandono) sea aún más relevante.
> * **Político / Institucional:** Existe un fuerte arraigo a las formas tradicionales de gestión. Sin embargo, al presentar la herramienta como un potenciador de ingresos y una mejora en la imagen de gestión de la directiva (Sin inmiscuirse en auditorías externas), se reduce la barrera de adopción institucional.

## Análisis de las 4Ps

### Producto

SocioUnido es una plataforma SaaS B2B modular diseñada exclusivamente para la realidad del fútbol argentino. Es un ecosistema compuesto por cuatro pilares:

* **Dashboard Administrativo (Web):** Centro de comando para la comisión directiva y gerencia, con métricas de recaudación, morosidad, accesos y gestión de espacios/servicios brindados.
* **Aplicación del Hincha/Socio (PWA/Mobile):** Interfaz para el usuario final. Contiene su carnet digital (QR), pagos de cuota social, compra de abonos, plataforma de alquiler de espacios/servicios y acceso a noticias o tienda del club.
* **Canal Conversacional:** Bot de WhatsApp con NLP para consultas de los hinchas y gestión de pagos automatizada.
* **Módulo de Alta Concurrencia (Estadios):** Generación de Tokens TOTP (QR dinámico offline) capaz de validar miles de accesos por minuto sin depender de la red WiFi/4G del estadio (Implementación futura, no considerada en un primer MVP).

### Plaza

Al ser un producto Cloud-based, la distribución del software es inmediata. La implementación física ocurre únicamente durante el *onboarding* al conectar el software con los molinetes del estadio.

Para definir nuestra estrategia de penetración, analizamos la estructura del fútbol argentino:

| Nivel | Categoría | Cantidad de Clubes |
| :--- | :--- | :--- |
| **1°** | **Liga Profesional** | **30** |
| **2°** | **Primera Nacional** | **36** |
| **3°** | **Primera B Metropolitana** | **22** |
| **3°** | **Torneo Federal A** | **37** |
| **4°** | **Primera C** | **28** |
| **4°** | **Torneo Regional Federal Amateur** | **~330** |
| **5°** | **Torneo Promocional Amateur** | **17** |

#### Estrategia de Penetración de Mercado (Go-To-Market):

Nuestra fase inicial de comercialización **no** apuntará a los equipos de élite. Nos enfocaremos estratégicamente en los clubes que se encuentran entre la **Primera B Metropolitana** y la **Primera C**. 

* **Justificación de Fase 1:** La magnitud y estructura organizacional de estos clubes nos permite acceder directamente a los tomadores de decisión (Presidentes o Tesoreros) de manera mucho más ágil, esquivando la densa burocracia y los contratos exclusivos preexistentes de los equipos de Primera División. Es un nicho con necesidades tecnológicas urgentes y presupuestos que justifican la inversión.
* **Visión a Largo Plazo (Fase 2):** Una vez consolidado el producto en el ascenso metropolitano, utilizaremos los casos de éxito, las métricas de mejora en la recaudación y las buenas reseñas operativas para escalar progresivamente hacia la **Primera Nacional** y, finalmente, la **Liga Profesional**. 

### Precio

#### Fórmulas de precio y Proyección de Ingresos

La estrategia de monetización de SocioUnido se basa en un "Pricing basado en el Valor" estructurado en tres componentes, como refleja nuestra proyección de ingresos:

$$Ingresos = \\ (Setup\_Fee \cdot q_{new\_clu.}) + \sum_{k} (SaaS\_Subs._k \cdot q_{act\_clu.\_k}) + (Mark.\_CPA \cdot q_{trans.})$$

1. **Setup Fee (Pago Único):** Cobro inicial por la configuración de la cuenta, migración de la base de datos del padrón de socios y la integración técnica con los molinetes del estadio.
2. **Suscripción Mensual SaaS B2B:** Tarifa escalonada basada en el volumen de socios activos del club. El costo se justifica ante la dirigencia, ya que se "paga solo" con el recupero de cuotas atrasadas y la eliminación de colados en la cancha.
3. **Marketplace CPA (Módulo Opcional de Monetización Conjunta):** SocioUnido habilita la app del hincha como un canal publicitario segmentado para sponsors o marcas deportivas. **Este servicio es opcional y negociable con cada club**. Si el club decide activarlo, SocioUnido cobra un porcentaje (CPA/Revenue Share) sobre el total de la pauta publicitaria generada, a cambio de encargarse de la gestión técnica, integración y el formateo correcto de las campañas dentro de la app.

#### Estimación de Precios

La referencia incluye sistemas de gestión de clubes como *TeamSnap* o soluciones locales como *SocioPlus*. Se prioriza el "Setup Fee" para cubrir costos de integración inicial y una suscripción mensual que escale con el club.

* **Precio moderado propuesto:**
  * **Setup Fee (Pago único):** \$4000 USD/mes (Cubre migración e integración).
  * **Suscripción Mensual (Avg.):** $200 USD (Para clubes de la B y C con ~2000-5000 socios).
  * **Marketplace CPA:** 5% de la pauta gestionada (Opcional).
* **Estimación de ingresos (Año 1):**
  Enfocándose en la Fase 1 (Entre Primera B y C = 87 clubes), con una penetración del ~12% (10 clubes):
  * **Setup Fees (10 clubes):** $20.000 USD (Se estima un tiempo de 2 semanas de integración promedio por club).
  * **Suscripciones Mensuales (10 clubes):** $2.000 USD/mes.
  * **Flujo proyectado (Año 1 total):** **$44.000 USD anuales** (Sin contar Marketplace CPA, que podría añadir un 10-15% adicional según el volumen de sponsors).

### Promoción

Dado que el cliente es B2B e institucional, la captación se centra en ventas corporativas y relaciones públicas:

* **Venta Consultiva (Outbound B2B):** Contacto directo con dirigentes de la Primera B y C, ofreciendo una "Auditoría de Recaudación".
* **Calculadoras de ROI:** Herramientas interactivas donde el tesorero del club pueda ingresar su cantidad de socios y el valor de la cuota, y el sistema le calcule de forma tangible cuánto dinero adicional ingresaría mensualmente al aplicar la tecnología de retención y QR dinámico.
* **Networking Estratégico:** Asistencia a reuniones de comité, asambleas de representantes y alianzas con consultoras de *Sports Management* que actúen como puente de confianza entre la dirigencia del club y nuestra tecnología.
