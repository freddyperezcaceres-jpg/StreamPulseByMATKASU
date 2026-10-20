# 🎙️ StreamPulse by Maktasu

**StreamPulse** es una aplicación de escritorio ligera e intuitiva diseñada para creadores de contenido y streamers de **TikTok Live**. Permite convertir los comentarios y comandos del chat en voz en tiempo real (Text-to-Speech / TTS) de manera ilimitada, gratuita y personalizable.

---

## ✨ Características Destacadas

* ♾️ **TTS Totalmente Gratuito e Ilimitado:** Sin restricciones de caracteres ni pagos por suscripción.
* 🛡️ **Filtros Anti-Spam y Moderación:**
  * Filtro de repetición de letras masivas.
  * Eliminación automática de emojis en usuario o mensaje.
  * Modos de activación por comandos específicos (`!tts`, `.`, `/` o cualquier comentario).
  * Control de Cooldown (tiempo de espera entre mensajes) por usuario.
* 👥 **Control de Permisos de Usuarios:** Filtra quién puede enviar mensajes (Todos, Seguidores, Suscriptores, Moderadores o Lista Blanca).
* ⚡ **Integración en Tiempo Real:** Motor integrado en Python con FastAPI y PyWebView para un consumo mínimo de recursos en tu PC de transmisión.

---

## 🚀 Descarga e Instalación

1. Ve a la sección de **[Releases / Lanzamientos](../../releases)** a la derecha de este repositorio.
2. Descarga el archivo ejecutable `StreamPulse.exe` de la versión más reciente.
3. Ejecuta la aplicación (no requiere instalación previa).

---

## 🛠️ Tecnologías Utilizadas

* **Backend:** Python, FastAPI, WebSockets, Uvicorn.
* **Integración TikTok Live:** `TikTokLive`.
* **Interfaz de Usuario:** `PyWebView`, HTML5/CSS3/JavaScript.
* **Empaquetado:** PyInstaller.

---

## 📄 Términos y Licencia

© **Maktasu**. Todos los derechos reservados.

Este software se distribuye de manera gratuita únicamente para uso personal e individual. Queda prohibida la redistribución no autorizada, modificación o ingeniería inversa del software empaquetado.
