# ¡Hola, somos Rumbita! 👋

<div align="center">
  <img src="https://img.shields.io/badge/Status-En%20Desarrollo-orange?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Infrastructure-DigitalOcean-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Backend-Fastify%20%2F%20Node.js-green?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Mobile-Capacitor%20%2F%20Ionic-purple?style=for-the-badge&logo=ionic&logoColor=white" />
</div>
<div align="center">
  <br>
  <a href="https://github.com/orgs/rumbita-cl/projects/1/views/1">
    <img src="https://img.shields.io/badge/📊_Project_Board-Ver_Tablero-2ea44f?style=for-the-badge&logo=github" alt="Project Board" />
  </a>
</div>
---

## 🚀 Sobre el Proyecto

**Rumbita** (`rumbita-cl`) es un ecosistema digital moderno compuesto por un sitio web comercial, una API de alto rendimiento y aplicaciones móviles multiplataforma. Nuestro enfoque prioriza la soberanía de los datos, la automatización robusta mediante CI/CD y una arquitectura optimizada tanto para entornos públicos como privados bajo VPN.

---

## 🛠️ Arquitectura y Tecnologías del Ecosistema

### 🌐 Infraestructura y Backend
* **Servidor Principal (Nginx / DigitalOcean / Debian):** Servidor multisitio configurado con gestión de certificados SSL automáticos (Certbot) y soporte para ambientes Alpha seguros ocultos tras una **VPN con ZeroTier One**.
* **API Core (Fastify + Node.js):** Backend ultrarrápido controlado y gestionado mediante **PM2**, que incluye flujos avanzados de autenticación (OAuth 2.0 con Google) y notificaciones push globales.
* **Base de Datos y Respaldo:** Integración inteligente con **Supabase** complementada por un sistema de respaldo incremental nocturno automatizado en la infraestructura propia.

### 📱 Aplicaciones Móviles (Capacitor)
* **Android:** Compilación automatizada de artefactos (APK/AAB) mediante flujos de integración continua (CI/CD) con GitHub Actions y Gradle.
* **iOS:** Despliegue multiplataforma preparado bajo un modelo híbrido para entornos Apple.

---

## ⚙️ Automatización y DevOps (CI/CD)

Nuestros repositorios aprovechan al máximo el poder de **GitHub Actions** y **GitHub Environments** para garantizar despliegues seguros, limpios y automatizados:
* **Despliegues SSH seguros** hacia servidores de producción mediante llaves ED25519 cifradas.
* **Sincronización de código limpia** con control de procesos para evitar duplicidades en PM2.
* **Gestión de variables de entorno por ambientes** (`alpha`, `staging`, `production`) inyectadas de forma dinámica en cada pipeline.

---

## 📂 Repositorios Principales de la Organización

* 🌐 **Sitio Web & Landing:** Interfaz comercial y pivote web del ecosistema.
* 🔌 **API Fastify:** Núcleo de servicios, lógica de negocio y autenticación.
* 📱 **App Móvil (Capacitor):** Aplicación nativa multiplataforma (Android/iOS).
* ⚙️ **Configuraciones Globales (.github):** Plantillas, perfiles y flujos de automatización centralizados de la organización.

---

<div align="center">
  <i>"El ritmo detrás de rumbita-cl: tecnología, automatización y control total de la infraestructura." 🚀</i>
</div>
