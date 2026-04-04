---
layout: default
title: 2. AutoCare Preventivo
nav_order: 2
---

# AutoCare: Ecosistema de Mantenimiento Automotriz Preventivo

## 🎯 Necesidad u oportunidad detectada

El mantenimiento de los vehículos particulares suele ser puramente reactivo. Los conductores pierden el rastro del historial de repuestos y acuden al taller solo cuando ocurre una rotura grave, lo cual resulta mucho más costoso y peligroso. 

## 💡 Solución planteada

Una WebApp que centraliza el mantenimiento del vehículo. Al ingresar el modelo y el kilometraje actual, el sistema cruza la información con los manuales del fabricante para generar un calendario de mantenimiento preventivo. Además, permite digitalizar el historial completo del auto subiendo fotos de las facturas del taller.

## 👥 Clientes objetivos

* **Talleres Mecánicos y Concesionarias:** Como herramienta B2B (SaaS) para fidelizar a sus clientes mediante recordatorios automáticos ("Es hora de cambiar la correa").
* **Propietarios de Vehículos Particulares:** Usuarios finales que buscan cuidar la vida útil y el valor de reventa de su auto.

## 📱 Medios de uso

* **Aplicación Web / PWA:** Interfaz orientada al conductor para ver alertas, semáforos de estado del auto y subir facturas.
* **Panel Administrativo B2B:** Dashboard para que el taller mecánico gestione su cartera de clientes y envíe avisos.

## 🤖 Uso de IA

* **Reconocimiento Óptico de Caracteres (OCR):** Para procesar fotos de facturas físicas y extraer automáticamente qué repuestos se cambiaron, la fecha y el costo, tabulándolo en la base de datos sin carga manual.
* **Modelos Predictivos (Machine Learning):** Algoritmos que estiman la probabilidad de fallo de una pieza específica cruzando la telemetría del usuario con los promedios de desgaste de ese modelo de auto.