---
layout: default
title: 5. SkyDictate
nav_order: 6
---

# SkyDictate: Supervisor Inteligente de Separación Aérea

## 🎯 Necesidad u oportunidad detectada

Los errores humanos en la comunicación entre la torre de control (ATC) y los pilotos son una de las causas principales de incidentes de proximidad. El incumplimiento de la separación mínima de 1000 pies a menudo ocurre por instrucciones mal dadas o mal interpretadas bajo situaciones de estrés o alta densidad de tráfico.

## 💡 Solución planteada

Desarrollo de un sistema de auditoría en tiempo real que "escucha" y procesa las frecuencias de radio aeronáuticas. 

SkyDictate digitaliza las instrucciones dadas por los controladores y las contrasta instantáneamente con un modelo de simulación de las posiciones actuales y las regulaciones vigentes. Si una instrucción rompe un protocolo de seguridad, el sistema emite una alerta preventiva antes de que el piloto ejecute la maniobra.

## 👥 Clientes objetivos

* **Proveedores de Servicios de Navegación Aérea (ANSP):** Para equipar torres de control con herramientas de soporte a la decisión.
* **Fabricantes de Aviones:** Para integrar sistemas de validación de voz en la aviónica de cabina.

## 📱 Medios de uso

* **Sistema Embebido en Torre:** Interfaz que transcribe y valida la voz del controlador.
* **Aviónica de Cabina:** Alertas visuales en el PFD (Primary Flight Display) sobre conflictos de altura próximos.

## 🤖 Uso de IA

* **Speech-to-Text (NLP) Especializado:** Modelado de lenguaje entrenado en fraseología aeronáutica estándar para entender instrucciones complejas.
* **Motor de Reglas Predictivo:** Análisis de escenarios para verificar que las nuevas coordenadas/alturas no generen conflictos con el tráfico circundante.
