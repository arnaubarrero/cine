# 🎟️ Sistema de Reservas de Butacas por Película en Tiempo Real

Esta aplicación permite a los usuarios **seleccionar una película** y **reservar butacas asociadas a esa función**, todo en tiempo real. El sistema está compuesto por un frontend en **Next.js** y un backend en **Laravel**, con comunicación en tiempo real mediante **WebSockets** para sincronizar las reservas entre múltiples usuarios.

---

## 📦 Tecnologías Utilizadas

### 🔹 Frontend (Next.js)
- React (App Router o Pages Router)
- TailwindCSS para estilos
- Axios para peticiones HTTP
- Socket.io-client para comunicación en tiempo real

### 🔹 Backend (Laravel)
- Laravel 10+
- Laravel Echo + Pusher o Laravel WebSockets
- Broadcasting de eventos
- Base de datos relacional (MySQL o PostgreSQL)

---

## ⚙️ Funcionalidades Principales

- 🎬 **Selección de película** y función.
- 🗺️ **Visualización dinámica** del mapa de butacas para la película seleccionada.
- 🟢 **Reserva y liberación** de butacas en tiempo real.
- 🔄 **Sincronización instantánea** entre usuarios mediante sockets.
- 🧾 Registro de reservas por película, usuario y horario.
- 🔐 (Opcional) Autenticación de usuarios.

---

## 🚀 Instalación

### 1. Clonar el repositorio

```bash
git clone https://github.com/arnaubarrero/cine.git