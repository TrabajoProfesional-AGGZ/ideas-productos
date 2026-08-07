---
layout: default
title: 12. MarketScout
nav_order: 13
---

# MarketScout: Comparador y optimizador de compras en supermercados

## 🎯 Necesidad u oportunidad detectada

Con la dispersión de precios y la constante variación de promociones bancarias, el consumidor pierde la referencia de dónde es más barato comprar.

Hacer la compra del mes requiere entrar a múltiples portales web de distintos supermercados para comparar, una tarea que demanda demasiado tiempo y esfuerzo.

## 💡 Solución planteada

Un motor de búsqueda y comparación de precios que unifica los catálogos de los principales supermercados. El usuario arma un único "carrito virtual" y la plataforma calcula instantáneamente en qué cadena de supermercados conviene realizar la compra total, o si es mejor dividirla.

Permite filtrar por tipo de producto, proximidad geográfica y envía notificaciones en tiempo real sobre promociones y descuentos.

## 👥 Clientes objetivos

* **Familias y compradores mensuales:** Consumidores que realizan compras de gran volumen y donde la diferencia de precios o la aplicación de descuentos bancarios impacta fuertemente en el bolsillo.
* **Buscadores de ofertas (Smart Shoppers):** Usuarios hiper-sensibles al precio que basan sus decisiones de consumo puramente en oportunidades y promociones vigentes.

## 📱 Medios de uso

* **Extensión de navegador / web app:** Ideal para realizar el armado del carrito grande sentado en la computadora, integrándose directamente con los checkouts de los supermercados.
* **App móvil:** Para recibir notificaciones push geolocalizadas ("Estás cerca de la sucursal X y hoy hay 30% en tu carrito guardado") y comparar precios escaneando códigos de barras en la góndola.

## 🤖 Uso de IA

* **Scraping y normalización de datos:** Uso de IA para extraer, limpiar y estandarizar los nombres de los productos de diferentes cadenas (ej. entender que "Coca Cola 1.5L" en el súper A es lo mismo que "Gaseosa Cola 1500ml marca Coca" en el súper B).
* **Motor de alertas inteligentes:** Algoritmo que aprende la frecuencia de consumo del usuario (ej. compra pañales cada 15 días) y dispara notificaciones de descuentos justo en el momento en que se predice que el usuario necesita reponer stock.
