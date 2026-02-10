# 💰 Sistema de Caja con Bot de Telegram

Proyecto backend en **Java + Spring Boot** que permite gestionar una caja diaria mediante un **bot de Telegram**.  
Desde el bot se pueden registrar ingresos y gastos, consultar balances y obtener promedios de recaudación.

La idea del proyecto es simular un sistema real de caja para un local/negocio, usando solo backend y mensajería.

---

## 🚀 Tecnologías utilizadas

- Java 17  
- Spring Boot  
- Spring Data JPA / Hibernate  
- MySQL  
- Telegram Bots API  
- Maven  

---

## 🤖 Funcionalidades

Actualmente el sistema permite:

- Registrar **ingresos** desde Telegram  
- Registrar **gastos** desde Telegram  
- Asignar proveedor automáticamente  
- Manejar fechas que no sean solo el día actual  
- Consultar caja del día  
- Resumen semanal  
- Resumen mensual  
- Balance mensual  
- Promedio diario de recaudación  

---

## 📌 Comandos del Bot

Ejemplos de uso:

```text
/ingreso 7000 cliente venta mostrador hoy
/gasto 3000 proveedor mercaderia ayer

/hoy
/semana
/mes

## Formato general
/ingreso monto proveedor [detalle] [fecha]
/gasto monto proveedor [detalle] [fecha]

/balance
/deshacer
